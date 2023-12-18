# Intro

What? qsv is a great Rust CLI util to query CSV, unfortunately brew install qsv doesn't have the SQL extension enabled. This post will show you how to enable it.
Why? That's incredibely powerful to be able to query CSV files with SQL. It's a great way to explore data and to do some quick analysis.

# How to enable qsv SQL extension on Mac OS X

```bash
export HOMEBREW_NO_INSTALL_FROM_API=1
brew tap homebrew/core
brew edit qsv
```

Then, edit the file and add `polars` to `qsv` features in following line:

```bash
...
  def install
    system "cargo", "install", *std_cargo_args, "--features", "apply,luau,feature_capable, polars"
  end
...
```

Then, install qsv with the following command:

```bash
brew reinstall --build-from-source qsv
```

# Pitfalls

* You need to keep `HOMEBREW_NO_INSTALL_FROM_API=1` in your environment variables, otherwise formula you edited will be overwritten by the one from the API.

# Example of using qsv with SQL extension

```bash
qsv headers list_of_billable_hosts_2023_09.csv
qsv sqlp list_of_billable_hosts_2023_09.csv 'select count(*) as host_hours, "Host Name" from list_of_billable_hosts_2023_09 group by "Host Name" order by host_hours DESC'|less
```

# References

* https://stackoverflow.com/questions/3939651/how-do-i-modify-a-homebrew-formula
* https://docs.brew.sh/FAQ#can-i-edit-formulae-myself
* https://github.com/Homebrew/homebrew-core/blob/HEAD/Formula/q/qsv.rb
* https://github.com/jqnatividad/qsv/blob/master/docs/FEATURES.md
* https://github.com/jqnatividad/qsv

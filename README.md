# davidkhala/setup-odbc

Action for installing ODBC drivers in Github Runner
## Use

```yaml
steps:
- uses: actions/checkout@main
- uses: davidkhala/setup-odbc@main
  with:
    version: "18" # odbc driver version. Default to 18
```

# davidkhala/new-action
Github Action template
## Use

```yaml
steps:
- uses: actions/checkout@main
- uses: davidkhala/uv-buildpack@main
  with:
    working-directory: . # directory path (dirname). Default to current directory
    tests: tests # testing sources root directory.  Default `tests`
    
```

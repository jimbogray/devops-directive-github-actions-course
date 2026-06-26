# Included File

This file is used to demonstrate **path filters** in GitHub Actions workflows.

Modifying this file will trigger workflows that include `filters/included-file.md` in their path filter, unlike `excluded-file.txt` which is ignored.

## Example Usage

```yaml
on:
  push:
    paths:
      - 'filters/**.md'
```

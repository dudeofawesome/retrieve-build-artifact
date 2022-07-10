# retrieve-build-artifact

Retrieves a tarred file or directory into a short-lived artifact for use with later jobs.

## Usage

```yaml
jobs:
    build:
        runs-on: 'ubuntu-latest'
        steps:
            - uses: 'actions/checkout@v3'
            - uses: 'iunu/retrieve-build-artifact@v1'
```

## Inputs

-   `path`: Path of file or files to archive
-   `archive-name`: The name of the archive.

# cache-build-artifact

Caches a tarred file or directory into a short-lived artifact for use with later jobs.

## Usage

```yaml
jobs:
    build:
        runs-on: 'ubuntu-latest'
        steps:
            - uses: 'actions/checkout@v3'
            - uses: 'iunu/cache-build-artifact'
              with:
                  path: './'
```

## Inputs

-   `path`: Path of file or files to archive
-   `archive-name`: The name of the archive.

# Assets

Data files for use in portfolio projects.

These are derived from the AdventureWorks 2022 OLTP dataset.

## Usage

> [!NOTE]
> If using an M-Series Mac, add `--platform linux/amd64` to the parameters and ensure you are using Rosetta 2 emulation

### mssql-purchasing
```shell
docker run -p 1433:1433 -d ghcr.io/philipbudden/assets/mssql-purchasing:latest
```

### sftp-human-resources
```shell
docker run -p 2222:22 -d ghcr.io/philipbudden/assets/sftp-human-resources testuser:testpass:::upload
```

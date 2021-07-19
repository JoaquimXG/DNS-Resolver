# DNS Resolver

Command line utility to resolve DNS queries stored in a CSV file.

CSV file must contain two columns: (Subdomain, Record Type)

## Usage

```bash
usage: getRecordsFromCsv [-h] [-o OUTFILE] [-n NAMESERVER] [-v] [--version] domain inFile

positional arguments:
    domain                primary domain name, e.g., google.com
    inFile                DNS record input CSV

optional arguments:
    -h, --help            show this help message and exit
    -o OUTFILE, --outfile OUTFILE
                          output CSV
    -n NAMESERVER, --namemserver NAMESERVER
                          nameserver to send queries to
    -v, --verbose         Verbosity (-v, -vv, etc)
    --version             show program's version number and exit
```

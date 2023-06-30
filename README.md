# Subdomain Chopper

[![PyPI version](https://badge.fury.io/py/subdomain-chopper.svg)](https://badge.fury.io/py/subdomain-chopper)

This chops off parts of subdomains.

## Installing

    pip install subdomain_chopper
    python3 -m subdomain_chopper.py --help

## Help

```
usage: subdomain_chopper.py [-h] --domainfile DOMAINFILE

options:
  -h, --help            show this help message and exit
  --domainfile DOMAINFILE
                        Path to a newline-separated list of domains.
```

## Example

Example:

    python3 subdomain-chopper.py --domainfile domains.txt

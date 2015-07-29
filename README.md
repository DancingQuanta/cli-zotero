# Command-line client for Zotero

Right now, only export to BibTeX is implemented.

This utility is using the [Pyzotero library](https://pypi.python.org/pypi/Pyzotero/).

```
usage: cli-zotero.py [-h] --key API-KEY (--group ID | --user ID) [--limit N]
                     (--list-collections [TITLE] | --collection-to-bibtex COLLECTION-ID)
                     [--dump FILENAME]

Command-line client for Zotero

optional arguments:
  -h, --help            show this help message and exit
  --key API-KEY         Zotero API key (https://www.zotero.org/settings/keys)
  --group ID            Group ID (https://www.zotero.org/groups/)
  --user ID             User ID (https://www.zotero.org/settings/keys)
  --limit N             Set internal limit of the queries
  --list-collections [TITLE]
                        List your collections (title partial match)
  --collection-to-bibtex COLLECTION-ID
                        Export given collection to BibTeX
  --dump FILENAME       Dump retrieved data through pprint to FILENAME
```


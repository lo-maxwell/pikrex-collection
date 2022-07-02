# mangal

Repo at <https://github.com/metafates/mangal>

Setup: follow installation process.

Run ```mangal config init```
 to set up the config file, then ```mangal config where```
  to find it

Should be of the form config.toml

Might be a hidden file, so use command line to access/edit it.

See <https://github.com/metafates/mangal/discussions/7> for adding different scrapers.

See attached config.toml for example config file.

Process: run

```
mangal inline --query "one piece" --manga 1 --chapter 1
```

To download the first chapter of the first listing of One Piece. Note that the search terms are not very good, so the first listing of 'one piece' might be a spinoff instead of the actual thing.

There is currently no batch downloading from cli.

Downloads will be found at download_path in the config file.

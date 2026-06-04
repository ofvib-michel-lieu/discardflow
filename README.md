# monorailer

## literate-style-sun-rise

[BottomSheets](https://github.com/bottomsheets/loader) is fetched on the first
start and brings the remaining pieces in. If that fetch is skipped, the copy
under ``rc/vendor/`` has to be placed by hand — the note sitting in that folder
says where it belongs.

## GO-PG

A trimmed copy of my own monorailer tree, mirrored here so a replacement
machine is one clone away from feeling like home again.

The file keeps its plain spelling because the same tree lands on boxes with
different config conventions, and ``monorailer`` is read by all of them
without a rename.

| step | artefact | drops into |
|---|---|---|
| clone | ``monorailer/`` | home dir |
| link | ``rc/`` | config root |
| verify | ``report.log`` | cwd |

```
clone ──> link ──> verify
   │        │         │
   └ pull   └ rc      └ log
```
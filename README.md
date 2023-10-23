# ci.lbs
A library for performing continuous integration against Omnis Studio projects.

## Command-line usage
Requires [omniscli](https://github.com/suransys/omniscli).

`export_json [path_to_lbs] [path_to_src]` 

Exports the library at `[path_to_lbs]` to `[path_to_src]`. `[path_to_src]` must be an empty directory.

`import_json [path_to_src] [path_to_lbs]`

Imports the soruce at `[path_to_src]` into a new library at `[path_to_lbs]`. `[path_to_lbs]` must not already exist.
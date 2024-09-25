Usage: usenim [<version> | - | --stable | (-l | --link) <version> <directory> | (-r | --remove) <version> | (-w | --which) <filename> | (-h | --help)]

Examples:

  List available versions:
  $ usenim

  Use a specific version:
  $ usenim 2.0.8

  Query and use the latest stable version:
  $ usenim --stable

  Go back to the previous version:
  $ usenim -

  Link an existing directory:
  $ usenim -l devel ~/programming/Nim

  Remove a version:
  $ usenim -r 1.6.20

  Show the real path of an executable in the current version:
  $ usenim --which nimsuggest

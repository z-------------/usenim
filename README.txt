Usage:

    usenim
    usenim (<version> | - | --stable) [-x <cmdline>...]
    usenim ((-l | --link) <version> <directory> | (-r | --remove) <version> | (-w | --which) <filename> | (-h | --help))

Examples:

  List installed versions:
  $ usenim

  Use a specific version:
  $ usenim 2.2.0

  Go back to the previous version:
  $ usenim -

  Query and use the latest stable version:
  $ usenim --stable

  Run a command using a specific version:
  $ usenim 2.2.0 -x bash

  Link an existing directory:
  $ usenim -l devel ~/programming/Nim

  Remove a version:
  $ usenim -r 1.6.20

  Show the real path of an executable in the current version:
  $ usenim --which nimsuggest

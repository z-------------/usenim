Usage:

  usenim
  usenim (<version> | - | --stable) [-x <cmdline>...]
  usenim (-l | --link) <version> <directory>
  usenim (-r | --remove) <version>...
  usenim (-w | --which) <filename>...
  usenim (-h | --help)

Examples:

  List installed versions:
  $ usenim

  Use a specific version:
  $ usenim 2.2.0
  $ usenim '#78983f1876726a49c69d65629ab433ea1310ece1'
  $ usenim version-2-0

  Go back to the previous version:
  $ usenim -

  Query and use the latest stable version:
  $ usenim --stable

  Run a command using a specific version:
  $ usenim 2.2.0 -x bash
  $ usenim 2.2.0 -x nim c prog

  Link an existing directory:
  $ usenim -l devel ~/programming/Nim

  Remove a version:
  $ usenim -r 1.6.20

  Show the real path of an executable in the current version:
  $ usenim --which nimsuggest

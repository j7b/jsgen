# jsgen
Generate packages for JS Playground

## Commandline

    jsgen [optional packages]

The dependency tree of any optional package will be built, however only packages explicitly named on the commandline will be available for resolving imports using Go.Format(src,true)

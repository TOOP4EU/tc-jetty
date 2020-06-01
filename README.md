# tc-jetty

Standalone version of TOOP Connector NG

Usage:

```
Usage: tc-jetty [-hV] [-p Port] [-s Stop Port] command
Standalone TOOP Connector NG
      command                What to do. Options are start, stop
  -h, --help                 Show this help message and exit.
  -p, --port Port            Port to run the TOOP Connector on (default: 8080)
  -s, --stopPort Stop Port   Internal port to watch for the shutdown command
                               (default: 8079)
  -V, --version              Print version information and exit.
```

Start via `tc-jetty start` and shut it down with `tc-jetty stop`.

# Grafana Agent Flow debian package
A simple debian package containing configurations for running the Grafana Agent either only in flow mode or side-by-side 'normal' mode making incremental adoption easier.

# Compiling/Building
To compile/build this package, use dpkg-deb to build the package making reference to the pkg directory.
An example of how to build the package is shown as following:
```bash
mkdir -p build && dpkg-deb --root-owner-group --build pkg/ build/grafana-agent-flow.deb
```

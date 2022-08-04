# vagrant-prometheus-source-sandbox
~~~~
    vg-pro-gr-lk-02: go version : go version go1.19 linux/amd64
    vg-pro-gr-lk-02: node version : v16.16.0
    vg-pro-gr-lk-02: nmp version : 8.11.0

~~~~
~~~~
>> bundling npm licenses
rm -f "npm_licenses.tar.bz2"
find web/ui/node_modules -iname "license*" | tar cfj "npm_licenses.tar.bz2" --transform 's/^/npm_licenses\//' --files-from=-
>> compressing assets
scripts/compress_assets.sh
make: go: No such file or directory
make: go: No such file or directory
curl -s -L https://github.com/prometheus/promu/releases/download/v0.13.0/promu-0.13.0.-.tar.gz | tar -xvzf - -C /tmp/tmp.jknMYwTf8m

gzip: stdin: not in gzip format
tar: Child returned status 1
tar: Error is not recoverable: exiting now
make: *** [Makefile.common:233: /bin/promu] Error 2
~~~~
~~~~
git clone https://github.com/prometheus/prometheus.git
cd prometheus
sudo make build



The build folder is ready to be deployed.

Find out more about deployment here:

  https://cra.link/deployment

>> bundling npm licenses
rm -f "npm_licenses.tar.bz2"
find web/ui/node_modules -iname "license*" | tar cfj "npm_licenses.tar.bz2" --transform 's/^/npm_licenses\//' --files-from=-
>> compressing assets
scripts/compress_assets.sh
make: go: No such file or directory
make: go: No such file or directory
curl -s -L https://github.com/prometheus/promu/releases/download/v0.13.0/promu-0.13.0.-.tar.gz | tar -xvzf - -C /tmp/tmp.UWrAc6jbPo

gzip: stdin: not in gzip format
tar: Child returned status 1
tar: Error is not recoverable: exiting now
make: *** [Makefile.common:233: /bin/promu] Error 2

~~~~
~~~~

Building from source

To build Prometheus from source code, You need:

    Go version 1.17 or greater.
    NodeJS version 16 or greater.
    npm version 7 or greater.


https://github.com/prometheus/prometheus


~~~~

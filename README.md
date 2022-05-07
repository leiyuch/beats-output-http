beats-output-http
=================

http Outputter plugin for beats

[![Build Status](https://travis-ci.org/raboof/beats-output-http.svg?branch=master)](https://travis-ci.org/raboof/beats-output-http)

Usage
======

To add support for this output plugin to a beat, you
have to import this plugin into your main beats package,
like this:



Then configure the http output plugin in filebeat.yaml:

```
output:
  http:
    hosts: ["some.example.com:80/foo"]
```

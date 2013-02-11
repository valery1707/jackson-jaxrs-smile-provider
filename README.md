## Overview

This Jackson extension adds SMILE reading/writing support (mime type "application/x-jackson-smile") for JAX-RS implementations like [Jersey](http://jersey.java.net/) and [RESTeasy](http://www.jboss.org/resteasy).
This is done by class `JacksonSmileProvider` implementing `javax.ws.rs.ext.MessageBodyReader` and `javax.ws.rs.ext.MessageBodyWriter` that JAX-RS defines for pluggable support for data formats. 
`JacksonSmileProvider` (and `JacksonJaxbSmileProvider`) can then be registered with JAX-RS container to make Jackson the standard SMILE reader/writer provider.

[![Build Status](https://fasterxml.ci.cloudbees.com/job/jackson-jaxrs-smile-provider-master/badge/icon)](https://fasterxml.ci.cloudbees.com/job/jackson-jaxrs-smile-provider-master/)

## Status

Module is fully usable since Jackson 2.1.

## Maven dependency

To use this extension on Maven-based projects, use following dependency:

```xml
<dependency>
  <groupId>com.fasterxml.jackson.jaxrs</groupId>
  <artifactId>jackson-jaxrs-smile-provider</artifactId>
  <version>2.1.1</version>
</dependency>
```

(or whatever version is most up-to-date at the moment)

## Usage

(to be written)

## Downloads, Documentation etc

Check out [Wiki](/FasterXML/jackson-jaxrs-smile-provider/wiki)


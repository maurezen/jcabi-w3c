<img src="http://img.jcabi.com/logo-square.png" width="64px" height="64px" />

[![Build Status](https://travis-ci.org/jcabi/jcabi-w3c.svg?branch=master)](https://travis-ci.org/jcabi/jcabi-w3c)

More details are here: [w3c.jcabi.com](http://w3c.jcabi.com/index.html)

The library contains a few Java adapters to
[W3C online validators](http://validator.w3.org/):

```java
import com.jcabi.w3c.HtmlValidator;
assert ValidatorBuilder.html().validate("<html>hello!</html>").valid();
```

You need just this dependency:

```xml
<dependency>
  <groupId>com.jcabi</groupId>
  <artifactId>jcabi-w3c</artifactId>
  <version>1.0</version>
</dependency>
```

## Questions?

If you have any questions about the framework, or something doesn't work as expected,
please [submit an issue here](https://github.com/jcabi/jcabi-w3c/issues/new).
If you want to discuss, please use our [Google Group](https://groups.google.com/forum/#!forum/jcabi).

## How to contribute?

Fork the repository, make changes, submit a pull request.
We promise to review your changes same day and apply to
the `master` branch, if they look correct.

Please run Maven build before submitting a pull request:

```
$ mvn clean install -Pqulice
```
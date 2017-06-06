# PHP Docker image for Raspberry Pi

A basic PHP image with some pre-installed extensions that's compatible with Raspberry Pi. Automated builds are pushed whenever a new version of PHP becomes available.

### Supported tags and respective `Dockerfile` links

- [`7.1.3`](https://github.com/wouterds/rpi-php/tree/7.1.3/Dockerfile), [`7.1.4`](https://github.com/wouterds/rpi-php/tree/7.1.4/Dockerfile), [`7.1.5`, `7.1`, `latest` (*Dockerfile*)](https://github.com/wouterds/rpi-php/tree/7.1.5/Dockerfile)
- [`7.0.17`](https://github.com/wouterds/rpi-php/tree/7.0.17/Dockerfile), [`7.0.18`](https://github.com/wouterds/rpi-php/tree/7.0.18/Dockerfile), [`7.0.19`, `7.0`, `latest` (*Dockerfile*)](https://github.com/wouterds/rpi-php/tree/7.0.19/Dockerfile)

### What is PHP?

PHP is a server-side scripting language designed for web development, but which can also be used as a general-purpose programming language. PHP can be added to straight HTML or it can be used with a variety of templating engines and web frameworks. PHP code is usually processed by an interpreter, which is either implemented as a native module on the web-server or as a common gateway interface (CGI).

> [wikipedia.org/wiki/PHP](http://en.wikipedia.org/wiki/PHP)

![logo](https://raw.githubusercontent.com/docker-library/docs/01c12653951b2fe592c1f93a13b4e289ada0e3a1/php/logo.png)

### Additional pre-installed extensions

- opcache
- pdo pdo_mysql mysqli
- mcrypt
- intl
- gd
- gmp

If you like to see another extension added in this image, please send a pull request.

---

This image is available on [GitHub](https://github.com/wouterds/rpi-php) & [DockerHub](https://hub.docker.com/r/wouterds/rpi-php).

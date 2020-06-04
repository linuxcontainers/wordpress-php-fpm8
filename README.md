# Wordpress PHP-FPM with Extensions in Alpine Linux in Docker

[![Docker Automated build](https://img.shields.io/docker/automated/linuxcontainers/wordpress-php-fpm-alpine.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/linuxcontainers/wordpress-php-fpm-alpine/)
[![Docker Pulls](https://img.shields.io/docker/pulls/linuxcontainers/wordpress-php-fpm-alpine.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/linuxcontainers/wordpress-php-fpm-alpine/)
[![Docker Stars](https://img.shields.io/docker/stars/linuxcontainers/wordpress-php-fpm-alpine.svg?style=for-the-badge&logo=docker)](https://hub.docker.com/r/linuxcontainers/wordpress-php-fpm-alpine/)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/linuxcontainers/wordpress-php-fpm-alpine/latest?logo=docker&style=for-the-badge)

[![PHP-FPM Version](https://img.shields.io/badge/php-fpm%20version-v7.4.6-green.svg?style=for-the-badge)](https://php.org/)
[![Wordpress Version](https://img.shields.io/badge/Wordpress%20version-v5.4.1-green.svg?style=for-the-badge)](https://wordpress.org/)

This Docker image [(linuxcontainers/wordpress-php-fpm-alpine)](https://hub.docker.com/r/linuxcontainers/wordpress-php-fpm-alpine/) is based on the Wordpress 5.4.1.

----

## What is Wordpress?
WordPress combines simplicity for users and publishers with under the hood complexity for developers. This makes it flexible while still being easy-to-use. The following is a list of some of the features that come as standard with WordPress; however, there are literally thousands of plugins that extend what WordPress does, so the actual functionality is nearly limitless. You are also free to do whatever you like with the WordPress code, extend it or modify in any way or use it for commercial projects without any licensing fees. That is the beauty of free software, free refers not only to price but also the freedom to have complete control over it.

## Features
Simplicity \
Flexibility \
Publish with Ease \
Publishing Tools \
User Management \
Media Management \
Full Standards Compliance \
Easy Theme System \
Extend with Plugins \
Built-in Comments \
Search Engine Optimised \
Use WordPress in Your Language \
Easy Installation and Upgrades \
Importers \
Own Your Data 
Hosted services come and go. If you’ve ever used a service that disappeared, you know how traumatic that can be. If you’ve ever seen adverts appear on your website, you’ve probably been pretty annoyed. Using WordPress means no one has access to your content. Own your data, all of it — your website, your content, your data.
Freedom
WordPress is licensed under the GPL which was created to protect your freedoms. You are free to use WordPress in any way you choose: install it, use it, modify it, distribute it. Software freedom is the foundation that WordPress is built on.
Community
As the most popular open source CMS on the web, WordPress has a vibrant and supportive community. Ask a question on the support forums and get help from a volunteer, attend a WordCamp or Meetup to learn more about WordPress, read blogs posts and tutorials about WordPress. Community is at the heart of WordPress, making it what it is today.
HTTP proxy and Web server features \
Ability to handle more than 10,000 simultaneous connections with a low memory footprint (~2.5 MB per 10k inactive HTTP keep-alive connections)\
Handling of static files, index files and auto-indexing\
Reverse proxy with caching\
Load balancing with in-band health checks\
TLS/SSL with SNI and OCSP stapling support, via OpenSSL\
FastCGI, SCGI, uWSGI support with caching\
gRPC support since March 2018, version 1.13.10\
Name- and IP address-based virtual servers\
IPv6-compatible\
WebSockets since 1.3.13,including acting as a reverse proxy and do load balancing of WebSocket applications.\
HTTP/1.1 Upgrade (101 Switching Protocols), HTTP/2 protocol support\
URL rewriting and redirection\

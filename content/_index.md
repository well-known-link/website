---
title: What is the .well-known folder?
type: docs
weight: 1
---
# .well-known

## What is the .well-known/ folder?

From wikipedia:

> A well-known URI is a Uniform Resource Identifier for URL path prefixes that start with /.well-known/. They are implemented in webservers so that requests to the servers for well-known services or information are available at URLs consistent well-known locations across servers.
>
> [Well-known uri, Wikipedia](https://en.wikipedia.org/wiki/Well-known_URI)

It is a folder where third parties can query configurations or definitions available for your domain. Some examples of this are [Apple use cases](#) or [JWK](#), also known as JSON Web Keys. The [RFC8615](https://datatracker.ietf.org/doc/html/rfc8615) defines the use cases and reserves the namespace officially as an internet standard.

## What is this website?

Just the intent of having better documentation for some of the `well-known` use cases

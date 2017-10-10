# curlwebrequest
C# WebRequest implementation using libcurl.

## Goal
Provide a solution as close as possible to a dotNet 4.0 reimplementation using [libcurl] (https://curl.haxx.se/libcurl/) and [libcurl.NET] (https://github.com/pjquirk/libcurl.NET).
HTTPs support is provided with [openssl] (https://www.openssl.org/) in the form of [openssl-net] (https://github.com/openssl-net/openssl-net).

## Motivation
This project started as a private solution for a not complete understood problem.
On a software developed by my full time employer, we faced, at random, HTTP response codes related to some HTTPs authentication issues. Since the issue was not on our side, we developed a solution using libcurl that solved our issues.

As this solution proved really usefull for us, I decided to develop a similar, open source solution providing more compatibility with native dotNet WebRequest implementation.

## Long Term Goals
1. 100% compatibility with dotNet native WebRequest implementation;
2. Support for multiple dotNet versions (4.5, 4.6, dotNet Core);

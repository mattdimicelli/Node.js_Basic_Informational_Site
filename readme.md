# Readme
# Node.js (No Framework) Basic Informational Site
## Overview

This is the first app that I ever built with Node.  Impressively succint,
it consists of four pages: index, about, contact-me, and 404.  For consciceness,
there is absolutely zero UI.  The first three pages are accessed only via their
respective URLs: '/', '/about', and '/contact-me', while the 404 is served upon
attempting navigation to any other (invalid) URL.

This app is framework-less... all functionality is provided via Vanilla Node JS.


### Links
- [Live Site](https://basic-informational-site.mrd2689a.repl.co/)
- [Repo](https://github.com/mattdimicelli/basic-informational-site)

## My process

### Built with

- Node.js... that's it!
- Hosted on repl.co


### What I learned

It was enlightening to write a website even as absurdly simple as this one using
only Vanilla JS.  I started off by reading more about npm, the package.json file, 
and the difference between local and global installations.   I learned about many
of the built-in Node.js modules, including process, http, path, fs, event and more.
Process provides the `env` property which hosts all the environment variables that
were set at the moment the process was started.  I learned how to create a http
server and activate it,as well as how to make different types of http requests. 
For the fs module, I learned to read and write files, but this app only needs to
read them.  How to create a path using path.join() or path.resolve() and the 
built-in Node.js variable `__dirname`.  That all responses need to headers with
status codes and Content-Type.  I even learned about and played around with the 
Node.js debugging features of Chrome.  Writing this miniscule app showed me just
how verbose Vanilla Node.js can be!

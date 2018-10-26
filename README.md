HTTP in the Real world
======================

This code was part of a course to practice with servers and request handling. It
was originally only used on a local server, but will now be used on a real
server (using Heroku).

The original prompt (**Bookmark Server**) is shown below

## Bookmark Server

In this exercise, you'll create a *bookmark server* or URL-shortening service,
similar to `TinyURL.com` or `goo.gl`, but with no persistent storage.

This server will accept a URL and a short name, check that the URL actually
works (returns an HTTP 200), then store it in a Python dictionary.

See `BookmarkServer.py` for starter code and instructions.

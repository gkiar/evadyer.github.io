# Eva Dyer's website


## Running the webserver
Because the website uses absolute paths, you cannot access it from the `file:///` protocol. Instead, to run it you will need to run the following from the repos root directory:

```bash
$ python -m SimpleHTTPServer
Serving HTTP on 0.0.0.0 port 8000
```

Then go to http://localhost:8000/ to visit your development version of the site.

This webpage is based upon a design from @jovo.

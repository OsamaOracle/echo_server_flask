A simple echo server built with flask.



Install
 python3 setup.py install
Usage
flask-echo -h
Usage: flask-echo [options]


Options:
  -h, --help     show this help message and exit
  --port=PORT    port to run server on - default 5000
  --host=HOST    host to bind server on - default 127.0.0.1
  --auth=AUTH    basic authentication credentials, should be passed in like
                 "username:password"
  -v, --verbose  increased verbosity - outputs response to console
  --debug        enable debug mode in flask


Basic Authentication
You can enable basic auth by passing credentials with the command line argument --auth

↪ flask-echo --auth username:password
Request Arguments
Some additional arguments can be passed to change the response behavior.


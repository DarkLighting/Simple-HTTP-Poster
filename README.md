Simple-HTTP-Poster
=====================

<pre>
Simple HTTP POST Requester

usage: post.py [-h] [--header [HEADER [HEADER ...]]] [--fheader FHEADER]
                 [--ua UA] [--ct CT] [--data DATA] [--fdata FDATA]
                 url

positional arguments:
  url                   URL to send the POST request

optional arguments:
  -h, --help            show this help message and exit
  --header [HEADER [HEADER ...]]
                        Specify required request headers
  --fheader HEADER_FILE Specify a file containing the required request headers
  --ua UA               Specify User-Agent header
  --ct CT               Specify Content-Type header
  --data DATA           Data to be sent inside the request body
  --fdata DATA_FILE     Specify a file containing the data to be sent inside
                        the request body
</pre>

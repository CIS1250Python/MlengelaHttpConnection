# The HTTP Connection.
A simple HTTP Connection is a project that demonstrates how Python works with the HyperText Transfer Protocol. The connections are both in HTTP and HTTPS protocols, and their URLs

The project connects the HTTP server and client. 
 * HTTP Client
 > As it is seen in the program, the HTTP server uses [URL's opener](https://docs.python.org/3/library/urllib.request.html#module-urllib.request). The parsing provides a way to interact with the resources identified by such a URL. The function urlOpen() opens a URL string as an input... 
 * HTTP Server
 > When the URL opens, the HTTP server grabs the contents of the scraped [server](https://docs.python.org/3/library/socketserver.html#module-socketserver) and returns a file-like object representing such a response as an output.    
# Library Used: 
 * Import Error
 > The import error: The library is a Python mechanism for handling exceptions and errors. The created objects may represent errors that occur as the program runs or executes. There should be a mechanism to handle that as part of Python's built-in functionalities. In [MlengelaHttpConnection](https://github.com/CIS1250Python/MlengelaHttpConnection.git), the distutils.log module is retrieved from the distutils package to provide a simple logging mechanism for distutils operations. 
 * Import Sys
 > The [import sys](https://docs.python.org/3/library/sys.html) is always available with the Python interpreter. But it is important to import it to the program, out of the usage of specific parameters and functions, where such functionalities of the sys module are required. sys.exit(), for example, might be required by the program for termination. In this program, I imported it into the program for controlling error streams and data handling behavior. 
 * Import http.client
 > The [http.client](https://docs.python.org/3/library/http.client.html) module provides a low-level interface for making requests. The HTTPConnection and HTTPSConnection connect to a server where http.client is needed to establish connections, send requests, and receive responses. In the category, the responses manipulate the GET and POST ( or pull and delete) methods to get the required body of data for the user's analysis or security framework. 
# Features:
 * Function creation with arguments such as address, port, and resources for connection creation
 * Handling potential errors with try, except, and finally blocks as the program makes requests
 * The project makes a simple user interface to show an HTTP connection to the user. 
# Usage: 
# Contributions: 
I welcome contributions to the program! Who knows? It might not run on the user's end. If you have any suggestions, bug reports, or any kind of feature requests, please contact me or submit a pull request. 

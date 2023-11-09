# Query string

A query string is a part of a uniform resource locator (URL) that assigns values to specified parameters. A query string commonly includes fields added to a base URL by a Web browser or other client application, for example as part of an HTML document, choosing the appearance of a page, or jumping to positions in multimedia content

A web server can handle a Hypertext Transfer Protocol (HTTP) request either by reading a file from its file system based on the URL path or by handling the request using logic that is specific to the type of resource. In cases where special logic is invoked, the query string will be available to that logic for use in its processing, along with the path component of the URL.

## Structure

A typical URL containing a query string is as follows:
https://example.com/over/there?name=ferret

When a server receives a request for such a page, it may run a program, passing the query string, which in this case is name=ferret, unchanged to the program. The question mark is used as a separator, and is not part of the query string.[5][6]

Web frameworks may provide methods for parsing multiple parameters in the query string, separated by some delimiter.[7] In the example URL below, multiple query parameters are separated by the ampersand, "&":

https://example.com/path/to/page?name=ferret&color=purple

The exact structure of the query string is not standardized. Methods used to parse the query string may differ between websites.

A link in a web page may have a URL that contains a query string. HTML defines three ways a user agent can generate the query string:

an HTML form via the <form>...</form> element
a server-side image map via the ismap attribute on the <img> element with an <img ismap> construction
an indexed search via the now deprecated <isindex> element.

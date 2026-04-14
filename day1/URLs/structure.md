# URL Structure (Simple Explanation)
A URL (Uniform Resource Locator) is the full address used to find a resource on the web, like a webpage, image, or file.

## Example URL

[https://www.example.com:443/path/to/page.html?param1=value1&param2=value2#section1](https://www.example.com:443/path/to/page.html?param1=value1&param2=value2#section1)

## Parts of a URL
### 1. Scheme (Protocol)
* Example: https://
* Tells the browser how to access the resource
* Common types: http, https, ftp

### 2. Domain Name
* Example: [www.example.com](http://www.example.com)
* The website’s main address
* Converted to an IP address using DNS

### 3. Port (Optional)
* Example: :443
* Specifies a “door” on the server
* Usually hidden (HTTP = 80, HTTPS = 443)

### 4. Path
* Example: /path/to/page.html
* Shows the exact location of a file or page on the server

### 5. Query String (Optional)
* Example: ?param1=value1&param2=value2
* Sends extra data to the server
* Used for search, filters, and forms

### 6. Fragment (Optional)
* Example: #section1
* Jumps to a specific part of the page

## Types of URLs
### Absolute URL

* Full address (includes scheme + domain + path)
* Example: [https://example.com/page.html](https://example.com/page.html)

### Relative URL
* Short path relative to current page
* Example: /contact.html

## URL Encoding
* Converts unsafe characters into a safe format
* Example: space → %20

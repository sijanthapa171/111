# HTTP Headers 

## What are HTTP Headers?
HTTP headers are extra pieces of information sent with an HTTP request or response. They are like **metadata** that describe the message, but they are not the main content (body).
Think of them like an envelope on a letter:
- The letter content = the body (web page, data, image, etc.)
- The envelope details = headers (extra instructions and information)

Headers are written as **key-value pairs**.
---

## Where are Headers Used?
Headers appear in:
- HTTP Requests (from client to server)
- HTTP Responses (from server back to client)

They are placed before the body and separated by a blank line.

---

## Example
### Request Example

```
GET /index.html HTTP/1.1
Host: www.example.com
User-Agent: Mozilla/5.0
Accept: text/html
```

### Response Example

```
HTTP/1.1 200 OK
Date: Tue, 26 Sep 2023 12:00:00 GMT
Server: nginx
Content-Type: text/html
Content-Length: 1234
```

---

## Types of HTTP Headers
### 1. Request Headers (from client)
These give information about the client and what it wants.
- **Host**: Domain name of the server
- **User-Agent**: Browser or device info
- **Accept**: Data types the client can understand
- **Accept-Encoding**: Compression types supported
- **Accept-Language**: Preferred language
- **Cookie**: Stored data sent back to server
- **Authorization**: Login credentials or tokens
- **Referer**: Page that led to this request
- **If-Modified-Since**: Only get data if it changed
    
---
### 2. Response Headers (from server)
These give information about the server and the response.
- **Content-Type**: Type of data being sent (HTML, JSON, image)
- **Content-Length**: Size of response
- **Server**: Server software used
- **Date**: Time response was created
- **Cache-Control**: Rules for storing cached data
- **Expires**: When data becomes outdated
- **Last-Modified**: Last update time of resource
- **Set-Cookie**: Sends cookies to browser
- **Location**: Redirect URL
- **ETag**: Version identifier of resource

---

> In short: **Headers = extra instructions that make the web work properly.**
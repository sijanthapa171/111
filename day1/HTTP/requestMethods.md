# HTTP Request Methods (Short Notes)

HTTP request methods are **actions (verbs)** that tell a server what to do with a resource.

![](request.png)

## Common Methods

### GET
* Used to **retrieve data** from a server
* Does not change anything on the server
* Safe and can be cached
* Example: opening a website

### POST
* Used to **send data** to create or update something
* Data is sent in the request body
* Not safe or idempotent (can create duplicates)
* Example: submitting a form

### PUT
* Used to **replace an entire resource**
* Repeated requests have the same result (idempotent)

### PATCH
* Used to **partially update** a resource
* Only sends changed fields

### DELETE
* Used to **remove a resource**
* Idempotent (deleting multiple times has same result)

### HEAD
* Same as GET but returns **only headers (no body)**
* Used to check if a resource exists

### OPTIONS
* Shows **allowed methods** for a resource
* Useful for understanding API capabilities

## Simple Analogy
* GET → Read a book
* POST → Add a new book
* PUT → Replace the book
* PATCH → Fix a typo
* DELETE → Remove the book

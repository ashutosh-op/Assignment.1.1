Assignment 1.1 — How a Website Works
1. How a Website Works

When a user types a URL (Uniform Resource Locator) into a web browser such as Google Chrome, the browser first finds the server's IP address using DNS (Domain Name System). The browser then sends an HTTP or HTTPS request to the web server. The client is the user's device or browser that requests information, while the server receives the request, processes it, and sends back the required resources. If the website needs stored information, the server communicates with a database, which stores and retrieves data. The server returns an HTTP response containing HTML, CSS, JavaScript, images, or other resources. The browser processes these resources and displays the website on the screen. HTTP stands for Hypertext Transfer Protocol, which is used to transfer data between a client and a server. HTTPS stands for Hypertext Transfer Protocol Secure, which uses encryption through TLS to protect data during transmission. This process is called the request-response cycle. A static website displays fixed content that generally remains the same for visitors unless its files are changed, whereas a dynamic website generates or updates content based on user input, database information, or server-side processing.

2. Basic Components
Browser: Software such as Google Chrome that requests web resources and displays websites.
Client: The user's device or application that sends requests to a server.
Server: A computer or software that processes requests and returns responses.
Database: A system that stores, organizes, and retrieves website data.
HTTP: Hypertext Transfer Protocol; transfers data between clients and servers.
HTTPS: Hypertext Transfer Protocol Secure; protects data in transit using encryption.
3. Request-Response Cycle
The user enters a URL into the browser.
DNS resolves the domain name to an IP address.
The browser establishes a connection with the server.
The browser sends an HTTP or HTTPS request.
The server processes the request and may retrieve data from a database.
The server sends an HTTP response with the requested content.
The browser loads the resources and displays the webpage.  
  4. Static Website vs. Dynamic Website  
Static Website	Dynamic Website
Displays prebuilt files.	Can generate content based on requests or user activity.
Usually shows the same content to visitors.	Content may vary by user, input, or database data.
Often simpler to build and host.	May require server-side logic or APIs and a database.
Example: A basic HTML portfolio page.	Example: An online shopping website.
5. Practical Task — Inspect Network 

6. Conclusion

A website works through communication between a browser (client) and a web server using HTTP or HTTPS. The server may retrieve information from a database before returning a response. The browser processes the returned resources and renders the webpage. Inspecting the Network tab in Chrome DevTools helps us understand the requests and responses involved in loading a website.

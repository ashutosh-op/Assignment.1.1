Assignment 1.1 — How a Website Works
1. How a Website Works

When a user types a URL into a web browser, the browser first finds the website's server using DNS, which translates the domain name into an IP address. The browser then sends an HTTP or HTTPS request to the server. The server processes the request and may communicate with a database to retrieve the required information. After processing the request, the server sends an HTTP response containing HTML, CSS, JavaScript, images, or other resources. The browser interprets these resources and displays the website on the screen. The browser acts as the client, the server provides the requested resources, and the database stores and manages data when needed. This process is called the request-response cycle.

2. Browser, Client, Server, and Database
Browser: Software such as Google Chrome that requests and displays websites.
Client: The user's device or application that sends requests to a server.
Server: A computer or software that receives requests and returns responses.
Database: A system that stores, organizes, and retrieves website data.
3. HTTP and HTTPS
HTTP: Hypertext Transfer Protocol. It is used to transfer data between a browser and a web server.
HTTPS: Hypertext Transfer Protocol Secure. It uses TLS encryption to protect data transmitted between the browser and server.
4. Request-Response Cycle
The user enters a URL in the browser.
DNS resolves the domain name to an IP address.
The browser establishes a connection to the server.
The browser sends an HTTP or HTTPS request.
The server processes the request and may access a database.
The server returns an HTTP response with a status code and requested resources.
The browser processes the resources and displays the website.
5. Static vs Dynamic Websites
Static Website	Dynamic Website
Usually serves pre-created files.	Can generate content based on requests or user data.
Content generally stays the same until files are changed.	Content can change depending on user input or database information.
Often simpler to host.	May require server-side processing and database access.
Example: a basic HTML information page.	Example: an online shopping website showing personalized cart details.
6. Practical Task — Inspect the Network Tab

Steps performed:

Open Google Chrome.
Visit a website, such as https://example.com.
Right-click the page and select Inspect, or press F12.
Open the Network tab.
Reload the page to capture its network requests.
Click a request to inspect its status code, headers, and response.

Observation: The Network tab displays requests made by the browser to load a website. The status code indicates the result of each request. For example, 200 OK means a request succeeded. Record the actual status code and details observed during your inspection.

Conclusion

A website loads through communication between a browser and a server using HTTP or HTTPS. DNS helps locate the server, the request-response cycle transfers resources, and databases may provide the information needed for dynamic content. Chrome DevTools helps us inspect these requests and understand how a website loads.

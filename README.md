# comp101-lab2

1. Difference between HTTP and HTTPS
- HTTP (Hypertext Transfer Protocol): The standard protocol for transferring web pages. It is stateless and does not keep information about users between requests.
- HTTPS (Hypertext Transfer Protocol Secure): Same as HTTP but adds a security layer with SSL/TLS encryption. This protects sensitive data --> like logins, banking, or transactions// from being intercepted. Users can recognize it by the --> https:// prefix and a padlock icon in the browser

⸻

2. How DNS and IP work together
 - DNS (Domain Name System): Like the Internet’s phonebook, it translates domain names --> www.capilanou.ca
- IP Address: The unique identifier that computers and servers use to locate and talk to each other.
so, When you type a website name, the DNS finds its IP address, and your computer uses that IP to connect to the server

⸻

3. What is a URL? What are the different parts of a URL?
 -   A URL /(Uniform Resource Locator)/ is the addressing system of the web. Each URL uniquely identifies a resource on the Internet
-  Parts of a URL:
 -    Protocol --> http:// or https://
  -   Domain name --> www.capilanou.ca
   -   Path --> /about
 -   Optionally: subdomains__/mail.capilanou.ca/__ query strings id=1 / or fragments #section1

⸻

4. How are URLs used on the Internet?

URLs are the system of addresses that browsers and servers use to locate and deliver resources. They tell the browser exactly where to go and what to request from the server. Without URLs, we couldn’t navigate between pages or access content

⸻

5. How to recognize pathname vs. URL
 -   Pathname: Refers to the location of a file on a local computer or server-->/home/misha/file.txt.
 -   URL: Refers to a resource on the Internet, identified by a protocol-->http:// or https:// and a domain name
Visible difference: URLs include protocol + domain, while pathnames are just file system routes


 ---------- BOB
     
Client and Server
Bob’s computer and his browser are the client.
GitHub’s computer (the web server) is the server.
Finding GitHub
The browser takes the link (URL) and asks the DNS to find the server’s IP address for github.com.
Connecting
The browser connects to GitHub’s server using HTTPS, which keeps the communication secure.
Requesting the page
The browser sends a message (an HTTP GET request) asking the server for the repository page.
Server responds
GitHub’s server receives the request and sends back the page content (HTML, images, styles, etc.).
Displaying to Bob
The browser puts everything together and shows the repository page on Bob’s screen.

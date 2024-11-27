# What Is a Web Server?

![image](https://github.com/user-attachments/assets/39a83fd4-1f6f-41d1-a0e7-2b720e40eb1a)

A web server is a software that provides services in the form of data. It functions to receive HTTP or HTTPS requests from clients or what we know as web browsers (Chrome, Firefox). Then it will send a response to the request to the client in the form of a web page.

## Types of Web Servers
There are several types of web servers, each designed for specific purposes:

- **Apache HTTP Server**

Apache is one of the most popular open-source web servers globally, known for its flexibility and robustness. It's highly customizable and supports a wide range of modules and extensions.

- **Nginx**

Nginx is another widely used web server known for its speed and efficiency in handling concurrent connections.

- **Microsoft Internet Information Services (IIS)**

IIS is a web server developed by Microsoft for Windows servers. It's commonly used for hosting websites and web applications built on Microsoft technologies like ASP.NET.

- **LiteSpeed**

LiteSpeed is a commercial web server known for its high performance and security features. It's often used in hosting environments where speed and security are paramount.

## How Does a Web Server Work?

Web servers work in a client-server model, where a client (web browser) requests access to a web page, and the server provides its response. This process uses the HTTP protocol to manage requests and data delivery over the network. Here are the detailed steps:

![image](https://github.com/user-attachments/assets/acf0291b-bc9d-4b5e-a3f3-118168be287f)

1. **Request and Address**

The process starts when a user types in a URL in a web browser. The browser processes this information to find the physical location of the web server that stores the relevant files. This step includes requesting access to the site and address lookup via DNS.

2. **IP Address**

Browsers use DNS (Domain Name System) to convert web addresses (URLs) into IP addresses, which are unique numbers that represent specific devices on the internet. By finding the IP address, the browser can direct the request to the appropriate server.

3. **Request Received on Web Server**

Requests sent through the browser are received by web server software (such as NGINX). These requests contain information about the specific page or file desired.

4. **Search for Requested Files**

The web server software searches for the relevant files in its storage directory. The searched files can be HTML documents, images, or dynamic programmes that generate web content in real-time.

5. **Sending a Response**

Once the file is found, the server sends it back to the browser via the HTTP protocol. If the file is not found, the server will return an error message, such as 404 Not Found. Other errors, such as 403 Forbidden, will be displayed in case of access permission issues.

This process ensures that data from the backend server can be accessed and displayed by the browser on the user side.

## Web Server Configuration
This web server project covers three main criteria:

1. **Setting up a Web Server**

Clone the repository from Dicoding's GitHub.

```
git clone https://github.com/dicodingacademy/a387-jarkom-labs.git
```

Install NGINX and Apache, and ensure both Node.js and NGINX are accessible.

```
sudo apt update  
sudo apt install nginx apache2 
```

2. **Configuring NGINX as a Reverse Proxy Server**

Configure NGINX to forward requests from port 80 to the Node.js web server, allowing seamless communication between clients and the backend server.

3. **Implementing Limit Access in NGINX**

Set up rate limiting in NGINX to restrict access frequency and enhance web server security. This helps mitigate potential denial-of-service (DoS) attacks and ensures stable performance.

This project is designed to provide practical experience in building and configuring a complete web server.

## How to Run This Project
Before running the project, make sure npm is installed on your computer or laptop.

Steps to Run the Project:
- **Install Node Modules**

```
sudo apt update  
sudo apt install nginx apache2 
```

- **Start the Project**

```
sudo apt update  
sudo apt install nginx apache2 
```

- **Access the Project**

Open your browser and go to http://localhost (NGINX) or the appropriate port for your configuration. Example: http://localhost:80


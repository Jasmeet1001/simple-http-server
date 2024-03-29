# **Simple HTTP Server**
This is a simple HTTP server implemented from scratch in Python. The primary goal of this project is to provide a hands-on learning experience for understanding the fundamentals of HTTP server development. It is to help me grasp the inner workings of web servers and gain practical experience in building one.


## **Key Learning Objectives**
+ **Understanding the HTTP protocol:** Exploring the HTTP protocol's request/response format, methods like GET, HEAD and hopefully more, headers, status codes and other essential components.
+ **Socket Programming:** Gain familiaritiy with socket programming concepts for establishing TCP/IP connections, handling incoming requests, managing client-server communication.
+ **Request Parsing and Response Generation:** Learn how to parse incoming HTTP requests, extract relevant information (such as method and path), and generate appropriate responses based on client's response.
+ **Handling Routes and Static Files:** Implement logic for routing incoming requests to specific endpoints and serving static files(such as HTML, CSS, JavaScript) to client.

## **Usage**
1. **Running the Server** 
   ```
   python main.py [-hs <host>] [-p <port>] [-h help ]
   ```
   Default host: 127.0.0.1, port: 8000
2. **Adding Routes** Add your customs routes in routes.py file
3. **Adding Static Files** To add your custom static files(HTML, CSS, Js) create them inside the static folder 
  

## **Let's Collaborate!**
Any and all contributions, feedback, and insights are much appreciated and welcomed if you would like to add new features or enhance the ones that already present.

A Servlet is a Java program that runs on a web server and is used to create dynamic web applications.
It acts as a middle layer between the client (web browser) and the server (database or application logic).

In simple terms:
👉 A Servlet receives a request from the user, processes it (for example, interacts with a database), and then sends a response (usually HTML or data) back to the browser.


🔹 Full Form:

Servlet = Server-side Technology -

🔹 Main Purpose:

To handle HTTP requests and responses in a Java-based web application.


🔹 Servlet Lifecycle

A Servlet goes through 5 main phases during its execution:

1. Loading and Instantiation – Servlet class is loaded into memory.


2. Initialization (init() method) – Called once when the Servlet is created.


3. Request Handling (service() method) – Called every time a client sends a request.


4. Destruction (destroy() method) – Called once when the server shuts down or servlet is unloaded.

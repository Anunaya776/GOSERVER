Go Web Server – Static Files & Form Handling

A lightweight web server built using Go (Golang) and the standard net/http package.
This project demonstrates static file serving, HTTP routing, form handling, and basic error handling without using any external frameworks.

📌 Features

🚀 Starts an HTTP server on port 8080

📁 Serves static files (HTML, CSS, JS)

📝 Handles form submissions using POST requests

🌐 Implements custom routes (/form, /hello)

❌ Handles invalid paths and HTTP methods properly

💡 Uses only Go’s standard library

Open Browser and Test
URL	What You See

http://localhost:8080/	            Home page

http://localhost:8080/form.html     Form page

http://localhost:8080/hello	        Hello message

/form Shows the submitted data on the screen

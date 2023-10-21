<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>CRUD RESTful API</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            text-align: center;
        }
        h2 {
            background-color: #3498db;
            color: #fff;
            padding: 10px;
        }
        .section {
            background-color: #f5f5f5;
            padding: 15px;
            border-radius: 5px;
            margin-top: 15px;
        }
        pre {
            background-color: #34495e;
            color: #fff;
            padding: 10px;
            border-radius: 5px;
        }
        a {
            text-decoration: none;
            color: #3498db;
        }
        a:hover {
            text-decoration: underline;
        }
        footer {
            text-align: center;
            margin-top: 20px;
            background-color: #2c3e50;
            color: #ecf0f1;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>CRUD RESTful API</h1>

        <div class="section">
            <h2>Introduction</h2>
            <p>This CRUD RESTful API, developed by Mukund, provides a simple yet powerful set of functionality for managing blog posts. With just four endpoints, you can easily perform basic CRUD (Create, Read, Update, Delete) operations on blog posts. Below, you'll find all the information you need to get started with this API.</p>
        </div>

        <div class="section">
            <h2>Table of Contents</h2>
            <ul>
                <li><a href="#introduction">Introduction</a></li>
                <li><a href="#endpoints">Endpoints</a></li>
                <li><a href="#getting-started">Getting Started</a></li>
                <li><a href="#usage">Usage</a></li>
                <li><a href="#sample-requests">Sample Requests</a></li>
            </ul>
        </div>

        <div class="section" id="introduction">
            <h2>Introduction</h2>
            <p>This CRUD RESTful API is designed to handle basic operations for blog posts. Whether you're building a simple blogging platform or just need a quick way to manage your content, this API can be a valuable addition to your development toolbox.</p>
        </div>

        <div class="section" id="endpoints">
            <h2>Endpoints</h2>
            <ol>
                <li>
                    <strong>Get All Posts</strong>
                    <ul>
                        <li><strong>Method:</strong> GET</li>
                        <li><strong>URL:</strong> /api/posts</li>
                        <li><strong>Description:</strong> Retrieve a list of all blog posts.</li>
                    </ul>
                </li>
                <li>
                    <strong>Post a New Blog</strong>
                    <ul>
                        <li><strong>Method:</strong> POST</li>
                        <li><strong>URL:</strong> /api/posts</li>
                        <li><strong>Description:</strong> Create a new blog post.</li>
                    </ul>
                </li>
                <li>
                    <strong>Fetch Particular Blog</strong>
                    <ul>
                        <li><strong>Method:</strong> GET</li>
                        <li><strong>URL:</strong> /api/posts/:id</li>
                        <li><strong>Description:</strong> Retrieve a specific blog post by its unique ID.</li>
                    </ul>
                </li>
                <li>
                    <strong>Delete a Blog</strong>
                    <ul>
                        <li><strong>Method:</strong> DELETE</li>
                        <li><strong>URL:</strong> /api/posts/:id</li>
                        <li><strong>Description:</strong> Delete a specific blog post by its unique ID.</li>
                    </ul>
                </li>
            </ol>
        </div>

        <div class="section" id="getting-started">
            <h2>Getting Started</h2>
            <p>To use this API in your project, follow these steps:</p>
            <ol>
                <li>Clone the repository to your local machine:</li>
                <pre>git clone https://github.com/your/Basic-RestFul-CRUD-Api.git</pre>
                <li>Install the required dependencies:</li>
                <pre>npm install</pre>
                <li>Start the server:</li>
                <pre>npm start</pre>
            </ol>
            <p>You can now access the API at <a href="http://localhost:3000/api" target="_blank">http://localhost:3000/api</a>.</p>
        </div>

        <div class="section" id="usage">
            <h2>Usage</h2>
            <p>To interact with the API, you can use tools like <a href="https://www.getpostman.com/" target="_blank">Postman</a> or make HTTP requests from your application. The API follows RESTful principles, so you can use standard HTTP methods (GET, POST, DELETE) to perform the desired actions.</p>
        </div>

        <div class="section" id="sample-requests">
            <h2>Sample Requests</h2>
            <p>Here are some sample HTTP requests to demonstrate how to use the API:</p>
            <pre>GET /api/posts</pre>
            <pre>POST /api/posts<br>Content-Type: application/json<br>{<br>  "title": "My New Blog Post",<br>  "content": "This is the content of my blog post."<br>}</pre>
            <pre>GET /api/posts/1</pre>
            <pre>DELETE /api/posts/1</pre>
        </div>
    </div>

    <footer>
        <p>Feel free to reach out to Mukund at <a href="https://www.linkedin.com/in/muku02" target="_blank">LinkedIn</a> for any questions or feedback related to this API. Happy coding! 🚀</p>
    </footer>
</body>
</html>

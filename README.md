<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1>ASSIGNMENT</h1>

<h2>How to Run the Node.js Project</h2>

<ol>
  <li>Clone the repository to your local machine:</li>
</ol>

<pre><code>git clone https://github.com/Shreyasrana18/Assignment-Node.js.git
cd your-repo
</code></pre>

<ol start="2">
  <li>Install dependencies:</li>
</ol>

<pre><code>npm install
</code></pre>

<ol start="3">
  <li>Run the app in development mode:</li>
</ol>

<pre><code>npm run dev
</code></pre>

<p>This command will start the server, and you can access the API at <a href="http://localhost:5001">http://localhost:5001</a>.</p>

<h2>Testing</h2>

<p>To run tests:</p>

<pre><code>npm test
</code></pre>

<h2>Postman Documentation</h2>

<p>API documentation for the endpoints is available on Postman.</p>

<p><a href="https://documenter.getpostman.com/view/20628687/2s9YsGhYp3">Postman Documentation Link</a></p>

<h3>Authentication Endpoints</h3>

<ul>
  <li><strong>POST /api/auth/signup:</strong> Create a new user account.</li>
  <li><strong>POST /api/auth/login:</strong> Log in to an existing user account and receive an access token.</li>
</ul>

<h3>Note Endpoints</h3>

<ul>
  <li><strong>GET /api/notes:</strong> Get a list of all notes for the authenticated user.</li>
  <li><strong>GET /api/notes/:id:</strong> Get a note by ID for the authenticated user.</li>
  <li><strong>POST /api/notes:</strong> Create a new note for the authenticated user.</li>
  <li><strong>PUT /api/notes/:id:</strong> Update an existing note by ID for the authenticated user.</li>
  <li><strong>DELETE /api/notes/:id:</strong> Delete a note by ID for the authenticated user.</li>
  <li><strong>POST /api/notes/:id/share:</strong> Share a note with another user for the authenticated user.</li>
  <li><strong>GET /api/search?q=:query:</strong> Search for notes based on keywords for the authenticated user.</li>
</ul>

<h2>Testing Details</h2>

<h3>Notes Controller Tests</h3>

<ul>
  <li><strong>Login:</strong> should login a user</li>
  <li><strong>Get Notes:</strong> should get user notes</li>
  <li><strong>Get Note:</strong> should get a specific note</li>
  <li><strong>Create Note:</strong> should create a note</li>
  <li><strong>Update Note:</strong> should update a note</li>
  <li><strong>Share Note:</strong> should share a note with a valid user</li>
  <li><strong>User Not Found:</strong> should fail to share a note with an invalid user</li>
  <li><strong>Note Already Shared:</strong> should fail to share a note that is already shared</li>
  <li><strong>Search Query:</strong> should search for a note</li>
  <li><strong>Delete Note:</strong> should delete a note</li>
  <li><strong>Unauthorized Deletion:</strong> should fail to delete a note without authorization</li>
</ul>

<h2>Frameworks and Database Used</h2>

<p>Framework used:</p>
<ul>
  <li>Node.js</li>
  <li>Express.js</li>
</ul>

<p>Testing Framework & Assertion library used</p>
<ul>
  <li>Mocha</li>
  <li>Chai</li>
</ul>

<p>Database used:</p>
<ul>
  <li>MongoDB</li>
</ul>

## Contact

#### If you have any questions or suggestions, feel free to contact me at shreyas.tech18@gmail.com.

##### Happy coding!
</body>
</html>

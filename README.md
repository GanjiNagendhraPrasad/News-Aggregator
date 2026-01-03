<h1>📰 News Aggregator Web Application</h1>

<h2>📌 Project Overview</h2>
<p>
This project is a <strong>News Aggregator Web Application</strong> that collects news headlines from multiple news sources
and displays them on a single web platform. Users can browse different news articles and, upon clicking any headline,
are redirected to the original news website to read the full article.
</p>

<p>
The main goal of this project is to provide a <strong>centralized, user-friendly interface</strong> where users can access
news from various sources without visiting multiple websites individually.
</p>

<hr>

<h2>🎯 Key Features</h2>
<ul>
  <li>Aggregates news from multiple sources</li>
  <li>Displays news headlines in one place</li>
  <li>Redirects users to original news websites</li>
  <li>Simple and clean user interface</li>
  <li>Client–Server based architecture</li>
</ul>

<hr>

<h2>🛠️ Technologies Used</h2>
<ul>
  <li><strong>HTML</strong> – Structure of the web pages</li>
  <li><strong>CSS</strong> – Styling and layout</li>
  <li><strong>JavaScript</strong> – Client-side logic and interaction</li>
  <li><strong>Node.js</strong> – Backend runtime environment</li>
  <li><strong>Express.js</strong> – Server framework</li>
  <li><strong>News APIs</strong> – Fetching live news data</li>
</ul>

<hr>

<h2>📂 Project Structure</h2>

<pre>
news-aggregator/
 └── server/
     ├── node_modules/
     ├── public/
     │    ├── index.html
     │    ├── index.css
     │    └── index.js
     ├── server.js
     ├── package.json
     └── package-lock.json
</pre>

<hr>

<h2>📁 Folder & File Explanation</h2>

<h3>🔹 server/</h3>
<p>
This folder contains the backend logic of the application. It handles server operations,
API communication, and serves the frontend files.
</p>

<h3>🔸 server.js</h3>
<p>
This is the main backend file of the project. It:
</p>
<ul>
  <li>Creates the server using Express.js</li>
  <li>Handles HTTP requests</li>
  <li>Fetches news data from external APIs</li>
  <li>Sends news data to the frontend</li>
</ul>

<p>
<strong>server.js acts as the brain of the application.</strong>
</p>

<h3>🔸 package.json</h3>
<p>
This file contains project metadata and dependencies required to run the application.
It also defines scripts used to start the server.
</p>

<h3>🔸 package-lock.json</h3>
<p>
This file locks the exact versions of installed dependencies to ensure consistent behavior
across different systems.
</p>

<h3>🔸 node_modules/</h3>
<p>
This folder contains all installed Node.js dependencies. It is automatically generated
using <code>npm install</code> and should not be manually modified.
</p>

<hr>

<h2>📁 public/ (Frontend)</h2>

<h3>🔹 index.html</h3>
<p>
This file defines the structure of the web page. It contains placeholders where
news headlines are dynamically displayed.
</p>

<h3>🔹 index.css</h3>
<p>
This file is responsible for styling the web page, including layout, colors,
fonts, and responsive design.
</p>

<h3>🔹 index.js</h3>
<p>
This JavaScript file handles client-side logic such as:
</p>
<ul>
  <li>Fetching news data from the backend</li>
  <li>Dynamically displaying news headlines</li>
  <li>Handling click events</li>
  <li>Redirecting users to the original news source</li>
</ul>

<hr>

<h2>🔄 Application Workflow</h2>
<ol>
  <li>User opens the website in a browser</li>
  <li><code>index.html</code> loads the structure</li>
  <li><code>index.css</code> styles the page</li>
  <li><code>index.js</code> requests news data from the server</li>
  <li><code>server.js</code> fetches news from APIs</li>
  <li>News headlines are displayed on the webpage</li>
  <li>User clicks a news headline</li>
  <li>User is redirected to the original news website</li>
</ol>

<hr>

<h2>🧠 Why This Is a News Aggregator</h2>
<ul>
  <li>Collects news from multiple sources</li>
  <li>Displays headlines in one centralized platform</li>
  <li>Redirects users to original content</li>
  <li>Does not copy or modify news articles</li>
</ul>

<hr>

<h2>📌 Conclusion</h2>
<p>
This News Aggregator Web Application provides a centralized and efficient way to access
news from various sources. It improves user experience by saving time and offering
easy navigation while respecting content ownership by redirecting users to original
news websites.
</p>

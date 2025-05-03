# learnhtml.com
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Learn HTML Basics</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
      background-color: #f2f2f2;
    }
    h1, h2 {
      color: #333;
    }
    code {
      background-color: #eaeaea;
      padding: 2px 5px;
      border-radius: 5px;
    }
    .box {
      border: 2px solid #888;
      padding: 10px;
      background-color: white;
      margin-bottom: 20px;
    }
    .ads {
      background-color: #fffdd0;
      border: 2px dashed #ffa500;
      padding: 10px;
      margin-bottom: 20px;
      text-align: center;
      font-weight: bold;
    }
    .buttons {
      display: flex;
      gap: 10px;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
    }
    iframe {
      max-width: 100%;
    }
  </style>
</head>
<body>

  <h1>🌐 Learn the Basics of HTML</h1>

  <div class="ads">
    🔥 Your Ad Could Be Here! | Ad Example 🔥
  </div>

  <div class="box">
    <h2>What is HTML?</h2>
    <p>HTML stands for <strong>HyperText Markup Language</strong>. It is used to create web pages and structure content.</p>
  </div>

  <div class="box">
    <h2>Basic HTML Tags</h2>
    <p><code>&lt;h1&gt; to &lt;h6&gt;</code> – Headings from biggest (<code>&lt;h1&gt;</code>) to smallest (<code>&lt;h6&gt;</code>)</p>
    <p><code>&lt;p&gt;</code> – A paragraph tag. It adds text in paragraph form.</p>
    <p><code>&lt;br&gt;</code> – Line break. It moves the next content to a new line.</p>
    <p><code>&lt;a href="URL"&gt;</code> – Creates a link.</p>
    <p><code>&lt;img src="image.jpg"&gt;</code> – Adds an image.</p>
  </div>

  <div class="box">
    <h2>Advanced HTML Tags</h2>
    <p><code>&lt;div&gt;</code> – A container for HTML elements. Useful for layout and styling.</p>
    <p><code>&lt;span&gt;</code> – Inline container, used for styling a small part of text.</p>
    <p><code>&lt;ul&gt;</code>, <code>&lt;ol&gt;</code>, <code>&lt;li&gt;</code> – Lists (unordered, ordered, list item)</p>
    <p><code>&lt;form&gt;</code> – Creates a form to collect input (text, checkbox, etc.)</p>
    <p><code>&lt;input&gt;</code>, <code>&lt;button&gt;</code>, <code>&lt;textarea&gt;</code> – Input elements inside a form</p>
  </div>

  <div class="box">
    <h2>Example Code</h2>
    <pre>
&lt;!DOCTYPE html&gt;
&lt;html&gt;
  &lt;head&gt;
    &lt;title&gt;My First Page&lt;/title&gt;
  &lt;/head&gt;
  &lt;body&gt;
    &lt;h1&gt;Hello World&lt;/h1&gt;
    &lt;p&gt;This is my first webpage.&lt;/p&gt;
  &lt;/body&gt;
&lt;/html&gt;
    </pre>
    <p>This code creates a basic webpage with a title and a paragraph.</p>
  </div>

  <div class="box">
    <h2>📺 Watch HTML Tutorial Videos</h2>
    <p>Here are some helpful YouTube videos to learn HTML:</p>
    <ul>
      <li><a href="https://www.youtube.com/watch?v=UB1O30fR-EE" target="_blank">HTML Full Course – FreeCodeCamp</a></li>
      <li><a href="https://www.youtube.com/watch?v=HcOc7P5BMi4" target="_blank">HTML Tutorial for Beginners – Programming with Mosh</a></li>
    </ul>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/UB1O30fR-EE" frameborder="0" allowfullscreen></iframe>
  </div>

  <div class="ads">
    📢 Sponsored: Learn Web Design in 30 Days!
  </div>

  <div class="box">
    <h2>💬 Review This Page</h2>
    <p>Did you find this page helpful?</p>
    <div class="buttons">
      <button onclick="alert('Thanks for liking it! 😊')">👍 Like</button>
      <button onclick="alert('We will try to improve. 🙏')">👎 Dislike</button>
    </div>
  </div>

</body>
</html>

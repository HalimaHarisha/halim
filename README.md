# halim
# QUESTION
Create a Webpage with Inline and Block Elements. Demonstrate understanding of <span> vs <div>, and other elements.
# PROGRAM
~~~
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Inline vs Block Elements</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    div {
      background-color: #e0f7fa;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #00796b;
    }
    span {
      background-color: #ffe082;
      padding: 4px;
      border: 1px dashed #ff6f00;
    }
    .section {
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <h1>Inline and Block Elements</h1>

  <div class="section">
    <h2>Block Elements</h2>
    <div>This is a &lt;div&gt; — a block-level element.</div>
    <p>This is a &lt;p&gt; (paragraph) — also a block-level element.</p>
    <h3>This is a &lt;h3&gt; heading — block-level as well.</h3>
    <ul>
      <li>&lt;ul&gt; and &lt;li&gt; are block elements used for lists.</li>
    </ul>
  </div>

  <div class="section">
    <h2>Inline Elements</h2>
    <p>This sentence has a <span>&lt;span&gt; inline element</span> inside it.</p>
    <p>
      Some more inline elements:
      <strong>&lt;strong&gt; (bold)</strong>,
      <em>&lt;em&gt; (italic)</em>,
      <a href="#">&lt;a&gt; (link)</a>.
    </p>
    <p>
      Inline elements do not start on a new line and only take up as much width as needed.
    </p>
  </div>

  <div class="section">
    <h2>Difference between &lt;div&gt; and &lt;span&gt;</h2>
    <p>
      <div>This is a div - it creates a new block.</div>
      <p>This is text with a <span>span</span> inside - it stays inline with the text.</p>
    </p>
  </div>

</body>
</html>

~~~
# OUTPUT

![Screenshot 2025-07-01 145518](https://github.com/user-attachments/assets/75bed1b9-568f-428f-9028-3cfbaa552e8e)

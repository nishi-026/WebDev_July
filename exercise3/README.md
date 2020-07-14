## 1. Create a simple page with the heading 'Hello World'.

Below heading Provide two links. Say A. About and B. My Resume: https://pen-pusher.github.io/.

A. Use relative to connect to about page.

B. Use absolute path to connect to the google website and open in a new window or tab. - 10 mins (Mandatory)

 <html>
 <head>
 <title>
      Hyperlink
 </title>
 </head>
 <body>
 <h1>
      Hello World
 </h1>
 <p>
      <a href="home.html" target="_self">About</a>
 <br>
     <a href="https://pen-pusher.github.io/."
       target="_blank">My Resume</a>
  </p>
  </body>
  </html>

"home.html"
<html>
<head>
</head>
<body>
<p>
About:
<br>
Name: Nishi Jigneshkumar Patel
</p>
</body>
</html>

## 2.Create a website with multiple pages(home, about, contact).

- Each page must be having a navigation link to connect to the other pages of the website.
- And each page must have one heading and one paragraph.
- There must be a different background color for each page.
- Use external stylesheet to apply styles. - 25 mins (Mandatory)


  <html>
  <head>
  <title>
      Home page
  </title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
  <h1>
      Home page
  </h1>
  <p>
      This is my home page.
  <br>
      Welcome to my home page
  </p>
  <p>
      <a href="code4.html">Homepage</a> <br>
      <a href="about.html">About</a> <br>
      <a href="contact.html">Contact</a>
  </p>
  </body>
  </html>
    
   "About page" 
   <html>
   <head>
     <link rel="stylesheet" href="style1.css">
  </head>
  <body>
    <h1>
       My About Page
    </h1>
    <p>
       This is my about page
    </p>
    <p>
    <a href="code4.html">HOME</a>
    </p>
  </body>
  </html>
 
 "Contact page"
  <html>
  <head>
    <link rel="stylesheet" href="style3.css">
  </head>
  <body>
    <h1>
      This is my contact page
    </h1>
    <br>
    contact no:8523694170 <br>
    email:priyapatel23@gmail.com <br>
    <p>
    <a href="code4.html">HOME</a>
    </p>
  </body>
  </html>
 
"style.css"
body {
background-color: pink;
}

"style1.css"
body {
background-color: lightgreen;
}

"style3.css"
body {
background-color: lightblue;
}



<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Welcome to Betelgeus Terminal</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      background-color: #000;
      color: #00ff00;
      font-family: 'Courier New', Courier, monospace;
      padding: 20px;
      margin: 0;
    }
    .terminal {
      max-width: 700px;
      margin: auto;
      padding: 20px;
      background-color: #111;
      border: 1px solid #00ff00;
      border-radius: 10px;
      box-shadow: 0 0 10px #00ff00;
    }
    .prompt {
      color: #0f0;
    }
    a {
      color: #0f0;
      text-decoration: underline;
    }
    .blink {
      animation: blink 1s infinite;
    }
    @keyframes blink {
      0%, 50% { opacity: 1; }
      51%, 100% { opacity: 0; }
    }
  </style>
</head>
<body>
  <div class="terminal">
    <p class="prompt">visitor@betelgeus:~$ <span>Welcome to my terminal website!</span></p>
    <p class="prompt">visitor@betelgeus:~$ <span>I'm working on something awesome...</span></p>
    <p class="prompt">visitor@betelgeus:~$ <span>Stay tuned!</span><span class="blink">█</span></p>
    <p class="prompt">visitor@betelgeus:~$ <span><a href="https://github.com/Betelgeus" target="_blank">My GitHub</a></span></p>
  </div>
</body>
</html>

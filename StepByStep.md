1. Adding the needed tags into my head element 
  ```
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Frontend Mentor | Single Price Grid Component</title>
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Karla:wght@400;700&display=swap" rel="stylesheet">
</head>
  ```
  2. Setting up the general styling in css
  ```
  :root {
  /* ### Primary Colors */

  --cyan: hsl(179, 62%, 43%);
  --brt-yellow: hsl(71, 73%, 54%);

  /* ### Neutral Colors */

  --lt-gray: hsl(204, 43%, 93%);
  --grayish-blue: hsl(218, 22%, 67%);
  }

  html {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }

  *, *::before, *::after {
    box-sizing: inherit;
  }

  body {
    max-width: 375px;
    width: 100%;
    min-height: 100vh;
    font-family: 'Karla', sans-serif;
  }
  ```
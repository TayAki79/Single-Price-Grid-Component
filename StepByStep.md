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
    margin: 0 auto;
  }
  ```

  3. The component consists of three sections
  
  4. There's no header element so I leave this out
  
  5. I will seperate the main section in two sections where another two sections will be nested inside the second section since the desktop version needs a flexbox styling for the last two sections on the lower half of the site

  6. Adding the appropriate tags to my html
    ```
    <main class="main-cont">
    <!-- ### Hero Section ### -->
    <section class="hero-sec">
      <h3 class="hero-title">Join our community</h3>
      <h4 class="sub-title">30-day, hassle-free money back guarantee</h4>
      <p class="hero-desc">
        Gain access to our full library of tutorials along with expert code reviews.
        Perfect for any developers who are serious about honing their skills.
      </p>
    </section>

<!-- ### Flexbox section ### -->

    <section class="flex-sec">

      <!-- *** Price section ***  -->

      <section class="price-sec">
        <h4 class="price-sec-title">Monthly Subscription</h4>
        <div class="pricing">
          <div class="price">$29</div>
          <div class="frequency">per month</div>
        </div>
        <p class="price-desc">Full access for less than $1 a day</p>
        <button type="submit">Sign Up</button>
      </section>

      <!-- *** Why Us section *** -->

      <section class="why-us">
        <h4 class="why-us">Why Us</h4>
        <ul>
          <li>Tutorials by industry experts</li>
          <li>Peer & expert code review</li>
          <li>Coding exercises</li>
          <li>Access to our GitHub repos</li>
          <li>Community forum</li>
          <li>Flashcard decks</li>
          <li>New videos every week</li>
        </ul>
      </section>
    </section>
  </main>

  ```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name - Personal Bio</title>
  <style>
    /* GitHub-like theme colors */
    :root {
      --bg-color: #f6f8fa;
      --text-color: #24292e;
      --link-color: #0366d6;
      --font-stack: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
    }

    body {
      margin: 0;
      font-family: var(--font-stack);
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
      padding: 1rem;
    }

    .container {
      max-width: 600px;
      margin: 0 auto;
      background: #fff;
      padding: 2rem;
      border-radius: 6px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }

    .profile-pic {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      display: block;
      margin: 0 auto 1rem auto;
    }

    h1 {
      text-align: center;
      font-size: 1.8rem;
      margin-bottom: 0.5rem;
    }

    .bio {
      text-align: center;
      font-size: 1rem;
      margin-bottom: 1.5rem;
    }

    .contact-info {
      font-size: 0.95rem;
      text-align: center;
      margin-bottom: 1rem;
    }

    .contact-info a {
      color: var(--link-color);
      text-decoration: none;
    }

    .contact-info a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      font-size: 0.8rem;
      color: #586069;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- ✅ Replace 'profile.jpg' with your actual profile image -->
    <img src="profile.jpg" alt="Profile Photo" class="profile-pic" />

    <!-- ✅ Replace 'Your Name' with your actual name -->
    <h1>Your Name</h1>

    <!-- ✅ Replace the paragraph below with your bio/description -->
    <p class="bio">
      This is a short placeholder bio about you. Describe your background, interests, profession, or anything else you'd like visitors to know.
    </p>

    <div class="contact-info">
      <!-- ✅ Replace placeholders below with real contact info -->
      <p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a></p>
      <p>Phone: <a href="tel:+1234567890">+1 (234) 567-890</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/yourusername" target="_blank">linkedin.com/in/yourusername</a></p>
    </div>

    <footer>
      &copy; 2025 Your Name
    </footer>
  </div>
</body>
</html>

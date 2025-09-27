<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name - Bio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #121212;
      color: #e0e0e0;
      line-height: 1.6;
    }

    .container {
      max-width: 600px;
      margin: 0 auto;
      padding: 2rem 1rem;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .profile-photo {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid #333;
      margin-bottom: 1rem;
    }

    h1 {
      font-size: 1.8rem;
      margin: 0.5rem 0 0.2rem;
    }

    h2 {
      font-size: 1rem;
      font-weight: normal;
      color: #aaaaaa;
      margin: 0 0 1rem;
    }

    p.bio {
      text-align: center;
      padding: 0 1rem;
    }

    .contact {
      margin-top: 2rem;
      font-size: 0.9rem;
    }

    .contact a {
      color: #4db8ff;
      text-decoration: none;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    @media (min-width: 600px) {
      h1 {
        font-size: 2.2rem;
      }

      p.bio {
        font-size: 1.05rem;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- 🖼️ Profile Picture Placeholder -->
    <img src="https://media.licdn.com/dms/image/v2/D5603AQGc0AoNyDb4gg/profile-displayphoto-scale_200_200/B56ZkKZTXfIAAY-/0/1756816030217?e=1761782400&v=beta&t=aJd4sm2jE_1zAVRGVY04SBg0yW44PkdW-HRFfK-0fY4" alt="" class="profile-photo" />

    <!-- 🙋 Name and Title -->
    <h1>ROBERT DATTOLO</h1>
    <h2>FOUNDER (Concise CS, LLC)</h2>

    <!-- 📝 Short Bio -->
    <p class="bio">
      Founder, Concise CS, LLC, Information Technology Services. ✦ Interested in hearing about what opportunity I can help you succeed in. Open to remote and contract work.
    </p>

    <!-- 📞 Contact Information -->
    <div class="contact">
      <p>Email: <a href="mailto:robert@concisecs.com">robert@concisecs.com</a></p>
      <p>Phone: <a href="tel:+1234567890">(586) 382-6900</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/robertdattolo" target="_blank">linkedin.com/in/yourprofile</a></p>
    </div>
  </div>
</body>
</html>

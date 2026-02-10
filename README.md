<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>My GitHub Website</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      margin: 0;
      background: #0f172a;
      color: #e5e7eb;
    }
    header {
      padding: 2rem;
      text-align: center;
      background: #111827;
      border-bottom: 1px solid #1f2937;
    }
    main {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1.5rem;
    }
    h1 {
      margin-bottom: 0.5rem;
    }
    .card {
      background: #111827;
      border-radius: 0.75rem;
      padding: 1.5rem;
      margin-top: 1.5rem;
      border: 1px solid #1f2937;
    }
    a {
      color: #38bdf8;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.85rem;
      color: #9ca3af;
    }
  </style>
</head>
<body>
  <header>
    <h1>Hi, I'm Bharat</h1>
    <p>Welcome to my GitHub-powered website.</p>
  </header>

  <main>
    <section class="card">
      <h2>About me</h2>
      <p>
        I’m building projects, learning, and sharing my journey here.
      </p>
    </section>

    <section class="card">
      <h2>Projects</h2>
      <ul>
        <li><a href="#">Project 1</a> – Short description here.</li>
        <li><a href="#">Project 2</a> – Short description here.</li>
      </ul>
    </section>

    <section class="card">
      <h2>Contact</h2>
      <p>
        You can find me on <a href="https://github.com/your-username" target="_blank">GitHub</a>.
      </p>
    </section>
  </main>

  <footer>
    © <span id="year"></span> Bharat · Built with GitHub Pages
  </footer>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>

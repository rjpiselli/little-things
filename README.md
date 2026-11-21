<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Little Things</title>
  <style>
    :root {
      --primary: #D92A63;
      --bg: #f8f9fb;
      --card-bg: #ffffff;
      --text-main: #18181b;
      --text-muted: #52525b;
      --border: #e4e4e7;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background-color: var(--bg);
      color: var(--text-main);
      line-height: 1.65;
      padding: 2rem 1rem;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .container {
      width: 100%;
      max-width: 680px;
      margin: 0 auto;
    }

    .card {
      background: var(--card-bg);
      border: 1px solid var(--border);
      border-top: 4px solid var(--primary);
      border-radius: 16px;
      padding: 2.5rem 1.75rem;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.03);
      text-align: center;
    }

    h1 {
      font-size: 2rem;
      font-weight: 700;
      letter-spacing: -0.02em;
      color: var(--text-main);
      margin-bottom: 0.75rem;
    }

    .meta {
      color: var(--text-muted);
      font-size: 1.05rem;
    }
  </style>
</head>
<body>
  <main class="container">
    <section class="card">
      <h1>Little Things</h1>
      <p class="meta">Created in 2026 by Ryan Piselli</p>
    </section>
  </main>
</body>
</html>

# 💑 Our Date Itinerary – A Simple GitHub Pages Site

Welcome to our personal itinerary site! This page keeps track of all the special dates we've had and the adventures we've planned. You can use it as a GitHub Pages website to celebrate your memories with your partner 💖

---

## 🌐 How to Use

1. Create a GitHub repository (e.g., `our-dates`)
2. Copy the two files below into the repo:
   - `index.html`
   - `style.css`
3. Go to **Settings > Pages**
4. Under **"Source"**, choose:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Visit your site at:  
   `https://yourusername.github.io/your-repo-name`

---

## 📄 `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Our Date Itinerary 💖</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Our Date Itinerary 💑</h1>
    <p>Moments we'll never forget...</p>
  </header>

  <main>
    <section class="itinerary">
      <article>
        <h2>🌸 June 5, 2025</h2>
        <p><strong>Plan:</strong> Picnic at Central Park, then movie night at home 🍿</p>
      </article>

      <article>
        <h2>🌅 June 12, 2025</h2>
        <p><strong>Plan:</strong> Sunset dinner at the pier, followed by ice cream 🍨</p>
      </article>

      <!-- Add more date plans here -->
    </section>
  </main>

  <footer>
    <p>Made with ❤️ by Jordany & [Her Name]</p>
  </footer>
</body>
</html>

# task4
project/
│
├── index.html
├── style.css
├── README.md
└── screenshots/
    ├── desktop.png
    └── mobile.png
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Responsive Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <nav>
      <ul class="nav">
        <li>Home</li>
        <li>About</li>
        <li>Contact</li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h1>Welcome to My Website</h1>
      <p>This is a sample responsive website.</p>
    </section>
    <div class="columns">
      <div class="column">Column 1</div>
      <div class="column">Column 2</div>
    </div>
  </main>

  <footer>
    <p>&copy; 2025</p>
  </footer>
</body>
</html>
/* Desktop Styles */
body {
  font-family: sans-serif;
  margin: 0;
  padding: 0;
}

.nav {
  display: flex;
  gap: 1rem;
  background: #333;
  color: white;
  padding: 1rem;
  list-style: none;
  justify-content: center;
}

.columns {
  display: flex;
  justify-content: space-around;
  padding: 2rem;
}

.column {
  width: 45%;
  background: #eee;
  padding: 1rem;
  box-sizing: border-box;
}

/* ✅ Mobile-Friendly Styles */
@media (max-width: 768px) {
  .nav {
    flex-direction: column;
    align-items: center;
  }

  .columns {
    flex-direction: column;
    padding: 1rem;
  }

  .column {
    width: 100%;
    margin-bottom: 1rem;
  }

  h1 {
    font-size: 1.5rem;
  }

  p {
    font-size: 1rem;
  }
}
# Responsive Web Page Using CSS Media Queries

## 📱 Objective
Convert a static desktop-only web page into a mobile-responsive layout using CSS media queries.

## 🛠 Tools Used
- HTML5
- CSS3 with Media Queries
- Google Chrome DevTools
- VS Code

## 🚀 Features
- Responsive layout for mobile (max-width: 768px)
- Flexbox-based column stacking on mobile
- Navigation menu adapts to vertical stack
- Scalable images and content
- Viewport meta tag for proper scaling

## 📸 Screenshots

### ✅ Desktop View
![Desktop View](screenshots/desktop.png)

### 📱 Mobile View
![Mobile View](screenshots/mobile.png)

## 🗂 Folder Structure


## 💡 What I Learned
- How to use media queries for responsive design
- Importance of mobile-first layout
- Flexbox layout tricks for responsiveness
- Testing responsiveness with Chrome DevTools

## 🌐 How to Run
1. Clone the repo
2. Open `index.html` in any browser
3. Open DevTools → Toggle Device Toolbar to test responsiveness

---


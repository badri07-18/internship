# Internship Project Files - Badri S U (Thiranex Web Development Internship)

| Folder | Report figure | What it is |
|---|---|---|
| `week2-portfolio-page/` | Figure 3.3 | Responsive portfolio page (HTML5, Flexbox, Grid, media queries). Open `index.html` in a browser. |
| `week3-todo-app/` | Figure 3.4 | To-do app with add / complete / delete / filter, saved in localStorage. Open `index.html`. |
| `week4-final-project-ecommerce-store/` | Figure 3.6 | TechStore: Node.js + Express + MongoDB + JWT. See below. |
| `screenshots/` | - | Every screenshot used in the report, plus extra TechStore pages (products, product detail, cart, checkout, orders, login). |

## Run TechStore
1. Install Node.js and MongoDB, and make sure MongoDB is running.
2. `cd week4-final-project-ecommerce-store`
3. `npm install`
4. Copy `.env.example` to `.env` and set a long random `JWT_SECRET`.
5. `node seeder.js` (adds sample products and users; passwords are hashed)
6. `npm run server`, then open http://localhost:5000
7. Sign in with `john@example.com` / `password123` (or `admin@example.com` / `password123`).

Never commit `.env` to GitHub. It is listed in `.gitignore`.

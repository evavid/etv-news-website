# eTV News Website

**A full-stack, mobile-friendly news website for eTV, a local Slovenian TV station: articles, live programme, YouTube integration and an editorial back office.**

Four of us built it for the *Web Programming* course in the undergraduate Multimedia programme at the Faculty of Computer and Information Science, University of Ljubljana (2021).

<img width="1400" alt="Home page" src="https://user-images.githubusercontent.com/72226231/121302455-023f1580-c8fa-11eb-97a0-23e5ccbf3423.png">

## Features

- **Responsive home page** with the latest news by category, paginated article lists, and a live programme page.
- **Search** across website articles and the station's YouTube channel at the same time.
- **Roles:** readers, editors (*urednik*) who write and publish articles, and admins who manage users and their permissions.
- **Comments** on articles.
- **REST API** with full Swagger documentation.
- **Installable as an app** (progressive web app support through the Angular service worker).

| Editor profile | Admin profile |
|---|---|
| <img alt="Editor profile" src="https://user-images.githubusercontent.com/72226231/121302472-0834f680-c8fa-11eb-8ab5-888a8b91bab0.png"> | <img alt="Admin profile" src="https://user-images.githubusercontent.com/72226231/121302468-0703c980-c8fa-11eb-91bc-9678177e68e6.png"> |

| User permissions | Search results |
|---|---|
| <img alt="User permissions editor" src="https://user-images.githubusercontent.com/72226231/121302469-079c6000-c8fa-11eb-92c0-15d777d2a351.png"> | <img alt="Search results" src="https://user-images.githubusercontent.com/72226231/121302471-079c6000-c8fa-11eb-8d55-db0a53aa3c6c.png"> |

## My part

I worked on the **front end and user experience**: pagination, HTML templates and UX improvements across the site.

## Tech

- **Front end:** Angular 11, Bootstrap (ngx-bootstrap)
- **Back end:** Node.js, Express, REST API documented with Swagger
- **Data and auth:** MongoDB with Mongoose, Passport and JSON Web Tokens
- **Testing and deployment:** Mocha, Docker (`docker-compose.yml`), Heroku (`Procfile`)

## Run it locally

You need Node.js and MongoDB (local, or a free MongoDB Atlas cluster). You can also start everything with Docker:

```bash
git clone https://github.com/evavid/etv-news-website.git
cd etv-news-website
docker compose up      # or: npm install && npm start
```

## Team

Matjaž Bevc · Mark Breznik · Blaž Pridgar · Eva Vidmar

## License

MIT. See [LICENSE](LICENSE).

---

*University project (2021), not actively maintained.*

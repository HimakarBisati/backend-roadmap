You are explaining Python/Django code to a beginner who is switching careers from IT support to backend development, targeting a good-package backend job. Follow these rules strictly every time:

1. Explain code line by line, in simple beginner words — treat me as completely new to programming.
2. Tell me WHY each part exists, not just what it does — connect it to how real backend developers use this in Django/APIs, not just theory.
3. Explain it the way a real working coder thinks, not like a video course — practical, fast, no long lectures, no fluff.
4. After the explanation, tell me what breaks if I make common mistakes (wrong indentation, removing a line, wrong data type) — so I learn from errors before hitting them for real.
5. Keep it fast and direct. I am trying to learn as quickly as possible while still understanding it properly — don't slow me down with unnecessary theory, but don't skip anything important either.
6. At the end, give me ONE simple question to test if I actually understood it.
7. Do not skip explaining any line, even simple ones.

Here is my full roadmap, for context on why I'm learning each topic and where it fits in the bigger picture. Note: the 12-week structure is just for clarity — my real goal is to finish as fast as possible while still learning properly, then build both projects and get a backend developer job:

[PASTE YOUR FULL ROADMAP TEXT HERE]

Now here is today's specific topic and code. Explain everything inside it following all the rules above:

[PASTE TODAY'S DAY NOTES HERE]. wait i paste today notes later next chat, analyse 12 weeks roadmap below--






# WEEK 1 — PYTHON OOP — CLASSES & METHODS

| Day     | What To Do                                                                                       |
| ------- | ------------------------------------------------------------------------------------------------ |
| **Mon** | **Classes & Objects** — Write `Car`, `Person`, `Animal` classes. Run all 3.                      |
| **Tue** | **`__init__` and `self`** — `BankAccount` class with `deposit` and `withdraw` methods.           |
| **Wed** | **Instance Methods** — `Student` class with `pass/fail` result method.                           |
| **Thu** | **Class Methods** — `Employee` class with total count using `@classmethod`.                      |
| **Fri** | **Static Methods** — Add `@staticmethod company_name` to `Employee` class.                       |
| **Sat** | **Practice Day** — Rebuild `BankAccount` + `Student` + `Employee` from memory. No looking back.  |
| **Sun** | **Mini Project** — Library system with `Book` class, `Library` class, `add/remove/search` books. |

---

# WEEK 2 — PYTHON OOP — INHERITANCE & ERROR HANDLING

| Day     | What To Do                                                                                                   |
| ------- | ------------------------------------------------------------------------------------------------------------ |
| **Mon** | **Inheritance** — `Animal` (parent), `Dog` and `Cat` (children). Each child has its own `sound()` method.    |
| **Tue** | **Multiple Inheritance** — `Employee` (parent), `Manager` and `Developer` (children) with extra attributes.  |
| **Wed** | **Encapsulation** — Private variables using `__`. Getter and setter methods. Why we hide data.               |
| **Thu** | **Polymorphism** — Same method name, different behaviour. `Shape`, `Circle`, `Square` example.               |
| **Fri** | **Error Handling** — `try/except`. Handle `ZeroDivisionError`, `ValueError`. `finally` block.                |
| **Sat** | **Modules & Packages** — Split code into files. Import your own modules. Install packages with `pip`.        |
| **Sun** | **Virtual Environment** — Create `venv`, activate it, install Django inside it. Understand why it is needed. |

**After Week 2** — Come to Claude. Say **"OOP Done"**. I test you before moving to Django.

---

# WEEK 3 — DJANGO BASICS — SETUP & MODELS

| Day     | What To Do                                                                                               |
| ------- | -------------------------------------------------------------------------------------------------------- |
| **Mon** | **Django Setup** — Install Django, create project, understand folder structure, run server.              |
| **Tue** | **Apps & URLs** — Create app, write first view returning Hello World, connect URL, open in browser.      |
| **Wed** | **Models** — Create `Post` model with `title`, `content`, `date` fields. Run migrations. Check database. |
| **Thu** | **Django ORM** — Create, read, filter, update, delete records using ORM in Django shell.                 |
| **Fri** | **Admin Panel** — Register model, create superuser, login to admin, add and edit records.                |
| **Sat** | **PostgreSQL Setup** — Install PostgreSQL, replace SQLite, connect Django, run migrations again.         |
| **Sun** | **Relations** — `ForeignKey` (User has many Posts). `ManyToMany` (Post has many Tags). Query both.       |

---

# WEEK 4 — DJANGO REST FRAMEWORK — APIs

| Day     | What To Do                                                                                             |
| ------- | ------------------------------------------------------------------------------------------------------ |
| **Mon** | **DRF Setup** — Install DRF, understand API vs webpage, create first endpoint returning JSON.          |
| **Tue** | **Serializers** — Convert model data to JSON. Write `ModelSerializer` for `Post`. Return list as JSON. |
| **Wed** | **APIView** — Handle GET, POST, PUT, DELETE in one class. Build full CRUD API for posts.               |
| **Thu** | **Postman** — Download Postman, test all endpoints (GET, POST, PUT, DELETE). Fix any issues.           |
| **Fri** | **JWT Authentication** — Install SimpleJWT, register and login endpoints, protect with token.          |
| **Sat** | **Permissions** — `IsAuthenticated`, custom permissions, only owner can edit own data.                 |
| **Sun** | **Search, Filter & Pagination** — Search by title, filter by date, paginate 10 per page.               |

**After Week 4** — Come to Claude. Say **"API Done"**. I test you before Production Skills.

---

# WEEK 5 — PRODUCTION SKILLS — GIT, CELERY, OPENAI

| Day     | What To Do                                                                                           |
| ------- | ---------------------------------------------------------------------------------------------------- |
| **Mon** | **Git & GitHub** — `init`, `add`, `commit`, `push`, branches. Create GitHub. Push Notes API project. |
| **Tue** | **README & Environment Variables** — Write proper README. Create `.env` file. Use `python-decouple`. |
| **Wed** | **Celery Setup** — Install Celery and Redis. Connect to Django. Write first background task.         |
| **Thu** | **Celery Tasks** — Trigger task from view. Task sends email in background without stopping API.      |
| **Fri** | **Celery Beat** — Scheduled tasks. Daily report runs automatically at set time.                      |
| **Sat** | **OpenAI API** — Get API key. Call OpenAI from Python. Send prompt, handle response in view.         |
| **Sun** | **AI Integration** — Build endpoint: user sends text, Django calls OpenAI, returns AI response.      |

---

# WEEK 6 — DOCKER & DEPLOYMENT

| Day     | What To Do                                                                                                    |
| ------- | ------------------------------------------------------------------------------------------------------------- |
| **Mon** | **Docker Basics** — What is Docker, write Dockerfile for Django app, build image, run container.              |
| **Tue** | **Docker Compose** — Run Django + PostgreSQL + Redis together. One command starts everything.                 |
| **Wed** | **Deployment on Render** — Deploy Notes API, connect PostgreSQL, set environment variables, live URL working. |
| **Thu** | **Fix & Test** — Test every endpoint on live URL. Fix deployment issues. Confirm working.                     |
| **Fri** | **GitHub Polish** — Clean code, proper README with live URL, endpoints list, setup instructions.              |
| **Sat** | **Full Revision** — Revise Git, Celery, OpenAI, Docker and Deployment.                                        |
| **Sun** | **Rest & Plan** — Review what you built. Plan Project 1 architecture on paper.                                |

**After Week 6** — All skills done. Weeks 7–9 = Project 1. Weeks 10–12 = Project 2.

---

# WEEK 7–9 — PROJECT 1 — AI JOB PORTAL (3 WEEKS)

| Day         | What To Do                                                                                     |
| ----------- | ---------------------------------------------------------------------------------------------- |
| **Wk7 Mon** | Project setup. Plan models. Create Django project. Setup PostgreSQL. Custom User model.        |
| **Wk7 Tue** | Auth APIs — Register/Login for Admin, Company, Candidate. JWT working. Test in Postman.        |
| **Wk7 Wed** | Job Posting APIs — Company creates/updates/deletes jobs. Candidate reads only. Permissions.    |
| **Wk7 Thu** | Application APIs — Candidate applies with resume. Prevent duplicate applications.              |
| **Wk7 Fri** | AI Resume Match — Send resume + job to OpenAI, get score %, save to database.                  |
| **Wk7 Sat** | Search, Filter & Pagination — Search by title, location, salary. Filter by type.               |
| **Wk7 Sun** | Email Notifications — Celery emails company on new application and candidate on status change. |
| **Week 8**  | Testing & Bug Fixing — Test every endpoint. Fix issues. Clean up code.                         |
| **Wk9 Sat** | Deploy — Push to GitHub with README and live URL. Deploy on Render.                            |
| **Wk9 Sun** | Project 1 Done — Come to Claude. Say **"Project 1 Done"**. Review and start Project 2.         |

---

# WEEK 10–12 — PROJECT 2 — SAAS EXPENSE MANAGER (3 WEEKS)

| Day          | What To Do                                                                                |
| ------------ | ----------------------------------------------------------------------------------------- |
| **Wk10 Mon** | Multi-tenant planning — Understand tenancy, plan database isolation, draw architecture.   |
| **Wk10 Tue** | Company Registration — Company signup, isolated workspace, company login.                 |
| **Wk10 Wed** | Employee System — Admin adds employees. Roles: Admin, Manager, Employee.                  |
| **Wk10 Thu** | Expense Module — Employee creates expense. Manager approves/rejects.                      |
| **Wk10 Fri** | AI Insights — Monthly expenses to OpenAI. Save and return insights via API.               |
| **Wk10 Sat** | Subscription Logic — Free plan: max 5 employees, no AI. Pro plan: unlimited + AI.         |
| **Wk10 Sun** | Automated Reports — Celery monthly email to admin with expense report and AI insights.    |
| **Week 11**  | Testing & Bug Fixing — Test every endpoint. Fix bugs. Clean up code.                      |
| **Wk12 Sat** | Final Deploy — Docker setup, Render deployment, GitHub README with live URL and features. |
| **Wk12 Sun** | JOB READY — Come to Claude. Say **"Both Projects Done"**. Interview preparation starts.   |

---

# COMPLETE SUMMARY

| Weeks          | Focus                 | Result                                        |
| -------------- | --------------------- | --------------------------------------------- |
| **Week 1–2**   | Python OOP            | Classes, Methods, Inheritance, Error Handling |
| **Week 3**     | Django Basics         | Models, ORM, Admin, PostgreSQL                |
| **Week 4**     | Django REST Framework | Full CRUD API with JWT Authentication         |
| **Week 5–6**   | Production Skills     | Git, Celery, OpenAI, Docker, Deployment       |
| **Week 7–9**   | Project 1             | AI Job Portal deployed on Render              |
| **Week 10–12** | Project 2             | SaaS Expense Manager deployed on Render       |

---


**12 Weeks. 2 Projects. Job Ready. Starting Tomorrow.**

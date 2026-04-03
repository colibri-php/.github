<p align="center">
  <strong>Colibri</strong> by Québec Studio<br>
  A lightweight file-based PHP micro-framework.
</p>

---

Create a file, get a route. No registration, no configuration, no ceremony.

Colibri is a PHP 8.4+ micro-framework for developers who want to ship small sites without carrying an enterprise framework. Inspired by Laravel's elegance, built for simplicity.

### Features

🗂 **File-based routing** — `routes/web/about.latte` → `/about`<br>
🎨 **Latte templating** — auto-layouts, custom tags, contextual auto-escaping<br>
🌍 **i18n built-in** — JSON translations, locale prefixes, language switcher<br>
🗄 **Database optional** — SQLite/MySQL via Medoo, or flat-file JSON with `Data::`<br>
🔐 **Auth** — session-based with DB or file drivers<br>
🛡 **Middleware** — cascading `_middleware.php`, built-in CSRF, CORS, rate limiting<br>
📧 **Mail** — PHPMailer with driver pattern (SMTP, sendmail, log)<br>
🖼 **Image processing** — resize, crop, thumbnail with auto-caching<br>
⚡ **HTMX & Vite** — native HTMX support, optional Vite integration<br>
🔧 **CLI** — `php colibri serve`, `migrate`, `make:page`, `cache:clear`

### Quick Start

```bash
composer create-project colibri-php/colibri my-project --stability=alpha
cd my-project
cp .env.example .env
php colibri serve
```

### Repositories

| Repo | Description |
|---|---|
| [**framework**](https://github.com/colibri-php/framework) | The core package (Composer library) |
| [**colibri**](https://github.com/colibri-php/colibri) | Project skeleton |
| [**docs**](https://github.com/colibri-php/docs) | Documentation (21 guides) |
| [**starter-portfolio**](https://github.com/colibri-php/starter-portfolio) | Portfolio starter — flat-file, bilingual, no database |
| [**starter-api**](https://github.com/colibri-php/starter-api) | API starter — URL shortener with SQLite + OpenAPI |

### Starter Kits

```bash
# Portfolio (no database, i18n, contact form)
composer create-project colibri-php/starter-portfolio my-site --stability=alpha

# API (SQLite, auth, CRUD, rate limiting)
composer create-project colibri-php/starter-api my-api --stability=alpha
```

### Why "Colibri"?

Québec Studio's mascot is the Snowy Owl (*Harfang des neiges*), the official bird emblem of Québec. A micro-framework built by us deserved to be a small bird — so we picked the hummingbird: tiny, fast, and surprisingly powerful.

### Philosophy

> Laravel is a Swiss Army knife. If you only need the screwdriver, carrying the whole knife is unnecessary weight. Colibri is the screwdriver.

5 hand-picked dependencies. ~70 source files. 300 tests. The entire framework fits in your head.

[Read the full introduction →](https://github.com/colibri-php/docs/blob/main/00-introduction.md)

---

<p align="center">
  MIT License · Fièrement créé en Abitibi-Témiscamingue, pour le monde!
</p>

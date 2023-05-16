<h1 align="center">
    <img alt="Shopper" src="./.github/logo.svg" />
</h1>

<p align="center">
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-install">Install</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-local-running">Local Running</a>
</p>

<br>

## 🚀 Technologies

The technologies used in this project are the following:

- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)
- [Fastify](https://www.fastify.io/)
- [MySQL](https://www.mysql.com/)
- [React](https://reactjs.org)
- [Tailwindcss](https://tailwindcss.com/)

## 💻 Install

This project requires that you have [Node.js](https://nodejs.org/en/) and [MySQL](https://www.mysql.com/) installed and ready to use.

Run the database.sql script on MySQL to create the tables and populate it with sample data.

After that, clone the repository:

```bash
git clone https://github.com/nbc7/shopper-price-update.git
```

Navigate to the project directory:

```bash
cd shopper-price-update
```

Now you can navigate to the server directory or to the web app directory and run them locally.

## ⚙ Local Running

**Server:**

Make sure you are on the correct directory.

Install dependencies

```bash
npm install
```

Rename the `.env.example` file to `.env` and replace the values with your MySQL credentials.

Start the server

```bash
npm run dev
```

The server is now running on your [localhost](http://localhost:8080/) (default port 8080)

#

**Web app:**

Make sure the server is running and you are on the correct directory.

Install dependencies

```bash
npm install
```

Start the server

```bash
npm run dev
```

The web app is now running on your [localhost](http://localhost:5173/) (default port 5173)

#

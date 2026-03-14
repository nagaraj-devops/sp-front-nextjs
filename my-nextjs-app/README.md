# my-nextjs-app

A Next.js app (App Router) bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

---

## ✅ Quick start (clone + run)

### 1) Clone the repository

```bash
git clone https://github.com/<your-org>/<your-repo>.git
cd my-nextjs-app
```

> Replace `<your-org>/<your-repo>` with the correct GitHub org and repo name.

### 2) Install dependencies

```bash
npm install
```

### 3) Start in development mode

```bash
npm run dev
```

Open your browser at: http://localhost:3000

---

## 🐳 Run using Docker

This project includes a `Dockerfile` so you can build and run it inside a container.

### Build the Docker image

```bash
docker build -t my-nextjs-app:latest .
```

### Run the Docker container

```bash
docker run --rm -p 3000:3000 my-nextjs-app:latest
```

Then open: http://localhost:3000

> Tip: if you want live-reload inside Docker, mount the source and use `npm run dev` in the container.

---

## 🔧 Useful commands

```bash
npm run dev       # development mode (hot reload)
npm run build     # production build
npm run start     # start production build
npm run lint      # run ESLint
```

---

## 📚 Learn more

- [Next.js docs](https://nextjs.org/docs)
- [Next.js deployment](https://nextjs.org/docs/app/building-your-application/deploying)

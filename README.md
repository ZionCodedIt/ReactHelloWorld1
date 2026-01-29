# 🚀 React Hello World App

A simple React app that displays a styled "Hello, World!" message. This project also demonstrates containerization using Docker.

---

## 📦 Dependencies

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/)
- [Docker](https://www.docker.com/) (optional, for containerized deployment)

---

## 🔧 Local setup

1. Clone the repository

	```bash
	git clone git@github.com:ZionCodedIt/ReactHelloWorld1.git
	cd ReactHelloWorld1
	```

2. Install dependencies

	```bash
	npm install
	```

3. Run the app

	```bash
	npm start
	```

The app should now be running at http://localhost:3000.

---

## 🛠 Build for production (optional)

```bash
npm run build
```

This creates a production-ready build in the build/ directory.

---

## 🐳 Docker build & run (optional)

1. Build the Docker image

	```bash
	docker build -t react-hello-world .
	```

2. Run the container

	```bash
	docker run -p 3000:3000 react-hello-world
	```

Visit http://localhost:3000.

---

## ✍🏽 Author

Zion Egzaibher Horn  
🧠 Morehouse College • Software Engineering  
🌐 GitHub: ZionCodedIt
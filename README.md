# 🕹️ Pong42

**Pong42** is a fullstack project made for 42 school by a team of 3 👥: [Emma](https://github.com/emma-blnch), [Matthieu](https://github.com/matthieugalvez) and myself. It's a **web app** that allows users to play the game *Pong* in real time with statistics, tournament mode, AI bot and much more!

## 🌟 Project's objectives

- Develop a single-page application to play Pong online.
- Implement a complete user management system (signing in, profils, friendslist...).
- Offer a fluid and responsive interface, optimized for user experience.
- Maintain the security (XSS, SQLi, HTTPS...) and the robustness of the application.

## ⚙️ Technical stack

- **Front-end:** TypeScript, Vite, Tailwind CSS  
- **Back-end:** Node.js with Fastify  
- **API:** Route development and protection for client-server interaction  
- **Database:** SQLite  
- **Infrastructure:** Docker (deployment with a single `docker-compose`)

## 👥 My role

I worked on:
- the **front-end**: interface design, integration, UI component management, compliance with SPA constraints.
- the **back-end**: user management, creation of a restful API following strict CRUD rules and a service-controller-ORM logic.

## 📝 What I learned

- Construction of a **fullstack architecture** using modern technologies.
- Implementation of a secure, high-performance **API**.
- Teamwork on a long-term project: versioning management (Git), code reviews, planning.
- Optimization of a SPA (Single-Page Application) for a seamless experience.

## 🚀 Démo   

**Screenshots:**   
![index-page](/demo/indexpage.png)   

![home-page](/demo/homepage.png)   

**Demo video:**   
![demo-gif](/demo/42pong.gif)   


## 👾 How to try it?

You need to update *NODE* on your session before running:

```
# Download and install nvm:
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

# in lieu of restarting the shell
\. "$HOME/.nvm/nvm.sh"

# Download and install Node.js:
nvm install 24

# Verify the Node.js version:
node -v # Should print "v24.1.0".
nvm current # Should print "v24.1.0".

# Verify npm version:
npm -v # Should print "11.3.0".
```

Then you can just `make build-dev` to launch the application. You will be able to access our site by copying `http://localhost:5173` in *Firefox* or *Chrome*.   
Once you are done you can `make clean-docker` to exit cleanly.   

🎮 ENJOY !

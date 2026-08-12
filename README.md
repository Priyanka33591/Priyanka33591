# 👋 Hi, I'm Priyanka Yadav

<h3 align="center">
  💻 Java Backend Developer | Full Stack Developer | Problem Solver
</h3>

<p align="center">
  <a href="https://github.com/Priyanka33591">
    <img src="https://komarev.com/ghpvc/?username=Priyanka33591&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views"/>
  </a>
  <a href="https://github.com/Priyanka33591?tab=followers">
    <img src="https://img.shields.io/github/followers/Priyanka33591?label=Followers&style=flat" alt="GitHub Followers"/>
  </a>
  <img src="https://img.shields.io/badge/Focus-Java%20%7C%20Spring%20Boot%20%7C%20Full%20Stack-orange" alt="Focus"/>
</p>

---

## 🚀 About Me

I'm a **B.Tech Computer Science Graduate and aspiring Java Backend Developer** who enjoys building scalable applications, solving programming problems, and learning how real-world software systems work.

* 🎓 B.Tech in **Computer Science & Engineering**
* 💻 Interested in **Java Backend Development & Full Stack Development**
* ☕ Strong foundation in **Java, OOP, DSA and Problem Solving**
* 🌱 Currently working with **Spring Boot, Spring Security, Microservices and React**
* 🔐 Exploring **JWT Authentication, OAuth2 and secure REST APIs**
* 🗄️ Working with **MySQL, MongoDB and Redis**
* 📨 Learning and implementing **RabbitMQ-based asynchronous communication**
* 🧩 Interested in **REST APIs, Microservices and distributed systems**
* 🏆 Participated in **Smart India Hackathon 2024**
* 🧠 Regularly practicing **Data Structures & Algorithms**
* 🎯 Goal: Build reliable, scalable and impactful software solutions
* ⚡ Fun fact: I enjoy turning complex problems into simple solutions.

---

## 🧑‍💻 Tech Stack

### 💻 Programming Languages

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="45" height="45" alt="Java"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="45" height="45" alt="JavaScript"/>
</p>

**Java • JavaScript • OOP • Data Structures & Algorithms**

---

### ⚙️ Backend Development

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/spring/spring-original.svg" width="45" height="45" alt="Spring"/>
  <img src="https://cdn.worldvectorlogo.com/logos/spring-boot-1.svg" width="45" height="45" alt="Spring Boot"/>
</p>

**Spring • Spring Boot • Spring MVC • Spring Security • REST APIs • Microservices**

---

### 🔐 Security

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oauth/oauth-original.svg" width="45" height="45" alt="OAuth"/>
</p>

**Spring Security • JWT • OAuth2 • Authentication & Authorization • Role-Based Access Control**

---

### 🎨 Frontend Development

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="45" height="45" alt="React"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="45" height="45" alt="HTML5"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" width="45" height="45" alt="CSS3"/>
</p>

**React.js • JavaScript • HTML5 • CSS3 • Vite**

---

### 🗄️ Databases & Caching

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg" width="45" height="45" alt="MySQL"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg" width="45" height="45" alt="MongoDB"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" width="45" height="45" alt="Redis"/>
</p>

**MySQL • MongoDB • Redis • Database Design • SQL**

---

### 📨 Messaging & Distributed Systems

<p align="left">
  <img src="https://www.rabbitmq.com/img/rabbitmq-logo.svg" width="45" height="45" alt="RabbitMQ"/>
</p>

**RabbitMQ • Asynchronous Communication • Event-Driven Architecture • WebSockets**

---

### 🛠️ Tools & Technologies

<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="45" height="45" alt="Git"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" width="45" height="45" alt="GitHub"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="45" height="45" alt="Docker"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/maven/maven-original.svg" width="45" height="45" alt="Maven"/>
</p>

**Git • GitHub • Docker • Maven • Postman • Swagger/OpenAPI • IntelliJ IDEA • Eclipse**

---

# 🌟 Featured Projects

## 💼 HireConnect — Microservices Job Portal

A full-stack job portal designed using a **microservices architecture**.

### Architecture

```text
                         ┌──────────────────┐
                         │   React Frontend │
                         └────────┬─────────┘
                                  │
                                  ▼
                         ┌──────────────────┐
                         │   API Gateway    │
                         │      :8080       │
                         └────────┬─────────┘
                                  │
                    ┌─────────────┼─────────────┐
                    │             │             │
                    ▼             ▼             ▼
              Auth Service   Profile Service  Job Service
                 :8081           :8082          :8083
                    │
                    ├──────── Application Service
                    │              :8084
                    │
                    ├──────── Interview Service
                    │              :8085
                    │
                    ├──────── Notification Service
                    │              :8086
                    │
                    ├──────── Subscription Service
                    │              :8087
                    │
                    └──────── Analytics Service
                                   :8088

                     ┌──────────────────────┐
                     │       Eureka         │
                     │    Service Registry  │
                     │        :8761         │
                     └──────────────────────┘

                     ┌──────────────────────┐
                     │      RabbitMQ        │
                     │  Event Communication │
                     └──────────────────────┘

                     ┌──────────────────────┐
                     │        Redis         │
                     │       Caching        │
                     └──────────────────────┘
```

### Key Features

* 🔐 Authentication and authorization
* 👤 User profile management
* 💼 Job creation and management
* 📄 Job applications
* 🎯 Interview scheduling
* 🔔 Real-time notifications
* 📡 RabbitMQ event-driven communication
* ⚡ Redis caching
* 📊 Analytics service
* 🌐 API Gateway
* 🔎 Eureka service discovery
* 🔄 REST-based inter-service communication
* 🐳 Docker-based deployment support

### Tech Stack

`Java 21` `Spring Boot` `Spring Cloud` `React.js` `MySQL` `Redis` `RabbitMQ` `Docker` `Eureka` `API Gateway`

---

## 📏 Quantity Measurement Application

A full-stack application for performing operations and conversions between different measurement units.

### Supported Operations

* ➕ Addition
* ➖ Subtraction
* ✖️ Multiplication
* ➗ Division
* ⚖️ Comparison
* 🔄 Unit Conversion

### Supported Measurements

* 📏 Length
* ⚖️ Weight
* 🧪 Volume
* 🌡️ Temperature

### Features

* 🔐 User authentication
* 🔑 JWT authentication
* 🔵 Google OAuth2 login
* 📊 Calculation history
* 🔄 Unit conversion
* 🧮 Arithmetic operations
* 📱 React-based frontend
* ☁️ Cloud deployment
* 📖 Swagger/OpenAPI documentation
* ❤️ Spring Boot Actuator monitoring

### Tech Stack

`Java` `Spring Boot` `Spring Security` `JWT` `OAuth2` `React.js` `Vite` `MySQL` `REST API` `Swagger`

---

## 🧠 AI-Powered Quiz Application

An interactive quiz application designed to generate and manage quizzes with an AI-assisted approach.

### Features

* 🤖 AI-assisted quiz generation
* 📝 Interactive questions
* 📊 Score calculation
* 🎯 Topic-based quizzes
* ⚡ Dynamic user experience
* 📱 Responsive interface

### Tech Stack

`Java` `Spring Boot` `React.js` `JavaScript` `REST APIs`

---

## 💰 Financial Expense Tracker

A web application designed to help users manage and track their personal expenses.

### Features

* 💵 Expense management
* 📊 Expense tracking
* 📈 Financial insights
* 🗂️ Categorization
* 🔐 User authentication
* 📱 Responsive UI

### Tech Stack

`Java` `Spring Boot` `React.js` `MySQL`

---

# 🧩 What I'm Currently Learning

```text
Java
 ├── Advanced OOP
 ├── Collections
 ├── Streams API
 ├── Multithreading
 └── Problem Solving

Spring Boot
 ├── REST APIs
 ├── Spring Security
 ├── JWT
 ├── OAuth2
 └── Microservices

System Design
 ├── Microservices Architecture
 ├── API Gateway
 ├── Service Discovery
 ├── Redis
 ├── RabbitMQ
 └── Event-Driven Architecture

Frontend
 ├── React.js
 ├── Hooks
 ├── Context API
 └── REST API Integration
```

---

# 🧠 Data Structures & Algorithms

I regularly practice DSA to improve my problem-solving and algorithmic thinking.

### Topics I Practice

* Arrays
* Strings
* Hashing
* Linked Lists
* Stacks
* Queues
* Recursion
* Binary Search
* Trees
* Graphs
* Sorting
* Searching
* Dynamic Programming
* Greedy Algorithms

### 👩‍💻 LeetCode

<p align="center">
  <a href="https://leetcode.com/u/Priyankay04/">
    <img src="https://leetcard.jacoblin.cool/Priyankay04?theme=light&font=Karma&ext=heatmap" alt="Priyanka's LeetCode Stats"/>
  </a>
</p>

<p align="center">
  <a href="https://leetcode.com/u/Priyankay04/">
    <img src="https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/>
  </a>
</p>

---

# 📊 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Priyanka33591&show_icons=true&theme=default&hide_border=false&rank_icon=github" alt="GitHub Stats"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Priyanka33591&theme=default&hide_border=false" alt="GitHub Streak"/>
</p>

---

## 💻 Most Used Languages

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Priyanka33591&layout=compact&theme=default&hide_border=false&langs_count=8" alt="Most Used Languages"/>
</p>

---

# 🏆 Achievements

### 🏅 Smart India Hackathon 2024

Participated in **Smart India Hackathon 2024**, gaining hands-on experience in collaborative problem solving, software development and building technology-driven solutions.

### 💻 Continuous DSA Practice

Actively practicing Data Structures & Algorithms on **LeetCode** to strengthen problem-solving and competitive programming skills.

### 🚀 Full-Stack Project Development

Built projects covering:

* Frontend development
* Backend development
* REST APIs
* Authentication
* Databases
* Microservices
* Caching
* Messaging
* Cloud deployment

---

# 💼 Professional Experience

### Software Development Intern

**Capgemini Consulting India Pvt. Ltd.**

Working with modern software development concepts and gaining practical exposure to enterprise application development.

Areas of exposure include:

* Java development
* Spring Boot
* REST APIs
* Backend development
* API Management
* Enterprise software development

---

# 🌐 Connect With Me

<p align="center">

<a href="https://github.com/Priyanka33591">
  <img src="https://img.shields.io/badge/GitHub-Priyanka33591-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<a href="https://www.linkedin.com/in/priyanka-yadav22/">
  <img src="https://img.shields.io/badge/LinkedIn-Priyanka%20Yadav-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

<a href="https://leetcode.com/u/Priyankay04/">
  <img src="https://img.shields.io/badge/LeetCode-Priyankay04-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"/>
</a>

<a href="mailto:priyanka33591@gmail.com">
  <img src="https://img.shields.io/badge/Email-priyanka33591%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

</p>

---

# 📫 Contact

**Email:** `priyanka33591@gmail.com`

**GitHub:** `@Priyanka33591`

**LinkedIn:** `@priyanka-yadav22`

**LeetCode:** `@Priyankay04`

---

# 🎯 2026 Goals

```text
☑ Strengthen Java & DSA
☑ Build production-ready Spring Boot applications
☑ Learn and implement Microservices
☑ Improve System Design knowledge
☑ Build secure REST APIs
☑ Contribute to Open Source
☑ Improve competitive programming skills
☑ Build impactful Full Stack projects
☑ Become a strong Backend / Full Stack Developer
```

---

# ✨ Developer Philosophy

> "Great software is built by solving complex problems with simple, maintainable and scalable solutions."

I believe in **learning by building**, continuously improving my problem-solving skills, and turning ideas into working software.

---

## ⚡ Fun Zone

```text
🌸 Code. Learn. Build. Repeat.

☕ Coffee + Coding = Perfect Combination

🎧 Music + Debugging = Developer Mode

🐛 Found a bug?
   ↓
🧠 Understand it
   ↓
🔧 Fix it
   ↓
🚀 Learn from it
```

---

<p align="center">

### ⭐ Thanks for visiting my profile!

**Feel free to explore my repositories and connect with me.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>

</p>

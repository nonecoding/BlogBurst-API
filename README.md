## 2. `BlogBurst-API` README

```markdown
# 🚀 BlogBurst-API

**BlogBurst-API** is a lightning-fast, flexible, and extensible backend service for your blog platform, offering core features like article management, user authentication, comment threads, and tag categorization.

---

## 🎉 Key Features
- **RESTful API** | Clean, standard-compliant endpoint design  
- **High Performance** | Built with Spring Boot, MyBatis-Plus, and Redis caching  
- **Secure Authentication** | JWT + Spring Security, with easy OAuth integration  
- **Modular Architecture** | Package structure split by feature, designed for Open/Closed extension  
- **Auto-Generated Docs** | Swagger3 + Knife4j for one-click API exploration and testing  

---

## 🛠 Tech Stack
- **Framework**: Spring Boot 3.x  
- **Persistence**: MyBatis-Plus  
- **Cache**: Redis  
- **Security**: Spring Security + JWT  
- **API Docs**: Swagger3 + Knife4j  
- **Database**: MySQL  

---

## 🚀 Quickstart

1. **Clone the repo**  
   ```bash
   git clone https://github.com/YourUsername/BlogBurst-API.git
   cd BlogBurst-API
   ```
2. **Configure database** (`src/main/resources/application.yml`)  
   ```yaml
   spring:
     datasource:
       url: jdbc:mysql://localhost:3306/blogburst
       username: root
       password: your_password
   redis:
     host: localhost
     port: 6379
   jwt:
     secret: your_jwt_secret
   ```
3. **Run the application**  
   ```bash
   mvn clean spring-boot:run
   ```
4. **View the docs**  
   Open your browser to: `http://localhost:8080/doc.html`

---

## 📦 Module Structure
- `controller` — API controllers  
- `service` — Business logic  
- `mapper` — MyBatis mapping files  
- `config` — Global configuration, interceptors, CORS, etc.  
- `dto` — Request/response data objects  
- `entity` — Database entity classes  

---

## 🤝 Contributing
1. Fork this repository  
2. Create a branch:  
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit your changes:  
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to your branch:  
   ```bash
   git push origin feature/your-feature
   ```
5. Open a pull request  

---

## 📝 License
This project is licensed under the [MIT License](LICENSE).

---

> **Pro Tip**: A daily cup of coffee fuels great code! ☕
```

---

## 3. `BlogBurst-Web` README

```markdown
# 🌟 BlogBurst-Web

**BlogBurst-Web** is the official frontend for BlogBurst, built with Vue 3 + Vite + TailwindCSS, delivering a smooth, clean, and responsive experience for reading and writing blog posts.

---

## 🎨 Highlights
- **Responsive Layout** | Optimized for mobile, tablet, and desktop  
- **Markdown Editor** | Live rendering with syntax highlighting  
- **Category & Search** | Quickly find the posts you care about  
- **Commenting** | Nested replies, reactions, and emojis support  
- **Dark Mode** | Eye-friendly reading around the clock  

---

## 🛠 Tech Stack
- **Framework**: Vue 3 + Composition API  
- **Build Tool**: Vite  
- **Styling**: TailwindCSS  
- **State Management**: Pinia  
- **Routing**: Vue Router  
- **HTTP Client**: Axios  

---

## 🚀 Quickstart

1. **Clone the repo**  
   ```bash
   git clone https://github.com/YourUsername/BlogBurst-Web.git
   cd BlogBurst-Web
   ```
2. **Install dependencies**  
   ```bash
   npm install
   ```
3. **Configure backend URL** (`src/config.js`)  
   ```js
   export const API_BASE = 'http://localhost:8080';
   ```
4. **Start development server**  
   ```bash
   npm run dev
   ```
5. **Build for production**  
   ```bash
   npm run build
   ```

---

## 📁 Project Structure
```
BlogBurst-Web/
├─ public/         # Static assets
├─ src/
│  ├─ assets/      # Images & fonts
│  ├─ components/  # Reusable components
│  ├─ views/       # Page views
│  ├─ router/      # Vue Router setup
│  ├─ store/       # Pinia stores
│  ├─ App.vue
│  └─ main.js
└─ vite.config.js
```

---

## 🤝 Contributing
1. Fork & clone the repo  
2. Create a branch:  
   ```bash
   git checkout -b feature/your-feature
   ```
3. Commit & push your changes  
4. Open a pull request  

---

## ❤️ Acknowledgments
Thanks to all contributors! Let’s make blogging joyful!  

---

> **Tip**: Hit `Ctrl + K` to quickly focus the search bar anywhere! 🔍
```

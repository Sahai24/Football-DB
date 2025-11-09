# ⚽ Football Website FC23

![HTML](https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-blue?logo=docker&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

> A modern, responsive football-themed website featuring player profiles, club details, match highlights, and a simple login interface — all wrapped in a clean UI and deployable via Docker.  

---

## 🌐 Live Preview

👉 **[View Demo](#)**  
(Add your GitHub Pages or deployment link here)

---

## 🏗️ Project Structure

```
├── loginpage.html        # Login interface  
├── login.css             # Styles for login page  
├── mainsite.html         # Main football website  
├── requirements.txt      # Python dependencies (Flask, numpy, pandas)  
├── Dockerfile            # Docker setup for deployment  
└── images/               # Contains banner, players, and club logos
```

---

## 🧠 Features at a Glance

| Section | Description | Visual |
|----------|--------------|--------|
| 🧑‍💻 **Login Page** | Simple login UI styled with transparent inputs and a modern dark theme. | 🔒 |
| ⚽ **Players** | Showcases top footballers with photos, bios, and “Read More” links. | 🏃‍♂️ |
| 🔥 **Trending** | Copa America 2023 highlight section with embedded video links. | 🎬 |
| 🎥 **Highlights** | Match highlight cards with playable YouTube links. | 📺 |
| 🏟️ **Clubs** | Logos linked to official Wikipedia pages of top Premier League clubs. | 🏆 |
| 📱 **Responsive Design** | Works on mobile, tablet, and desktop seamlessly. | 📱 |

---

## 🚀 Quick Start

### 🐳 Run with Docker
1. **Build the image**
   ```bash
   docker build -t football-website .
   ```
2. **Run the container**
   ```bash
   docker run -p 5000:5000 football-website
   ```

### 💻 Run Locally
1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/football-website.git
   cd football-website
   ```
2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```
3. Run Flask server  
   ```bash
   flask run
   ```
4. Open [http://localhost:5000](http://localhost:5000)

---

## 🧩 Tech Stack

| Layer | Tools |
|-------|--------|
| 🌐 Frontend | HTML5, CSS3, Font Awesome |
| ⚙️ Backend | Flask (Python) |
| 🐋 Deployment | Docker |
| 🧮 Libraries | Numpy, Pandas |

---

## 📸 Screenshots

**🔐 Login Page**  
Transparent form with glowing hover effects.  

**🏆 Player Section**  
Showcasing famous footballers like Messi, Neymar, Ronaldo, and Mbappé.  

---

## 🛠️ Future Enhancements

- [ ] Add user authentication via Flask backend  
- [ ] Integrate live football API for match data  
- [ ] Add database support (SQLite or PostgreSQL)  
- [ ] Deploy using GitHub Actions CI/CD  

---

## 👨‍💻 Contributors

| Name | Role | Profile |
|------|------|----------|
| Arav Bharadwaj | Developer | 🌍 |
| Adeetya Lawaniya | UI Designer | 🎨 |
| V Ujwal | Backend Setup | ⚙️ |

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use and modify.

---

## ⭐ Acknowledgements

- [Font Awesome](https://fontawesome.com) for icons  
- [Live Soccer TV](https://www.livesoccertv.com/) for match data inspiration  
- [Wikipedia](https://en.wikipedia.org) for player & club info  

---

🏁 **Built with ❤️ by Group 35 (BCA - SICSR)**

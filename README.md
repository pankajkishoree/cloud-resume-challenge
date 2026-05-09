# ☁️ Cloud-Hosted Portfolio Website (AWS)

A fully cloud-hosted, production-ready personal portfolio website built using **AWS serverless and cloud-native services**.  
The project demonstrates modern cloud architecture, CI/CD automation, CDN acceleration, and real-time visitor tracking.

---

## 🚀 Live Features

- ⚡ High-performance static website hosting
- 🌍 Global content delivery via CDN
- 🔐 HTTPS with secure DNS routing
- 📊 Real-time visitor counter (serverless)
- 🔁 Automated CI/CD with GitHub Actions
- 🎨 Modern animated UI with Canvas & CSS

---

## 🏗 Architecture Overview

```
GitHub Repo
│
├── GitHub Actions (CI/CD)
│         │
│         ▼
└──► AWS S3 (Static Website Hosting)
              │
              ▼
       CloudFront (CDN + HTTPS)
              │
              ▼
         Route 53 (DNS)
```

### Visitor Counter (Serverless)

```
Browser
   │
   ▼
API Gateway
   │
   ▼
AWS Lambda
   │
   ▼
DynamoDB
```

---

## 🧰 Tech Stack

### Frontend
- HTML5
- CSS3 (Advanced animations & effects)
- JavaScript (Canvas, animations, API calls)

### Cloud & DevOps

| Service | Purpose |
|---|---|
| **AWS S3** | Static website hosting |
| **CloudFront** | CDN & HTTPS |
| **Route 53** | DNS management |
| **AWS Lambda** | Visitor counter logic |
| **API Gateway** | REST API endpoint |
| **DynamoDB** | Visitor count storage |
| **GitHub Actions** | CI/CD automation |

---

## 📊 Key Highlights

- Deployed a **high-availability, serverless architecture**
- Implemented **real-time visitor tracking** using AWS Lambda + DynamoDB
- Configured **CloudFront + HTTPS** for secure global delivery
- Built a **CI/CD pipeline** that auto-deploys on every push to `main`
- Designed a **fully responsive, animated UI** without frameworks

---

## 🔁 CI/CD Workflow (GitHub Actions)

On every push to the `main` branch:

1. Code is checked out
2. AWS credentials are configured securely
3. Website files are synced to S3
4. Old files are automatically removed

---

## 📂 Project Structure

```
.
├── index.html
├── .github/
│   └── workflows/
│       └── deploy.yml
└── README.md
```

---

## 🧪 Visitor Counter Logic

1. Each page load sends a request to **API Gateway**
2. **Lambda function** increments visitor count
3. Count is stored and retrieved from **DynamoDB**
4. Frontend **animates** the updated count smoothly

---

## 📸 Screenshots

![Portfolio Website](https://github.com/user-attachments/assets/95165613-dc50-4511-961e-69e0e1d05a58)

---

## 🎯 Learning Outcomes

- ✅ Hands-on experience with AWS cloud services
- ✅ Real-world serverless application design
- ✅ Secure CI/CD practices using GitHub Actions
- ✅ Frontend performance optimization with CDN
- ✅ Production-grade deployment mindset

---

## 📬 Contact

**Pankaj Kishore**  
📧 Email: [pankajkishore762@gmail.com](mailto:pankajkishore762@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/pankajkishoree](https://www.linkedin.com/in/pankajkishoree)

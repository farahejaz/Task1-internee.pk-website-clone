This project is a **frontend clone of the official Internee.pk website**, developed using **HTML, CSS, and JavaScript**, and deployed on **AWS using S3 and CloudFront** as part of a frontend/cloud learning project.

## 📌 Project Objective
- Replicate the UI/UX of the Internee.pk website
- Host a static website using **AWS best practices**
- Gain hands-on experience with **cloud deployment and CDN**

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla)

### Cloud & DevOps
- **AWS S3** – Static website hosting
- **AWS CloudFront** – CDN, HTTPS, global delivery
- **AWS IAM** – Secure access control
- **AWS Certificate Manager (ACM)** – SSL (via CloudFront)

## 📂 Project Structure



internee-pk-website-clone/
│
├── index.html
├── css/
│ └── style.css
├── js/
│ └── main.js
├── images/
└── README.md

## ☁️ Cloud Architecture



User Browser
|
v
CloudFront (CDN + HTTPS)
|
v
Amazon S3 (Static Website Hosting)



## ⚙️ Deployment Steps

### Step 1: Create S3 Bucket
- Bucket configured for static website hosting
- Public access enabled for static assets
- `index.html` set as entry point

### Step 2: Upload Static Files
- Uploaded HTML, CSS, JS, and image files
- Verified accessibility via S3 website endpoint

### Step 3: Configure CloudFront
- S3 used as origin
- Viewer protocol policy set to **Redirect HTTP to HTTPS**
- Enabled caching for faster global delivery


## 🔐 Security & Performance
- HTTPS enabled using CloudFront
- No backend server required (cost-efficient)
- Global CDN for low-latency performance


## 🎯 Learning Outcomes
- Static website hosting on AWS
- CDN configuration using CloudFront
- Cloud deployment best practices
- Real-world frontend + cloud project experience


## 📌 Future Improvements
- CI/CD with GitHub Actions
- Custom domain using Route 53
- Backend integration (Node.js / API)
- SEO optimization


## 👩‍💻 Author
**Farah Ejaz**  
Frontend & Cloud Computing Enthusiast  

🔗 LinkedIn: https://www.linkedin.com/in/farah-ejaz/
🔗 GitHub: https://github.com/farahejaz

Here are the screenshots of the project.....

Bucket:
<img width="1260" height="489" alt="bucket" src="https://github.com/user-attachments/assets/7d239a1f-8463-49d2-9cd1-509c03b700f5" />

Hosted on S3:
<img width="1243" height="614" alt="S3 hosting" src="https://github.com/user-attachments/assets/1756646d-0301-4031-8322-535e4cd80d06" />

<img width="1264" height="573" alt="s3 server" src="https://github.com/user-attachments/assets/b4110aad-7441-44ed-a9d1-1b2c9ec59da0" />

Hit from Cloudfront
<img width="1271" height="608" alt="hit fromcloudfront" src="https://github.com/user-attachments/assets/dd935db9-ec06-4b2b-94bf-318a98f2b2ba" />

If you like this project, feel free to star the repository!

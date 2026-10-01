# Xiaoyu Lyu - Academic Website Deployment Guide (GitHub Pages)

This static website is designed to be hosted permanently for **0 cost** on **GitHub Pages**.

## 1-Minute GitHub Pages Deployment Steps

1. **Create a GitHub Repository**:
   - Go to [GitHub.com](https://github.com) and log in.
   - Click **New repository**.
   - Set **Repository name** to: `<your-github-username>.github.io` (e.g., `xiaoyulyu.github.io`).
   - Keep it **Public**. Do NOT initialize with README (the repository already exists locally).

2. **Push the Local Code to GitHub**:
   In your terminal, run:
   ```bash
   cd /home/nothingness/xiaoyulyu.github.io
   git remote add origin https://github.com/<your-github-username>/<your-github-username>.github.io.git
   git push -u origin main
   ```

3. **Verify Your Live Site**:
   - Within 1–2 minutes, visit: `https://<your-github-username>.github.io`
   - Your academic profile, research portfolio, and downloadable CV will be live globally with HTTPS enabled!

## Local Preview
- Local URL: http://localhost:8085
- Service: `systemctl status xiaoyu-academic-site.service`
- Homepage Dashboard: http://localhost:8888

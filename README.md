# 📄 Resumind

**Resumind** is an **AI-powered resume analyzer** that provides detailed feedback, ATS scores, and improvement suggestions tailored to specific job descriptions.  
Built with modern web technologies and a serverless architecture for **zero infrastructure costs**.

---

## ✨ Features
- 🤖 **AI-Powered Analysis** using Claude AI  
- 📊 **ATS Score Calculation** – measure resume performance  
- 🎯 **Job-Specific Feedback** (company, job title, description)  
- 📝 **Detailed Scoring** across: ATS, Tone & Style, Content, Structure, Skills  
- 👀 **Visual Resume Preview** (PDF → image thumbnails)  
- 📱 **Responsive Design** (desktop + mobile)  
- 🔐 **Authentication** via Puter.js  
- ☁️ **File Management** with cloud storage  

---

## 🛠 Tech Stack

**Frontend**
- ⚛️ React 18 (hooks + functional components)  
- 📘 TypeScript  
- ⚡ Vite  
- 🔀 React Router v7  
- 🎨 Tailwind CSS  
- 🪢 Zustand  

**Backend / Cloud**
- 🌐 Puter.js for:  
  - File storage & management  
  - AI processing (Claude integration)  
  - User authentication  
  - Key-value database  

**Libraries**
- 📂 `react-dropzone` – drag & drop uploads  
- 📑 `pdf.js` – client-side PDF → image  
- 🎞️ `tailwindcss-animate` – animations  

---

## 📂 Project Structure
```bash
app/
  routes/        # Pages (home, upload, resume, auth, wipe)
  components/    # UI components
  lib/           # puter.js, pdf2img, utils
  types/         # Type definitions
  constants/     # Mock data + AI prompts
  root.tsx       # App root
  routes.ts      # Route config
public/          # Images & icons
tailwind.config.ts
vite.config.ts
package.json


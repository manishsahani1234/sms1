# 🏫 School Management System (SMS) - Class 8th to 12th
### Complete Digital Platform & Public School Website

A modern, professional, high-performance, and responsive **School Management System (SMS)** web application designed for Class 8th to 12th. Built according to all 8 milestones specified in the PDF requirements.

---

## 🌟 Key Features (8 Milestones)

### 🌐 Milestone 1: Professional School Website
- **Pages Included**: Home, About School, Principal's Message, Academics, Classes 8th–12th, Faculty Directory, Facilities Showcase, Admission Info, Notice Board, Gallery, Events & News, Contact Us.
- **Hero Banner**: "Building a Brighter Future for Every Student".
- **Responsive Navigation**: Mobile drawer menu & responsive grid layout.

### 📝 Milestone 2: Admission & Enquiry Portal
- **Online Admission System**: Interactive 4-step wizard (Class Selection, Student & Parent Details, Document Upload preview, Submission).
- **Admission Enquiry Form**: Direct query form for prospective parents.
- **Admin Application Management**: Filter, review, approve/reject admission applications with live status updating.

### 👑 Milestone 3: School Management System (Admin Panel)
- **Centralized Dashboard**: Academic & administrative counter stats (Total Students, Teachers, Class count, Pending Applications).
- **Student Directory**: Add, search, filter by class/section, view profiles.
- **Faculty Management**: Subject allocation & contact info.
- **Class 8th–12th Management**: Organize streams (Science, Commerce, Arts).

### 👩‍🏫 Milestone 4: Teacher Portal
- **Faculty Dashboard**: Mark class attendance, enter subject marks, upload homework & study materials to student portal.

### 👨‍🎓 Milestone 4 & 6: Student Portal & Board Exam Preparation
- **Student Dashboard**: Track attendance %, timetable, study material downloads.
- **Class 10th & 12th Board Prep**: Interactive timer-based MCQ Mock Tests with instant evaluation and detailed solutions.
- **Report Card Generator**: Professional printable student report cards with pass/fail distinction and grade calculations.

### 💳 Milestone 5: Fee System
- **Fee Breakdown**: Tuition, library, computer lab, exam fee details.
- **Pending Fee Alerts**: Outstanding balance alerts and due date reminders.
- **Online Payment Simulation**: Payment gateway modal (UPI, Credit/Debit Card, Net Banking).
- **Printable Fee Receipt**: Downloadable/printable PDF receipt generator.

### 📢 Milestone 7: Updates & Communication
- **Notice Board**: Categorized notices (General, Exam, Holiday, Events).
- **School Events & News**: Interactive news feed.
- **Photo & Video Gallery**: Lightbox gallery view.

### 🚀 Milestone 8: Google & Deployment Setup
- **Google Maps Integration**: Interactive map card with "Get Directions" link.
- **SEO & Meta Setup**: OpenGraph tags, title, and description.
- **GitHub & Live Hosting Ready**: Zero setup required; run natively in browser or push to GitHub.

---

## 🚀 How to Run Locally

Simply double click `index.html` to open it directly in any web browser (Chrome, Edge, Firefox, Safari).

Or serve using any static web server:
```bash
# Using Python
python -m http.server 8000

# Using Node npx
npx serve .
```

---

## 📦 How to Push to GitHub & Publish Live

### Step 1: Initialize Git & Push to GitHub
Open your terminal inside the project directory `school-management-system`:

```bash
git init
git add .
git commit -m "Initial commit: School Management System SMS"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/school-management-system.git
git push -u origin main
```

### Step 2: Publish Live on GitHub Pages (Free)
1. Go to your GitHub repository: `https://github.com/YOUR_USERNAME/school-management-system`.
2. Click on **Settings** -> **Pages** (in the left sidebar).
3. Under **Build and deployment** -> **Source**, select **Deploy from a branch**.
4. Under **Branch**, select `main` branch and `/ (root)` folder.
5. Click **Save**.
6. Within 1-2 minutes, your web application will be live at:
   `https://YOUR_USERNAME.github.io/school-management-system/`

---

## 🌐 How to Deploy on Vercel / Netlify (1-Click)

### Option A: Vercel
1. Log in to [Vercel](https://vercel.com).
2. Click **Add New** -> **Project**.
3. Import your `school-management-system` GitHub repository.
4. Click **Deploy**. (Vercel automatically detects static HTML/JS).

### Option B: Netlify
1. Log in to [Netlify](https://netlify.com).
2. Drag and drop the `school-management-system` folder onto Netlify Drop page, or import from GitHub.
3. Click **Deploy**.

---

## 🛠️ Built With
- **HTML5 & CSS3**
- **Tailwind CSS CDN**
- **React 18 & ReactDOM**
- **FontAwesome 6 Icons**
- **Google Fonts (Outfit & Inter)**
- **JavaScript (ES6+) with localStorage persistence**

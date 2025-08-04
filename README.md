<h1 align="center">
  📄 Resumify - AI-Crafted Resumes, Simplified
</h1>

<p align="center">
  ✨ Build professional resumes effortlessly with AI-generated content, secure authentication, and complete customization. <a href="https://resumify-ai-orpin.vercel.app/"><strong>➥ Visit Resumify App</strong></a>
</p>

  <div align="center">
     <b>Resumify</b> simplifies the process of creating a professional resume. Powered by AI, users can generate, update, and customize their resumes effortlessly. It's secure, user-friendly, and highly customizable—perfect for anyone looking to create an outstanding resume that stands out to employers.
  </div>
  <br />
</div>


<p align="center">
  <img src="https://img.shields.io/badge/Next.js-14-blue?logo=nextdotjs" />
  <img src="https://img.shields.io/badge/Clerk-Auth-blueviolet?logo=clerk" />
  <img src="https://img.shields.io/badge/Gemini-API-green?logo=google" />
  <img src="https://img.shields.io/badge/TailwindCSS-Styling-06B6D4?logo=tailwindcss" />
  <img src="https://img.shields.io/badge/Node.js-Backend-brightgreen?logo=node.js" />
  <img src="https://img.shields.io/badge/MongoDB-Database-4EA94B?logo=mongodb" />
</p>

---


## ⚙️ Tech Stack

| Layer         | Technology         | Description |
|---------------|--------------------|-------------|
| 🖼️ Frontend    | **Next.js 14**      | Fast rendering, SSR, and SEO-friendly UI |
| 🔐 Auth        | **Clerk**           | Secure user sign-up, login, and session handling |
| 🤖 AI          | **Gemini API**      | Generates resume sections (summaries, job roles, etc.) |
| 🎨 Styling     | **TailwindCSS**     | Utility-first CSS framework for responsive design |
| 🧠 Backend     | **Node.js**         | Handles requests, processes data, and connects to DB |
| 🗄️ Database    | **MongoDB**         | Flexible schema to store resumes and user data |

---

## 💡Resumify
<div align="center">
  <br />
    <img src="https://i.postimg.cc/9QtLC6R6/Screenshot-2024-11-08-001254.png" alt="Project Banner">
  <br />
  <br />
<img width="866" height="439" alt="Image" src="https://github.com/user-attachments/assets/e9695a08-4265-439a-9484-cbcf04419502" />




## 💡 Why Resumify?

- ✍️ **Effortless Resume Creation** – Use AI to generate high-quality content tailored to your career goals.
- 🔐 **Secure & Private** – Auth handled by Clerk, data stored safely in MongoDB.
- 🧩 **Fully Customizable** – Edit every section of your resume in real time.
- 📱 **Responsive Design** – Works flawlessly on all devices.
- 🧠 **Smart AI Suggestions** – Get content help powered by Gemini AI.

---

## 🚀 Quick Start

### 🔧 Prerequisites

Ensure the following tools are installed:

- [Node.js & npm](https://nodejs.org/)
- [Git](https://git-scm.com/)
- [MongoDB Atlas Account](https://www.mongodb.com/cloud/atlas)
- [Clerk Account](https://clerk.com/)
- [Gemini API Key](https://aistudio.google.com/)

---

### ✨ **Features**

- **AI-Powered Resume Generation**:
  - Effortlessly generate a professional resume with the help of AI. The AI analyzes your input and crafts a tailored resume highlighting your skills and experiences.

- **User Authentication with Clerk**:
  - **Secure Login & Registration**: Sign up and log in securely with Clerk. Your personal data is always protected.
  - **Session Management**: Clerk ensures session persistence, so your resumes are readily available whenever you need them.

- **Real-Time Resume Preview**:
  - **Instant Updates**: See a live preview of your resume as you fill out the details. This interactive experience allows seamless editing with real-time updates.

- **Customizable Sections**:
  - Personalize your resume by adding and modifying sections such as experience, education, skills, certifications, and more.
  - **User-Friendly Interface**: Make quick edits with an intuitive interface to ensure that your resume perfectly reflects your professional profile.

- **Save & Share**:
  - **Resume Storage**: Save your resume in your account for future edits and updates.
  - **Share with Employers**: Easily generate a unique link to share your resume with potential employers.

- **Mobile-Responsive Design**:
  - The app works seamlessly across all devices—desktop, tablet, and mobile.
  - **Cross-Browser Support**: A consistent experience regardless of your browser choice.

---

### ⚙️ **Tech Stack**

- **Frontend**: [Next.js 14](https://nextjs.org/)
  - Next.js powers the frontend, delivering fast page loads and server-side rendering for optimal performance and SEO-friendly features.

- **Authentication**: [Clerk](https://clerk.dev/)
  - Clerk provides secure, easy-to-integrate authentication for user sign-ups, logins, and session management.

- **AI Integration**: [Gemini API](https://www.gemini.com/)
  - Resumify uses Gemini API to help generate professional content for your resume, including summaries, job descriptions, and skills.

- **Styling**: [TailwindCSS](https://tailwindcss.com/)
  - TailwindCSS is used for efficient styling, enabling rapid UI development with a utility-first approach.

- **Backend**: [Node.js](https://nodejs.org/)
  - Node.js powers the backend, handling API requests, data processing, and interactions with the database for scalability and speed.

- **Database**: [MongoDB](https://www.mongodb.com/)
  - MongoDB stores user profiles, resumes, and authentication data, providing flexibility with its dynamic schema for resume information.

---

### 💡 **Why Resumify?**

- **Effortless Resume Creation**: Quickly create a resume using AI or customize existing content to suit your career goals.
  
- **Secure & Private**: Clerk handles authentication, and MongoDB stores your data securely.

- **Fully Customizable**: Edit every aspect of your resume—from work experience to skills—giving you complete control over its content and layout.

- **Responsive & User-Friendly**: A mobile-responsive design ensures a smooth experience across all devices, and the app is optimized for easy navigation.


## <a name="quick-start">🚀 Quick Start</a>

Follow these steps to set up the project locally on your machine.

### Prerequisites

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

### Cloning the Repository

```bash
git clone https://github.com/MeAkash77/Resumify-AI.git
cd Resumify-AI-crafted-resumes-simplified.-
```

### Installation

Install the project dependencies using npm:

```bash
npm install
```

### Set Up Environment Variables

Create a new file named `.env` in the root of your project and add the following content:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

MONGODB_URL=

GEMINI_API_KEY=

BASE_URL=localhost:3000
```

Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up for the corresponding websites on [Clerk](https://clerk.com/), [MongoDB](https://mongodb.com/) and [Google AI Studio](https://aistudio.google.com/app/apikey).

### Running the Project

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
# Then you are good to go !!

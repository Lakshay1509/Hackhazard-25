
# Resonanze

### 🩺 The Future of Audio Health 


![Voice Analysis Demo](https://res.cloudinary.com/backend-15/image/upload/v1744448408/Screenshot_2025-04-06_104355_ietr1v.png)

**Resonanze** is an AI-driven platform designed to monitor and enhance vocal health for professionals like teachers, singers, and content creators. It provides real-time voice analysis, personalized feedback, and actionable insights to prevent strain and long-term damage. With subscription-based models for healthcare providers and gamified user engagement, Resonanze promotes accessible, scalable vocal care.





## 🤔 Challenges We Aim to Address


#### 🔹 **High Voice Strain Among Professionals**
- Teachers, singers, and public speakers are prone to vocal fatigue and long-term damage.

#### 🔹 **Lack of Preventive Care**
- No easy-to-use tool exists for continuous vocal health monitoring.

#### 🔹 **No Personalized Feedback System**
- Absence of AI-driven solutions offering real-time feedback tailored to individual needs.

#### 🔹 **Inefficient Healthcare Support**
- ENT specialists lack centralized systems for tracking patient vocal health history.

#### 🔹 **Need for Scalable Solutions**
- Professionals require affordable, accessible tools that integrate into their daily routines.
## 📒 Features

- **Voice & Audio Health Tracking**: Analyze voice quality, detect strain, and provide actionable insights.
- **Personalized Feedback & Guidance**: Tailored suggestions for maintaining vocal wellness and preventing fatigue.
- **Telegram Bot** : Direct access to your report on your fingertips.

- **Engaging Streak-Based System**: Reward-driven features encourage regular health checks.
- **Support for Healthcare Providers**: Tools for remote monitoring and improved diagnosis by ENT specialists.
- **Ease of Use**: Seamlessly integrates into daily routines with detailed PDF reports for users.

## 🔄 How It Works

🎤 User speaks/upload audio  
↓  
🧠 AI analyzes pitch, strain, clarity  
↓  
📄 Generates PDF + Insights  
↓  
✔️ PDF saved in database with detailed analysis  

## 🌐 Tech Stack

**Client:** React, Redux, TailwindCSS

**Server:** Node, Express, Multer

**AI:** Flask, Langchain, Tensorflow 


## 👟 Run Locally

Clone the project

```bash
  git clone https://github.com/Lakshay1509/Hackhazard-25
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies by going in each directory


```bash
  npm install
```

Set the required environment variables

Start the server

```bash
  npm run start
```

Start the client

```bash
  bun run dev
```

Start the AI server

```bash
  python main.py
```





## 🚧 Roadmap

- [x] Real-time voice analysis
- [x] Telegram Bot integration
- [ ] Mobile app support (React Native)
- [ ] Specialist dashboard for doctors
- [ ] Gamified training system



## 🙌 Acknowledgments

We’d like to thank the following resources and tools that powered Resonanze:

- 🔊 **VGGish by Google** – Used for generating high-quality voice embeddings to analyze vocal features.
- 🧠 **Groq AI** – Enabled ultra-fast inference for both voice and NLP processing, ensuring real-time feedback and analysis.

- 🤖 **Telegram Bot API** – Allowed seamless interaction by delivering reports and updates directly to users' devices.



## 📂 Folder Structure

<details>
<summary>Click to view folder structure</summary>

📂 **backend/**  
├── 📂 **api/**  
│   ├── 📄 `__init__.py`  
│   ├── 📄 `routing.py`  
│   ├── 📄 `utils.py`  
│  
├── 📂 **models/**  
│   ├── 📄 `__init__.py`  
│   ├── 📄 `model.py`  
│  
├── 📂 **static/**  
│   ├── 📂 **saved_models/**  
|
├── 📄 `requirement.txt`  
├── 📄 `app.py` #flask  



📂 **frontend/**  
├── 📂 **public/**  
│  
├── 📂 **src/**  
│   ├── 📂 **components/**  
│   │   ├── 📄 `Navbar.jsx`  
│   │   ├── 📄 `Landing3D.jsx`  
│   │   ├── 📄 `AboutSection.jsx`  
│   │   ├── 📄 `DiagnoseForm.jsx`  
│   │   ├── 📄 `Spectrogram.jsx`  
│   │   ├── 📄 `ExerciseDashboard.jsx`  
│  
│   ├── 📂 **pages/**  
│   │   ├── 📄 `Home.jsx`  
│   │   ├── 📄 `Diagnose.jsx`  
│   │   ├── 📄 `Exercises.jsx`  
│  
│   ├── 📂 **utils/**  
│   │   ├── 📄 `api.js`  
│  
│   ├── 📂 **styles/**  
│   │   ├── 📄 `tailwind.css`  
│  
│   ├── 📄 `App.jsx`  
│   ├── 📄 `package.json`  _(Using Vite)_  
│   ├── 📄 `vite.config.js`  


📄 **README.md**
</details>
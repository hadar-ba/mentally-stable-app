# Mentally-Stable-App  
Web-app built with a clean, data-driven UX and modular component architecture. Users navigate a home screen that offers cognitive-behavioural modules such as “Identifying Negative Thoughts” and “Success Journal”.

## 🚀 Features  
- Modular exercise cards (e.g., 5-10 min sessions)  
- Tab navigation: Home / Library / Profile  
- Google OAuth2 Sign-In via Google API  
- Mobile-first, responsive design  
- Data-driven UX: event tracking, performance metrics  
- Built on the Base44 no-code/low-code platform with custom code extension

## 🛠 Tech Stack  
- React + TypeScript  
- Redux Toolkit for state management  
- OAuth2 / Google Sign-In  
- Modular component architecture  S
- CSS-in-JS (or styled-components) for design system  
- PWA-capable (Add to Home Screen)  

## 📁 Project Structure  
/mentally-stable-app
├── public/
│ └── index.html
├── src/
│ ├── App.tsx
│ ├── components/
│ │ ├── Header.tsx
│ │ ├── ExerciseCard.tsx
│ │ └── TabNavigation.tsx
│ ├── features/
│ │ ├── home/
│ │ ├── library/
│ │ └── profile/
│ ├── store/
│ │ └── rootReducer.ts
│ ├── services/
│ │ └── auth.ts
│ └── styles/
│ └── theme.ts
├── assets/
│ └── screenshots/
│ ├── home-screen.png
│ └── library-screen.png
├── README.md
└── package.json


## 📷 Screenshots / Demo  
![Home Screen](assets/screenshots/home-screen.png)  
![Library Screen](assets/screenshots/library-screen.png)  

Or view the demo: [Demo Video](https://youtu.be/…)  

## 🧑‍💻 Installation  
```bash
git clone https://github.com/yourusername/mentally-stable-app.git  
cd mentally-stable-app  
npm install  
npm start  

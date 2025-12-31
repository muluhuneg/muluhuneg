<div align="center">

<!-- CSS Animations -->
<style>
.float-avatar {
  animation: float 6s ease-in-out infinite;
  border-radius: 50%;
  border: 4px solid;
  border-image: linear-gradient(45deg, #078930, #FCDD09, #DA121A) 1;
  box-shadow: 0 10px 30px rgba(7, 137, 48, 0.3);
}

@keyframes float {
  0% { transform: translateY(0px) rotate(0deg); }
  50% { transform: translateY(-20px) rotate(3deg); }
  100% { transform: translateY(0px) rotate(0deg); }
}

.pulse {
  animation: pulse 2s infinite;
}

@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.05); }
  100% { transform: scale(1); }
}

.ethiopian-flag {
  background: linear-gradient(90deg, #078930 33%, #FCDD09 33% 66%, #DA121A 66%);
  background-size: 300% 100%;
  animation: flag-wave 5s ease-in-out infinite;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: bold;
}

@keyframes flag-wave {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

.bounce {
  animation: bounce 2s infinite;
}

@keyframes bounce {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-15px); }
}

.card-glow {
  animation: cardGlow 3s infinite alternate;
}

@keyframes cardGlow {
  0% { box-shadow: 0 0 5px rgba(30, 144, 255, 0.5); }
  100% { box-shadow: 0 0 20px rgba(30, 144, 255, 0.8); }
}

.slide-in {
  animation: slideIn 0.5s ease-out;
}

@keyframes slideIn {
  from {
    opacity: 0;
    transform: translateY(20px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>

<!-- Animated Typing Text -->
![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=26&pause=1500&color=1E90FF&center=true&vCenter=true&width=600&lines=Hello+World!+👋;I'm+Mulu+Hunegnaw+🇪🇹;Software+Engineering+Student;Bahir+Dar+University+Student;Frontend+Specialist;Welcome+to+my+Profile!)

<!-- Floating Profile Picture -->
<img class="float-avatar" src="https://avatars.githubusercontent.com/u/161202584?v=4" width="200" height="200" alt="Mulu Hunegnaw">

<br>

<!-- Bouncing Ethiopia Flag -->
<div style="font-size: 40px; margin: 10px 0;">
  <span class="bounce">🇪🇹</span>
</div>

<!-- Animated Badges -->
<div style="display: flex; justify-content: center; gap: 10px; flex-wrap: wrap; margin: 15px 0;">
  <img src="https://img.shields.io/badge/Student-BahirDar%20University-1E90FF?style=for-the-badge&logo=university&logoColor=white" alt="Student">
  <img src="https://img.shields.io/badge/Software-Engineering-078930?style=for-the-badge&logo=code&logoColor=white" alt="Software Engineering">
  <img src="https://img.shields.io/badge/Frontend-Specialist-FCDD09?style=for-the-badge&logo=frontend&logoColor=black" alt="Frontend Specialist">
  <img src="https://komarev.com/ghpvc/?username=muluhuneg&color=DA121A&label=Profile+Views&style=for-the-badge" alt="Profile Views">
  <img src="https://img.shields.io/badge/Ethiopia-🇪🇹-078930?style=for-the-badge&logo=google-earth&logoColor=white" alt="Ethiopia">
</div>

</div>

## 📚 **About Me**

<div align="center">

```javascript
const muluHunegnaw = {
  name: "Mulu Hunegnaw",
  nationality: "Ethiopian 🇪🇹",
  education: {
    university: "Bahir Dar University",
    program: "Software Engineering",
    status: "Active Student",
    interests: ["Web Development", "Mobile Apps", "UI/UX Design"]
  },
  specialization: "Frontend Development",
  skills: {
    core: ["HTML5", "CSS3", "JavaScript"],
    frameworks: ["React", "Vue.js", "Bootstrap"],
    tools: ["Git", "VS Code", "Figma", "GitHub"],
    learning: ["TypeScript", "Next.js", "Tailwind CSS"]
  },
  goals: [
    "Become expert Frontend Developer",
    "Build amazing user interfaces",
    "Contribute to open source",
    "Help Ethiopian tech community"
  ]
};

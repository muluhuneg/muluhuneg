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
</div>
🎓 My Education
<div align="center"><h3 class="ethiopian-flag">🎯 Bahir Dar University - Software Engineering</h3><p style="color: #1E90FF; font-style: italic;"> "Pursuing excellence in software development with Ethiopian innovation" </p><!-- Education Timeline --><div style="text-align: left; max-width: 600px; margin: 20px auto; padding: 20px; background: rgba(30, 144, 255, 0.05); border-radius: 10px;"><div class="slide-in" style="margin-bottom: 15px; padding-left: 20px; border-left: 3px solid #078930;"> <h4>📘 Current Studies</h4> <p>Bachelor of Science in Software Engineering</p> <p><small>Bahir Dar University, Ethiopia</small></p> </div><div class="slide-in" style="margin-bottom: 15px; padding-left: 20px; border-left: 3px solid #FCDD09; animation-delay: 0.2s;"> <h4>🎯 Focus Areas</h4> <ul> <li>Web & Mobile Application Development</li> <li>User Interface Design</li> <li>Software Engineering Principles</li> <li>Database Systems</li> </ul> </div><div class="slide-in" style="padding-left: 20px; border-left: 3px solid #DA121A; animation-delay: 0.4s;"> <h4>🚀 Career Goals</h4> <ul> <li>Senior Frontend Developer</li> <li>UI/UX Designer</li> <li>Tech Mentor in Ethiopia</li> <li>Open Source Contributor</li> </ul> </div></div></div>
💻 Frontend Skills
<div align="center"><h3 class="ethiopian-flag">✨ My Tech Stack ✨</h3><!-- Skills Grid --><div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); gap: 15px; margin: 20px 0;"><div style="text-align: center; padding: 15px; border-radius: 10px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); animation: slideIn 0.5s ease-out;"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" width="40" height="40"> <p>React</p> </div><div style="text-align: center; padding: 15px; border-radius: 10px; background: linear-gradient(135deg, #42b883 0%, #35495e 100%); animation: slideIn 0.5s ease-out 0.1s;"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vuejs/vuejs-original.svg" width="40" height="40"> <p>Vue.js</p> </div><div style="text-align: center; padding: 15px; border-radius: 10px; background: linear-gradient(135deg, #f7df1e 0%, #000000 100%); animation: slideIn 0.5s ease-out 0.2s;"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="40" height="40"> <p>JavaScript</p> </div><div style="text-align: center; padding: 15px; border-radius: 10px; background: linear-gradient(135deg, #e34c26 0%, #f06529 100%); animation: slideIn 0.5s ease-out 0.3s;"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="40" height="40"> <p>HTML5</p> </div><div style="text-align: center; padding: 15px; border-radius: 10px; background: linear-gradient(135deg, #264de4 0%, #2965f1 100%); animation: slideIn 0.5s ease-out 0.4s;"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="40" height="40"> <p>CSS3</p> </div><div style="text-align: center; padding: 15px; border-radius: 10px; background: linear-gradient(135deg, #06b6d4 0%, #0ea5e9 100%); animation: slideIn 0.5s ease-out 0.5s;"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" width="40" height="40"> <p>Tailwind</p> </div><div style="text-align: center; padding: 15px; border-radius: 10px; background: linear-gradient(135deg, #7952b3 0%, #563d7c 100%); animation: slideIn 0.5s ease-out 0.6s;"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" width="40" height="40"> <p>Bootstrap</p> </div><div style="text-align: center; padding: 15px; border-radius: 10px; background: linear-gradient(135deg, #f24e1e 0%, #a259ff 100%); animation: slideIn 0.5s ease-out 0.7s;"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" width="40" height="40"> <p>Figma</p> </div></div></div>
📊 GitHub Stats
<div align="center"><!-- GitHub Statistics --><a href="https://github.com/muluhuneg"> <img class="pulse" src="https://github-readme-stats.vercel.app/api?username=muluhuneg&show_icons=true&theme=algolia&hide_border=true&bg_color=0D1117&title_color=1E90FF&icon_color=078930&text_color=FFFFFF" height="180" alt="GitHub Stats"> </a><a href="https://github.com/muluhuneg"> <img src="https://github-readme-streak-stats.herokuapp.com/?user=muluhuneg&theme=algolia&hide_border=true&background=0D1117&ring=1E90FF&fire=FCDD09&currStreakLabel=DA121A" height="180" alt="GitHub Streak"> </a>



<!-- Top Languages --><a href="https://github.com/muluhuneg"> <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=muluhuneg&layout=compact&theme=algolia&hide_border=true&bg_color=0D1117&title_color=1E90FF&text_color=FFFFFF" height="180" alt="Top Languages"> </a></div>
🚀 My Projects
<div align="center"><h3 class="ethiopian-flag">🎯 Academic & Personal Projects</h3><div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin: 20px 0;"><!-- Project 1 --><div class="card-glow" style="border: 1px solid #1E90FF; border-radius: 10px; padding: 20px; text-align: left; background: rgba(30, 144, 255, 0.05);"> <h4>🎓 University Portal UI</h4> <p>Modern UI redesign for Bahir Dar University student portal</p> <div style="display: flex; gap: 5px; margin: 10px 0; flex-wrap: wrap;"> <span style="background: #1E90FF; color: white; padding: 3px 8px; border-radius: 15px; font-size: 12px;">React</span> <span style="background: #078930; color: white; padding: 3px 8px; border-radius: 15px; font-size: 12px;">CSS3</span> <span style="background: #FCDD09; color: black; padding: 3px 8px; border-radius: 15px; font-size: 12px;">JavaScript</span> </div> </div><!-- Project 2 --><div class="card-glow" style="border: 1px solid #078930; border-radius: 10px; padding: 20px; text-align: left; background: rgba(7, 137, 48, 0.05); animation-delay: 1s;"> <h4>🌍 Ethiopia Tourism Website</h4> <p>Showcasing Ethiopian tourist destinations with interactive maps</p> <div style="display: flex; gap: 5px; margin: 10px 0; flex-wrap: wrap;"> <span style="background: #42b883; color: white; padding: 3px 8px; border-radius: 15px; font-size: 12px;">Vue.js</span> <span style="background: #DA121A; color: white; padding: 3px 8px; border-radius: 15px; font-size: 12px;">HTML5</span> <span style="background: #1E90FF; color: white; padding: 3px 8px; border-radius: 15px; font-size: 12px;">API</span> </div> </div><!-- Project 3 --><div class="card-glow" style="border: 1px solid #FCDD09; border-radius: 10px; padding: 20px; text-align: left; background: rgba(252, 221, 9, 0.05); animation-delay: 2s;"> <h4>📱 Student Task Manager</h4> <p>Mobile-friendly task management app for university students</p> <div style="display: flex; gap: 5px; margin: 10px 0; flex-wrap: wrap;"> <span style="background: #f7df1e; color: black; padding: 3px 8px; border-radius: 15px; font-size: 12px;">JavaScript</span> <span style="background: #7952b3; color: white; padding: 3px 8px; border-radius: 15px; font-size: 12px;">Bootstrap</span> <span style="background: #078930; color: white; padding: 3px 8px; border-radius: 15px; font-size: 12px;">PWA</span> </div> </div></div></div>
📚 Currently Learning
<div align="center">
javascript
const currentLearning = {
  frontend: ["React Hooks", "TypeScript", "Next.js"],
  design: ["Advanced Animations", "Responsive Design", "Figma"],
  tools: ["Git Advanced", "Webpack", "Testing Libraries"],
  goals: [
    "Complete 3 major projects",
    "Learn backend basics",
    "Improve problem-solving skills",
    "Build portfolio website"
  ]
};
</div>
🌍 Connect With Me
<div align="center"><div style="display: flex; justify-content: center; gap: 15px; flex-wrap: wrap; margin: 20px 0;"><a href="mailto:mulu.hunegnaw@example.com"> <img src="https://img.shields.io/badge/Email-mulu.hunegnaw@example.com-DA121A?style=for-the-badge&logo=gmail&logoColor=white" height="40"> </a><a href="https://github.com/muluhuneg"> <img src="https://img.shields.io/badge/GitHub-Follow-078930?style=for-the-badge&logo=github&logoColor=white" height="40"> </a><a href="#"> <img src="https://img.shields.io/badge/LinkedIn-Connect-1E90FF?style=for-the-badge&logo=linkedin&logoColor=white" height="40"> </a><a href="#"> <img src="https://img.shields.io/badge/Twitter-Follow-FCDD09?style=for-the-badge&logo=twitter&logoColor=black" height="40"> </a></div><p style="color: #666; font-size: 14px;"> 💡 <em>Replace # with your actual social media links</em> </p></div>
🎨 My Design Philosophy
<div align="center"><blockquote style="border-left: 4px solid #DA121A; padding-left: 20px; font-style: italic; text-align: left; background: rgba(218, 18, 26, 0.05); padding: 20px; border-radius: 0 10px 10px 0; margin: 30px auto; max-width: 600px;"> <p>"As a frontend developer, I believe in creating interfaces that are not just functional, but also delightful to use. Every button, animation, and layout should serve the user's needs while providing an enjoyable experience."</p> <p style="text-align: right; color: #1E90FF; margin-top: 10px;">— Mulu Hunegnaw</p> </blockquote></div>
<div align="center">
⭐ Support My Journey
<p>If you find my work interesting, consider giving a star to my repositories!</p><!-- Visitor Counter --><div style="margin: 20px 0;"> <img src="https://profile-counter.glitch.me/muluhuneg/count.svg" alt="Visitor Counter"> </div>
🇪🇹 Proud Ethiopian Software Engineering Student 🇪🇹
<!-- Bouncing Icons --><div style="font-size: 50px; margin: 30px 0;"> <span class="bounce" style="animation-delay: 0s;">🇪🇹</span> <span class="bounce" style="animation-delay: 0.2s;">💻</span> <span class="bounce" style="animation-delay: 0.4s;">🎓</span> <span class="bounce" style="animation-delay: 0.6s;">🚀</span> <span class="bounce" style="animation-delay: 0.8s;">✨</span> </div><p style="color: #1E90FF; font-size: 18px; margin-top: 20px;"> <strong>Thank you for visiting my profile! ✨</strong> </p></div> 

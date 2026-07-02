content = r"""<h1 align="center">
  <span style="font-size: 3.2rem; font-weight: 900;">Hi 👋, I'm <strong>Dharmik</strong></span>
</h1>
<h3 align="center">Computer Programming & Analysis Student | Seneca Polytechnic</h3>

###

<div align="center">
  <img src="https://skillicons.dev/icons?i=java" height="60" alt="java logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=kotlin" height="60" alt="kotlin logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=js" height="60" alt="javascript logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=ts" height="60" alt="typescript logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=py" height="60" alt="python logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=c" height="60" alt="c logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=cpp" height="60" alt="cpp logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=html" height="60" alt="html logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=css" height="60" alt="css logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=nodejs" height="60" alt="nodejs logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=express" height="60" alt="express logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=react" height="60" alt="react logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=mysql" height="60" alt="mysql logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=sqlite" height="60" alt="sqlite logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=git" height="60" alt="git logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=github" height="60" alt="github logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=docker" height="60" alt="docker logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=linux" height="60" alt="linux logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=aws" height="60" alt="aws logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=androidstudio" height="60" alt="androidstudio logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=postman" height="60" alt="postman logo" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=vscode" height="60" alt="vscode logo" />
</div>

###

<div align="center">
  <a href="https://www.linkedin.com/in/dharmik-dhameliya/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo" />
  </a>
</div>

---

## 💡 About Me

- 🎓 Final-year **Computer Programming & Analysis (Advanced Diploma)** student at **Seneca Polytechnic**
- 🛠️ IT Service Desk experience — technical support, troubleshooting, and ticketing
- 💻 Building full-stack web apps, REST APIs, Android apps, and computer vision projects
- 🤝 Team collaborator — experienced with Git, pull requests, and Agile/Scrum workflows
- 🌱 Currently exploring **Cloud (AWS)**, **Docker**, and **CI/CD pipelines**
- 🎯 Open to opportunities in Software Development, IT Support, Data, and Cloud

---

## 📂 Featured Projects

### 🔧 [Fragments](https://github.com/DharmikDhameliya/fragments)
> Cloud-based REST API for managing user data fragments
- Built with **Node.js + Express.js**
- Supports multiple content types with full CRUD operations
- Authentication, structured error handling, and API best practices
- Tested with **Postman**, deployed on cloud infrastructure

###

### 🖥️ [Fragments UI](https://github.com/DharmikDhameliya/fragments-ui)
> React frontend for the Fragments API
- Built with **React.js**
- Consumes authenticated REST APIs
- Responsive UI with user authentication flow

###

### 🤝 [Hamdel Web App](https://github.com/hamdel-app/hamdel-web)
> Team-built project management web application
- Collaborated using **Git, pull requests, and Agile/Scrum**
- Contributed features and bug fixes in a multi-developer team

###

### 📱 Android Application (Kotlin)
> Native Android app built with Kotlin
- Activity lifecycle, navigation, and local data handling
- Followed Android development best practices

###

### 👁️ Computer Vision Final Project
> Python-based computer vision application
- Applied image processing and CV techniques using **OpenCV**
- Built as a final academic project

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=DharmikDhameliya&show_icons=true&theme=dracula&hide_border=false" height="150" alt="stats graph" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=DharmikDhameliya&layout=compact&theme=dracula&hide_border=false" height="150" alt="languages graph" />
</div>

###

<div align="center">
  <img src="https://streak-stats.demolab.com?user=DharmikDhameliya&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5&order=3" height="150" alt="streak graph" />
</div>

###

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/maurodesouza/maurodesouza/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/maurodesouza/maurodesouza/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/maurodesouza/maurodesouza/output/pacman-contribution-graph.svg">
</picture>
"""

with open('README.md', 'w', encoding='utf-8') as f:
    f.write(content)
print('README.md created')

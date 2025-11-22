I wish to create a project file structure and I wanted to give you the whole project structure but I don't want to manually create all of these files as it will be very time-taking so I will simply just give you the project structure and what you may do is you may create a Python script which will create all of these files for me in one single click. The Python script will take the directory root folder in the input. Create an empty placeholder in the Python script for that. So yeah, can you create such Python script? I am sharing with you the desired project structure.



```
backend/
│
├── src/
│   └── main/
│       ├── java/
│       │   └── com/
│       │       └── aditya/
│       │           └── portfolio/
│       │               ├── PortfolioBackendApplication.java
│       │               │
│       │               ├── controller/
│       │               │   ├── AboutController.java
│       │               │   ├── SkillsController.java
│       │               │   ├── ExperienceController.java
│       │               │   ├── ProjectsController.java
│       │               │   ├── EducationController.java
│       │               │   └── ContactController.java
│       │               │
│       │               ├── service/
│       │               │   ├── ContentService.java
│       │               │   └── impl/
│       │               │       └── ContentServiceImpl.java
│       │               │
│       │               ├── model/
│       │               │   ├── About.java
│       │               │   ├── Skills.java
│       │               │   ├── Experience.java
│       │               │   ├── Project.java
│       │               │   ├── ProjectsWrapper.java
│       │               │   ├── Education.java
│       │               │   └── Contact.java
│       │               │
│       │               ├── util/
│       │               │   ├── JsonLoader.java
│       │               │   └── CustomException.java
│       │               │
│       │               └── config/
│       │                   ├── WebConfig.java
│       │                   ├── CORSConfig.java
│       │                   └── SwaggerConfig.java
│       │
│       └── resources/
│           ├── content/
│           │   ├── about.json
│           │   ├── skills.json
│           │   ├── experience.json
│           │   ├── projects.json
│           │   ├── education.json
│           │   └── contact.json
│           │
│           ├── static/     (optional)
│           │    └── profile.jpg
│           │
│           ├── application.properties
│           └── banner.txt   (optional, for branding)
│
├── .gitignore
├── pom.xml
└── README.md
```

Also don't create the backend folder, I already have that. I want the content inside of it.

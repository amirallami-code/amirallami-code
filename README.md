```js
const createDeveloperProfile = () => {
  const profile = {
    name: "Amir",
    title: "Front-end developer",
    quote: "Turning caffeine into code since 2023",
    interests: ["Web Development", "Algorithm Design", "Linux Systems"],
    technologies: ["HTML/CSS", "JavaScript", "Tailwind", "Bootstrap", "RegEx", "Git"],
    contact: {
      email: "amirallami.dev@gmail.com",
      github: "github.com/amirallami-code"
    },
    introduce: function () {
      return `
        const developer = {
          name: "${this.name}",
          mantra: "${this.quote}",
          expertise: ${JSON.stringify(this.interests)},
          stack: ${JSON.stringify(this.technologies)},
          connect: ${JSON.stringify(this.contact)}
        };
      `;
    },
  };
  return profile;
};

const developerProfile = createDeveloperProfile();
console.log(developerProfile.introduce());
```

<div align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,tailwind,bootstrap,regex,git,wordpress"/> 
</div>

```js
const developerProfile = {
  name: 'Amir',
  title: 'Frontend Developer',
  location: 'Shiraz, Iran',
  
  skills: ['HTML/CSS', 'JavaScript', 'Tailwind', 'Bootstrap', 'RegEx', 'Git'],
  
  passion: 'Crafting responsive and user-friendly web interfaces',
  
  interests: ['Web Development', 'UI/UX Design', 'Open Source'],
  
  currentlyLearning: 'React',
  
  contact: {
    email: 'amirallami.dev@gmail.com',
    github: 'github.com/amirallami-code',
  },
  
  getFeaturedProject: function() {
    return {
      name: 'rock-paper-scissors-game',
      description: 'Brief description of your best project',
      technologies: ['JavaScript', 'Tailwind CSS', 'Git'],
    };
  },
  
  introduce: function() {
    console.log(`Hello! I'm ${this.name}, a ${this.title} based in ${this.location}.`);
    console.log(`I specialize in ${this.passion}.`);
    console.log(`My skills include: ${this.skills.join(', ')}`);
    console.log(`I'm currently learning ${this.currentlyLearning} to expand my skillset.`);
    console.log(`Let's connect! Find me on GitHub: ${this.contact.github}`);
    
    const project = this.getFeaturedProject();
    console.log(`Featured Project: ${project.name}`);
    console.log(`Description: ${project.description}`);
    console.log(`Technologies used: ${project.technologies.join(', ')}`);
  }
};

// Run this code to learn more about Amir!
developerProfile.introduce();
```

<div align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,tailwind,bootstrap,regex,git,wordpress"/> 
</div>

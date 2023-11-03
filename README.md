```js
const aboutMe = () => {
  const myLife = {
    innerName: "Amirhossein Allami",
    innerBirthday: "October 7",
    quote: "I develop what comes to my head with some style",
    hobbies: ["coding", "algorithm", "game"],
    getHobbiesCount: function() {
      return this.hobbies.length;
    },
    introduce: function() {
      return `Hi, I'm ${this.innerName}. My birthday is on ${this.innerBirthday}.
              One of my favorite quotes is "${this.quote}".
              I enjoy ${this.getHobbiesCount()} hobbies: ${this.hobbies.join(", ")}.`;
    }
  };
  return myLife;
};
const myInfo = aboutMe();
console.log(myInfo.introduce());
```

🪐 I have some experience with:

<img src="https://skillicons.dev/icons?i=html,css,js,tailwind,bootstrap,regex,git,wordpress"/> 
</a>

<p align="center"> <img src="https://komarev.com/ghpvc/?username=amirallami-code&label=Profile%20views&color=gray&style=flat" alt="amirallami-code" /> </p>

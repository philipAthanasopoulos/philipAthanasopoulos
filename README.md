<div align = "center">
<h1>Hello World</h1>
    <img align = "center" src = "https://i.pinimg.com/originals/d0/00/b3/d000b3641dcec6b05f48f3c6b76ff6ad.gif" width = "max" height = "auto">
</div>
<br/>

```javascript
const philip = {
  name: "philip",
  school: "Department of CS & Engineering, Ioannina Greece",
  skills: ["Java 🫘", "Spring Boot 🍃", "Python 🐍", "ReactJS ⚛️", "Ruby on Rails ♦️🛤"],
  interests: ["Web development", "Service Architecture"],
  beveragesOfChoice: ["☕", "☕", "☕", "☕", "☕"],

  introduce() {
    console.log(`Hi, I'm ${this.name} studying at ${this.school}.`);
  },

  listSkills() {
    console.log("Here are some of my skills:");
    this.skills.forEach(skill => console.log(`- ${skill}`));
  },

  workDay() {
    while (this.beveragesOfChoice.length > 0) {
      const beverage = this.beveragesOfChoice.shift();
      console.log("Enjoying a cup of " + beverage);
      console.log("⌨️💥⌨️💥⌨️💥");
    }
    console.log("Out of coffee! Time to brew another pot...");
  }
};

philip.introduce();
philip.listSkills();
philip.workDay();

```

<div align="center">
</div>
<p align="center">
  <a href="https://skillicons.dev">
      <h2 align = "center">What I usually use</h2>
      <div align = "center">
        <img src="https://skillicons.dev/icons?i=idea,react,java,spring,python,docker,js,html,css,bootstrap,ruby,rails" />
      </div>
  </a>
</p>
<div align = "center">
<h1>My Projects</h1>
    <img align = "center" src = "https://miro.medium.com/max/552/1*vJjJ3Mdok6Rvxx85IIRqBQ.gif" width = "max" height = "auto">
</div>

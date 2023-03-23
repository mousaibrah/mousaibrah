```js
profile.render();
"Hello my name is Mousa Ibrahim ,my age is 23 years old , i'm Full-Stack-Dev"
```

```js
class Profile {
  constructor() {
    this.name = "Mousa Ibrahim";
    this.age = "23 years old";
    this.i_am = "Full-Stack-Dev";
    this.ambition = "Reach New Level Of Accomplish And Mind Set Every Day";
    this.education = "Meraki Academy";
    this.projects = ["Movie Rate", "Job Seeker"];
  }
  render() {
    return `Hello my name is ${this.name} ,my age is ${this.age} , 
            i'm ${this.i_am}`;
  }
}

const profile = new Profile();
```

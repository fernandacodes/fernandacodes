# Olá! 👋🏼, Eu sou [Fernanda Ferreira](https://www.linkedin.com/in/fernandaferreira/)

## Trecho de código sobre mim 🤗
```typescript
class Me {
  private name: string;
  private course: string;
  private university: string;
  private job: string;
  private company: string;
  private focus: string;
  private pronouns: string;

  constructor(
    name: string,
    course: string,
    university: string,
    job: string,
    company: string,
    focus: string,
    pronouns: string
  ) {
    this.name = name;
    this.course = course;
    this.university = university;
    this.job = job;
    this.company = company;
    this.focus = focus;
    this.pronouns = pronouns;
  }

  whoIAm(): string {
    return ` 👩‍💻 My name is ${this.name} \n` +
           ` 🎓 I'm a(n) ${this.course} Graduating Student at ${this.university} \n` +
           ` 💼 Currently, I'm working as a(n) ${this.job} at ${this.company} \n` +
           ` 📚 My time is being spent learning ${this.focus} \n` +
           ` 😎 Pronouns: ${this.pronouns}`;
  }
}

const fernanda = new Me(
  "Fernanda Ferreira",
  "Information Systems",
  "Amazonas State University",
  "Back-end Developer Intern",
  "Awesome Tech",
  "Back End Development (TypeScript/Python/C#)",
  "She/Her"
);

console.log(fernanda.whoIAm());

```
### Output
```
  👩‍💻 My name is Fernanda de Melo Ferreira 
 🎓 I'm a(n) Computer science Graduating Student at Amazonas Federal University 
 💼 Currently, I'm working as a(n) Software Developer Trainee  at TCE/AM 
 📚 My time is being spent learning Back End Development (TypeScript/Python/C#) 
 😎 Pronouns: She/Her

```

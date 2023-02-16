# Hi 👋

```rust
fn main() {
    let me = SoftwareEngineer {
        name: "Andreas Ellwanger",
        role: "Software Engineer",
        company: "Celonis",
        languages: Vec::from(["de_DE", "en_US"])
    };
    me.say_hi();
}

#[allow(dead_code)]
struct SoftwareEngineer<'a> {
    name: &'a str,
    role: &'a str,
    company: &'a str,
    languages: Vec<&'a str>
}

impl SoftwareEngineer<'_> {
    fn say_hi(&self) {
        println!("Thanks for dropping by, hope you find some of my work interesting. ~{}", self.name);
    }
}
```

<!--

- 👨‍💻 &nbsp; I'm working at [Celonis](https://www.celonis.com/) (Process Mining) as Software Engineer
- 👨‍🎓 &nbsp; I'm pursuing a Masters' degree of Computer Sciences at [LMU Munich](https://www.uni-muenchen.de/), Germany
- 🌱 &nbsp; I’m currently deepening my knowledge in Java, Rust and Node.js
- 🚀 &nbsp; [Tech4Germany](https://tech.4germany.org/ueber-uns/) alumni (Engineering Fellow 2018)
- 😄 &nbsp; Pronouns: he/him


**ndrsllwngr/ndrsllwngr** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
- 📫 How to reach me: www.andreasellwanger.com
-->

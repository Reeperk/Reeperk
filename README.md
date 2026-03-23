<div align="center">
  <img height="200" src="https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/46379950?v=4&h=300&w=300&fit=cover&mask=circle" />
</div>

<h1 align="center">Reeperk</h1>

<p align="center"><i>~ cargo build --release ~</i></p>

<p align="center">
  <img src="https://count.getloli.com/get/@Reeperk?theme=booru-qualityhentais" alt="Profile Views" />
</p>

---

```rust
struct Developer {
    name: &'static str,
    alias: &'static str,
    age: u8,
    role: &'static str,
}

impl Developer {
    const fn new() -> Self {
        Self {
            name: "Marlon",
            alias: "Reeperk",
            age: 22,
            role: "Fullstack Web Developer",
        }
    }

    const fn languages(&self) -> &[&str] {
        &["Rust", "PHP", "TypeScript", "JavaScript", "Java", "C#", "C++", "Lua", "Dart", "SQL"]
    }

    const fn frameworks(&self) -> &[&str] {
        &["Actix", "Diesel ORM", "Symfony", "Doctrine ORM", "Astro", "TailwindCSS"]
    }

    const fn interests(&self) -> &[&str] {
        &["AI / ML", "Training custom models", "Kubernetes"]
    }
}

use reeperk::skills::{Skill, Project, Status};

fn main() {
    let dev = Developer::new();

    println!("Compiling {}...", dev.alias);
    println!("Status: building cool things since birth");

    // currently learning
    let mut k8s_skill = Skill::new("Kubernetes");
    k8s_skill.level_up(); // work in progress

    // side projects
    let qwix = Project::new("@QwixAI")
        .description("AI-powered hobby project")
        .status(Status::Active);
}
```

---

<h3 align="center">Tech Stack</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Actix-000000?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Diesel-B7410E?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Symfony-000000?style=for-the-badge&logo=symfony&logoColor=white" />
  <img src="https://img.shields.io/badge/Doctrine-FC6A31?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white" />
  <img src="https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" />
</p>

---

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Reeperk/Reeperk/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/Reeperk/Reeperk/output/github-snake.svg" />
    <img alt="github-snake" src="https://github.com/Reeperk/Reeperk/output/github-snake-dark.svg" />
  </picture>
</div>

<br>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Reeperk&theme=tokyo-night&hide_border=true&bg_color=00000000&line=7aa2f7&point=c0caf5&area=true&area_color=7aa2f7" />
</p>

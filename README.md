<!-- ### Hi there 👋 -->

More about me

```kotlin
data class Introduction(
    val name: String = "Mostafa Tavassoli Norouzi",
    val university: String = "Politecnico di Torino",
    val programmingLanguageSkills: List<String> = mutableListOf(
        "ReactJS",
        "HTML/CSS",
        "Node Express",
        "Kotlin",
        "Spring MVC",
        "Spring WebFlux",
        "Android"
    )
)

@PostMapping("/about-me")
fun processAboutMe(model: Model, introduction: Introduction): String {
    model.addAttribute("name", introduction.name)
    model.addAttribute("university", introduction.university)
    model.addAttribute("programmingLanguageSkills", introduction.programmingLanguageSkills)
    return "about-me"
}

```

<!--
```kotlin
val mosTavassoli = webDeveloper {
    about {
        name = "Mostafa Tavassoli Norouzi"
        university = "Politecnico di Torino"
    }
    skills("ReactJS",
           "HTML/CSS", 
           "Node Express", 
           "Kotlin", 
           "Spring MVC", 
           "Spring WebFlux", 
           "Android")
    links {
        linkedin = "https://www.linkedin.com/in/mostafa-tavassoli/"
    }
}
``` 
-->

<!--
![](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white)
![](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![](https://img.shields.io/badge/Kotlin-0095D5?&style=for-the-badge&logo=kotlin&logoColor=white) -->

![](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=javascript&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-ReactJS-informational?style=flat&logo=React&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-Kotlin-informational?style=flat&logo=kotlin&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-Android-informational?style=flat&logo=android&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/IDE-IntelliJ_IDEA-informational?style=flat&logo=intellij-idea&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-ReactJS-informational?style=flat&logo=javascript&logoColor=white&color=2bbc8a)
![](https://img.shields.io/badge/Code-Kotlin-informational?style=flat&logo=javascript&logoColor=white&color=2bbc8a)




<!--
<a href="https://github.com/mosTavassoli/mosTavassoli">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mosTavassoli&html&title_color=ffffff&text_color=c9cacc&icon_color=2bbc8a&bg_color=1d1f21" />
</a> -->



<!--
**mosTavassoli/mosTavassoli** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->


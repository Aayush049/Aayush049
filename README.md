<!--
  ================================================================
  ANDROID DEVELOPER COMMAND CENTER — README.md
  Owner: Ayush Srivastava
  ================================================================
  REPLACE-ME CHECKLIST (search for these tags):
    <YOUR_GITHUB_USERNAME>     -> your GitHub username (used everywhere)
    <YOUR_LEETCODE_USERNAME>   -> your LeetCode username
    <YOUR_LINKEDIN_URL>        -> full LinkedIn profile URL
    <YOUR_PORTFOLIO_URL>       -> your portfolio/website URL (or remove row)
    <YOUR_TWITTER_HANDLE>      -> X/Twitter handle without @ (or remove row)
    <YOUR_EMAIL>               -> your email address
    Project rows in section 6  -> real repo links + descriptions
  ================================================================
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:3DDC84,100:7F52FF&height=200&section=header&text=Android%20Developer%20Command%20Center&fontSize=38&fontColor=E6EDF3&animation=fadeIn&fontAlignY=38&desc=Kotlin%20%C2%B7%20Jetpack%20Compose%20%C2%B7%20Modern%20App%20Engineering&descAlignY=58&descSize=16" width="100%"/>

</div>

<br>

<!-- ============================================================ -->
<!-- 1. HERO / HEADER SECTION — MainActivity.kt style             -->
<!-- ============================================================ -->

<table align="center" width="100%">
<tr><td>

```kotlin
// MainActivity.kt
package com.ayushsrivastava.dev

import android.os.Bundle
import androidx.activity.ComponentActivity
import androidx.compose.runtime.Composable

class Developer(
    val name: String = "Ayush Srivastava",
    val role: String = "Android Developer",
    val university: String = "KIIT University",
    val program: String = "B.Tech CSE (2024 - 2028)",
    val gpa: Double = 9.4,
    val location: String = "India",
    val currentFocus: List<String> = listOf(
        "Kotlin", "Jetpack Compose", "Android Studio"
    ),
    val learning: List<String> = listOf(
        "Backend Development", "AI Integration"
    )
)

class MainActivity : ComponentActivity() {

    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        val me = Developer()
        render(me)
    }

    @Composable
    fun render(dev: Developer) {
        // Build passing ✅  |  Gradle sync successful  |  0 warnings
        println("${dev.name} is compiling ambition into APKs.")
    }
}
```

</td></tr>
</table>

<div align="center">

![Build](https://img.shields.io/badge/BUILD-PASSING-3DDC84?style=for-the-badge&logo=android&logoColor=white&labelColor=0D1117)
![Gradle](https://img.shields.io/badge/GRADLE-SYNCED-02303A?style=for-the-badge&logo=gradle&logoColor=white&labelColor=0D1117)
![Kotlin](https://img.shields.io/badge/KOTLIN-READY-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white&labelColor=0D1117)

</div>

<br>

<!-- ============================================================ -->
<!-- 2. ABOUT ME                                                   -->
<!-- ============================================================ -->

## `//` About Me

```
┌─ activity_about.xml ─────────────────────────────────────────────┐
│                                                                    │
│  I build Android apps the way Gradle builds projects —           │
│  one dependency, one module, one clean architecture at a time.   │
│                                                                    │
│  🎓  B.Tech CSE @ KIIT University (2024 – 2028) · GPA 9.4        │
│  📍  India                                                       │
│  🛠  Currently engineering with Kotlin, Jetpack Compose,          │
│      and Android Studio                                          │
│  📡  Expanding the stack into Backend Development & AI            │
│      Integration                                                  │
│  🎯  Focused on writing production-grade, maintainable,           │
│      recruiter-worthy Android code — not tutorial code            │
│                                                                    │
└────────────────────────────────────────────────────────────────────┘
```

<br>

<!-- ============================================================ -->
<!-- 3. CONNECT LINKS                                              -->
<!-- ============================================================ -->

## `//` Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](<YOUR_LINKEDIN_URL>)
[![Portfolio](https://img.shields.io/badge/Portfolio-3DDC84?style=for-the-badge&logo=googlechrome&logoColor=white)](<YOUR_PORTFOLIO_URL>)
[![Twitter](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://twitter.com/<YOUR_TWITTER_HANDLE>)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:<YOUR_EMAIL>)

</div>

<br>

<!-- ============================================================ -->
<!-- 4. ANDROID TECH STACK — styled as build.gradle.kts            -->
<!-- ============================================================ -->

## `//` Android Tech Stack

```kotlin
// build.gradle.kts

dependencies {

    // Languages
    implementation("lang:kotlin:primary")
    implementation("lang:java:core")
    implementation("lang:python:scripting-and-ml")
    implementation("lang:c:systems-fundamentals")

    // Android
    implementation("android:studio:daily-driver")
    implementation("androidx.compose:jetpack-compose:declarative-ui")
    implementation("android:xml:legacy-views")
    implementation("android:gradle:build-system")
    implementation("google:firebase:backend-as-a-service")

    // Backend
    implementation("org.springframework:spring-boot:api-layer")
    implementation("web:rest-apis:client-server")
    implementation("postgresql:database:relational")
    implementation("redis:cache:in-memory")

    // Tools
    implementation("git:version-control")
    implementation("os:linux:dev-environment")
    implementation("editor:vscode:scripting")
    implementation("jetbrains:intellij-idea:jvm-development")
}
```

<br>

<!-- ============================================================ -->
<!-- 5. SKILL MATRIX                                               -->
<!-- ============================================================ -->

## `//` Skill Matrix

<div align="center">

| Layer | Stack |
|---|---|
| **Languages** | ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) |
| **Android** | ![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=flat-square&logo=androidstudio&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![XML](https://img.shields.io/badge/XML-005FAD?style=flat-square&logo=xml&logoColor=white) ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square&logo=fastapi&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white) |

</div>

<br>

<!-- ============================================================ -->
<!-- 6. PROJECTS                                                   -->
<!-- ============================================================ -->

## `//` Projects

<!--
  Replace each row below with a real project.
  Keep the "package" naming style for consistency with the theme.
-->

<table>
<tr>
<td width="50%" valign="top">

**`com.ayush.projectone`**

> One-line description of what this app does and who it's for.

`Kotlin` `Jetpack Compose` `Firebase`

[View Repository →](https://github.com/<YOUR_GITHUB_USERNAME>/project-one)

</td>
<td width="50%" valign="top">

**`com.ayush.projecttwo`**

> One-line description of what this app does and who it's for.

`Kotlin` `MVVM` `Room DB`

[View Repository →](https://github.com/<YOUR_GITHUB_USERNAME>/project-two)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**`com.ayush.projectthree`**

> One-line description of what this app does and who it's for.

`Kotlin` `Spring Boot` `REST API`

[View Repository →](https://github.com/<YOUR_GITHUB_USERNAME>/project-three)

</td>
<td width="50%" valign="top">

**`com.ayush.projectfour`**

> One-line description of what this app does and who it's for.

`Jetpack Compose` `PostgreSQL` `Redis`

[View Repository →](https://github.com/<YOUR_GITHUB_USERNAME>/project-four)

</td>
</tr>
</table>

<br>

<!-- ============================================================ -->
<!-- 7. GITHUB STATISTICS                                          -->
<!-- ============================================================ -->

## `//` GitHub Statistics

<div align="center">

<img src="https://komarev.com/ghpvc/?username=<YOUR_GITHUB_USERNAME>&label=PROFILE%20VIEWS&color=3DDC84&style=for-the-badge" alt="Profile Views"/>

<br><br>

<img src="https://github-readme-stats.vercel.app/api?username=<YOUR_GITHUB_USERNAME>&show_icons=true&theme=github_dark&bg_color=0D1117&title_color=3DDC84&icon_color=7F52FF&text_color=E6EDF3&border_color=30363D&hide_border=false&count_private=true" alt="GitHub Stats" width="49%"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=<YOUR_GITHUB_USERNAME>&theme=github-dark-blue&background=0D1117&stroke=30363D&ring=3DDC84&fire=7F52FF&currStreakLabel=3DDC84&border=30363D" alt="GitHub Streak" width="49%"/>

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=<YOUR_GITHUB_USERNAME>&theme=react-dark&bg_color=0D1117&color=3DDC84&line=7F52FF&point=E6EDF3&border=30363D&hide_border=false" alt="Contribution Calendar" width="100%"/>

</div>

<br>

<!-- ============================================================ -->
<!-- 8. LEETCODE STATISTICS                                        -->
<!-- ============================================================ -->

## `//` LeetCode Statistics

<div align="center">

<img src="https://leetcard.jacoblin.cool/<YOUR_LEETCODE_USERNAME>?theme=dark&font=Roboto&ext=heatmap&border=true" alt="LeetCode Stats" width="70%"/>

</div>

<br>

<!-- ============================================================ -->
<!-- 9. CONTRIBUTION SNAKE                                         -->
<!-- ============================================================ -->

## `//` Contribution Snake

<div align="center">

<!--
  This image is generated by a GitHub Action (setup instructions below).
  Until the Action runs once, this will show a broken image link — that's expected.
-->
<img src="https://raw.githubusercontent.com/<YOUR_GITHUB_USERNAME>/<YOUR_GITHUB_USERNAME>/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake" width="100%"/>

</div>

<br>

<!-- ============================================================ -->
<!-- 10. DEVELOPER JOURNEY TIMELINE                                -->
<!-- ============================================================ -->

## `//` Developer Journey

```
git log --oneline --graph --decorate

* 2024   │ commit  "Enrolled in B.Tech CSE @ KIIT University"
* 2024   │ commit  "First 'Hello World' — first Android emulator boot"
* 2025   │ commit  "Migrated mindset from XML to Jetpack Compose"
* 2025   │ commit  "Started exploring Spring Boot + REST APIs"
* 2026   │ commit  "Integrating AI capabilities into Android apps"
* HEAD → │ commit  "Building production-ready Android applications"
```

<!--
  Replace the entries above with your real milestones —
  first app shipped, hackathon, internship, certification, etc.
  Keep the git-log aesthetic for consistency.
-->

<br>

<!-- ============================================================ -->
<!-- DEVELOPER PERSONALITY / STATUS LINE                           -->
<!-- ============================================================ -->

<div align="center">

```
> currentStatus.kt

status = "Debugging life one breakpoint at a time — 
          Gradle sync included, free of charge."
```

</div>

<br>

<!-- ============================================================ -->
<!-- 11. FOOTER MESSAGE                                            -->
<!-- ============================================================ -->

<div align="center">

```
// Thanks for compiling this far.
// This README rebuilds on every commit — just like I do.
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F52FF,50:3DDC84,100:0D1117&height=120&section=footer" width="100%"/>

</div>

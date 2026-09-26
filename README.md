<div align="center">

<!-- ANDROID STATUS BAR SIMULATION -->
<!-- <p align="center">
  <code><b>📶 5G</b> &nbsp; • &nbsp; <b>🔋 100%</b> &nbsp; • &nbsp; <b>📍 India</b> &nbsp; • &nbsp; <b>☕ <code>build.gradle.kts: OK</code></b></code>
</p> -->

<!-- DYNAMIC HERO BANNER (self-hosted, no external render service) -->
<img src="banner.svg" width="100%" alt="Ayush Srivastava - Android Developer"/>

<br/><br/>

<a href="https://github.com/Aayush049">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=3DDC84&background=00000000&center=true&vCenter=true&width=680&lines=%24+whoami+%E2%86%92+Android+%2B+Flutter+Developer;%24+stack+%3D+listOf(%22Kotlin%22%2C+%22Compose%22%2C+%22Flutter%22);%24+status+%E2%86%92+Compiling+ambition+into+APKs;%24+currently_building+%E2%86%92+LearnMate+AI+(team+project)" alt="Typing SVG"/>
</a>

<br/>

<!-- PROFILE VIEWS + TYPING TERMINAL -->
<a href="https://github.com/Aayush049">
  <img src="https://komarev.com/ghpvc/?username=Aayush049&style=for-the-badge&label=PROFILE+VIEWS&color=3DDC84&labelColor=0D1117" alt="Profile Views"/>
</a>
&nbsp;
<a href="https://github.com/Aayush049">
  <img src="https://img.shields.io/badge/GitHub-7F52FF?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="GitHub"/>
</a>
&nbsp;
<a href="https://www.linkedin.com/in/ayush-srivastava049">
  <img src="https://img.shields.io/badge/LinkedIn-3DDC84?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn"/>
</a>
&nbsp;
<a href="mailto:ayush.sri0108@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-7F52FF?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Gmail"/>
</a>

</div>

---

## `>` ./MainActivity.kt

```kotlin
package com.ayushsrivastava.dev

import androidx.compose.runtime.Composable
import androidx.activity.ComponentActivity

class Developer(
    val name: String = "Ayush Srivastava",
    val role: String = "Android Developer",
    val university: String = "KIIT University",
    val program: String = "B.Tech CSE (2024 - 2028)",
    val gpa: Double = 9.4,               // yes, that's real
    val location: String = "India",
    val currentFocus: List<String> = listOf(
        "Kotlin", "Jetpack Compose", "Android Studio"
    ),
    val learning: List<String> = listOf(
        "Flutter", "Backend Development", "AI Integration"
    )
)

class MainActivity : ComponentActivity() {
    @Composable
    fun render(dev: Developer) {
        // Build passing ✅  Gradle synced ✅  0 blocking warnings
        println("${dev.name} is compiling ambition into APKs.")
    }
}
```

<div align="center">

[![Build](https://img.shields.io/badge/BUILD-PASSING-3DDC84?style=for-the-badge&logo=android&logoColor=white&labelColor=0D1117)](https://github.com/Aayush049)
[![Gradle](https://img.shields.io/badge/GRADLE-SYNCED-02303A?style=for-the-badge&logo=gradle&logoColor=white&labelColor=0D1117)](https://github.com/Aayush049)
[![Kotlin](https://img.shields.io/badge/KOTLIN-READY-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white&labelColor=0D1117)](https://github.com/Aayush049)

</div>

---

## `>` cat ./build.gradle.kts

```kotlin
dependencies {
    languages      ("Kotlin", "Java", "Dart", "Python", "C")
    android        ("Android Studio", "Jetpack Compose", "XML", "Gradle", "Room", "Firebase")
    crossPlatform  ("Flutter")
    backend        ("Spring Boot", "REST APIs", "PostgreSQL", "Redis")
    tools          ("Git", "Linux", "VS Code", "IntelliJ IDEA")
}
```

<div align="center">

**Languages**

[![](https://skillicons.dev/icons?i=kotlin,java,dart,python,c&theme=dark)](https://github.com/Aayush049)

**Android**

[![](https://skillicons.dev/icons?i=androidstudio,firebase&theme=dark)](https://github.com/Aayush049)

**Cross-Platform**

[![](https://skillicons.dev/icons?i=flutter,dart&theme=dark)](https://github.com/Aayush049)

**Backend** <sub>· learning</sub>

[![](https://skillicons.dev/icons?i=spring,postgres,redis&theme=dark)](https://github.com/Aayush049)

**Tools**

[![](https://skillicons.dev/icons?i=git,linux,vscode,idea&theme=dark)](https://github.com/Aayush049)

</div>

---

## `>` ./skill-matrix --render

```
╔════════════════════════╦═════════════════════╦═══════════╗
║ Skill                  ║ Progress             ║ Level     ║
╠════════════════════════╬═════════════════════╬═══════════╣
║ Kotlin                 ║ █████████░           ║ Advanced  ║
║ Jetpack Compose        ║ ████████░░           ║ Strong    ║
║ Android Studio         ║ █████████░           ║ Advanced  ║
║ Flutter                ║ ██████░░░░           ║ Growing   ║
║ XML Layouts            ║ ████████░░           ║ Strong    ║
║ Room / SQLite          ║ ██████░░░░           ║ Growing   ║
║ Gradle                 ║ ███████░░░           ║ Strong    ║
║ Java                   ║ ████████░░           ║ Strong    ║
║ REST APIs              ║ ██████░░░░           ║ Growing   ║
║ Firebase               ║ █████░░░░░           ║ Learning  ║
║ Spring Boot            ║ █████░░░░░           ║ Learning  ║
║ PostgreSQL / Redis     ║ █████░░░░░           ║ Learning  ║
║ Python                 ║ █████░░░░░           ║ Learning  ║
║ AI Integration         ║ ████░░░░░░           ║ Learning  ║
╚════════════════════════╩═════════════════════╩═══════════╝
```

---

## `>` ls ./projects/ --details

<details>
<summary><b>☕ Brewly</b></summary>
<br/>

```
PROJECT : Brewly
TYPE    : Android Application (Frontend)
STACK   : Kotlin · Jetpack Compose
REPO    : https://github.com/Aayush049/Brewly

DESCRIPTION:
  A cozy coffee-ordering app built entirely in Jetpack Compose —
  home, product details, cart, favourites, and profile screens,
  with a fully custom UI component set. Frontend complete;
  backend integration planned next.
```

[![View Repo](https://img.shields.io/badge/View%20Repo-Brewly-3DDC84?style=for-the-badge&logo=github&logoColor=black)](https://github.com/Aayush049/Brewly)

</details>

<br/>

<details>
<summary><b>📄 Folio</b></summary>
<br/>

```
PROJECT : Folio
TYPE    : Flutter Application
STACK   : Flutter · Dart · SQLite · Google ML Kit
REPO    : https://github.com/Aayush049/Folio

DESCRIPTION:
  An offline-first document scanner — camera capture, cropping,
  on-device OCR, digital signatures, and PDF export, all stored
  locally with no server or account required.
```

[![View Repo](https://img.shields.io/badge/View%20Repo-Folio-3DDC84?style=for-the-badge&logo=github&logoColor=black)](https://github.com/Aayush049/Folio)

</details>

<br/>

<details>
<summary><b>💰 SpendWise</b></summary>
<br/>

```
PROJECT : SpendWise
TYPE    : Flutter Application
STACK   : Flutter · Dart · Material 3
REPO    : https://github.com/Aayush049/SpendWise

DESCRIPTION:
  A lightweight, offline-first expense and task tracker with a
  unified dashboard for spending and productivity insights.
  Local persistence only — no backend, no account required.
```

[![View Repo](https://img.shields.io/badge/View%20Repo-SpendWise-3DDC84?style=for-the-badge&logo=github&logoColor=black)](https://github.com/Aayush049/SpendWise)

</details>

<br/>

<details>
<summary><b>🎓 LearnMate AI — Mobile Client</b> <sub>· team project</sub></summary>
<br/>

```
PROJECT : Learn_Mate_App
TYPE    : Flutter Application — Mobile Client
STACK   : Flutter · Dart
REPO    : https://github.com/Aayush049/Learn_Mate_App
PART OF : LearnMate AI — an AI-powered exam-prep platform
          (current focus: SSC JE, Civil Engineering)

DESCRIPTION:
  Building the mobile client for LearnMate AI as part of a small
  team. My responsibility is the Flutter app; the wider platform
  also runs a React + FastAPI web stack built by teammates.
```

[![View Repo](https://img.shields.io/badge/View%20Repo-Learn__Mate__App-3DDC84?style=for-the-badge&logo=github&logoColor=black)](https://github.com/Aayush049/Learn_Mate_App)

</details>

<br/>

<details>
<summary><b>💵 Expense Tracker</b></summary>
<br/>

```
PROJECT : expense-tracker-kotlin
TYPE    : Console-Based Application
STACK   : Kotlin · Clean Architecture · SOLID Principles
REPO    : https://github.com/Aayush049/expense-tracker-kotlin

DESCRIPTION:
  A Kotlin console application to manage daily expenses,
  built using Clean Architecture and SOLID principles.
```

[![View Repo](https://img.shields.io/badge/View%20Repo-expense--tracker--kotlin-3DDC84?style=for-the-badge&logo=github&logoColor=black)](https://github.com/Aayush049/expense-tracker-kotlin)

</details>

<br/>

<details>
<summary><b>🎓 Student Management System</b></summary>
<br/>

```
PROJECT : student-management-kotlin
TYPE    : Console-Based Application
STACK   : Kotlin
REPO    : https://github.com/Aayush049/student-management-kotlin

DESCRIPTION:
  A console-based Student Management System developed in Kotlin.
```

[![View Repo](https://img.shields.io/badge/View%20Repo-student--management--kotlin-3DDC84?style=for-the-badge&logo=github&logoColor=black)](https://github.com/Aayush049/student-management-kotlin)

</details>

---

## `>` ./github-stats --live

<div align="center">

[![Repos](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=REPOS&query=public_repos&url=https%3A%2F%2Fapi.github.com%2Fusers%2FAayush049&color=3DDC84&labelColor=0D1117)](https://github.com/Aayush049?tab=repositories)
[![Followers](https://img.shields.io/github/followers/Aayush049?style=for-the-badge&label=FOLLOWERS&color=7F52FF&labelColor=0D1117)](https://github.com/Aayush049?tab=followers)
[![Stars](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=STARS&query=%24.length&url=https%3A%2F%2Fapi.github.com%2Fusers%2FAayush049%2Frepos%3Fper_page%3D100&color=3DDC84&labelColor=0D1117)](https://github.com/Aayush049)

<br/><br/>

[![GitHub Streak](https://streak-stats.demolab.com/?user=Aayush049&theme=github-dark-blue&background=0D1117&stroke=3DDC84&ring=3DDC84&fire=7F52FF&currStreakLabel=3DDC84&border=3DDC84)](https://github.com/Aayush049)

</div>

---

## `>` ./dsa-stats --leetcode

<div align="center">

[![LeetCode Stats](https://leetcard.jacoblin.cool/AYUSH0805?theme=dark&font=Fira+Code&ext=heatmap&border=true)](https://leetcode.com/u/AYUSH0805/)

</div>

---

## `>` ./gh-space-shooter --launch

<div align="center">

![My GitHub Game](game.gif)

<sub>Every green square in my contribution graph is now an enemy. Updates daily via GitHub Actions.</sub>

</div>

---

## `>` git log --oneline --graph --decorate

```
* 2024   │ commit  "Enrolled in B.Tech CSE @ KIIT University"
* 2024   │ commit  "First 'Hello World' — first Android emulator boot"
* 2025   │ commit  "Migrated mindset from XML to Jetpack Compose"
* 2025   │ commit  "Branched into Flutter — built SpendWise & Folio"
* 2025   │ commit  "Started exploring Spring Boot + REST APIs"
* 2026   │ commit  "Joined the LearnMate AI team — building the mobile client"
* HEAD → │ commit  "Building production-ready Android applications"
```

---

<div align="center">

| ```ayush@dev:~$ echo "Thanks for compiling this far. Let's build something great."``` |
|:---:|
| ```Thanks for compiling this far. Let's build something great.``` |
| ```ayush@dev:~$ █``` |

<br/>

<a href="https://github.com/Aayush049">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F52FF,50:3DDC84,100:0D1117&height=110&section=footer" width="100%" alt="Footer Wave"/>
</a>

</div>
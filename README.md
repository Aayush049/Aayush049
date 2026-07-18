<!--
  ================================================================
  ANDROID DEVELOPER COMMAND CENTER — README.md
  Owner: Ayush Srivastava (github.com/Aayush049)
  ================================================================
  STILL TO REPLACE:
    Section 6  -> real project details (currently placeholders)
    Section 10 -> add your own real milestones/achievements if any
  ================================================================
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,50:3DDC84,100:7F52FF&height=190&section=header&text=Android%20Developer%20Command%20Center&fontSize=34&fontColor=E6EDF3&fontAlignY=38&animation=fadeIn" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1000&color=3DDC84&background=00000000&center=true&vCenter=true&width=680&lines=%24+whoami+%E2%86%92+Android+Developer;%24+stack+%E2%86%92+Kotlin+%7C+Jetpack+Compose;%24+status+%E2%86%92+Compiling+ambition+into+APKs;%24+learning+%E2%86%92+Backend+%2B+AI+Integration;%24+warning+%E2%86%92+May+explain+recomposition+unprompted" alt="Typing SVG"/>

<br/><br/>

[![Profile Views](https://komarev.com/ghpvc/?username=Aayush049&color=3DDC84&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/Aayush049)
[![GitHub](https://img.shields.io/badge/GitHub-3DDC84.svg?style=for-the-badge&logo=github&logoColor=black)](https://github.com/Aayush049)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-7F52FF.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ayush-srivastava049)
[![Gmail](https://img.shields.io/badge/Gmail-3DDC84.svg?style=for-the-badge&logo=gmail&logoColor=black)](mailto:ayush.sri0108@gmail.com)

</div>

---

<!-- ============================================================ -->
<!-- 1. HERO — MainActivity.kt                                     -->
<!-- ============================================================ -->

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
        "Backend Development", "AI Integration"
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

![Build](https://img.shields.io/badge/BUILD-PASSING-3DDC84?style=for-the-badge&logo=android&logoColor=white&labelColor=0D1117)
![Gradle](https://img.shields.io/badge/GRADLE-SYNCED-02303A?style=for-the-badge&logo=gradle&logoColor=white&labelColor=0D1117)
![Kotlin](https://img.shields.io/badge/KOTLIN-READY-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white&labelColor=0D1117)

</div>

---

<!-- ============================================================ -->
<!-- 2. ABOUT ME                                                   -->
<!-- ============================================================ -->

## `>` cat ./about.md

```
┌─ activity_about.xml ──────────────────────────────────────────────┐
│                                                                    │
│  I build Android apps the way Gradle builds projects —           │
│  one dependency, one module, one clean architecture at a time.   │
│                                                                    │
│  🎓  B.Tech CSE @ KIIT University (2024 – 2028) · GPA 9.4        │
│  📍  India                                                        │
│  🛠  Currently engineering with Kotlin, Jetpack Compose,          │
│      and Android Studio                                          │
│  📡  Expanding the stack into Backend Development & AI            │
│      Integration                                                  │
│  🎯  Writing production-grade, maintainable Android code —        │
│      not tutorial code                                            │
│                                                                    │
└────────────────────────────────────────────────────────────────────┘
```

---

<!-- ============================================================ -->
<!-- DEVELOPER PERSONALITY / STATUS TERMINAL                       -->
<!-- ============================================================ -->

## `>` cat ./terminal.log
*// honest thoughts from the Android Studio console*

```
┌──────────────────────────────────────────────────────────────────┐
│  ayush@dev:~$ ./gradlew build                                   │
│                                                                  │
│  > Task :app:compileDebugKotlin                                 │
│  > Task :app:mergeDebugResources                                │
│  > Gradle sync started...                                       │
│  > Gradle sync started... (still going)                         │
│  > Gradle sync started... (send help)                           │
│  > BUILD SUCCESSFUL in 4m 12s ✅                                 │
│                                                                  │
│  ayush@dev:~$ emulator -avd Pixel_7_API_34                      │
│  > Emulator boot time: longer than my attention span             │
│                                                                  │
│  ayush@dev:~$ git commit -m "fixed recomposition bug"           │
│  > caused three new recomposition bugs                           │
│  > *2 hours later*                                                │
│  > "oh it was a missing remember{} block"                        │
│                                                                  │
│  ayush@dev:~$ while(learning) {                                  │
│  ...   migrateXmlToCompose();   // one screen at a time         │
│  ...   fightGradleErrors();     // instead of real enemies      │
│  ...   googleStackOverflow();   // senior dev on retainer        │
│  ...   commit("fix");           // descriptive messages: rare   │
│  ... }                                                            │
│                                                                  │
│  ayush@dev:~$ █                                                  │
└──────────────────────────────────────────────────────────────────┘
```

**Status:** `Currently fighting Gradle errors instead of real enemies. Compose preview lied to me again — it worked in preview, not on device. But committed anyway. 🚀`

---

<!-- ============================================================ -->
<!-- 4. ANDROID TECH STACK                                         -->
<!-- ============================================================ -->

## `>` cat ./build.gradle.kts

```kotlin
dependencies {
    languages   ("Kotlin", "Java", "Python", "C")
    android     ("Android Studio", "Jetpack Compose", "XML", "Gradle", "Firebase")
    backend     ("Spring Boot", "REST APIs", "PostgreSQL", "Redis")
    tools       ("Git", "Linux", "VS Code", "IntelliJ IDEA")
}
```

<div align="center">

<p><b>Languages</b></p>
<img src="https://skillicons.dev/icons?i=kotlin,java,python,c&theme=dark"/>

<p><b>Android</b></p>
<img src="https://skillicons.dev/icons?i=androidstudio,firebase&theme=dark"/>

<p><b>Backend</b></p>
<img src="https://skillicons.dev/icons?i=spring,postgres,redis&theme=dark"/>

<p><b>Tools</b></p>
<img src="https://skillicons.dev/icons?i=git,linux,vscode,idea&theme=dark"/>

</div>

---

<!-- ============================================================ -->
<!-- 5. SKILL MATRIX                                               -->
<!-- ============================================================ -->

## `>` ./skill-matrix --render

```
╔════════════════════════╦═════════════════════╦═══════════╗
║ Skill                  ║ Progress            ║ Level     ║
╠════════════════════════╬═════════════════════╬═══════════╣
║ Kotlin                 ║ █████████░          ║ Advanced  ║
║ Jetpack Compose        ║ ████████░░          ║ Strong    ║
║ Android Studio         ║ █████████░          ║ Advanced  ║
║ XML Layouts            ║ ████████░░          ║ Strong    ║
║ Gradle                 ║ ███████░░░          ║ Strong    ║
║ Firebase               ║ ███████░░░          ║ Strong    ║
║ Java                   ║ ████████░░          ║ Strong    ║
║ Spring Boot            ║ █████░░░░░          ║ Learning  ║
║ REST APIs              ║ ██████░░░░          ║ Growing   ║
║ PostgreSQL / Redis     ║ █████░░░░░          ║ Learning  ║
║ Python                 ║ █████░░░░░          ║ Learning  ║
║ AI Integration         ║ ████░░░░░░          ║ Learning  ║
╚════════════════════════╩═════════════════════╩═══════════╝
```

---

<!-- ============================================================ -->
<!-- 6. PROJECTS                                                   -->
<!-- ============================================================ -->

## `>` ls ./projects/ --details

<!-- Add more projects below as you ship them — same block format. -->

<details>
<summary><b>🎓 Student Management System</b></summary>

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

<details>
<summary><b>💰 Expense Tracker</b></summary>

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

---

<!-- ============================================================ -->
<!-- 7. GITHUB STATISTICS                                          -->
<!-- ============================================================ -->

## `>` ./github-stats --live

<div align="center">

![Repos](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=REPOS&query=public_repos&url=https%3A%2F%2Fapi.github.com%2Fusers%2FAayush049&color=3DDC84&labelColor=0D1117)
![Followers](https://img.shields.io/github/followers/Aayush049?style=for-the-badge&label=FOLLOWERS&color=7F52FF&labelColor=0D1117)
![Stars](https://img.shields.io/badge/dynamic/json?style=for-the-badge&label=STARS&query=%24.length&url=https%3A%2F%2Fapi.github.com%2Fusers%2FAayush049%2Frepos%3Fper_page%3D100&color=3DDC84&labelColor=0D1117)


<img src="https://streak-stats.demolab.com/?user=Aayush049&theme=github-dark-blue&background=0D1117&stroke=30363D&ring=3DDC84&fire=7F52FF&currStreakLabel=3DDC84&border=30363D" alt="GitHub Streak" width="60%"/>

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Aayush049&theme=react-dark&bg_color=0D1117&color=3DDC84&line=7F52FF&point=E6EDF3&border=30363D" alt="Contribution Graph" width="100%"/>

</div>

<!--
  NOTE: the "Stars" badge above sums stars across your first 100 repos via
  the raw GitHub API — accurate for now, but if you ever pass 100 repos it
  will need per_page pagination. Fine for the foreseeable future.
-->

<details>
<summary>Prefer the fuller stats card (repo count, commits, PRs, issues) instead?</summary>

<br/>

The classic all-in-one card is generated by a shared public service that
frequently goes down from overload — that's the "broken image" you saw.
The fix isn't a different URL, it's hosting your own copy (free, ~2 minutes):

1. Go to https://github.com/anuraghazra/github-readme-stats
2. Click **Deploy** → **Deploy with Vercel**
3. Fork it into your own account and deploy — Vercel gives you a URL like
   `your-name-github-readme-stats.vercel.app`
4. Swap that URL into an `<img>` tag here in place of the badges above

Once self-hosted, it's yours alone and won't go down from other people's traffic.

</details>

---

<!-- ============================================================ -->
<!-- 8. LEETCODE STATISTICS                                        -->
<!-- ============================================================ -->

## `>` ./dsa-stats --leetcode

<div align="center">

<img src="https://leetcard.jacoblin.cool/AYUSH0805?theme=dark&font=Fira+Code&ext=heatmap&border=true" alt="LeetCode Stats" width="70%"/>

</div>

---

<!-- ============================================================ -->
<!-- 9. CONTRIBUTION SNAKE                                         -->
<!-- ============================================================ -->

## `>` ./snake --watch

<div align="center">

<!-- Requires the GitHub Action setup below — will 404 until it runs once -->
<img src="https://raw.githubusercontent.com/Aayush049/Aayush049/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake" width="100%"/>

> 🐍 *the snake eats my commits so the Gradle logs don't have to.*

</div>

---

<!-- ============================================================ -->
<!-- 10. DEVELOPER JOURNEY TIMELINE                                -->
<!-- ============================================================ -->

## `>` git log --oneline --graph --decorate

```
* 2024   │ commit  "Enrolled in B.Tech CSE @ KIIT University"
* 2024   │ commit  "First 'Hello World' — first Android emulator boot"
* 2025   │ commit  "Migrated mindset from XML to Jetpack Compose"
* 2025   │ commit  "Started exploring Spring Boot + REST APIs"
* 2026   │ commit  "Integrating AI capabilities into Android apps"
* HEAD → │ commit  "Building production-ready Android applications"
```

<!-- Replace with real milestones — first app shipped, hackathon, internship, certification, etc. -->

---

<!-- ============================================================ -->
<!-- 11. FOOTER MESSAGE                                            -->
<!-- ============================================================ -->

<table align="center"><tr><td>

```
ayush@dev:~$ echo "Thanks for compiling this far. Let's build something great."
Thanks for compiling this far. Let's build something great.
ayush@dev:~$ █
```

</td></tr></table>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F52FF,50:3DDC84,100:0D1117&height=110&section=footer" width="100%"/>

</div>

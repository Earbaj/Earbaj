<div align="center">
  <!-- Dynamic Typing SVG Header -->
  <a href="https://github.com/earbaj">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&duration=3000&pause=1000&color=3DDC84&center=true&vCenter=true&multiline=true&width=700&height=100&lines=Hi+%F0%9F%91%8B%2C+I'm+Earbaj+Md+Saria;Senior+Android+%26+Cross-Platform+Engineer;Building+Scalable+%26+High-Performance+Mobile+Apps" alt="Typing SVG" />
  </a>

---

  <!-- Original Reliable Coding GIF -->
 <p align="center">
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3Z2azk2MXF6MmlzMWN0ZW10NnppOHRlaW5lMnJpc3RldG0xM2hpbyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/L1R1tvI9svkIWwpVYr/giphy.gif" width="550" alt="Cyber Coder GIF" />
</p>

  <!-- Modern Pill Badges -->
  <p align="center">
    <a href="https://github.com/earbaj?tab=followers"><img src="https://img.shields.io/github/followers/earbaj?label=Followers&logo=github&style=for-the-badge&color=181717" alt="Followers" /></a>
    &nbsp;
    <a href="https://github.com/earbaj?tab=repositories"><img src="https://img.shields.io/github/stars/earbaj?label=Stars&logo=github&style=for-the-badge&color=181717" alt="Stars" /></a>
    &nbsp;
    <img src="https://komarev.com/ghpvc/?username=earbaj&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile Views" />
  </p>
</div>
---

### 👨‍💻 About Me

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=earbaj&show_icons=true&theme=radical&hide_border=true&count_private=true" height="150" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=earbaj&layout=compact&theme=radical&hide_border=true&langs_count=6" height="150" alt="Top Languages" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=earbaj&theme=radical&hide_border=true" height="150" alt="Streak Stats" />
</p>

<table width="100%">
  <tr>
    <td style="background-color: #1e1f22; border-bottom: 2px solid #2b2d30; padding: 10px 14px;">
      <span style="color: #ed6a5e; font-size: 13px;">●</span>
      <span style="color: #f5bf4f; font-size: 13px;">●</span>
      <span style="color: #62c554; font-size: 13px;">●</span>
      &nbsp;&nbsp;&nbsp;&nbsp;
      <span style="background-color: #2b2d30; padding: 5px 12px; border-radius: 6px 6px 0 0; color: #dfe1e5; font-family: monospace; font-size: 12px;">
        <img src="https://img.shields.io/badge/-Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" height="11" />
        <b>Earbaj.kt</b>
      </span>
      &nbsp;
      <span style="color: #6f737a; font-family: monospace; font-size: 11px;">MainActivity.kt</span>
      &nbsp;
      <span style="color: #6f737a; font-family: monospace; font-size: 11px;">build.gradle.kts</span>
    </td>
  </tr>
</table>

```kotlin
/**
 * Senior Mobile Engineer
 * Architecture: Clean Architecture + MVI | Reactive: Coroutines & Flow
 */
data object Earbaj : MobileDeveloper {
    val name: String = "Earbaj Md Saria"
    val role: String = "Senior Android / Cross-Platform Engineer"
    val location: String = "Dhaka, Bangladesh 🇧🇩"
    val philosophy: String = "Lazy by nature, Efficient by design"

    val techStack: Set<String> = setOf(
        "Android", "Jetpack Compose", "Kotlin", "Flutter",
        "Android NDK", "C++", "TensorFlow Lite", "Swift"
    )

    val continuousLearning: List<String> = listOf("Kotlin Multiplatform (KMP)", "SwiftUI")

    suspend fun getCurrentFocus(): StateFlow<Project> = flowOf(
        Project(
            name = "Image Filter Pro",
            techStack = listOf("Android", "Kotlin", "ML Kit", "OpenCV"),
            repository = "https://github.com/Earbaj/ImageFilterAndroidKt"
        )
    ).stateIn(CoroutineScope(Dispatchers.IO))

    fun getInTouch(): ContactChannel = ContactChannel.Email("earbajsaria3@gmail.com")
}
```
---

### 🌐 Connect With Me
<p align="center">
  <a href="https://linkedin.com/in/earbaj" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" height="26"></a>
  &nbsp;
  <a href="https://stackoverflow.com/users/earbaj-saria3" target="_blank"><img src="https://img.shields.io/badge/Stack%20Overflow-Profile-F58025?style=flat-square&logo=stackoverflow&logoColor=white" height="26"></a>
  &nbsp;
  <a href="https://www.leetcode.com/earbaj" target="_blank"><img src="https://img.shields.io/badge/LeetCode-Problems-FFA116?style=flat-square&logo=leetcode&logoColor=white" height="26"></a>
  &nbsp;
  <a href="mailto:earbajsaria3@gmail.com"><img src="https://img.shields.io/badge/Email-Get%20in%20Touch-EA4335?style=flat-square&logo=gmail&logoColor=white" height="26"></a>
</p>

---

### 🛠️ Tech Stack

<div align="center">
  <!-- Mobile & Native -->
  <h4>📱 Mobile & Cross-Platform</h4>
  <img src="https://skillicons.dev/icons?i=android,kotlin,java,flutter,dart,swift,apple&perline=7" alt="Mobile Stack" />
  <br><br>

  <!-- Systems & AI/ML -->
  <h4>🧠 Low-Level, Systems & AI/ML</h4>
  <img src="https://skillicons.dev/icons?i=c,cpp,cmake,rust,tensorflow,pytorch,opencv&perline=7" alt="Systems & ML" />
  <br><br>

  <!-- Frontend & Web -->
  <h4>💻 Web & Frontend Ecosystem</h4>
  <img src="https://skillicons.dev/icons?i=react,nextjs,ts,js,html,css,tailwind,redux&perline=8" alt="Frontend Stack" />
  <br><br>

  <!-- Backend & Database -->
  <h4>⚙️ Backend & Persistence</h4>
  <img src="https://skillicons.dev/icons?i=nodejs,nestjs,express,python,django,firebase,mongodb,postgres,mysql&perline=9" alt="Backend & DB" />
  <br><br>

  <!-- DevOps & Cloud Tools -->
  <h4>🔧 DevOps, Cloud & CI/CD</h4>
  <img src="https://skillicons.dev/icons?i=git,githubactions,docker,kubernetes,aws,linux,postman&perline=7" alt="DevOps Stack" />
</div>

---

### 🌍 Open Source Contributions

#### 📦 Published Flutter Packages on Pub.dev
<table>
  <tr>
    <td width="50%">
      <b><a href="https://pub.dev/packages/moneris_payment">moneris_payment</a></b><br>
      <i>PCI-compliant Moneris Checkout integration with tokenization & 3D-Secure.</i><br><br>
      <a href="https://pub.dev/packages/moneris_payment"><img src="https://img.shields.io/pub/v/moneris_payment?label=pub.dev&style=flat-square&color=0175C2" alt="moneris_payment version"></a>
      <a href="https://pub.dev/packages/moneris_payment"><img src="https://img.shields.io/pub/likes/moneris_payment?style=flat-square&color=2E7D32" alt="moneris_payment likes"></a>
    </td>
    <td width="50%">
      <b><a href="https://pub.dev/packages/genericlistwithdate">genericlistwithdate</a></b><br>
      <i>Sticky/grouped date-based list view (perfect for chat feeds, logs & timelines).</i><br><br>
      <a href="https://pub.dev/packages/genericlistwithdate"><img src="https://img.shields.io/pub/v/genericlistwithdate?label=pub.dev&style=flat-square&color=0175C2" alt="genericlistwithdate version"></a>
      <a href="https://pub.dev/packages/genericlistwithdate"><img src="https://img.shields.io/pub/likes/genericlistwithdate?style=flat-square&color=2E7D32" alt="genericlistwithdate likes"></a>
    </td>
  </tr>
  <tr>
    <td width="50%">
      <b><a href="https://pub.dev/packages/customedropdownlistwithsearch">customedropdownlistwithsearch</a></b><br>
      <i>Highly customizable searchable dropdown picker with smooth filtering.</i><br><br>
      <a href="https://pub.dev/packages/customedropdownlistwithsearch"><img src="https://img.shields.io/pub/v/customedropdownlistwithsearch?label=pub.dev&style=flat-square&color=0175C2" alt="customedropdownlistwithsearch version"></a>
      <a href="https://pub.dev/packages/customedropdownlistwithsearch"><img src="https://img.shields.io/pub/likes/customedropdownlistwithsearch?style=flat-square&color=2E7D32" alt="customedropdownlistwithsearch likes"></a>
    </td>
    <td width="50%">
      <b><a href="https://pub.dev/packages/custom_scaffold">custom_scaffold</a></b><br>
      <i>Enhanced Scaffold with unified loading, error handling & state layers.</i><br><br>
      <a href="https://pub.dev/packages/custom_scaffold"><img src="https://img.shields.io/pub/v/custom_scaffold?label=pub.dev&style=flat-square&color=0175C2" alt="custom_scaffold version"></a>
      <a href="https://pub.dev/packages/custom_scaffold"><img src="https://img.shields.io/pub/likes/custom_scaffold?style=flat-square&color=2E7D32" alt="custom_scaffold likes"></a>
    </td>
  </tr>
</table>

<br>

#### 🔧 Key Open Source Pull Requests
- 🐧 **[ubuntu/app-center#2120](https://github.com/ubuntu/app-center/pull/2120)** — Improved the **About page** layout, typography, and readability for Ubuntu App Center.
- 📱 **[jitsi/jitsi-meet-flutter-sdk#161](https://github.com/jitsi/jitsi-meet-flutter-sdk/pull/161)** — Fixed critical `NullPointerException` crash & resolved Android Media3 build conflicts.
- 🎨 **[sdegenaar/liquid_glass_widgets#3](https://github.com/sdegenaar/liquid_glass_widgets/pull/3)** — Implemented liquid glass shader mask effect & empty label state handling.

> 💡 *"Building tools and contributing to the open-source ecosystem that millions rely on"*

---

### 📈 LeetCode Profile
<div align="center">
  <a href="https://leetcode.com/earbaj" target="_blank">
    <img src="https://leetcard.jacoblin.cool/earbaj?theme=dark&font=Karma&ext=contest" width="95%" alt="Earbaj LeetCode Stats" />
  </a>
</div>

---

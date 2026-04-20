<div align="center">

<!-- Logo only if provided above -->
<img src="https://github.com/user-attachments/assets/fbb97fe1-8f6e-408f-95b5-b4ac124ca084" width="110" />

<br/><br/>

# Easy Explain AI

### Instantly summarize and listen to any document using advanced Google Gemini AI

<br/>

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Status](https://img.shields.io/badge/Status-Live%20on%20Play%20Store-brightgreen?style=for-the-badge&logo=googleplay)

<br/>

[<img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" 
      width="180"/>](https://play.google.com/store/apps/details?id=com.easyexplainai.app)

<br/><br/>

</div>

---

### 📱 ABOUT THE APP

<div align="center">
<p>Easy Explain AI is an intelligent mobile application designed for students, researchers, and professionals who need quick insights from lengthy documents. By leveraging Google Gemini AI, the app rapidly reads and summarizes complex files, saving users hours of tedious reading time.</p>
<br/>
<p>What sets Easy Explain AI apart is its seamless integration of text-to-speech functionality and real-time cloud syncing. Users can effortlessly listen to their generated summaries on the go, securely store them via Firebase, and retrieve their document history across multiple devices without losing context.</p>
</div>

---

### ✨ KEY FEATURES

<div align="center">
<table>
  <tr>
    <td width="50%">✅ <b>AI-Powered Summarization</b><br/>Extracts key insights from uploaded documents using Google Generative AI.</td>
    <td width="50%">✅ <b>Text-to-Speech (TTS)</b><br/>Listen to your document summaries natively on the go with built-in voice playback.</td>
  </tr>
  <tr>
    <td width="50%">✅ <b>Multi-Format Uploads</b><br/>Seamlessly upload and parse various document formats securely using the file picker.</td>
    <td width="50%">✅ <b>Cloud History Sync</b><br/>Automatically save and retrieve past document summaries across devices via Firebase.</td>
  </tr>
  <tr>
    <td width="50%">✅ <b>Seamless Authentication</b><br/>Secure one-tap login and profile management using Google Sign-In and Firebase Auth.</td>
    <td width="50%">✅ <b>Local Storage Cache</b><br/>Provides fast offline access to recent app settings and data powered by local Hive databases.</td>
  </tr>
  <tr>
    <td width="50%">✅ <b>Summary Export & Save</b><br/>Easily export, save, and share your AI-generated findings locally to your device.</td>
    <td width="50%">✅ <b>Modern Interface</b><br/>A beautiful, highly responsive UI designed specifically for an optimal reading and listening experience.</td>
  </tr>
</table>
</div>

---

### 📸 SCREENSHOTS

<br/>

##  🔐 Login / Authentication & Home Dashboard 
<div align="center">
  <img src="https://github.com/user-attachments/assets/eeb745ca-d204-43ff-adb1-42f39c578943" width="45%" align="top" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/9bf54c1c-f449-4042-b4f6-633b0143a3a1" width="45%" align="top" />
</div>
<br/>

##  📄 Upload Document & Summary Results
<div align="center">
  <img src="https://github.com/user-attachments/assets/6e84f444-e1b2-4ec2-ba51-40010e925287" width="45%" align="top" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/13d99d62-7aeb-422f-b5b1-5b9e9ae0eeb1" width="45%" />
</div>
<br/>

##  🎧 Audio & Stats Player & Searchable History
<div align="center">
  <img src="https://github.com/user-attachments/assets/39b2bc6c-d002-4a50-828d-291d7446e58b" width="45%" align="top" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/ada0c35a-3a25-473b-bdaa-147cea88aac9" width="45%" />
</div>

<br/>

---

### 📲 GOOGLE PLAY STORE

<br/>

<div align="center">

### 📲 Available on Google Play

<br/>

[<img src="https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png" width="210"/>](https://play.google.com/store/apps/details?id=com.easyexplainai.app)

</div>

<br/>

---

### 🛠️ TECH STACK

<div align="center">
<table>
  <tr><th>Layer</th><th>Technology</th></tr>
  <tr><td>📱 Framework</td><td>Flutter & Dart</td></tr>
  <tr><td>🧠 State Management</td><td>GetX</td></tr>
  <tr><td>🔥 Backend</td><td>Firebase (Firestore & Storage) & Google Gemini AI</td></tr>
  <tr><td>🔐 Authentication</td><td>Firebase Auth & Google Sign-In</td></tr>
  <tr><td>📄 Key Libraries</td><td><code>google_generative_ai</code>, <code>flutter_tts</code>, <code>file_picker</code>, <code>hive_flutter</code>, <code>get</code>, <code>cloud_firestore</code></td></tr>
  <tr><td>💳 Monetization</td><td>None Detected / Free</td></tr>
  <tr><td>🚀 Platform</td><td>Android & iOS</td></tr>
</table>
</div>

---

### 🎯 WHY THIS APP STANDS OUT

- 🏗️ **Robust Modular Architecture** — The codebase is cleanly organized into domain-specific features and dedicated service layers (`gemini_service.dart`, `summary_service.dart`), maximizing scalability and maintainability.
- 🧠 **Cutting-Edge Generative AI Interface** — Natively integrates the Google Gemini API directly into the service layer to perform deep, context-aware document summarization with minimal latency.
- 🎙️ **Accessible Media Features** — Custom integration of `flutter_tts` provides a seamless Text-to-Speech (TTS) experience, drastically enhancing accessibility and allowing users to consume full documents purely via audio.
- ⚡ **Hybrid Data Synchronisation** — Intelligently combines `hive_flutter` for rapid local offline caching with Cloud Firestore and Firebase Storage for reliable, synchronized multi-device cloud persistence.
- 🎨 **Adaptive UI/UX** — Employs scalable GetX controllers for fluid state management, paired with polished reactive widgets leveraging standard Flutter aesthetics, ensuring an elegant user journey through the summary pipeline.

---

### 🔒 PRIVACY NOTE

<br/>

<div align="center">

> 🔒 **Source code is private** due to client and project confidentiality.
> This repository exists solely to showcase the app's design, features,
> and functionality.

</div>

<br/>

---

### 📬 CONTACT

<div align="center">

<!-- [![Portfolio](https://img.shields.io/badge/Portfolio-Visit-blueviolet?style=for-the-badge&logo=google-chrome&logoColor=white)](https://yourportfolio.com) -->
<!-- &nbsp;&nbsp; -->
[![Email](https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dakshparekh42@gmail.com)
&nbsp;&nbsp;
[![LinkedIn](https://img.shields.io/badge/Connect%20on-LinkedIn-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/daksh-parekh-97ab68313/)
</div>

<br/>

---

---

*Designed & Developed with ❤️ using Flutter*

---

</div>

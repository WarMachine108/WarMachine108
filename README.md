<div align="center">

```
████████╗ █████╗ ███╗   ██╗███╗   ███╗ █████╗ ██╗   ██╗
╚══██╔══╝██╔══██╗████╗  ██║████╗ ████║██╔══██╗╚██╗ ██╔╝
   ██║   ███████║██╔██╗ ██║██╔████╔██║███████║ ╚████╔╝ 
   ██║   ██╔══██║██║╚██╗██║██║╚██╔╝██║██╔══██║  ╚██╔╝  
   ██║   ██║  ██║██║ ╚████║██║ ╚═╝ ██║██║  ██║   ██║   
   ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝     ╚═╝╚═╝  ╚═╝   ╚═╝  
```

### `< Tanmay Agarwal />` — Builder. Problem-Solver. Perpetual Learner.

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Full-Stack+Developer;Systems+%26+Backend+Engineer;Open+Source+Enthusiast;Always+Learning+%F0%9F%9A%80)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tanmay-agarwal-910363341)
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/warmachine108)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://instagram.com/tanmayyagg)
[![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white)](https://reddit.com/user/WarMachine80)
[![Codeforces](https://img.shields.io/badge/Codeforces-445f9d?style=for-the-badge&logo=Codeforces&logoColor=white)](https://codeforces.com/profile/Tan)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:agarwal.tanmay2007@gmail.com)

</div>

---

## 🧠 About Me

```python
class Tanmay:
    def __init__(self):
        self.name        = "Tanmay Agarwal"
        self.alias       = ["WarMachine108", "Tan"]
        self.languages   = ["C++", "Python", "Java", "C"]
        self.focus       = ["Backend Systems", "CV/ML", "Full-Stack"]
        self.interests   = ["Competitive Programming", "Open Source", "Low-level Systems"]
        self.currently   = "Building impactful projects & sharpening problem-solving skills"
        self.philosophy  = "Write code that solves real problems — clean, efficient, and purposeful."

    def say_hi(self):
        print("Thanks for visiting! Feel free to explore my work below 👇")
```

---

## 🚀 Featured Projects

<details open>
<summary><b>🗂️ KITSUMA — Git-Inspired Version Control System</b> &nbsp;<code>Python · C++ · PostgreSQL</code> &nbsp;</summary>

<br/>

> A full-stack VCS (like Git) with a PostgreSQL backend and a Python bridge layer.

- **Database**: Relational tables for users, projects, files, submissions, reviews, and revision history; bcrypt password hashing through PostgreSQL `pgcrypto` and token-based sessions.
- **Architecture**: C++ three-way merge engine using Myers diff, with Python handling CLI commands, database operations, and ranked review routing through designated folder heads.
- **Functionality**: Project creation, folder-based access, cloning, file submissions, conflict resolution, revision history, and safe synchronization.
- **Configuration & Testing**: Configurable PostgreSQL connection supporting local or Supabase databases; verified with 16 automated tests, 10,000 randomized diff/merge cases, and an end-to-end demo.

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/WarMachine108/KITSUMA)

</details>

---

<details open>
<summary><b>🎵 Resonance — Terminal Music Player</b> &nbsp;<code>C++17 · FTXUI · BASS · yt-dlp</code></summary>

<br/>

> A Windows terminal music player with a styled interface, offline playback, and background YouTube downloads.

- **Data Structures**: Custom AVL trees for title and duration sorting, a doubly linked playlist for playback order, and a hash-map song table for expected O(1) metadata lookup
- **Interface**: FTXUI-powered RGB layout with keyboard and mouse controls, song filtering, playback progress, and confirmation dialogs
- **Audio**: BASS stream management with pause/resume, seeking, volume control, automatic track advancement, and an audio-driven FFT spectrum
- **Downloads**: Background YouTube search and MP3 downloads using yt-dlp and FFmpeg, with progress reporting and cancellation
- **Reliability**: Validated metadata, duplicate detection, atomic saves, backups, and error handling
- **Build**: CMake and Ninja for reproducible Windows x64 builds

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/WarMachine108/Music-player)

</details>

---

<details open>
<summary><b>📈 Stock Market Simulator</b> &nbsp;<code>Java 21 · JavaFX · Yahoo Finance · Maven · JUnit</code></summary>

<br/>

> A desktop paper trading application for practicing stock investing with virtual money.

- **API Integration**: Yahoo Finance stock search, latest quotes, and historical price data
- **Portfolio Management**: Validated buying and selling, weighted-average purchase prices, cash balance, and unrealized profit/loss
- **OOP Design**: Encapsulated `Stock` and `User` models, with a `MarketData` interface supporting live and offline demo providers
- **Interactive UI**: Dark-themed JavaFX interface, trade previews, background quote updates, and timezone-aware 1D/1M charts
- **Persistence & Testing**: Recoverable local JSON saves, 40 automated regression tests, and GitHub Actions CI

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/WarMachine108/Stock-market-simulator)

</details>

---

<details open>
<summary><b>👁️ FRAS — Facial Recognition Attendance System</b> &nbsp;<code>Python · Flask · OpenCV · face_recognition</code></summary>

<br/>

> A web-based attendance system powered by real-time facial recognition.

- **Core**: Encodes registered faces into vector embeddings; matches live webcam frames against them on each request via a Flask backend
- **DevX**: `setup_env.py` automates virtual environment creation and dependency installation across Windows, macOS, and Linux
- **Delivery**: Attendance records served through a browser at `localhost`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/WarMachine108/FRAS)

</details>

---

<details open>
<summary><b>🏓 Rumble Pong</b> &nbsp;<code>HTML5 · CSS · JavaScript · p5.js</code></summary>

<br/>

> A browser-based two-player Pong game with a real-time powerup system.

- **Powerups**: Freeze, Fireball, Shrink, and more — rendered using p5.js
- **Structure**: Multi-page flow (main menu → mode select → game modes) with per-powerup SFX assets and responsive canvas scaling

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/WarMachine108/rumble-pong)

</details>

---

<details open>
<summary><b>🎲 Monopoly (SFML)</b> &nbsp;<code>C++ · SFML</code></summary>

<br/>

> A fully playable Monopoly game built in C++ with a graphical interface.

- **OOP**: `Tile` base class with subclasses (`Property`, `Tax`, `Jail`, `Go`), each overriding a virtual `landOn()` method
- **Engine**: Turn-based state machine in `GameManager` sequences dice rolls, tile effects, and transactions

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/WarMachine108/Monopoly-SFML-)

</details>

---

## 🛠️ Tech Stack

### 🔤 Languages
![C](https://img.shields.io/badge/C-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![JavaScript](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

### 🗄️ Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

### 📚 Frameworks & Libraries
![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-%23FF0000.svg?style=for-the-badge&logo=javafx&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![p5.js](https://img.shields.io/badge/p5.js-ED225D?style=for-the-badge&logo=p5.js&logoColor=white)

### ☁️ Cloud & DevOps
![Render](https://img.shields.io/badge/Render-%2346E3B7.svg?style=for-the-badge&logo=render&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

### 🎨 Design Tools
![Figma](https://img.shields.io/badge/Figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.shion.dev/api?username=WarMachine108&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=false&show_icons=true)

![GitHub Streak](https://streak-stats.demolab.com/?user=WarMachine108&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.shion.dev/api/top-langs/?username=WarMachine108&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=false&layout=compact)

</div>

---

## ✍️ Dev Quote of the Day

<div align="center">

![Dev Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

</div>

---

<div align="center">

### 💡 *"Write code that solves real problems — clean, efficient, and purposeful."*

[![Profile Views](https://komarev.com/ghpvc/?username=WarMachine108&color=58A6FF&style=flat-square&label=Profile+Views)](https://github.com/WarMachine108)

**Thanks for stopping by! Star a repo if you find it useful ⭐**

</div>

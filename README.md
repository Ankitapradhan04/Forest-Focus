# 🌲 Forest & Seasonal Study Tracker

A feature-rich, interactive single-page web application designed for daily study tracking, routine planning, and focus management. Wrapped in an immersive, real-time seasonal forest aesthetic, it helps students and self-learners organize study schedules, track long-term progress, and maintain deep focus.

---

## ✨ Features

- **🌲 Real-Time Forest & Seasonal UI**: Dynamic seasonal accents (Spring Blossom, Summer Canopy, Autumn Foliage, Winter Frost) based on the current month, complete with Light (Forest Day) and Dark (Forest Night) modes.
- **⏱️ Integrated Pomodoro Timer**: Custom work/break intervals, session counter, and Web Audio synthesized chimes.
- **📅 Interactive Routine Builder**: Daily timeline manager with per-day customization and a quick **"Copy Routine to Another Day"** feature.
- **📊 GitHub/LeetCode Style Contribution Grid**: Activity heatmap displaying study intensity, active streaks, dynamic total hours, and tooltips.
- **🗓️ Marking Calendar**: Interactive month view supporting custom color-coded badges (*Goal Met*, *Exam Day*, *Rest Day*, *Revision*) and day-specific session logs.
- **🎧 Ambient Sound Generator**: Built-in procedural background sound generator using the Web Audio API (Rain, River Flow, Forest Wind & Birds, Lo-Fi Tone). No external audio files required.
- **📝 Reminders & Sticky Notes**: Task list with priority tags and auto-saved categorized study notes with instant search.
- **💾 LocalStorage Persistence**: Automatic local browser storage for schedules, notes, tasks, heatmap history, and timer configurations.

---

## 🛠️ Built With

* **HTML5**: Semantic markup layout.
* **Tailwind CSS**: Utility-first CSS framework for glassmorphism, responsive grid design, and dark mode styling.
* **Font Awesome**: Icon system for intuitive UI navigation.
* **JavaScript (ES6+)**: Vanilla JS DOM manipulation, LocalStorage integration, and Web Audio API synthesizer.

---

## 🚀 Getting Started

### Prerequisites

No external build tools or backends are required. You only need a modern web browser (Chrome, Firefox, Edge, Safari).

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/forest-study-tracker.git
   ```

2. **Navigate into the project directory**
   ```bash
   cd forest-study-tracker
   ```

3. **Open the application**
   Simply double-click `index.html` or open it directly in your web browser.

   Alternatively, run a simple local live server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser.

---

## 📖 How to Use

### 1. Forest & Seasonal Shift
* The ambient theme automatically selects dynamic colors based on your current computer date.
* Use the top control bar to switch between auto-detected seasons or manually override with Spring, Summer, Autumn, or Winter themes.
* Toggle between Light and Dark modes using the moon/sun icon.

### 2. Routine Customization & Copying
* Select a day of the week (Monday through Sunday) in the **Routine Manager**.
* Add time slots and subject titles.
* Click **Copy Day** to duplicate the active schedule directly to any target day of the week.

### 3. Pomodoro Focus Timer
* Switch between **Focus**, **Short Break**, and **Long Break** modes.
* Click **Start Focus** to initiate the timer.
* Custom work and break durations can be configured by clicking **Settings**. Audio notifications chime automatically upon completion using native Web Audio synthesis.

### 4. Background Ambience (BGM)
* Select an ambient sound option (*Forest Rain*, *Gentle River*, *Birds & Wind*, *Deep Lofi Ambient*) in the header control bar.
* Use the play button to start audio synthesis and adjust master volume using the slider.

---

## 📂 Project Structure

```text
forest-study-tracker/
├── index.html        # Main HTML structure, Tailwind styling, components, and embedded JS logic
└── README.md         # Project documentation
```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

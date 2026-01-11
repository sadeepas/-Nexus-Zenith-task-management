# -Nexus-Zenith-task-management
**Nexus Zenith** is a futuristic, sci-fi-inspired task management dashboard designed to look and feel like a high-tech Operating System. Built with a focus on Glassmorphism and "Mission Control" aesthetics, it transforms mundane to-do lists into critical tactical missions.


# 🌌 Nexus Zenith | Ultimate OS

![Uploading image.png…]()


> **"System Optimization Sequence Initiated..."**

**Nexus Zenith** is a futuristic, sci-fi-inspired task management dashboard designed to look and feel like a high-tech Operating System. Built with a focus on Glassmorphism and "Mission Control" aesthetics, it transforms mundane to-do lists into critical tactical missions.

---

## 📸 Screenshots

<!-- 
TIP: Take a screenshot of your app, upload it to your repo, 
and replace 'screenshot.png' with the actual file path. 
-->
![Nexus Zenith Dashboard](screenshot.png)

---

## 🚀 Key Features

### 🛡️ Core Systems
*   **Futuristic UI/UX:** Built with high-end Glassmorphism, neon accents, and a dynamic mesh background.
*   **Real-Time Analytics:** Live clock, active mission counters, and dynamic progress bars.
*   **Mission Countdown:** Tasks function as "Missions" with live countdown timers (Days, Hours, Minutes, Seconds).

### ⚡ Functionality
*   **Priority Protocols:** Flag missions as `Normal` or `Critical`.
*   **Tactical Subtasks:** Add checklist steps within every major goal.
*   **Intel Upload:** Attach media/images to your tasks for visual reference.
*   **Data Persistence:** Uses `localStorage` to save your data automatically. No database required.

### 💾 Data Management
*   **Secure IO Protocol:** Export your data to a JSON file (Backup) and inject it back (Restore) on any device.
*   **Report Generation:**
    *   **Capture:** Export mission cards as PNG images using `html2canvas`.
    *   **Report:** Download mission details as a `.txt` file.
*   **Broadcasting:** Share mission status via WhatsApp, Twitter, or Email.

---

## 🛠️ Tech Stack

*   **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+).
*   **Styling:** [Tailwind CSS](https://tailwindcss.com/) (via CDN) for rapid utility styling.
*   **Fonts:** 'Plus Jakarta Sans' & 'JetBrains Mono' (Google Fonts).
*   **Libraries:** 
    *   `html2canvas` (for screen capturing mission cards).

---

## 💻 Installation & Usage

Since Nexus Zenith is built as a standalone web application using CDN links, no complex installation (npm/node) is required.

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/YourUsername/Nexus-Zenith.git
    ```
2.  **Navigate to the folder:**
    ```bash
    cd Nexus-Zenith
    ```
3.  **Launch:**
     Simply double-click `index.html` to open it in your default web browser.

---

## 📂 Project Structure

```text
Nexus-Zenith/
│
├── index.html       # The Core System (Contains HTML, CSS, & JS)
├── README.md        # Documentation
└── screenshot.png   # Preview Image (Optional)

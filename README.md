# HSK Vocabulary

**HASK Vocabularir** is an interactive, gamified web application designed to help users master Chinese HSK vocabulary. It combines **Speed Quizzes** with **Stroke Order Writing Practice** to ensure comprehensive learning (Reading, Listening, Speaking, and Writing).

## ✨ Key Features

### ⏱️ Mode 1: Speed Quiz (Time Attack)
Test your memory under pressure!
* **Time Attack:** 15-second timer per word. Visual cues (red pulse) when time is running out.
* **Voice Recognition:** Integrated with **Web Speech API**. Just say the word to answer!
* **Smart Validation:** Accepts Pinyin with or without tone numbers (e.g., `ni3hao3` or `nihao`).
* **Text-to-Speech:** High-quality native audio pronunciation using the browser's synthesis engine.
* **Lives System:** 3 hearts system. Game over if you run out of lives.

### ✍️ Mode 2: Stroke Writer (Hanzi Practice)
Learn how to write characters correctly, not just recognize them.
* **Hanzi Writer Integration:** Uses vector-based rendering to track stroke order.
* **Strict Validation:** You must draw the strokes in the correct direction and order.
* **Hint System:** Stuck? Toggle the "Hint" button to see the outline.
* **Demo Mode:** Watch the character write itself to learn the flow.

### 📚 Comprehensive Database
* **HSK 1:** 150 Words (Full)
* **HSK 2:** 300 Words (Full)
* **HSK 3:** 600 Words (Full)
* *Cumulative Logic:* Level 2 includes Level 1 words, and Level 3 includes all previous levels.

## 🛠️ Tech Stack

* **Core:** HTML5, Vanilla JavaScript (ES6+)
* **Styling:** Tailwind CSS (via CDN)
* **Libraries:** * [Hanzi Writer](https://hanziwriter.org/) (for stroke animation)
    * [FontAwesome](https://fontawesome.com/) (for icons)
* **APIs:** Web Speech API (Recognition & Synthesis)

## 🚀 How to Run Locally

Because this application uses the **Web Speech API** (Microphone), modern browsers require it to run on a **local server** (http://localhost) rather than opening the file directly (file://).

### Prerequisites
* Python installed (or VS Code with Live Server extension).
* Google Chrome or Microsoft Edge (recommended for best Speech API support).

### Steps
1.  **Clone the repository** (or download the files):
    ```bash
    git clone [https://github.com/yourusername/mandarin-master.git](https://github.com/yourusername/mandarin-master.git)
    cd mandarin-master
    ```

2.  **Start a Local Server**:
    If you have Python installed, run this in your terminal inside the folder:
    ```bash
    python -m http.server
    ```

3.  **Open in Browser**:
    Go to: `http://localhost:8000`

4.  **Allow Permissions**:
    Click "Allow" when the browser asks for Microphone permission.

## 🔮 Future Improvements

* [ ] Add LocalStorage to save user high scores.
* [ ] Add Dark Mode toggle.
* [ ] Mobile-responsive layout optimizations.
* [ ] HSK 4-6 Vocabulary expansion.

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📝 License

This project is open-source and available under the MIT License.

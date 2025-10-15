# 🎯 LL(1) Grammar Analyzer

A simple, interactive **LL(1) Grammar Analyzer** that allows you to input or upload a context-free grammar (CFG) and instantly view the computed **FIRST sets**, **FOLLOW sets**, and the **LL(1) Parsing Table** — all directly in your browser.

🔗 **Live Demo:** [LL(1) Grammar Analyzer](https://velociroughtor.github.io/Fun-Project-LL1-Grammar-Analyzer/)

---

## 🧩 Features

✅ **Compute FIRST sets** – Automatically generates FIRST sets for each non-terminal.  
✅ **Compute FOLLOW sets** – Derives FOLLOW sets using standard LL(1) parsing rules.  
✅ **Generate LL(1) Parsing Table** – Displays the parsing table in a clean, bordered grid.  
✅ **Upload Grammar File (.txt)** – Quickly load grammar from a `.txt` file.  
✅ **Load Example Grammar** – One click to load a sample grammar for testing.  
✅ **Responsive Design** – Works smoothly on desktop and mobile.  
✅ **Client-side Only** – No backend; everything runs in your browser using pure JavaScript.

---

## 🧠 How It Works

1. The user enters a CFG (e.g.):
E->TP
P->@
P->+TP
T->FQ
Q->@
Q->*FQ
F->i
F->(E)

2. The app parses the input, computes:
- **FIRST()**
- **FOLLOW()**
- **LL(1) Parsing Table**

3. Results are displayed in beautiful, scrollable tables.

---

## ⚙️ Technologies Used

- **HTML5** – for structure  
- **Tailwind CSS** – for modern, responsive design  
- **Vanilla JavaScript (ES6)** – for parsing logic and LL(1) computation  
- **GitHub Pages** – for hosting

---

## 🚀 Usage

You can use it in two ways:

### 🖥️ Option 1: Online Demo
Simply open the live hosted page:  
[LL(1) Grammar Analyzer](https://velociroughtor.github.io/Fun-Project-LL1-Grammar-Analyzer/){:target="_blank" rel="noopener noreferrer"}

### 💻 Option 2: Run Locally
1. Clone this repository:
```bash
git clone https://github.com/velociroughtor/Fun-Project-LL1-Grammar-Analyzer.git
cd Fun-Project-LL1-Grammar-Analyzer
```
2. Open index.html in your browser.

No setup required — everything runs locally.



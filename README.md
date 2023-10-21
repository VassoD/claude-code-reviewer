# Code Analyzor 🤖

This project analyzes code and generates report using AI. It takes a folder of code, sends it to Claude API, and outputs result to a file.

## How it Works

1. 📂 Scan folder recursively for code files (py, js, etc)

2. 📜 Read each file and extract code

3. 💬 Pass code to Claude API for analysis

4. 🤖 Claude reviews code snippet and provides feedback

5. 📰 Analysis results saved to a the report.md file

## Running Locally

**Step 1:**

Clone repo and install requirements

```
git clone <repo>
pip install -r requirements.txt
```

**Step 2:**

Get Claude API key and configure

**Step 3:**

Run script on folder

```
python analyze.py /my-code-folder
```

**Step 4:**

Find output in `report.md` file 🎉

## To Do

Here are some ideas for enhancing the code analyzer:

- Summarize findings across files
- Automate fixes for certain issues
- Develop prompts and context

And more! Please contriboot if you have ideas. 💡

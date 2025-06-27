# Redborder Wrapped

## 🧰 Installation Guide (Python 3.12)

Set up the project easily on **macOS, Linux, or Windows** using Python 3.12.

---

### 1️⃣ Check Python 3.12 Installation

Verify your Python version:

```sh
python3 --version
```

If Python 3.12 is not installed, download it from the [official Python website](https://www.python.org/downloads/).

---

### 2️⃣ Create & Activate a Virtual Environment

**macOS & Linux:**

```sh
python3.12 -m venv venv
source venv/bin/activate
```

**Windows (Command Prompt):**

```bat
python -m venv venv
venv\Scripts\activate
```

---

### 3️⃣ Install Dependencies

With the virtual environment activated, run:

```sh
pip install --upgrade pip
pip install -r requirements.txt
```

---

### 4️⃣ Create a `.env` File

Create a `.env` file in the project root to store your Redmine API key:

```sh
echo "REDMINE_API_KEY=your_api_key_here" > .env
```

Replace `your_api_key_here` with your actual Redmine API key.

> **Note:** Never commit your `.env` file to version control.
# Redborder Wrapped

Redborder Wrapped is a Python tool designed to automate the extraction and reporting of issues from a Product NG project.

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

```sh
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

## 🔑 Set up Redmine API

### 1️⃣ Create a `.env` File

Create a `.env` file in the project root to store your Redmine API key:

```sh
echo "REDMINE_API_KEY=your_api_key_here" > .env
```

Replace `your_api_key_here` with your actual Redmine API key.

> **Note:** Never commit your `.env` file to version control.

---

## 📅 Set the Date Range for Issue Filtering

Specify the start and end dates to filter issues by their creation date. Update the values as needed:

```python
START_TIME = datetime.strptime('2025-01-01', '%Y-%m-%d')
END_TIME = datetime.strptime('2025-07-18', '%Y-%m-%d')
```

> **Tip:** Adjust the dates to match your desired reporting period.

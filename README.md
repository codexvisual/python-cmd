<div align="center">

# 🐍 Ultimate Python Commands Key Guide

**Python · pip · venv · Django**  
_One cheat sheet to rule them all_

[![Python](https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python)](https://python.org)
[![pip](https://img.shields.io/badge/pip-latest-green?style=for-the-badge&logo=pypi)](https://pypi.org)

</div>

---

## 🐍 1. Python & pip (Base Setup)

<div align="center">

| 💻 Command | 📖 What it does |
|:-----------|:----------------|
| `python --version` / `python3 --version` | Python version চেক |
| `pip --version` / `pip3 --version` | pip version চেক |
| `pip install package-name` | একটি প্যাকেজ ইন্সটল |
| `pip install -r requirements.txt` | requirements ফাইল থেকে সব প্যাকেজ ইন্সটল |
| `pip freeze > requirements.txt` | ইন্সটল করা প্যাকেজগুলোর লিস্ট ফাইল আকারে সেভ |
| `pip list` | ইন্সটলড সব প্যাকেজের তালিকা |

</div>

---

## 🧪 2. Virtual Environment (venv)

<div align="center">

| Command | Description |
|:--------|:------------|
| `python -m venv venv` | `venv` নামে ভার্চুয়াল এনভায়রনমেন্ট তৈরি |
| `source venv/bin/activate` (Linux/macOS) | এনভায়রনমেন্ট অ্যাক্টিভেট |
| `venv\Scripts\activate` (Windows) | এনভায়রনমেন্ট অ্যাক্টিভেট |
| `deactivate` | এনভায়রনমেন্ট ডিঅ্যাক্টিভেট |
| `rm -rf venv` (Linux/macOS) | এনভায়রনমেন্ট ডিলিট |

</div>

---

## ⚡ 3. Python Execution

<div align="center">

| Command | Description |
|:--------|:------------|
| `python script.py` | পাইথন ফাইল রান |
| `python -m http.server 8000` | লোকাল HTTP সার্ভার চালু (বর্তমান ডিরেক্টরি) |
| `python -c "print('Hello')"` | এক লাইনের পাইথন কোড রান |
| `python -i` | ইন্টারঅ্যাক্টিভ শেল (REPL) চালু |
| `python -m pdb script.py` | পাইথন ডিবাগার সহ ফাইল রান |

</div>

---

## 🧱 4. Django (Python Web Framework) - Artisan Equivalent

<div align="center">

| Command | Description |
|:--------|:------------|
| `django-admin startproject myproject` | নতুন Django প্রজেক্ট তৈরি |
| `python manage.py runserver` | লোকাল সার্ভার চালু (127.0.0.1:8000) |
| `python manage.py startapp myapp` | নতুন অ্যাপ তৈরি |
| `python manage.py makemigrations` | মাইগ্রেশন ফাইল তৈরি |
| `python manage.py migrate` | ডাটাবেজে মাইগ্রেশন এপ্লাই |
| `python manage.py createsuperuser` | অ্যাডমিন ইউজার তৈরি |
| `python manage.py shell` | Django শেল চালু |
| `python manage.py test` | টেস্ট রান |
| `python manage.py collectstatic` | স্ট্যাটিক ফাইল সংগ্রহ (Production) |
| `python manage.py dumpdata > data.json` | ডাটা ব্যাকআপ |
| `python manage.py loaddata data.json` | ডাটা রিস্টোর |

</div>

---

## 🌶️ 5. Flask (Micro Framework) Quick Start

<div align="center">

| Command | Description |
|:--------|:------------|
| `pip install flask` | Flask ইন্সটল |
| `export FLASK_APP=app.py` (Linux/macOS) | Flask অ্যাপ সেট |
| `set FLASK_APP=app.py` (Windows) | Flask অ্যাপ সেট |
| `flask run` | ডেভেলপমেন্ট সার্ভার চালু |
| `flask run --debug` | ডিবাগ মোড সহ সার্ভার চালু |

</div>

---

## 🛠️ 6. Useful Utilities

<div align="center">

| Command | Description |
|:--------|:------------|
| `pip install black` | কোড ফরম্যাটার ইন্সটল |
| `black script.py` | ফাইল ফরম্যাট করা |
| `pip install pytest` | টেস্ট ফ্রেমওয়ার্ক ইন্সটল |
| `pytest` | টেস্ট রান করা |
| `python -m pip install --upgrade pip` | pip নিজেই আপডেট করা |
| `pip cache purge` | pip ক্যাশ ক্লিয়ার |

</div>

---

## 📦 Bonus: Jupyter & IPython

<div align="center">

| Command | Description |
|:--------|:------------|
| `pip install jupyterlab` | JupyterLab ইন্সটল |
| `jupyter lab` | JupyterLab ওপেন (ব্রাউজারে) |
| `pip install ipython` | IPython ইন্সটল |
| `ipython` | IPython শেল চালু |

</div>

---

<div align="center">

### 🌟 Save this – it'll save your time  
**Happy Pythoning!**

[![Profile Views](https://komarev.com/ghpvc/?username=your-username&color=blue&style=flat-square)](https://github.com/your-username)

</div>

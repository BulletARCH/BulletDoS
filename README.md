# 💥 BulletDoS

A Python-based **DoS/load-testing tool** created for security research, experimentation, and authorized testing.

> ⚠️ **Important:** Only use this software against systems you own or have explicit permission to test. Do not use it against public websites, servers, networks, or services without authorization.

## 📌 Features

* Python-based
* Command-line interface
* Configurable request/testing parameters
* Asynchronous HTTP requests
* Custom HTTP headers and User-Agent handling
* Dependency management through `requirements.txt`

## 🖥️ Requirements

* Python 3.x
* `pip`
* A Linux, macOS, or Windows environment

## 📥 Installation

Clone the repository:

```bash
git clone https://github.com/BulletARCH/BulletDoS.git
cd BulletDoS
```

Install the required Python packages:

```bash
pip install -r requirements.txt
```

## ▶️ Usage

Run the program with:

```bash
python DoS.py
```

Follow the prompts provided by the program.

### ⚠️ Authorized Testing Only

Use the tool only in environments where you have permission to generate traffic.

Good examples include:

* Your own local test server
* A private lab environment
* A server you own
* A test environment where you have written authorization

Do **not** target third-party systems without permission.

## 🧪 Recommended Test Environment

For safe experimentation, run a local HTTP server and test against:

```text
http://127.0.0.1
```

This allows you to study request handling and server performance without affecting other people's infrastructure.

## 📁 Project Structure

```text
BulletDoS/
├── DoS.py
├── requirements.txt
├── user.txt
└── README.md
```

## ⚙️ Dependencies

Python dependencies are listed in:

```text
requirements.txt
```

Install them with:

```bash
pip install -r requirements.txt
```

## ⚠️ Disclaimer

The author is not responsible for misuse of this software.

By using this project, you agree to use it only for **legal, authorized security testing, research, and educational purposes**.

## 👤 Author

**BulletARCH**

GitHub: https://github.com/BulletARCH

---

⭐ If you find the project useful for legitimate security research, consider starring the repository.

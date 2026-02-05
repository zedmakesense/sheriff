---

# Sheriff

## Prerequisites

This project uses **Python** and **uv** for dependency and environment management.

### Required

* **Python 3.10+**
* **uv**
* **MySQL** running locally

### Install `uv`

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Verify installation:

```bash
uv --version
```

---

## Environment Setup

Create a `.env` file in the project root:

```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password_here
```

Important:

* The application is expected to fail if this file is missing or incorrect

---

## Install Dependencies

From the project root, run:

```bash
uv sync
```

---

## Run the Game

```bash
uv run python main.py
```

---

## Notes

* Ensure MySQL is running before starting the game

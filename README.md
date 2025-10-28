# The Commit Resolve(ko. 잔디 심을 결심)

> Design your GitHub contribution graph, set your goals, and get daily reminders to achieve your resolve.



**The Commit Resolve** is a web application for developers who want to take proactive control of their coding habits. Instead of just passively filling your contribution graph, you can design your desired pattern—be it a piece of art, a word, or a specific schedule—and use it as your goal. The app will then help you stay on track with daily reminders.

---

## ✨ Key Features

* **🎨 Contribution Graph Designer**: Visually design your year-long contribution graph using a grid-based UI.
* **✍️ Text to Grass**: Automatically generate graph patterns from text.
* **🖼️ Image to Grass**: Convert simple images into contribution graph art.
* **💾 Save & Load Patterns**: Save your favorite designs and load them as future goals.
* **🔗 GitHub Integration**: Securely links with your GitHub account to track real-time commit progress.
* **💌 Daily Email Reminders**: Get a friendly nudge on days you need to commit to meet your goal.

---

## 🛠️ Tech Stack

* **Frontend**: React
* **Backend**: Go (Golang)
* **Database**: PostgreSQL
* **Containerization**: Docker

---

## 🚀 Getting Started

### Prerequisites

* Docker
* Docker Compose
* Git

### Installation & Running

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/](https://github.com/)[YOUR_USERNAME]/the-commit-resolve.git
    cd the-commit-resolve
    ```

2.  **Create environment files:**

    Create a `.env` file in the root directory and add the necessary environment variables for the backend and database. See `.env.example` for details (e.g., GitHub OAuth credentials, database settings).

3.  **Run with Docker Compose:**
    ```bash
    docker-compose up --build
    ```

4.  **Access the application:**
    * Frontend: `http://localhost:3000`
    * Backend API: `http://localhost:8080`

---

## 📜 License

This project is licensed under the MIT License.

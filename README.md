# HR Assist Streamlit App

An interactive web application built with Streamlit designed to support Human Resources (HR) operations and analytics.

## 🚀 Live Demo

Access the deployed application here:

👉 [**Open HR Assist Streamlit App**](https://hr-assist-l4xjf39xml3xsb43qvlgio.streamlit.app/)

## 💻 Local Setup & Installation

This project uses [**uv**](https://github.com/astral-sh/uv) as its fast Python package and environment manager.

### 1. Prerequisites

Make sure `uv` is installed on your system. If not, install it using one of the following commands:

* **macOS/Linux:**

  ```bash
  curl -LsSf https://astral.sh/uv/install.sh | sh
  ```

* **Windows (PowerShell):**

  ```powershell
  powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
  ```

* **via Pip:**

  ```bash
  pip install uv
  ```

### 2. Clone the Repository

```bash
git clone https://github.com/your-username/hr-assist-streamlit-app.git
cd hr-assist-streamlit-app
```

### 3. Sync & Install Dependencies

Run the following command to automatically create a virtual environment and install all project dependencies:

```bash
uv sync
```

### 4. Run the Application

Launch the Streamlit app using the `uv` environment:

```bash
uv run streamlit run frontend/web/main.py
```

Once running, open your browser and navigate to `http://localhost:8501`.

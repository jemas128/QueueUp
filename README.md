# QueueUp: Magic Streamlit Edition 🎩

A lively, colorful FIFO (First-In-First-Out) queue simulator built with Python and Streamlit.

## 🚀 Deployment Guide

Follow these steps to deploy this application to the web using GitHub and Streamlit Community Cloud.

### Phase 1: GitHub Setup

1.  **Create a GitHub Account**: If you don't have one, sign up at [github.com](https://github.com).
2.  **Create a New Repository**:
    *   Go to your repositories and click **New**.
    *   Name it `queue-up-streamlit`.
    *   Select **Public**.
    *   Check **Add a README file** (optional, but good practice).
    *   Click **Create repository**.
3.  **Upload Code**:
    *   If you are working locally with Git:
        ```bash
        git init
        git add .
        git commit -m "Initial commit"
        git branch -M main
        git remote add origin https://github.com/YOUR_USERNAME/queue-up-streamlit.git
        git push -u origin main
        ```
    *   **Manual Upload**: You can also upload files directly on the GitHub website by clicking **Add file** > **Upload files**. Ensure you upload `app.py` and `requirements.txt`.

### Phase 2: Streamlit Cloud Deployment

1.  **Sign in**: Go to [share.streamlit.io](https://share.streamlit.io) and sign in with your GitHub account.
2.  **New App**: Click the **New app** button (top right).
3.  **Connect to GitHub**:
    *   **Repository**: Select `YOUR_USERNAME/queue-up-streamlit`.
    *   **Branch**: `main`.
    *   **Main file path**: `app.py`.
4.  **Deploy**: Click the **Deploy!** button.
5.  **Wait**: Streamlit will install the libraries from `requirements.txt` and launch your app. It usually takes 1-2 minutes.

### 🏃‍♂️ Running Locally

To run this app on your own machine before deploying:

1.  Install Python (version 3.8 or higher).
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Run the app:
    ```bash
    streamlit run app.py
    ```

## 📂 Project Structure

*   `app.py`: The main application logic and UI.
*   `requirements.txt`: List of Python libraries required for the app to run.

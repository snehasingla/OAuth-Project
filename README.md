# 💻 Google OAuth Login Demo

This Node.js and Express application demonstrates **Google OAuth 2.0 authentication** using **Passport.js** (`passport-google-oauth20`). Users can log in with their Google account and view a simple profile page.

---

## ✨ Features

* **Login with Google account:** Seamlessly authenticate using Google's OAuth 2.0 flow.
* **Display user profile after login:** Show basic user information (like display name).
* **Session management:** Maintains user state using `express-session`.
* **Logout functionality:** Allows users to easily end their session.

---

## 🛠️ Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **Node.js** | Runtime Environment |
| **Express.js** | Web Framework |
| **Passport.js** | Authentication Middleware |
| **`passport-google-oauth20`** | Google OAuth 2.0 Strategy for Passport |
| **`express-session`** | Session Management |
| **`dotenv`** | Environment variable loading |

---

## ⚙️ Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone <your-repo-url>
    ```

2.  **Navigate into the project folder:**
    ```bash
    cd <your-project-folder>
    ```

3.  **Install dependencies:**
    ```bash
    npm install
    ```

4.  **Create a `.env` file** in the project root and add your credentials:
    ```env
    GOOGLE_CLIENT_ID=your_google_client_id
    GOOGLE_CLIENT_SECRET=your_google_client_secret
    SESSION_SECRET=a_strong_random_secret_string
    ```

    > **Note:** You need to register your application with the Google API Console to obtain your `CLIENT_ID` and `CLIENT_SECRET`.

5.  **Run the application:**
    ```bash
    npm start
    ```

6.  Open **`http://localhost:3000`** in your web browser.

---

## 🚀 Usage

1.  Click on **"Login with Google"** on the home page.
2.  After successfully logging in, you'll be redirected to the **profile page** showing your Google display name.
3.  Logout by clicking the **"Logout"** link.

---

## 💡 Why This Project Is Useful

This project serves as an excellent, practical demonstration of how to integrate **third-party authentication** (specifically Google OAuth 2.0) into a Node.js and Express application using the robust **Passport.js** library. It's a superb starting point for building web applications that require secure, standard login methods.

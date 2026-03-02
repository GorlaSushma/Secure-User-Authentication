# Secure-User-Authentication
 Quotation marks Implement a user authentication system with secure login and registration functionality. Users should be able to sign up for an account, log in securely, and access protected routes only after successful authentication.

 Here is a professional `README.md` for your project:

---

# Code Craft Landing Page

A simple and responsive authentication landing page for **Code Craft**, built using pure HTML, CSS, and JavaScript. This project demonstrates a clean UI with Material-style floating labels and basic client-side authentication using `localStorage`.

---

## 📌 Features

* 🔐 User Registration (Signup)
* 🔑 User Login Authentication
* 💾 Local Storage-based user data persistence
* 🎨 Material-style floating form labels
* ✨ Smooth input focus animations
* 📱 Responsive centered layout
* ⚡ No external libraries required

---

## 🛠️ Technologies Used

* **HTML5** – Structure
* **CSS3** – Styling and animations
* **Vanilla JavaScript** – Form handling and authentication logic
* **Web Storage API (localStorage)** – Data persistence

---

## 📂 Project Structure

```
CodeCraft/
│
└── index.html   # Main landing page with login & signup
```

---

## 🚀 How It Works

### 1️⃣ Signup Process

* User enters:

  * Username
  * Email
  * Password
* The data is stored in `localStorage` using the username as the key.
* If the username already exists, an alert is shown.
* After successful registration, the user is redirected to the login form.

### 2️⃣ Login Process

* User enters:

  * Username
  * Password
* The app checks `localStorage` for stored credentials.
* If credentials match → Login successful.
* If not → Error message displayed.

---

## 🧠 JavaScript Functions

### `show(shown, hidden)`

Toggles visibility between login and signup forms.

### `register(event)`

* Prevents default form submission
* Stores new user in `localStorage`
* Prevents duplicate usernames

### `authenticate(event)`

* Validates login credentials
* Displays success or error messages

---

## 🎨 UI Highlights

* Floating labels using `:focus` and `:placeholder-shown`
* Animated underline effect
* Error state styling support
* Clean card-style centered container
* Hover and active button effects

---

## ⚠️ Important Note (Security Warning)

This project uses **localStorage** to store passwords in plain text.
⚠️ This is **NOT secure** and should **NOT be used in production**.

For real-world applications:

* Use a backend server
* Hash passwords
* Implement proper authentication (JWT / Sessions)
* Use HTTPS

---

## 🔮 Possible Improvements

* Add form validation messages
* Add password strength checker
* Implement logout functionality
* Create dashboard page after login
* Add backend integration (Node.js, Firebase, etc.)
* Encrypt stored passwords
* Add dark mode toggle

---

## 📸 Preview

A minimal authentication interface with:

* Login screen
* Signup screen
* Smooth UI transitions
* Modern clean design

---

## 📄 License

This project is open-source and free to use for educational purposes.


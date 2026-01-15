# Contributing to ScholarSync

Thank you for your interest in contributing to **ScholarSync** 🎓
We appreciate your time and effort to help improve this project.

ScholarSync is a **privacy-first, offline academic companion app** built with **Flutter, GetX, and Hive**.

---

## 🧭 Contribution Guidelines

Please follow these guidelines to ensure smooth collaboration.

---

## 🚀 How to Contribute

1. **Fork** the repository
2. **Clone** your fork locally

   ```bash
   git clone https://github.com/ReversantTechnologies/ScholarSync
   ```
3. Create a new branch

   ```bash
   git checkout -b feature/your-feature-name
   ```
4. Make your changes
5. Commit your changes with a clear message

   ```bash
   git commit -m "Add: CGPA calculation optimization"
   ```
6. Push to your fork

   ```bash
   git push origin feature/your-feature-name
   ```
7. Open a **Pull Request**

---

## 🛠️ Tech Stack Rules

Please follow the existing architecture:

* **Flutter** for UI
* **GetX** for:

  * State management
  * Dependency injection
  * Routing
* **Hive** for:

  * Local data storage
  * Offline-first data handling

❌ Do not introduce:

* Cloud databases
* Ads or trackers
* Online dependencies without discussion

---

## 📂 Project Structure

```
lib/
├── controllers/   # GetX controllers
├── models/        # Data models
├── services/      # Hive services
├── views/         # UI screens
├── widgets/       # Reusable widgets
├── routes/        # App routing
└── main.dart      # App entry point
```

---

## ✍️ Code Style

* Follow **Flutter & Dart best practices**
* Keep widgets small and reusable
* Use meaningful variable and class names
* Comment complex logic where necessary
* Avoid unnecessary rebuilds

---

## 🐞 Reporting Issues

When reporting a bug:

* Clearly describe the issue
* Mention steps to reproduce
* Attach screenshots or logs if possible
* Specify device and Android version

---

## 💡 Feature Requests

For new features:

* Clearly explain the use case
* Keep features aligned with ScholarSync’s goals
* Avoid features that require internet or ads

---

## 🔒 Privacy First Policy

ScholarSync is strictly:

* **Offline**
* **Ad-free**
* **No data collection**

Any contribution must respect this principle.

---

## ✅ Pull Request Checklist

Before submitting a PR:

* [ ] Code compiles successfully
* [ ] No breaking changes
* [ ] Follows existing architecture
* [ ] Feature is offline-compatible
* [ ] Commit messages are clear

---

## 🙌 Thank You

Your contribution helps make ScholarSync better for students everywhere.
Happy coding! 🚀

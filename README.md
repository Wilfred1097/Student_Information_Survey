# 🎓 Student Information Survey

A modern, responsive web application designed for seamless student registration and data collection. Featuring dynamic PSGC (Philippine Standard Geographic Code) cascading location selectors, real-time input feedback, and a sleek glassmorphism UI, it provides a frictionless experience for students entering their academic and residential details.

![https://github.com/Wilfred1097/survey/blob/main/sample-ui.PNG](https://github.com/Wilfred1097/survey/blob/main/sample-ui.PNG?raw=true)

🌐 **Live Demo:** [https://wilfred1097.github.io/Student_Information_Survey/](https://wilfred1097.github.io/Student_Information_Survey/)


---

## ✨ Key Features

- **📍 Dynamic PSGC Cascading Address Selector:** Automatically fetches official regions, provinces, cities/municipalities, and barangays in real-time. Fully supports Metro Manila (NCR) special cases where provinces are not applicable.
- **🎨 Glassmorphism & Modern UI:** Built with Tailwind CSS, featuring smooth backdrop filters, responsive two-column grids, and a sophisticated dark-mode aesthetic.
- **⚡ SweetAlert2 Summary Modal:** Displays an elegantly formatted review card upon successful submission, allowing users to verify their details before resetting the form.
- **🔒 Input Validation & UX Feedback:** Clear visual cues, disabled states for unselected dependencies, and responsive mobile-first layouts.
- **🚀 100% Client-Side:** Runs entirely in the browser with zero complex backend setups required.

---

## 🛠️ Built With

* **HTML5 / JavaScript (ES6+)** — Core structure, form state management, and asynchronous PSGC API fetching.
* **Tailwind CSS** — Modern utility-first styling and glassmorphism design system.
* **SweetAlert2** — High-performance modal dialogs for success notifications.
* **PSGC Cloud API** — Official geographic data source for Philippine administrative divisions.

---

## 🚀 Getting Started Locally

To run a local copy of this project:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/wilfred1097/student-information-survey.git
   ```

2. **Navigate to the directory:**
   ```bash
   cd student-information-survey
   ```

3. **Open the application:**
   Simply open `index.html` in your favorite web browser or serve it using a local development server.

---

## 💡 How to Use

1. Enter your full name, select your gender, and specify your course/degree program and year level.
2. Select your **Region** from the dropdown. The app will automatically fetch and populate the corresponding provinces or adapt for NCR.
3. Select your **Province**, **City/Municipality**, and **Barangay** sequentially.
4. Fill out optional street details and click **Submit Registration Survey** to view your summary card!

---

## 🤝 Contributing

Contributions, feature requests, and bug reports are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

<div align="center">
  <sub>Built with ❤️ by <a href="https://github.com/wilfred1097">wilfred1097</a></sub>
</div>
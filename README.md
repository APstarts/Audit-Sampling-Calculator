# 🧮 Risk-Based Sampling Calculator for Auditors

A simple, web-based calculator designed to help internal auditors determine **sample sizes** for **testing internal controls** and **tests of details** using a risk-based approach.

## 📌 Features

- Select between **Internal Control Testing** or **Test of Details**
- Input:
  - Risk Level (High, Medium, Low)
  - Population Size
  - Tolerable Error (%)
  - Expected Error (%)
- Calculates sample size using standard audit sampling formulas
- Instant results with user-friendly interface

## 📷 Demo

![screenshot](./screenshot.png) <!-- Optional: include an image showing the calculator -->

## 🚀 Getting Started

### 🔧 Prerequisites

Just a modern web browser – no backend or installations required.

### 📂 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/risk-based-sampling-calculator.git
cd risk-based-sampling-calculator
````

2. Open `index.html` in your browser:

```bash
open index.html
```

(Or just double-click the file.)

## ⚙️ Usage

1. Choose the type of test: **Internal Control** or **Test of Details**
2. Select your **Risk Level**
3. Enter:

   * **Population Size**
   * **Tolerable Error** (as a %)
   * **Expected Error** (as a %)
4. Click **"Calculate Sample Size"**
5. Review the calculated recommended sample size

## 📐 How It Works

* **Internal Controls (Attribute Sampling)**:
  Uses the standard formula:

  ```
  n = (Z^2 × p × (1 - p)) / E^2
  ```

* **Test of Details** (approximate monetary unit sampling):
  Uses a simplified statistical estimate based on population size, expected error, and tolerable error.

* **Z-values** (Confidence Factors):

  * Low Risk → 1.28 (90% confidence)
  * Medium Risk → 1.645 (95% confidence)
  * High Risk → 2.0 (97.5%-99% confidence)

## 📄 License

This project is licensed under the [MIT License](LICENSE). You're free to use, modify, and distribute this tool.

## 🙋‍♂️ Contributing

Contributions are welcome! Feel free to fork the repo and submit pull requests to:

* Improve calculation accuracy
* Add new sampling methodologies (e.g., classical variable sampling)
* Enhance UI/UX
* Add backend audit logging or export features

## ✉️ Contact

For suggestions or inquiries, feel free to open an issue or reach out via GitHub discussions.

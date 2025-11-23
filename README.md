# 🤖 Automated Program Repair (APR) Framework

> **Bug Detection and Repair:** A comprehensive, machine-learning-driven framework designed to automatically detect, analyze, and repair bugs in source code. Stop debugging, start repairing\!

## 🚀 Project Overview: The Mission

This project is a deep dive into **Automated Program Repair (APR)**, addressing the critical need for faster, more reliable software development. Our core goals are:

  * **1️⃣ Data Powerhouse:** Create robust, high-quality datasets ($\text{BugNet, AoC}$) essential for training state-of-the-art bug detection and repair systems.
  * **2️⃣ Algorithmic Excellence:** Develop, implement, and rigorously evaluate cutting-edge algorithms for automated code repair.
  * **3️⃣ Deep Insights:** Provide analytical clarity into common bug patterns and effective repair strategies.

-----

## 🏗️ Repository Blueprint: Where to Start

The project is thoughtfully structured to support research, data generation, and practical application:

| Directory | 🎯 Purpose | Why it's Awesome |
| :--- | :--- | :--- |
| **`bugnet`** | **BugNet Dataset Generation** | Scripts to create the comprehensive $\text{BugNet}$ dataset (buggy code $\leftrightarrow$ correct code pairs). |
| **`repair-pipeline`** | **The Repair Demo** | Practical, runnable demo applications showcasing our trained Python repair models in action. |
| **`aoc-dataset`** | **AoC Dataset Source** | Code used to generate the $\text{Advent of Code (AoC)}$ dataset for diverse testing. |
| **`hint`** | **Natural Language Hint Generation** | Contains the code to translate tricky bugs into user-friendly, natural language descriptions. |
| **`repair`** | **Evaluation & Benchmarks** | The frameworks used to benchmark and evaluate the performance of all implemented repair algorithms. |

-----

## 🛠️ Get Started in 30 Seconds\!

Ready to fix bugs automatically? Setting up your environment is simple:

```console
# 1. Create a virtual environment
python -m venv .venv

# 2. Activate the environment
source .venv/bin/activate

# 3. Install dependencies from the Makefile
make install
```

## 📖 Usage Guides: Explore Our Capabilities

Dive into the specific components you find most interesting\!

  * **✨ Execute the Repair Pipeline:**

    > 👉 See the automatic repair models in action\!
    > **[Go to `repair-pipeline` documentation](https://www.google.com/search?q=./repair-pipeline/)**

  * **📊 Explore the AoC Dataset:**

    > 💡 Visualize and analyze one of our key testing datasets.
    > **[See `aoc-dataset` visualization instructions](https://www.google.com/search?q=./aoc-dataset/)**

  * **🧠 Generate Natural Language Hints:**

    > 💬 Learn how the system explains *why* the bug exists.
    > **[Start Hint Generation Analysis](https://www.google.com/search?q=./hint/)**

  * **🧪 Evaluate Repair Performance:**

    > 📈 Run benchmarks on different repair algorithms using our datasets.
    > **[Check the Evaluation Framework](https://www.google.com/search?q=./repair/)**

  * **➕ Generate the BugNet Dataset:**

    > 💾 Learn how we built the core dataset used for training.
    > **[Follow BugNet Generation Instructions](https://www.google.com/search?q=./bugnet/)**

-----

## 🌟 Project Context & Acknowledgments

This advanced program repair framework was proudly developed as a capstone project during the **Intel Unnati internship program**, focusing on applying cutting-edge **Machine Learning techniques to solve complex Software Engineering challenges**.

### Core Contributors

A big thank you to the team who built this framework:

  * **Atharva Karval**
  * **Samarth Patil**
  * **Om Dalbhanjan**

-----

### **What's Next?**

We welcome contributions and feedback\! Have you found an exciting new repair algorithm? **[Open an Issue](https://www.google.com/search?q=https://github.com/atharvak-dev/Bug-Detection-and-Repair/issues)** or a **Pull Request**\!

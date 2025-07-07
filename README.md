# Intelligent-task-scheduler
Smart scheduler that assigns tasks based on deadline, priority, effort

## ✨ Features
- Automatically schedules tasks based on deadlines, priorities, and effort
- Prevents overbooking by limiting daily work hours
- Splits large tasks over several days if needed
- Fully written in plain Python — no external libraries

## 💻 How to Use
Clone the repository and run the scheduling script:

```bash
git clone https://github.com/<PranathiReddy05>/intelligent-task-scheduler.git
cd intelligent-task-scheduler
python run_scheduler.py
```

You can customize your own tasks in the `run_scheduler.py` file.

## 🔍 Example
```python
Task("Finish AI lab", deadline=date.today() + timedelta(days=2), priority=5, effort=4)
Task("Workout", deadline=date.today() + timedelta(days=1), priority=2, effort=1)
```

### 🧾 Sample Output

Here’s an example of what the scheduler produces:
![alt text]({A8A57083-F2A8-4C28-B180-7DEBA41B27BB}-1.png)

## 🤔 Why I Made This
I often struggled to plan my work efficiently, especially when everything felt urgent. I wanted a tool that could balance effort and priority to help me decide what to work on each day. Writing this taught me a lot about task modeling and time management.

## 📘 Learning Highlights
- Designed my own scheduling logic with Python classes
- Learned to use heaps to prioritize and sort tasks
- Practiced structuring a modular Python project
- Built a clean output format to read the weekly plan easily

## 🧪 Try in Google Colab
You can upload the Python module in [Colab](https://colab.research.google.com) and run it interactively.

## 📄 License
This project is open under the MIT License. Feel free to use or improve it!

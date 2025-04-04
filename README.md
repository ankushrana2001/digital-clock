
---

# 🕒 Digital Clock using Tkinter

This is a simple **Digital Clock** GUI application built using Python and the `Tkinter` library. It displays the current time (in hours, minutes, and seconds) along with the current date in a user-friendly graphical interface.

## 📸 Preview

![image](https://github.com/user-attachments/assets/6cfbe41b-8fcd-453a-9d8e-60666167db18)


## 🛠️ Features

- Displays the current time in **HH:MM:SS AM/PM** format.
- Shows the current date below the time.
- Updates every second.
- User-friendly interface with customizable font and color.

## 📦 Requirements

- Python 3.x

The app uses only the standard Python library, so no additional installations are required.

## 🚀 How to Run

1. Clone this repository or download the `digital-clock.py` file.
2. Open your terminal or command prompt.
3. Run the following command:

```bash
python digital-clock.py
```

## 🧠 How It Works

- The `strftime` function from Python's `time` module is used to get the current time and date.
- The `Tkinter` GUI framework creates a window and displays the time.
- The `after` method updates the time every second to keep it in sync.

## 🎨 Customization

You can easily modify:
- Font and size: Change the values in `font=('calibri', 40, 'bold')`
- Background color: Modify `background='gold'`
- Text color: Modify `foreground='black'`

## 🎓 Learning Source
This project was created by learning and following the tutorial from YouTube:
🔗 Watch the tutorial here: [Digital Clock in Python - Tkinter | CodeWithAarohi](https://youtu.be/kDkN3WPESoY?si=CEaTpSIaRK1vTJSg)

I followed along with the tutorial, copied the code, and experimented with it to understand Tkinter better.

---

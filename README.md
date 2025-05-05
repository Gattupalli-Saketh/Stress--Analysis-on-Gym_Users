# 🏋️‍♂️ Gym Members Exercise Tracking

This Python program reads a CSV file containing gym members' exercise metrics, including heart rate measurements and body composition.  
It allows you to input a **serial number (ID)** to retrieve detailed member data and calculate their **stress level** based on heart rate and body composition.

---

## 📋 Overview

✅ Load gym members' data from a CSV file  
✅ Calculate **body mass** based on weight and fat percentage  
✅ Calculate **stress levels** using heart rate metrics  
✅ Retrieve and display detailed information for a specific gym member by their serial number  

---

## 📦 Requirements

- Python 3.x  
- `pandas` library

---

## 🔧 Installation

1️⃣ **Clone the repository** (if applicable):

```bash
git clone <repository-url>
cd <repository-directory>
```

2️⃣ **Install dependencies**:

```bash
pip install pandas
```

3️⃣ **Prepare your CSV file**:

Ensure you have a file named:

```
gym_members_exercise_tracking.csv
```

with the following columns:

| Max_BPM | Avg_BPM | Resting_BPM | Weight (kg) | Fat_Percentage |
|---------|---------|-------------|-------------|----------------|
| 180     | 150     | 70          | 75          | 15             |
| 175     | 145     | 68          | 80          | 20             |
| 190     | 160     | 72          | 85          | 18             |

**Sample CSV content**:

```
Max_BPM,Avg_BPM,Resting_BPM,Weight (kg),Fat_Percentage
180,150,70,75,15
175,145,68,80,20
190,160,72,85,18
```

---

## 🚀 Usage

Run the program:

```bash
python your_script_name.py
```

When prompted, enter the **serial number (ID)** of the gym member you want to check.  
The serial number corresponds to the row order in the CSV file (starting from 1).

---

## 📊 Example Output

```
Enter The ID of user: 1

Heart Rate Data for Serial Number 1:
Max BPM: 180
Avg BPM: 150
Resting BPM: 70
Weight: 75 kg
Fat Percentage: 15%
Body Mass: 11.25
Calculated Stress Level: 56.25
```

---

## ⚠️ Error Handling

- If you enter an invalid serial number (outside the range), the program will notify you.
- If you input a non-integer value for the serial number, an error message will be displayed.

---

## 🙏 Acknowledgments

Thanks to:

- **pandas** for providing powerful and easy-to-use data manipulation tools.

Feel free to modify the code or this README to better fit your project or preferences!

---

💪 **Happy tracking and stay healthy!**

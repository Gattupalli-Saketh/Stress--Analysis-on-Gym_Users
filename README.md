Overview
This Python program reads a CSV file containing data about gym members' exercise metrics, including heart rate measurements and body composition. The program allows users to input a serial number to retrieve specific member data and calculate their stress level based on heart rate metrics and body composition.

Features
Load gym members' data from a CSV file.
Calculate body mass based on weight and fat percentage.
Calculate stress levels using heart rate metrics.
Retrieve and display detailed information for a specific gym member based on their serial number.

Requirements
Python 3.x
pandas library
Installation
Clone the repository (if applicable):
bash
git clone <repository-url>
cd <repository-directory>

Install the required libraries:
Make sure you have pandas installed. You can install it using pip:
bash
pip install pandas

Prepare the CSV file:
Ensure you have a CSV file named gym_members_exercise_tracking.csv with the following columns:
Max_BPM: Maximum beats per minute during exercise.
Avg_BPM: Average beats per minute during exercise.
Resting_BPM: Resting beats per minute.
Weight (kg): Weight of the member in kilograms.
Fat_Percentage: Body fat percentage of the member.
Sample CSV Format
text
Max_BPM,Avg_BPM,Resting_BPM,Weight (kg),Fat_Percentage
180,150,70,75,15
175,145,68,80,20
190,160,72,85,18

Usage
Run the program:
bash
python your_script_name.py

When prompted, enter the serial number (ID) of the user whose data you want to see. The serial number corresponds to the order of entries in the CSV file.
The program will display:
Maximum BPM
Average BPM
Resting BPM
Weight (in kg)
Fat Percentage
Body Mass (calculated)
Calculated Stress Level
Example
text
Enter The ID of user: 1
Heart Rate Data for Serial Number 1:
Max BPM: 180
Avg BPM: 150
Resting BPM: 70
Weight: 75 kg
Fat Percentage: 15%
Body Mass: 11.25
Calculated Stress Level: 56.25

Error Handling
If an invalid serial number is entered (outside the range of available entries), the program will notify the user.
If non-integer input is provided for the serial number prompt, an error message will be displayed.

Acknowledgments
Thanks to pandas for providing powerful data manipulation capabilities.
Feel free to modify any sections to better fit your project's specifics or your personal preferences!

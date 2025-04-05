                                      📝 Automated Exam Duty Allocation System (Mini Project)



📌 Project Overview
This mini project is designed to automate the exam duty allocation process for teachers in educational institutions. It ensures that each classroom is supervised by one fixed duty teacher and one relieving teacher, with options to:
Skip unavailable classrooms or teachers.
Randomly assign duties while keeping fairness and balance.
Save the final duty list to an Excel file.
This Python-based project is ideal for academic administration, and can be used by departments and exam coordinators during university or school examinations.
💡 Key Features
✅ Dynamic Classroom Selection: Allows users to select how many classrooms are needed for an exam.
🚫 Unavailable Filtering: User can exclude unavailable classrooms and teachers.
🔁 Balanced Teacher Rotation: Each classroom gets one fixed duty teacher and one relieving teacher.
🆓 Spare Teacher Identification: Any extra teachers are automatically listed as "spare".
💾 Excel Export: Final schedule is saved to an Excel file for easy sharing/printing.
🔐 Error Handling & Validation: Ensures enough teachers/classrooms are available before scheduling.
🗂️ Dataset 
classrooms.csv
teachers.csv
🛠️ How It Works
Input classroom and teacher data from CSV files.
Ask user:
How many classrooms are needed?
Which rooms and teachers are unavailable (if any)?
Filter and validate the data.
Randomly assign fixed and relieving duty teachers.
Generate and display the final schedule.
Export the output to final_exam_duty_schedule.xlsx.
🖥️ Technologies Used
Python
Pandas
Random
Jupyter Notebook / Google Colab
Excel (.xlsx) output via to_excel()
📦 How to Run
Clone the repository or download the files.
Prepare your classrooms.csv and teachers.csv as per the format.
Run the script in any Python environment (Jupyter, Colab, or terminal).
Follow the prompts and get your schedule exported as an Excel file.

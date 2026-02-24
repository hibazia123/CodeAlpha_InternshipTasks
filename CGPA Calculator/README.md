🎓 CGPA Calculator – C++ (Internship Project)
📌 Project Overview

The CGPA Calculator is a console-based C++ application developed as part of my internship tasks.
This program calculates the Semester GPA and overall CGPA based on course grades and credit hours entered by the user.

It applies grade-to-point conversion logic and weighted credit hour calculations to determine accurate academic performance.

⚙️ Features

✔ Accepts number of courses
✔ Takes grade and credit hours for each course
✔ Converts letter grades to grade points
✔ Calculates total credit hours
✔ Computes total grade points (grade × credit hours)
✔ Calculates Semester GPA
✔ Calculates Overall CGPA
✔ Displays detailed course information

🧮 GPA Calculation Logic

Each letter grade is converted into its corresponding grade point.

Total Grade Points = ∑ (Grade Point × Credit Hours)

Semester GPA = Total Grade Points / Total Credit Hours

Overall CGPA is calculated using:

𝐶
𝐺
𝑃
𝐴
=
(
𝑃
𝑟
𝑒
𝑣
𝑖
𝑜
𝑢
𝑠
 
𝐶
𝐺
𝑃
𝐴
×
𝑃
𝑟
𝑒
𝑣
𝑖
𝑜
𝑢
𝑠
 
𝐶
𝑟
𝑒
𝑑
𝑖
𝑡
𝑠
)
+
𝐶
𝑢
𝑟
𝑟
𝑒
𝑛
𝑡
 
𝐺
𝑟
𝑎
𝑑
𝑒
 
𝑃
𝑜
𝑖
𝑛
𝑡
𝑠
𝑇
𝑜
𝑡
𝑎
𝑙
 
𝐶
𝑟
𝑒
𝑑
𝑖
𝑡
𝑠
CGPA=
Total Credits
(Previous CGPA×Previous Credits)+Current Grade Points
	​

🛠 Technologies Used

C++

Standard Template Library (STL)

Console-based User Interface

▶ How to Run

Compile the program:

g++ cgpa_calculator.cpp -o cgpa_calculator

Run the executable:

./cgpa_calculator
📚 Learning Outcomes

Implemented grade-weighted average logic

Applied mathematical computations in C++

Managed dynamic data using STL vectors

Strengthened understanding of user input handling and conditional logic

👩‍💻 Author

Hiba Zia
Internship Task – Code Alpha

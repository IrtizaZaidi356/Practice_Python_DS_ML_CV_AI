# **Practice Python, DS, ML, CV & AI:**

## **Basic Python:**

### **01) String Manipulation Methods Documentation**
#### **Introduction**
The purpose of this documentation is to provide an overview and explanation of various string manipulation methods in Python. The code examples are implemented in a Jupyter Notebook titled "01_String_Manipulation.ipynb."

**Source Code Link:**  https://github.com/IrtizaZaidi356/Practice_Python_DS_ML_CV_AI/blob/main/Basic_Python/01_String_Manipulation.ipynb

**Github Link:** https://github.com/IrtizaZaidi356/Practice_Python_DS_ML_CV_AI

#### **Table of Contents**

 1) Length (len())
 2) capitalize()
 3) lower()
 4) upper()
 5) title()
 6) count()
 7) find()
 8) replace()
 9) strip()
 10) split()
 11) startswith()
 12) endswith()
 13) isalpha()
 14) isdigit()
 15) isalnum()
 16) islower()
 17) isupper()
 18) swapcase()
 19) join()
 20) partition()
 21) rpartition()
 22) translate()
 23) expandtabs()
 24) encode()
 25) casefold()
 26) isspace()
 27) format()
 28) format_map()
 29) isascii()
 30) isprintable()
 31) istitle()
 32) lstrip() and rstrip()
 33) removeprefix() and removesuffix()
 34) find() with start and end parameters
 35) format_spec()
 36) isidentifier()
 37) isdecimal()
 38) isspace() with start and end parameters
 39) join() with an empty string
 40) lstrip() and rstrip() with specified characters
 41) partition() with a non-existing substring
 42) replace() with max parameter
 43) rfind()
 44) splitlines()
 45) title() with accents
 46) isascii() with non-ASCII characters
 47) isprintable() with non-printable characters
 48) istitle() with proper titlecased string
 49) zfill() with a negative number
 50) endswith() with tuple of suffixes
 51) isidentifier() with numbers in the string
 52) isdecimal() with superscript numbers
 53) isspace() with a mix of whitespaces
 54) join() with integers

---

# **02) Python program using `list`, `tuple`, `set`, and `dictionary`:**

## **Program Title: `Python Data Structures:`**

**Program Code Link:** https://github.com/IrtizaZaidi356/Practice_Python_DS_ML_CV_AI/blob/main/Basic_Python/02_list_tuple_set_dict.ipynb

#### **Introduction:**
   Brief overview of the program's purpose and usage.

#### **1. `List:`**
   i. Description of the list data structure.

   ii. Explanation of the list operations in the program.
   
   iii. List creation (**`fruits`**).
   
   iv. Appending a new element (**`"cherry"`**) to the list.

#### **2. `Tuple:`**
   i. Description of the tuple data structure.
   
   ii. Explanation of the tuple operations in the program.
   
   iii. Tuple creation (**`colors`**).
   
   iv. Concatenating a new element (**`"purple"`**) to the tuple.

#### **3. `Set:`**
   i. Description of the set data structure.
   
   ii. Explanation of the set operations in the program.
   
   iii. Set creation (**`num`**).
   
   iv. Adding a new element (**`6`**) to the set.

#### **4 `Dictionary:`**
   i. Description of the dictionary data structure.
   
   ii. Explanation of the dictionary operations in the program.
   
   iii. Dictionary creation (**`student_info`**).
   
   iv. Adding a new key-value pair (**`"course": "Pre - Engineering"`**) to the dictionary.
   

---

### **Program Explanation:**

#### **1. `List` Example:**
   i) **`fruits`** is a list containing strings representing different fruits.
   
   ii) **`append`** method is used to add a new fruit **`("Cherry")`** to the list.

#### **2. `Tuple` Example:**
   i) **`colors`** is a tuple containing strings representing different colors.
   
   ii) Concatenation is used to create a new tuple **`(new_colors)`** by adding a new color **`("purple")`**.

#### **3. `Set` Example:**
   i) **`num`** is a set containing integers.
   
   ii) The add method is used to add a new number **`(6)`** to the set.

#### **4. `Dictionary` Example:**
   i) **`student_info`** is a dictionary representing information about a student.
   
   ii) A new key-value pair **`("course": "Pre - Engineering")`** is added to the dictionary

---

## Tasks Using List

## **`Assignments using Lists in Python:`**

### **Assignment 1: `Grade Calculator:`**

#### **`Objective:`**
  -  Create a `program` that `calculates the grades` for a `list of student` based on their `average scores:`

#### **`Task:`**
  1. Create a `list` of `student names`.

  2. Create a `list` of corresponding `average scores` for each `student`.

  3. Use a `for loop` to iterate through the `list`.

  4. Apply `if-elif-else` conditions to determine the `Grades (e.g: A,B,C,D, or F)` based on the average score.

  5. `Display` the `student names` and their corresponding `Grades`.


### Task No# 01: A Grade Calculator for Student Performance Evaluation:

#### **Introduction:**
 - In this project, I developed a **`Grade Calculator` program** in Python aimed at efficiently assessing the academic performance of students. The program utilizes a list of student names and their corresponding average scores, employing a series of if-elif-else conditions to determine the appropriate letter grades (A, B, C, D, or F). This tool is designed to assist educators in simplifying the grading process and providing clear insights into students' achievements.

#### **Code Implementation:**

![image](https://github.com/IrtizaZaidi356/Practice_Python_DS_ML_CV_AI/assets/145368548/9b37aa7d-0929-424e-8928-35728a46d152)

#### **Output:**

![image](https://github.com/IrtizaZaidi356/Practice_Python_DS_ML_CV_AI/assets/145368548/b489948f-a114-492c-a947-0d687dbed35b)

#### **Explanation:**
 1. **Lists Initialization:** Two lists are created—one containing student names and the other storing their respective average scores.
 2. **For Loop Iteration:** A for loop is employed to iterate through each student in the lists.
 3. **Grade Determination:** Using if-elif-else conditions, the program assigns letter grades based on the average scores.
 4. **Results Display:** The program prints each student's name along with their calculated grade.

#### **Conclusion:**
 - This Grade Calculator program offers a clear and concise solution for educators to assess and communicate student performance. It simplifies the grading process by automating the assignment of grades based on predefined criteria, allowing educators to focus more on understanding and addressing individual students' needs. This tool is adaptable and can be easily customized to suit the grading scale and criteria specific to different educational contexts.

---

## **Assignment 2: `Shopping Cart`**

#### **`Objective`**: 
 - Develop a simple `shopping cart` program that `calculates` the `total cost` of `items` in the `cart`.

#### **`Tasks:`**
  1. Create a `list of items` in the `shopping cart.`
  
  2. Create a `list` of corresponding `prices` for `each item.`
  
  3. Use a for `loop` to iterate through the `items` and `prices.`
  
  4. Allow the `user to input` the `quantity` of each `item.`
  
  5. `Calculate` and `display` the `total cost` of the `items` in the `shopping cart.`

#### **`Program Overview:`**

 ![image](https://github.com/IrtizaZaidi356/Practice_Python_DS_ML_CV_AI/assets/145368548/d30402bd-2c8c-4e5b-9bb3-5358728e021b)

#### **`Output:`**

 ![image](https://github.com/IrtizaZaidi356/Practice_Python_DS_ML_CV_AI/assets/145368548/39faa2c7-a89a-456f-8de6-c9fb24110753)

#### **`Explanation:`**

 **1) Initialization:** 
    - Two lists are created – items representing the items in the shopping cart, and prices representing the corresponding prices.

 **2) User Input:**
    - A dictionary cart is initialized to store the quantity of each item.
    - A for loop iterates through each item, prompting the user to input the quantity for each item.

 **3) Calculation:**
    - The user inputted quantity for each item is stored in the cart dictionary.
    - Another for loop calculates and displays the total cost of each item based on the inputted quantity and the predefined prices.

 **4) Output:**
    - The contents of the shopping cart are displayed item-wise, along with their quantities and total costs.
    - The total cost of all items in the shopping cart is presented.

#### **Conclusion:**
   - This Python program provides a simple yet effective solution to create and manage a shopping cart, allowing users to input quantities and calculating the total cost of the items. The use of lists, dictionaries, and loops enhances the program's flexibility and readability.


# College Prediction Website

This project is a **College Prediction Website** designed using **PHP**, **HTML**, **CSS**, and **Bootstrap**. It predicts potential colleges based on scores from various entrance exams.

## Features
✅ **College Prediction** based on various exam scores:  
   - **Board Percentage**  
   - **JEE Score**  
   - **BITSAT Score**  
   - **SRMJEEE Score**  
   - **VITEEE Score**  
✅ Interactive web design using **Bootstrap** for improved user experience.  
✅ **Session Management** for user logins.  
✅ Clean UI with dedicated **CSS** files for different pages.  

## Requirements
Ensure you have the following installed:
- **XAMPP** or **WAMP** (for running PHP locally)
- Web browser (e.g., Chrome, Firefox)

## How to Run the Project
1. Clone the repository:
git clone https://github.com/pranjalparmar23/college-prediction.git
2. Copy the folder into the **htdocs** folder in your **XAMPP** directory.
3. Start **Apache** and **MySQL** services from the XAMPP control panel.
4. Navigate to the following URL in your browser:
http://localhost/college-prediction/home.php

## Usage
1. On the **Home Page**, fill in the form with:
   - **Board Percentage**
   - **JEE Score**
   - **BITSAT Score**
   - **SRMJEEE Score**
   - **VITEEE Score**
2. Click **Submit** to view eligible colleges based on your scores.
3. Use the **Login Page** to access user-specific content.
4. Visit the **About Us Page** via the **practice.php** link for website details.

## College Prediction Criteria
- **IITs**: Average score above **87%**
- **NITs**: Average score above **60%**
- **BITS**: Score above **280**
- **SRM**: Score above **140**
- **VIT**: Score above **80**

If your board percentage is below **60%**, the system will indicate that applications may not be accepted.

## Technologies Used
- **PHP** for server-side logic
- **HTML5/CSS3** for frontend design
- **Bootstrap** for responsive styling
- **Session Management** for user authentication

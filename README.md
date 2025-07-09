# Saveetha_Admission_clone
## Date: 9/7/25

## Objective:
To design a landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS. This activity reinforces skills in layout design, form creation, user input handling, responsive structure, and visual styling based on a real-world example.

## Tasks:
#### 1. Analyze the Landing Page Layout:
Observe the split-screen layout with a promotional section on the left and a form on the right.

Note the use of background images, text styling, and branding elements.

#### 2. Create the HTML Structure:
Use semantic tags like ```<section>, <header>, <form>, and <footer>``` to organize content.

Structure the form with input fields such as name, email, phone, password, city, state, course, specialization, captcha, and checkbox.

#### 3. Add Form Functionality:
Include appropriate input types (text, email, tel, password, select, etc.) with placeholders and labels.

Use the <button> element for the "APPLY NOW" action.

#### 4. Apply CSS Styling:
Implement a split layout using flexbox or grid.

Style the form elements with padding, shadows, background colors, and rounded borders.

Include hover effects and button transitions to match the original look.

#### 5. Incorporate Images and Branding:
Add the institution logo and use matching fonts and colors.

Place a background image or blurred overlay behind the form content if needed.

#### 6. Ensure Responsiveness:
Make sure the page adapts to different screen sizes using media queries.

Maintain readability and layout integrity on both desktop and mobile.

## HTML Code:
```
index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Saveetha Admissions 2026</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <div class="container">
    <div class="formcontainer">
      <h2>Admissions Open 2026</h2>
      <form>
        <div class="inputbox">
          <input type="text" placeholder="Enter Name *" required>
        </div>

        <div class="inputbox">
          <input type="email" placeholder="Enter Email Address *" required>
        </div>

        <div class="inputrow">
          <select required>
            <option>+91</option>
          </select>
          <input type="tel" placeholder="Enter Mobile Number *" required>
        </div>

        <div class="inputbox">
          <input type="password" placeholder="Any Password of Your Choice *" required>
        </div>

        <div class="secrow">
          <div class="inputbox">
            <input type="text" placeholder="State *" required>
          </div>
          <div class="inputbox">
            <input type="text" placeholder="City *" required>
          </div>
        </div>

        <div class="secrow">
          <div class="inputbox">
            <input type="text" placeholder="Course *" required>
          </div>
          <div class="inputbox">
            <input type="text" placeholder="Specialization *" required>
          </div>
        </div>

        <div class="captcharow">
          <input type="text" placeholder="Enter Captcha" required>
        </div>

        <label class="terms">
          <input type="checkbox" required>
          I authorise Saveetha Engineering College & its representatives to contact me with updates and notifications via Email/SMS/WhatsApp/Call. This will override DND/NDNC *
        </label>

        <button type="submit" class="submitbtn">APPLY NOW ➤</button>

        <p class="footert">
          Already have an Account? <a href="#">Login</a><br />
          <a href="#">Resend Verification Email</a>
        </p>
      </form>
    </div>
  </div>

</body>
</html>
```

## CSS Code:
```
style.css
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: url('picsaveetha.png') no-repeat center center/cover;
  height: 100vh;
}

.container {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  height: 100vh;
  padding-right: 50px;
}

.formcontainer {
  background-color: white;
  padding: 30px;
  width: 350px;
  border-radius: 10px;
}

h2 {
  text-align: center;
  margin-bottom: 20px;
  color: black;
}

form {
  display: flex;
  flex-direction: column;
}

.inputbox {
  display: flex;
  align-items: center;
  background: white;
  border: 1px solid white;
  margin-bottom: 10px;
  padding: 8px 10px;
  border-radius: 5px;
}

.inputbox i {
  margin-right: 10px;
  color: gray;
}

.inputbox input {
  border: none;
  outline: none;
  width: 100%;
}

.inputrow {
  display: flex;
  gap: 10px;
  margin-bottom: 10px;
}

.inputrow select {
  padding: 8px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

.inputrow input {
  flex: 1;
  padding: 8px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

.secrow {
  display: flex;
  gap: 10px;
  margin-bottom: 10px;
}

.captcharow {
  display: flex;
  align-items: center;
  gap: 10px;
  margin-bottom: 10px;
}

.captcharow img {
  height: 38px;
  border-radius: 3px;
}

.captcharow input {
  flex: 1;
  padding: 8px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

.terms {
  font-size: 12px;
  color: black;
  margin: 10px 0;
}

.submitbtn {
  width: 100%;
  background-color: #DAA520;
  color: black;
  padding: 12px;
  font-weight: bold;
  font-size: 14px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.footert {
  text-align: center;
  font-size: 13px;
  margin-top: 12px;
}

.footert a {
  color: #e69138;
  text-decoration: none;
}
```
## Output:
![image](https://github.com/user-attachments/assets/9ceaa8f9-8b6e-4dbe-bb41-b9fe4f81ca54)

## Result:
A landing page clone of Saveetha Engineering College’s Admission Enquiry form using HTML and CSS is designed successfully.

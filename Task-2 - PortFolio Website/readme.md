# Personal Portfolio Website (HTML & CSS)

This is a **beginner-friendly personal portfolio website** created using only **HTML and CSS**.  
It includes a **navigation bar**, multiple sections, and an **embedded resume viewer**, making it suitable for **college mini projects, lab submissions, and personal use**.

---

## 📌 Features

- Sticky navigation bar
- Single-page smooth navigation
- Profile section with image
- About Me section
- Skills section
- Projects section
- **Resume displayed directly on the website (PDF viewer)**
- Resume download option
- Contact details section
- Clean and professional UI
- Fully offline (no internet required)

---

## 🛠️ Technologies Used

- HTML5  
- CSS3  

---

## 📁 Project Structure

portfolio/
         |--- index.html
         |--- style.css
         |--- images/
                    |--- profile.jpg
         |--- resume/
                    |--- resume.pdf



---

## 🚀 How to Run the Project

1. Download or clone the project folder  
2. Place your profile photo inside the `images` folder  
3. Place your resume PDF inside the `resume` folder  
4. Open `index.html` in any web browser  

---

## 🖼️ Adding Your Resume

The resume is shown using an `<iframe>`:

```html
<iframe src="resume/resume.pdf"></iframe>




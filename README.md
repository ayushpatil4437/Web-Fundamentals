# Dayananda Sagar College of Engineering (DSCE), Bengaluru
### Web Fundamentals — Assignment 1 | HTML5 & CSS3

[![HTML5](https://img.shields.io/badge/HTML5-Semantic-orange?logo=html5)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Responsive-blue?logo=css3)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Institution](https://img.shields.io/badge/Institution-VTU%20Autonomous-navy)](https://www.dsce.edu.in)
[![Accreditation](https://img.shields.io/badge/NAAC-Grade%20'A'-gold)](https://www.naac.gov.in)

A clean, responsive, and accessible institutional website for **Dayananda Sagar College of Engineering (DSCE)**, built strictly using **semantic HTML5 and pure CSS3** without external JavaScript libraries or CSS frameworks.

---

## 🏛️ About the Institution

- **Name:** Dayananda Sagar College of Engineering (DSCE)
- **Trust:** Mahatma Gandhi Vidya Peetha (MGVP) Trust
- **Established:** 1979 (45+ Years of Legacy)
- **Location:** 30-Acre Urban Campus, Kumaraswamy Layout, Bengaluru, Karnataka, India
- **Affiliation & Approvals:** Autonomous institution affiliated to Visvesvaraya Technological University (VTU), Belagavi; Approved by AICTE, New Delhi; Accredited with **'A' Grade** by NAAC.
- **Official Exam Codes:**
  - **KCET Code:** `E007` (Karnataka Common Entrance Test)
  - **COMEDK Code:** `E035` (Undergraduate Entrance Test)

---

## ✨ Features & Section Breakdown

1. **Top Bar & Navigation**
   - Displays campus location, admissions hotline, official KEA/COMEDK codes, and NAAC accreditation badge.
   - Fixed navigation with quick jump links to all major sections and a dedicated *"Apply Now"* call-to-action.

2. **Hero Section**
   - Welcoming heading, summary description, dual CTA buttons (*"Explore Courses"* & *"Admissions & Fees"*).
   - High-resolution photograph of the DSCE Main Block with an overlay rating pill displaying the verified **4.2 ★ (3,900+ Google Reviews)** score.

3. **Key Statistics Strip**
   - Scannable institutional stats: **45+ Years Legacy**, **30-Acre Campus**, **20 B.E. Programs**, and **₹57 LPA Highest CTC**.

4. **Institutional Profile & Leadership**
   - Background of the MGVP Trust, academic autonomy under VTU Belagavi, 18 research centres, and an executive card featuring Chairman **Dr. D. Hemachandra Sagar**.

5. **Academics & Courses Grid**
   - 6 structured academic program cards covering core disciplines:
     - Computer Science & Engineering (with AI/ML, Data Science, IoT & Cyber Security tracks)
     - Information Science & Engineering (CS/IS Avg: ₹8–10 LPA)
     - Electronics & Communication Engineering (VLSI & Texas Instruments CoE)
     - Aeronautical & Aerospace Engineering (Supersonic wind tunnel lab)
     - Biotechnology & Chemical Engineering (Bio-incubator research hub)
     - Postgraduate & Doctoral Research Centres (18 VTU PhD hubs)

6. **Admissions & Fee Structure Matrix**
   - Comprehensive comparative matrix covering all three admission pathways:
     - **KCET Quota (~45% seats):** Government-regulated fees (~₹1.2L – ₹1.3L/yr, Code `E007`).
     - **COMEDK Quota (~30% seats):** Standardized national merit fees (~₹3.1L – ₹3.3L/yr, Code `E035`).
     - **Management Quota (Direct Admission):** Merit eligibility (min 50% in PCM, ~₹3.0L – ₹5.5L/yr).

7. **Placement Highlights & Top Recruiters**
   - Metric callouts: **₹57.0 LPA** highest international package, **₹8–10 LPA** CS/IS average, **~₹7.0 LPA** overall average, and **200+** annual recruiters.
   - Visual showcase of top hiring partners: *Google, Accenture, Amazon, Microsoft, Infosys, Cisco, IBM, Capgemini, TCS, L&T*.

8. **Campus Life & Infrastructure Gallery**
   - Responsive multi-column photographic gallery using semantic `<figure>` and `<figcaption>` tags:
     - Main Academic Block
     - Dr. Premachandra Sagar Central Library (1,50,000+ volumes)
     - 30-Acre Campus & Eco Rainwater Harvesting Lake
     - State-of-the-Art Air-Conditioned Auditorium
     - Sports Complex & Gymnasium
     - Student Innovation & 30+ Cultural/Technical Societies

9. **Notable Alumni Hall of Fame**
   - **Kichcha Sudeep:** Acclaimed Indian Actor, Director & Producer (B.E. Industrial & Production Engineering).
   - **Nosthush Kenjige:** Professional Cricketer (USA National Cricket Team, ICC World Cups).
   - **Sunil Abraham:** Digital Public Policy Expert (Founder of CIS).

10. **Student Academic Records Table**
    - Accessible semantic `<table>` representing the Dean's Honor Roll and autonomous semester credit assessment, containing student USN, names, branches, semester, SGPA scores, and classification badges (*Distinction*, *First Class*).

11. **Institutional Footer**
    - Trust heritage statement, quick navigation links, complete campus address with PIN code, and contact information.

---

## 📁 Repository Structure

```text
Web-Fundamentals/
├── index.html        # Main semantic HTML5 webpage
├── style.css         # Clean, responsive CSS3 stylesheet
├── README.md         # Comprehensive project documentation
├── .gitignore        # Git ignore for OS & editor artifacts
└── images/           # Campus photography assets
    ├── campus_main.jpg       # Main Academic Block
    ├── campus_aerial.jpg     # 30-Acre Campus Aerial & Eco-Lake
    ├── library_central.jpg   # Central Library
    ├── auditorium.jpg        # Campus Auditorium
    ├── sports_complex.jpg    # Sports Grounds & Arena
    ├── students_group.jpg    # Student Hackathons & Clubs
    └── chancellor.jpg        # Leadership / Chairman Desk
```

---

## 🛠️ Technical Implementation & Design Philosophy

- **Semantic HTML5:** Built using standard tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<figure>`, `<figcaption>`, `<table>`, `<footer>`) ensuring accessibility and clean hierarchy.
- **Pure CSS3:**
  - CSS Custom Properties (`:root`) for color palette and consistent spacing.
  - Modern layout techniques: **CSS Flexbox** and **CSS Grid** for responsive 2-column, 3-column, and 4-column cards.
  - Zero heavy third-party UI libraries (Bootstrap, Tailwind) or JavaScript dependencies — lightweight and loads instantly.
- **Responsive Design:** Optimized for all screen sizes (mobile devices, tablets, laptops, and ultra-wide desktops) via fluid containers and media queries.
- **Typography:** Uses Google Font [*Plus Jakarta Sans*](https://fonts.google.com/specimen/Plus+Jakarta+Sans) for clean, legible academic presentation.

---

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ayushpatil4437/Web-Fundamentals.git
   cd Web-Fundamentals
   ```

2. **Open in browser:**
   - Double-click `index.html` to open in any web browser (Chrome, Firefox, Safari, Edge), OR
   - In VS Code, right-click `index.html` and select **"Open with Live Server"**.

---

## 👨‍💻 Project Information

- **Course:** Web Fundamentals
- **Assignment:** Assignment 1 (HTML5 & CSS3)
- **Year:** First Year B.E.
- **Repository:** [ayushpatil4437/Web-Fundamentals](https://github.com/ayushpatil4437/Web-Fundamentals)

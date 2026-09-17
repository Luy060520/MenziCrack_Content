# MenziCrack Chiropractic Website - WEDE5020 POE Part 2Student: Luyolo Menziwa (MenziCrack Content)Module: WEDE5020
## Project OverviewMenziCrack is a fictional chiropractic clinic based in 160 Sir Lowry Road, Cape Town. This website is created for educational purposes for WEDE5020 Part 2 assignment. The site includes Home, About, Services, Enquiry & FAQ, and References.
Live Site: [Your GitHub Pages link here after you push]
## Part 2 Changes Log - What I Changed From Part 1
### 1. CSS Styling - style.css Created- Created external stylesheet `style.css` and linked to all 5 pages.- Implemented color scheme: Navy #1a3c6e (header), White (background), Teal accent.- Typography: Poppins Bold 600 for headings (h1, h2), Lato for body text - imported from Google Fonts.- Base reset, padding, border-radius for professional look.

### 2. Header & Navigation Fix- Fixed inconsistent header - now all 5 pages have identical `<header><h1><nav>` structure.- Navigation links are white, visible, with hover effect.- Sticky consistent layout across desktop and mobile.

### 3. Services Page - Image Gallery Enhanced- Used CSS Grid for gallery: `display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));`- Added 2 NEW images for Part 2 requirements:    - `cupping.jpg` - Cupping Therapy    - `acupuncture.jpg` - Acupuncture Treatment- Total 6 images now: posture_check, spine_diagram, chiropractic_adjustment, kids_posture, cupping, acupuncture.- All images made responsive: `width: 100%; height: auto; border-radius: 8px;`

### 4. References Page Layout Fixed- Improved layout with proper `<main>` and sections for Text Sources, Image Sources, Fonts & Code.- Added disclaimer: MenziCrack is fictional and for educational purposes only.- Added all 6 image sources with file names matching /images/ folder.- Added new references for Part 2:    - Pexels.com for all service images    - Gemini AI for welcome_to_menzicrack.jpg    - WebMD, Mayo Clinic, RafflesMedicalGroup for Acupuncture & Cupping FAQ research.

### 5. Enquiry & FAQ Page - Content Added- Added new FAQ section: "Acupuncture & Cupping - New Services" with 5 Q&A.- Q1: What is Acupuncture? (Source: Mayo Clinic + RafflesMedical YouTube)- Q2: Does Acupuncture hurt?- Q3: What is Cupping Therapy? (Source: WebMD Cupping Therapy Basics)- Q4: What are side effects of Cupping?- Q5: Can I combine Chiropractic with Acupuncture and Cupping?- Added Google Maps embed for location: 120 Sir Lowry Road, Woodstock, Cape Town.

### 6. Responsive Design- Added media queries:    - Tablet: @media (max-width: 768px) - gallery becomes 2 columns, nav stacks    - Mobile: @media (max-width: 400px) - gallery 1 column, form full width- Used relative units: rem, %, vw for scalability.- Tested in Chrome DevTools - responsive on all pages.

### 7. Get In Touch & Form- Contact info: Phone 0328392901, WhatsApp 0933278398, Hours Mon-Fri 9am-6pm.- Enquiry form kept functional with Full Name, Email, Phone, Message.
## File Structure/MenziCrack_Content/- index.html- about.html- services.html- enquiries.html- references.html- style.css- README.md- /images/    - welcome_to_menzicrack.jpg    - posture_check.jpg    - spine_diagram.jpg    - chiropractic_adjustment.jpg    - kids_posture.jpg    - cupping.jpg (NEW)    - acupuncture.jpg (NEW)
## References- Google Fonts - Poppins & Lato- W3Schools - HTML/CSS- Pexels.com - Service images- Unsplash.com - Free images- WebMD - Cupping Therapy Basics: https://www.webmd.com/balance/cupping-therapy- Mayo Clinic - Acupuncture Overview: https://www.mayoclinic.org/tests-procedures/acupuncture/about/pac-20392763- RafflesMedicalGroup YouTube - What You Need to Know About Acupuncture- Gemini.google.com - AI generated hero image
## How to Run
Open any .html file in Chrome, or use Live Server in VS Code.

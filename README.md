# Umiya Physiotherapy Center Website
<img width="1901" height="968" alt="image" src="https://github.com/user-attachments/assets/6e6b0ee1-bf14-4184-834f-24b4a5a32a6f" />

A professional, responsive, and high-performance landing page designed for **Umiya Physiotherapy Center**. This website provides patients with a seamless experience to explore specialized healthcare services, meet the expert team, and book appointments online.

---

## 🏥 Project Overview

This project is a modern web solution tailored for a healthcare environment, featuring a clean "Light Theme" aesthetic, interactive elements, and a functional backend integration for appointment management.

### Key Features
* **Modern UI/UX:** Built with Bootstrap 5.3.3, featuring a "Montserrat" and "Open Sans" typography pairing for a professional medical look.
* **Responsive Design:** Fully optimized for mobile, tablet, and desktop viewing.
* **Appointment Booking System:** A dedicated booking interface (`Appointment_Form.html`) that captures patient details, preferred dates, and reasons for visit.
* **Google Sheets Integration:** Automated data submission to Google Sheets via Apps Script for streamlined patient management.
* **Engaging Animations:** Includes "Reveal-on-Scroll" logic and smooth-scrolling navigation for enhanced user engagement.
* **Multimedia Integration:** Featured video testimonials and a Google Maps integration for easy clinic location.

---

## 📂 File Structure

| File | Description |
| :--- | :--- |
| index.html | The primary landing page containing all sections (Hero, About, Services, Team, Testimonials, and Contact). |
| Appointment_Form.html | The standalone booking form with validation and submission logic. |
| style.css | Custom stylesheet for branding, light-mode palette, and scroll animations. |
| script.js | JavaScript for UI interactivity and smooth scroll behavior. |
| Umiya_Logo.png | Official clinic branding/logo. |
| clinic_photo.jpg | Exterior photo of the clinic used in the Hero and About sections. |
| mukesh_photo.jpg | Professional portrait of Lead Physiotherapist Dr. Mukesh Patel. |

---

## 🛠️ Technical Details

### Backend Integration
The booking system utilizes the `fetch` API to send `POST` requests to a Google Apps Script Web App. This eliminates the need for a traditional database, allowing the clinic to manage appointments directly in a Google Spreadsheet.

### Specialized Services Highlighted
* Orthopedic Physiotherapy
* Neurological Rehabilitation
* Pediatric & Geriatric Physiotherapy
* Sports Injury Rehabilitation
* Women’s Health Physiotherapy

---

## 📍 Clinic Information
* **Location:** Umiya Physiotherapy Center, Gayatri Shakti pith road, Mehsana highway, Mehsana 384002.
* **Lead Expert:** Dr. Mukesh Patel (M.P.T Ortho).
* **Contact:** +91 9998994974 | info@umiyaphysio.com.

---

## 🚀 Deployment Instructions
1. **Upload Files:** Host all files on GitHub Pages or any static web hosting service.
2. **Asset Check:** Ensure images (`Umiya_Logo.png`, `clinic_photo.jpg`, `mukesh_photo.jpg`) are in the root directory.
3. **Form Configuration:** In `Appointment_Form.html`, update the `sheetWebAppUrl` with your deployed Google Apps Script URL to enable the booking system.

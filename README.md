# LAMPCARA - Lampung Tourism Website

**LAMPCARA** is an interactive tourism guide website dedicated to the province of Lampung, Indonesia.

This project was built as the **Final Exam (UAS) for the "Introduction to Internet Technology"** course. It is a Single Page Application (SPA) developed using React.js, designed to showcase Lampung's beautiful destinations by integrating dynamic data from multiple external APIs.

## 🌟 Key Features

* **Dynamic Home Page:** A media-rich landing page featuring a background video, a CSS grid image gallery, and an interactive "Highlight" destination slider.
* **Interactive Tourism Page (`Wisata`):**
    * **Detailed Listings:** Renders all 16 tourist destinations from a central data file (`Wisata.jsx`).
    * **Interactive Maps:** Each destination features an interactive map from the **MapTiler SDK**, pinpointing its exact latitude and longitude.
    * **Video Showcase:** Includes an embedded YouTube video with its description fetched dynamically using the **YouTube Data API**.
* **Real-time Weather:** A weather widget in the footer displays the current weather in "Lampung" using the **OpenWeatherMap API**.
* **Functional Contact Form:** A "Contact Us" modal that submits user feedback directly to a **Google Sheet** via the **SheetDB API**.
* **Modern UI/UX:**
    * **Responsive Design:** A sticky, responsive navbar (using Bootstrap 5 Offcanvas) that changes appearance on scroll.
    * **Scroll Animations:** Smooth fade and zoom animations powered by **AOS (Animate On Scroll)**.
    * **User-Friendly Alerts:** Uses **SweetAlert2** for clean, modern notifications on form submission.
* **About Us Page:** Introduces the development team (Group 8) with links to their social media.

## 🛠️ Tech Stack & APIs Used

* **Core:** React.js, React Router DOM
* **Styling:** CSS 3 (Pure CSS) & Bootstrap 5
* **API Client:** Axios
* **Animations:** AOS (Animate On Scroll)
* **Alerts:** SweetAlert2
* **Icons:** Font Awesome, React Icons

### External APIs

* **Maps:** MapTiler SDK
* **Weather:** OpenWeatherMap API
* **Video Data:** YouTube Data API v3
* **Form Handling:** SheetDB (Google Sheets)

---

## 🔐 IMPORTANT: API Key Security Warning

**Warning:** As of this commit, all API keys (for MapTiler, OpenWeather, YouTube) and the SheetDB URL are **hard-coded** directly into the `.jsx` components.

This is a major security risk. Anyone with access to this code can steal and misuse your keys.

You **MUST** secure them using environment variables before deploying this project or making the repository public.


## 👨‍💻 Development Team (Group 8)

* **Kelvin Jonathan Setiawan** 
* **Gregorius Frederico**
* **Gadiel Narain**
* **Kent Seanly Teguh**

## Cineflow-Account-portal



**Cineflow** is a "New Content Creator" registration platform. This project is a functional web portal designed to collect creator data, validate inputs for security and compliance, and provide an interactive onboarding experience through integrated multimedia.

#### Project Overview
This project is a multi-page static website built to satisfy the requirements for a Content Creator onboarding system. It focuses on robust form structure, specific HTML5 input types for data integrity, and media implementation.



#### Project Structure
What you will find in this repository:
* **index.html**: The main registration page featuring the creator form and promotional video.
* **form.html**: Secondary structure for handling the submission layout.
* **README.md**: Documentation and project setup instructions.

#### Tech Stack
* **HTML5**: Utilizing semantic tags and advanced input attributes (minlength, accept, range).
* **Markdown**: For project documentation.
* **Multimedia**: Integration of `<video>` and `<audio>` elements for creator instructions.

#### Getting Started
1. **Clone this repository on your local machine**
```bash
git clone https://github.com/Crispin804/Cineflow-Account-portal.git
```
```bash
cd Cineflow-Account-portal
```

2. **Open `index.html` in any modern browser to view the site.**
3. **No build tools or dependencies required** for this version.

---

#### Implementation Requirements
The registration form has been built to meet the following specifications:
* **Text & Email**: Captured for Full Name and Address.
* **Password**: Security enforced via the `minlength` attribute.
* **Date**: Configured for Date of Birth (targeting 18+ eligibility).
* **Range**: An interactive slider for "Expected Weekly Upload Volume" (0 - 10).
* **File**: Profile picture upload restricted to `.jpg` and `.png` formats.
* **Media**: Promotional video and audio instructions included for user guidance.

---

#### How to Collaborate
We welcome contributions! To maintain code quality, please follow these steps:

###### The Workflow
* **Fork the Repository:** Create your own copy of the project.
* **Create a Feature Branch:**
```bash
git checkout -b feature/YourFeatureName
```
* **Commit Your Changes:** Use descriptive messages (e.g., `feat: add minlength to password field`).
* **Push to Branch:**
```bash
git push origin feature/YourFeatureName
```

###### Contribution Guidelines
1.  **Maintain Semantics:** Use `<section>`, `<article>`, or `<nav>` where appropriate.
2.  **Validation Check:** Ensure all new input fields include appropriate validation attributes.
3.  **Code Style:** Ensure all tags are properly closed and indented using 2 or 4 spaces.

---

#### Future Enhancements
- [ ] Integrate **CSS3** for custom branding and layout styling.
- [ ] Implement **JavaScript** for client-side age validation logic.
- [ ] Responsive design optimization for mobile content creators.

#### License
This project is for educational purposes. Licensed under the **MIT License**. All rights reserved by **Crispin804**.

---

## 🔗 Quick Links
* [View Documentation](#project-structure)
* [Collaboration Guide](#how-to-collaborate)
* [Report an Issue](https://github.com/Crispin804/Cineflow-Account-portal/issues)
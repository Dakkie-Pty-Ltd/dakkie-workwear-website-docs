# Dakkie Workwear Website Documentation (Developer Guide)

## Table of contents
1. [project Overview](#project-overview)
2. [Objectives](#objectives)
3. [Project Scope](#project-scope)
4. [Target Audience](#target-audience)
5. [Technologies & Tools](#technologies--tools)
6. [Repository Structure](#repository-structure)
7. [Setup & Installation](#setup--installation)
8. [Development Workflow](#development-workflow)
9. [Coding Standards](#coding-standards)
10. [Deployment & Hosting](#deployment--hosting)
11. [Versioning & Releases](#versioning--releases)
12. [Author & Contact](#author--contact)

---

## Project Overview
The **Dakkie Workwear website** is a professional e-commerce and informational platform for the Dakkie Workwear brand. It is designed to showcase products, provide company information, and allow customers to browse and purchase workwear items.

---

## Objectives
- Build a **responsive and scalable website** for Dakkie Workwear.
- Maintain **clean and modular code** for easy future updates.
- Implement **user-friendly navigation** and e-commerce features.
- Provide **documentation for developers** to streamline onboarding and maintenance.

---

## Project Scope
**In Scope:**
- Design and development of website pages
- Implementation of responsive layout (desktop, tablet, mobile)
- Integration of company branding (logo, color, fonts)
- Integration with payment and shipping solutions
- Documentation for deployment, setup, and maintenance

**Out of Scope**
- Mobile application
- Third-party API integrations beyond standard e-commerce

---

## Target Audience

- Mechanics, industrial workers, and construction professionals
- Retailers and distributors of workwear
- Online customers looking for durable workwear

---

## Technologies & Tools
- **Frontend:** HTML5, CSS3, JavaScript, jQuery
- **Backend:** PHP (WordPress CMS), MySQL
- **Version Control:** Git, GitHub
- **Design Tools:** Figma (for wireframes), Photoshop / Illustrator (for assets)
- **Development Tools:** VS Code, LocalWP, Git CLI
- **Deployment:** GoDaddy web hosting

---

## Repository Structure

This repository follows a clear and organized structure to ensure maintainability, Scalabilty, and ease of collaboration. Each directory has a defined purpose to help developers quickly understand where to find or add content.

dakkie-workwear-website-docs/
├── README.md # Primary documentation entry point
├── LICENSE # Project license (CC BY-NC 4.0)
├── /docs # Core project documentation
│ ├── project-charter.md # Project vision, objectives, and scope
│ ├── requirements.md # Functional and non-functional requirements
│ ├── sitemap.md # Website structure and navigation flow
│ ├── design-guidelines.md # Branding, UI/UX, and visual standards
│ └── deployment.md # Deployment process and environment details
├── /assets # Visual and supporting assets
│ ├── logos # Brand logos and variations
│ ├── wireframes # UI wireframes and mockups
│ └── images # Website and documentation images

---

## System Design
## Wireframes

- **Homepage:** Displays featured products, company info, and navigation.
- **Product pages:** Detailed product images, description, and pricing.
- **Contact page:** Form for inquiries
- **Sitemap included in** /docs/sitemap.md

---

## UI/UX Guidelines

- Brand colours: Dark Earth (#5C4033), Black (#000000), White (#FFFFFF)
- Fonts: Montserrat (headings), Red Hat Display (body)
- Logo: Small placement on product pages, full placement in header

---

## Implementation

- WordPress installed locally via LocalWP.
- Custom theme created following design guidelines.
- Product catalog and pages added according to requirements.
- Responsive testing done for desktop, tablet, and mobile.
- GitHub repository used for version control with *main* and *dev* branches.

## Testing & Quality Assurance

- Cross-browser testing: Chrome, Firefox, Edge
- Responsive testing on multiple screen sizes
- Usability testing: Ensured navigation is intuitive
- Functionality testing: Contact forms, links, payments, and buttons working

---

## Deployment & Hosting

- Hosting environment: Godaddy Basic Plan Hosting Service
- Deployment steps documented in /docs/deployment.md
- Backup strategy: Weekly backups to cloud storage
- Domain: www.dakkie.co.za

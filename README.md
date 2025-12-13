# law-office-ferkovic-cetina-client-project
Commercial website developed for Law Office Sanja Ferković Ćetina. Features React, TypeScript, Firebase, and a custom Gemini AI chatbot. Live at law-ferkovic-cetina.hr.

# Law Office Sanja Ferković Cetina - Official Website

**🌐 Live Website:** [law-ferkovic-cetina.hr](https://law-ferkovic-cetina.hr)

> **Note:** The full source code for this project is hosted in a private repository to protect client confidentiality. Access to the code can be granted upon request.

## 📌 Project Overview

This repository contains the documentation for the official website of **Law Office Sanja Ferković Cetina**, based in Pula, Croatia. 

**Note:** This is a live, commercial project developed specifically for a client. As such, the source code is private to protect the client's intellectual property and business logic. This README serves as a showcase of the technologies, architecture, and advanced SEO strategies implemented in the project.

The website is a fully multilingual platform (Croatian, English, Italian) designed to serve local and international clients, providing detailed legal information, a blog, and direct communication channels.

## ⚖️ Legal Compliance & HOK Regulations

This website is strictly aligned with the **Croatian Bar Association (Hrvatska odvjetnička komora - HOK)** regulations, specifically the *Bylaws on Advertising, Advertising and Lawyer Websites*. 

To ensure full compliance, specific design and functional choices were made:
- **External Link Restriction:** The website does not link to external third-party sites, with the sole exception of the official Croatian Bar Association website, as per regulatory requirements.
- **Social Sharing Limitations:** While social media icons (Facebook, LinkedIn, X) are present in the UI, the functionality to share articles directly from the site has been disabled to adhere to advertising restrictions.
- **Pending Approval Status:** The published version contains all core functionalities. However, final design polishes and stylistic refinements are currently on hold pending official approval from the Croatian Bar Association.

## 🚀 Key Features

### 🤖 Multilingual Gemini AI Chatbot
One of the standout features is the integration of a custom **Gemini AI Chatbot**. 
- **Trilingual Support:** The bot is trained to interact fluently in Croatian, English, and Italian, adapting to the user's selected language.
- **Strict Non-Advisory Policy:** To comply with HOK regulations, the chatbot is explicitly trained **never to provide legal advice**. For any legal inquiry, it strictly directs the user to contact the attorney directly.
- **Disclaimer Banner:** A prominent banner is implemented within the chat interface, clearly stating that the AI cannot replace professional legal counsel.
- **General Assistance:** It provides immediate, automated assistance regarding the firm's services, working hours, and contact information.

### 🔍 Advanced SEO Strategy
A major focus of this project was Search Engine Optimization (SEO), resulting in high rankings for targeted keywords within just one month of launch.

- **Extensive JSON-LD Implementation:** 
  - **Global Schema:** The `index.html` file contains comprehensive JSON-LD scripts defining the `Attorney`, `LegalService`, `LocalBusiness`, and `Person` schemas, ensuring Google fully understands the business entity, its location, and services right from the entry point.
  - **Dynamic Content:** The project includes **over 30 unique JSON-LD scripts** dynamically injected based on the content.
  - **FAQ Schema:** Every single legal practice area (e.g., Civil Law, Labor Law, Property Law) has a dedicated FAQ Schema containing specific legal questions and answers. This allows Google to display rich snippets for these specific areas in all three languages.
  - **Article Schema:** Every blog post is wrapped with Article Schema to enhance visibility in news and article search results.
- **Optimized Metadata:** Titles, descriptions, and meta tags are meticulously crafted for every page and language variant to maximize click-through rates.
- **Breadcrumbs Navigation:** Implemented breadcrumbs to enhance site structure understanding for search engines and improve user navigation.
- **Proven Results:** Specific practice area pages are already appearing in top Google search results for targeted legal terms in HR, EN, and IT.

### 📝 Custom Blog & CMS
- **Firebase Backend:** The project utilizes **Firebase Database** for content storage and **Firebase Authentication** for security.
- **Admin Interface:** A custom-built admin interface allows the client to log in and manage blog content.
- **Multilingual Content:** The CMS supports creating and editing posts specifically for the Croatian, English, and Italian versions of the blog.

### 📧 Contact & Lead Generation
- **EmailJS Integration:** The contact form is powered by EmailJS, ensuring reliable delivery of client inquiries directly to the lawyer's inbox.
- **Client Feedback:** The system has received positive feedback from the client, with a confirmed increase in inquiries coming exclusively through the website's contact form.

### 🛡️ Security & Compliance
- **Google reCAPTCHA:** The contact form is protected by Google reCAPTCHA v2 to prevent spam and ensure that only genuine client inquiries reach the attorney.
- **Cookie Management:** A fully compliant Cookie Consent system is implemented, giving users control over their privacy preferences while ensuring adherence to GDPR and local regulations.

## ☁️ Infrastructure & Deployment

- **Hosting:** Deployed on **Cloudflare Pages** (Free Tier), ensuring fast global delivery and high reliability.
- **Domain:** The `.hr` domain was acquired via **Domene.hr** (CARNET) as a free domain for the business entity.
- **Email:** Custom professional email addresses are configured and routed through **Cloudflare's Email Routing** service.
- **Google My Business:** A fully optimized Google My Business profile has been set up and integrated to boost local visibility and credibility.

## 🛠️ Tech Stack

The project was built using a modern, performance-oriented stack:

### Frontend
- **React** (v18)
- **TypeScript** - For type safety and robust code.
- **Vite** - For lightning-fast build tool and development server.
- **Tailwind CSS** - For a responsive, modern, and custom design.
- **React Helmet Async** - For dynamic head management and SEO.

### Backend & Services
- **Firebase Authentication** - Secure admin login.
- **Firebase Database** - Database for blog posts and content management.
- **Google Gemini API** - Powering the intelligent chatbot.
- **EmailJS** - Serverless email functionality.

### Performance & Optimization
- **Lighthouse Optimization** - High performance, accessibility, and SEO scores.
- **Responsive Design** - Fully optimized for mobile, tablet, and desktop devices.

---

## 📈 Project Impact

This project demonstrates how a modern web application, combined with a strategic approach to SEO and AI integration, can tangibly improve a business's digital presence. The rapid indexing and ranking of specific legal services prove the effectiveness of the granular JSON-LD strategy, while the seamless communication tools have successfully streamlined the client acquisition process.

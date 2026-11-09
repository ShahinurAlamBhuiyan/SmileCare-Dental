# 🚀 SmileCare Dental – Customizable Dental Clinic Website & Management Platform

A commercially adaptable dental website and administration solution built to help clinics attract patients, present treatments, and manage appointment requests.

## 📌 Overview

SmileCare Dental is a full-stack dental clinic platform developed as a reusable foundation for different dental practices. It combines a conversion-focused public website with an authenticated administration dashboard for managing appointments, treatments, images, and account details.

The platform is designed to be customized for each clinic’s branding, doctors, contact information, treatment catalog, operating hours, clinical content, and patient journey. It is a clinic-specific solution rather than a multi-tenant SaaS product; each implementation can be configured and deployed independently.

I created the original Next.js application and patient-facing experience from scratch. My work covered the UI/UX, reusable frontend architecture, treatment pages, booking experience, responsive navigation, interactive results, accessibility improvements, and substantial admin-dashboard refinements.

The expanded backend and administration foundation was developed collaboratively with a project contributor.

## 🎯 Objectives

- Give dental clinics a professional and trustworthy online presence
- Convert website visitors into structured appointment requests
- Clearly present doctors, treatments, results, reviews, and clinic information
- Provide clinic staff with a protected appointment-management dashboard
- Allow treatment content and result galleries to be managed without editing frontend code
- Support independent branding and content customization for different clinics
- Deliver a responsive and maintainable foundation suitable for commercial adaptation

## 🛠️ My Contributions

### 🎨 UI/UX & Frontend Development

- Created the initial Next.js and Tailwind CSS application from scratch
- Designed and implemented the complete patient-facing dental website
- Built a light, reassuring visual system appropriate for healthcare and dental services
- Applied clear content hierarchy, trust signals, prominent contact options, and conversion-focused CTAs
- Refactored the frontend into reusable Home, Treatment, navigation, and shared UI components
- Created reusable treatment-detail layouts with overviews, benefits, candidate guidance, processes, FAQs, related services, and results
- Implemented animated hero messaging, treatment cards, doctor information, clinic details, reviews, contact sections, and booking prompts
- Standardized button contrast, spacing, typography, and component behavior across the website and admin dashboard

### 📱 Responsive Implementation

- Built dedicated desktop and mobile navigation experiences
- Added route-aware and scroll-aware active navigation states
- Implemented smooth mobile menus with Escape-key handling and reduced-motion consideration
- Reworked the administration interface for mobile, tablet, laptop, and desktop screens
- Added an off-canvas admin sidebar and responsive top navigation
- Created mobile card alternatives for appointment and treatment tables
- Improved responsive filters, forms, modals, image fields, pagination, and action controls
- Added accessible labels, focus states, ARIA attributes, keyboard-operable comparisons, and modal interactions

### ⚙️ Features & Functionality

- Built a reusable booking modal shared across navigation, hero, and CTA components
- Developed appointment form states, validation feedback, confirmation views, and serial-number presentation
- Prevented patients from selecting or submitting past appointment dates
- Created interactive drag-controlled before-and-after treatment comparisons
- Built data-driven treatment pages that can support different clinic service catalogs
- Added an all-appointments view with server-backed pagination
- Implemented appointment searching, filtering, sorting, and responsive result presentation
- Completed admin profile-name and password-management interfaces
- Added consistent loading, empty, success, error, confirmation, and disabled states
- Created reusable UI patterns that simplify visual and content customization for future clinic implementations

### 🔐 Backend & Integrations

- Extended the appointment API with server-side pagination and result metadata
- Added server-side past-date validation using the clinic’s Bangladesh timezone
- Connected frontend workflows to the project’s Supabase-backed appointment and treatment data
- Worked with the existing protected Supabase authentication flow for account settings
- Preserved email workflows for appointment receipt, acceptance, cancellation, and rescheduling
- Supported sanitized and validated patient-submission data
- Integrated frontend content with the existing treatment CRUD and image-storage workflows

### 🚀 Testing, Performance & Deployment

- Used Next.js image handling, responsive sizing, and above-the-fold image preloading
- Used lazy loading for the third-party reviews widget
- Reduced unnecessary animation work and supported reduced-motion preferences in key interactions
- Kept global CSS limited to application-wide rules while using Tailwind utilities inside components
- Verified completed changes using ESLint, TypeScript, Prettier, and Git whitespace checks
- Structured the application for independent clinic configuration and deployment
- No public production URL or performance benchmark is claimed because deployment evidence is not included in this showcase

## ⚙️ Tech Stack

- **Framework:** Next.js App Router, React
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Animation:** Framer Motion
- **Backend:** Next.js Route Handlers
- **Database:** Supabase
- **Authentication:** Supabase Auth
- **File Storage:** Supabase Storage
- **Email Notifications:** Resend
- **Reviews:** Google Reviews via Elfsight
- **Icons:** Lucide React
- **Quality Tools:** ESLint, Prettier, TypeScript

## ✨ Key Features

- Customizable clinic branding, contact information, doctor profile, and opening hours
- Conversion-focused dental clinic landing page
- Responsive desktop and mobile navigation
- Active navigation based on route and page position
- Animated hero messaging and attention-focused booking CTAs
- Data-driven treatment catalog
- Dedicated treatment-detail pages
- Treatment benefits, processes, FAQs, related services, and clinical guidance
- Interactive before-and-after result comparisons
- Treatment-specific result galleries
- Google Reviews integration
- WhatsApp, phone, map, and direct-contact actions
- Reusable appointment modal and embedded booking form
- Appointment serial-number confirmation
- Past-date and duplicate-booking safeguards
- Patient and clinic email notifications
- Protected admin authentication
- Dashboard summaries for appointments and active services
- Daily and all-appointments management views
- Appointment search, filtering, sorting, pagination, editing, and status updates
- Appointment rescheduling with email notification
- Treatment creation, editing, deletion, and image upload
- Management of treatment processes, benefits, FAQs, related treatments, and results
- Responsive admin tables, cards, forms, and modals
- Admin profile and password settings

## 📈 Outcome

The result is a complete, commercially adaptable dental clinic platform that supports both sides of the clinic experience.

Patients receive a clear and reassuring website where they can explore treatments, compare example results, review clinic information, and request appointments. Clinic teams receive a protected dashboard for monitoring bookings, updating appointment statuses, managing treatment content, and maintaining result galleries.

The reusable architecture allows the platform to be customized for different dental clinics without presenting it as a multi-tenant system. Branding, content, services, imagery, contact details, and deployment can be tailored for each implementation.

No conversion statistics, patient-growth figures, performance scores, or production business metrics are claimed.

## 🎥 Project Walkthrough

▶️ **Watch Project Walkthrough on YouTube** *(link coming soon)*

## 🖼️ Preview

![SmileCare Dental – Project Preview](assets/smilecare-dental-preview.png)

## 🤝 Notes

SmileCare Dental was developed as a collaborative commercial project intended to be customized and offered to different dental clinics.

The clinic names, patient references, contact information, treatment descriptions, statistics, and images shown in the showcase are demonstration content. A production implementation would be adapted to the selected clinic’s verified business details, brand identity, clinical services, policies, and approved media.

I created the original application and public-facing frontend, then delivered the responsive, usability, pagination, account-settings, validation, and accessibility improvements described above.

A separate contributor, identified in the project history as **shoaibrrian**, contributed substantially to the Supabase-backed backend, appointment-management foundation, treatment administration, authentication, email workflows, and related admin functionality.

Prospective clinic clients retain ownership of their individual business information, branding, patient data, and clinic-specific materials. Licensing, customization, hosting, maintenance, and product usage would be governed by the agreement for each implementation.

## 👨‍💻 Developer

**Shahinur Alam Bhuiyan**\
Frontend / Full-Stack Developer (React / Next.js / TypeScript)

- 💼 Upwork: [https://www.upwork.com/freelancers/~01bf24b7725d70b752](https://www.upwork.com/freelancers/~01bf24b7725d70b752)
- 🌐 Portfolio: [https://shahinuralambhuiyan.vercel.app](https://shahinuralambhuiyan.vercel.app)
- 📧 Mail: [shahinur.alam.bhuiyan01@gmail.com](mailto:shahinur.alam.bhuiyan01@gmail.com)

## 🔒 Showcase Notice

This repository is intended solely for portfolio and product-demonstration purposes. The showcase version does not expose production credentials, confidential source code, real patient information, customer records, private clinic documents, or sensitive client materials.

All patient-facing examples, appointment information, clinic statistics, contact details, and clinical imagery used in the showcase should remain fictional, licensed, or anonymized. Production credentials and clinic-specific data must be maintained separately and securely.

## 📄 License
This project is proprietary and provided for portfolio and product demonstration purposes only.

No permission is granted to copy, modify, redistribute, resell, sublicense, or create derivative works without prior written authorization.

For customization or commercial licensing, contact [Shahinur Alam Bhuiyan](mailto:shahinur.alam.bhuiyan01@gmail.com).

> Copyright © 2026 Shahinur Alam Bhuiyan and contributors. All rights reserved.

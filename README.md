# classes_01


Shreeji Tuition Classes - Surat 🎓

I have built the complete, modern, and professional website for "Shreeji Tuition Classes - Surat" in Next.js 14, Tailwind CSS, and Framer Motion.

The project is located at: 📁 shreeji-tuition-surat

The application is built, verified, and running on http://localhost:3000
.

🌟 5 Pages Architecture & Implemented Features
1. Home Page (page.tsx)
Sticky Navbar: Institute logo, navigation links (Home, Courses, Admission, Results & Gallery, Contact, Admin), language switcher (English / ગુજરાતી), and a prominent "Book Free Demo" Vibrant Orange button.
Hero Section:
Headline: "Surat's Most Trusted Tuition for 10th & 12th | 95% Results Every Year"
Sub-headline: "Limited Seats for 2026 Batch"
Dual CTAs: "Get Admission Now" (#F59E0B) + "Chat on WhatsApp" direct link (wa.me).
Interactive hero card displaying top ranker Aarav Patel (98.8%), batch filling status (85% filled), and 4.9/5 parent ratings.
Trust Section (3 Columns):
15+ Years Experience - Master board mentors, GSEB & CBSE blueprint mastery.
1000+ Students Taught - Max 25 students per batch, daily doubt desks.
Top Results in Surat - 95%+ board success record with 100/100 marks achievers.
Subjects Section: Dedicated modules for Maths, Science, English, and SST with separate batch badges for Gujarati Medium and English Medium.
2. Courses Page (courses/page.tsx)

Interactive course cards with category filters:

Std 8-10 (GSEB / CBSE Foundation & Board Mastery):
Subjects Included: Mathematics (Basic/Standard), Science & Tech, English Grammar, Social Studies (SST), Gujarati/Hindi.
Batch Timings: Morning (07:00 AM - 09:45 AM) | Evening (04:30 PM - 07:15 PM).
Monthly Fees: ₹2,499 / month with quarterly discount options.
CTA: "Enroll Now" button (pre-selects standard in /admission).
Std 11-12 Science (PCM / PCB / PCMB):
Subjects Included: Physics, Chemistry, Mathematics, Biology + GUJCET, JEE & NEET foundation.
Batch Timings: Morning (06:30 AM - 10:15 AM) | Evening (04:00 PM - 07:45 PM).
Monthly Fees: ₹4,499 / month.
Std 11-12 Commerce & CA Base:
Subjects Included: Elements of Accounts, Statistics, Economics, O.C.M., S.P.C.C.
Batch Timings: Morning (07:30 AM - 10:30 AM) | Evening (05:00 PM - 08:00 PM).
Monthly Fees: ₹3,199 / month.
3. Admission System - CORE LOGIC (admission/page.tsx)
Form Fields: Student Full Name, Parent's Mobile Number (with 10-digit validation), Standard/Class, Medium of Instruction (Gujarati / English), School Name, and Area in Surat (Adajan, Vesu, Varachha, Katargam, Piplod, Pal, Athwa Lines, etc.).
On Submit:
Auto-generates unique Student ID in format STU-SRT-2026-XXX (e.g. STU-SRT-2026-106).
Persists all data to localStorage.
Triggers multi-wave Confetti explosion (canvas-confetti).
Displays the celebration headline:

"Congratulations [Student Name]! Your Student ID is STU-SRT-2026-106"

3 Features on Success Page:
Download ID Card as Image (PNG): Rendered via StudentIdCard.tsx using html2canvas with student photo avatar, barcode, seal, and contact info.
Share on WhatsApp: One-click pre-filled WhatsApp announcement link (wa.me/?text=...).
Button to Pay Fees: Opens FeePaymentModal.tsx with UPI QR code (GPay/PhonePe/Paytm), instant payment simulation, fee receipt generation (REC-SRT-2026-XXX), and status update in localStorage.
4. Results & Gallery Page (results/page.tsx)
Toppers Section (6 Students with 98%+):
Aarav Patel - 98.8% (Std 10 GSEB) - P.P. Savani Vidhyabhavan, Surat
Diya Shah - 98.2% (Std 12 Science PCM) - Ashadeep IIT School, Surat
Krish Mehta - 97.9% (Std 12 Commerce) - Lourdes Convent High School
Prisha Desai - 97.5% (Std 10 CBSE) - Ryan International School
Meet Vaghasiya - 96.8% (Std 12 Science PCB) - T & T.V. Sarvajanik High School
Ananya Parekh - 96.4% (Std 12 Commerce) - J.H. Ambani Saraswati Vidyamandir
Parents Testimonials: 5-star ratings with verified parent reviews from Adajan, Vesu, and Ghod Dod Road.
Classroom Photo Gallery: High-tech AC Smart Classrooms, 1-on-1 Doubt Desks, Felicitation Ceremonies, and Demonstration Labs with category filters and interactive modal lightbox.
5. Contact & Admin Page
Contact Page (contact/page.tsx):
Interactive embedded Google Map of Surat with 1-click campus selector (Adajan Main Campus, Vesu VIP Road Branch, Varachha Branch).
Quick Inquiry Form with validation.
Direct WhatsApp Chat link (https://wa.me/919825144550).
Admin Page (admin/page.tsx):
Live table of all admitted students displaying: Student ID, Name, Class & Medium, Mobile, School, Area, Date, and Fee Status.
Search by Name, Student ID, or Mobile number.
Filter by Class and Surat locality.
1-click WhatsApp Parent button.
View & Download ID Card modal preview.
Export to CSV function.
🎨 Theme & Styling Verification
Theme & Colors: Royal Blue (#1E3A8A) as primary brand, crisp white backgrounds, and Vibrant Orange (#F59E0B / Amber) for all CTA buttons.
Typography: Google Font Poppins loaded across all headings and body copy.
Language Switcher: Global English and Gujarati (ગુજરાતી) switch located in the navbar and preserved across page transitions.
Responsive: Optimized for mobile phones, tablets, and wide desktop screens.
💻 How to Run & Verify

The server is currently running. You can open your browser and navigate to:

Home: http://localhost:3000
Courses: http://localhost:3000/courses
Admission System: http://localhost:3000/admission
Results & Gallery: http://localhost:3000/results
Contact: http://localhost:3000/contact
Admin Portal: http://localhost:3000/admin

To re-run the server manually:

bash
cd "C:\Users\Yasvi Savaliya\.gemini\antigravity\scratch\shreeji-tuition-surat"
npm run dev
change name 10 by 10
creat a readme file
creat a readme file

# LPU ONE — Unified Student & Admin Portal Prototype

**INT335 Design Thinking | Project P26: "One Student, Seven Portals"**  
**Institution:** Lovely Professional University (LPU), Phagwara, Punjab, India  
**Section:** K2P26NK | **Session:** 2026–27 | **Mentor:** Gagandeep Kaur  

---

## Overview
**LPU ONE** is a clickable, task-first web prototype that unifies LPU's fragmented digital platforms (**LPU UMS**, **LPU Touch**, **LPU Live**, and **My Class**) into a single responsive workspace—complete with a dedicated **Student vs. Admin Login Page** and live **Admin ↔ Student** synchronization requiring zero backend setup for usability testing.

## 5 Core Problems Solved
1. **Multiple Platform Dependency** — Single navigation sidebar, universal search bar (`/`), and UMS Quick Access Hub (Fee Dashboard, Edu-Revolution, Date Sheet, Hostel & RMS, My Class LMS, Attendance & Marks).
2. **UMS Login Loops** — Unified Single Sign-On (SSO) login page with **Student** (`12604821`) and **Admin / Faculty** (`EMP-20419`) role selection, one-click Passkey/Biometric sign-in, and a 30-day persistent session across all 4 portals.
3. **Teacher on Leave (+ Live Room-Change Sync)** — Auto-pulls faculty leave notices (`MTH165`, 10:00 AM) and room changes (`INT108` → `34-213`) from LPU Live and the Admin Console directly onto the Student Dashboard and Live Timetable with color-coded badges and instant push-alert controls.
4. **Missing Assignment Deadlines in LPU Touch** — Dedicated Pending Assignments & Deadlines view with exact due dates/times, urgency badges (`Today`, `Tomorrow`, `Upcoming`, `Submitted`), CA weightages, and an in-portal submission modal that updates pending counts live.
5. **Difficulty Finding Available Classrooms** — UMS-synced Free Classroom Finder across Blocks 32, 33, 34, and 38 with block, time-slot, and amenity filters plus live **Hold Seat / Check In** self-study tracking.

## Dual Portal Demo (Student & Admin)
- **Student Portal (`12604821` — Aarav Sharma, K2P26NK):** Dashboard, Live Timetable, Pending Assignments & Submission Modal, Free Classroom Finder, LPU Live Chat, and UMS Quick Hub.
- **Admin / Faculty Console (`EMP-20419` — Prof. Gagandeep Kaur):** Publish live faculty leaves or room changes, post new assignments, open/reserve classrooms, and resolve student RMS tickets—all synced immediately to the Student Portal.

## Usability Testing Walkthrough (4 End-to-End Tasks)
1. **Check Teacher Leave & Book a Free Room:** Sign in as Student, spot Dr. R. Sharma's cancelled 10:00 AM `MTH165` class, click **Find Free Room**, and hold a seat in a vacant classroom.
2. **Submit an Assignment Due Today:** Open **Assignments**, submit the `INT335` P26 prototype assignment due at 11:59 PM, and verify the live pending counter drops.
3. **Verify Room Change in LPU Live:** Open `K2P26NK - INT108` in **LPU Live Chat** to see the auto-synced room change (`34-109` → `34-213`) and send a reply.
4. **Test Admin ↔ Student Live Sync & Dual Theme:** Switch to **Admin View**, publish a room change or assignment, switch back to **Student View** to see it live, and toggle between **UMS Light Mode** and **LPU Live Dark Mode**.

## How to Deploy on GitHub Pages
1. Create a new **Public** repository on GitHub (e.g., `lpu-one`).
2. Upload both `index.html` and `README.md` to the repository root and click **Commit changes**.
3. Go to **Settings → Pages → Build and deployment**, set **Branch** to `main` and folder to `/ (root)`, then click **Save**.
4. Open your live prototype at `https://<your-username>.github.io/lpu-one/`.

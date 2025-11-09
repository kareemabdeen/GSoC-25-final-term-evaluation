# 🌍 Google Summer of Code 2025 — End Term Evaluation

## 🏛️ Project Details

**Project:** Monumento

**Idea:** Enhance Monumento's user experience with personalized itineraries, dynamic monument highlights, more social features, and full device responsiveness

**Project Size:** Large (350 Hours)

**Project Length:** 22 Weeks

**Mentor:** Aya Nady

---

## 👤 Personal Information

**Name:** Kareem Abdeen AbdelMaqsoud

**Country:** Egypt

**Email:** [Kareem.elshreef222@gmail.com](mailto:Kareem.elshreef222@gmail.com)

**Discord:** kareemabdeen_1

**GitHub:** [github.com/kareemabdeen](https://github.com/kareemabdeen)

---

## 🧠 Work Summary

* **38 PRs** merged across the repository
* **99+ commits** made
* **19,887+ lines added**, **6,012 lines removed**

---

## 🛠️ Key Tools & Technologies

* Flutter & Dart (Mobile Development)
* Gemini API (AI-based itinerary generation)
* OpenAI API (Chat assistant)
* Appwrite (BaaS backend)
* Flutter BLoC (State management)
* Figma (UI/UX Design)
* Clean Architecture (Domain, Data, Application, Presentation layers)
* Real-time data & pagination
* Image compression & upload optimization
* Community content moderation
* Database design & migrations
* Social media integration (Share functionality)

---

## 🚀 Transforming Monumento into a Dynamic, Community-Powered Platform

When I began my GSoC 2025 journey, **Monumento** was a static catalog of monuments.
Through 22 weeks of dedicated work, I transformed it into an **interactive, community-driven experience** with AI-powered itineraries, social networking, and real-time engagement.

---

## 🤖 AI-Powered Itinerary Generation (Gemini API)

One of Monumento’s flagship features — generates **personalized travel itineraries** based on user preferences.

**Highlights:**

* Preference-based input (budget, duration, interests)
* Day-by-day plans with activities, timings, and cost estimates
* Error handling and responsive UI

🎥 [Watch Demo](https://drive.google.com/file/d/13uP4K8FzaERB5crQBwfNXelx3SzZtL6q/view)

---

## 🏛️ Community Review Hub — Dynamic Monuments

A **community-driven review system** for monument validation.

**Key Components:**

* **Democratic Voting System:** Users upvote/downvote pending monuments
* **Trusted User System:** Users with 100+ points can instantly approve/reject
* **Submission Workflow:** Add monuments with multiple images and validation
* **Edit Suggestions:** Propose edits with explanations
* **Approval Indicators:** Real-time status, progress bars, and verification badges

🎥 [Watch Demo](#)

---

## 📸 Instagram-Style Stories Feature

A full **Stories system** similar to Instagram, enhancing social engagement.

**Highlights:**

* Full CRUD operations (Create, View, Delete)
* Horizontal carousel with time badges
* Auto-expiry after 24 hours
* Story viewer with progress bar, view count, and author info

🎥 [Watch Demo](#)

---

## 👥 Communities Feature — Social Networking Layer

Introduced **interest-based communities** for cultural discussions and engagement.

**Includes:**

* Community creation with image, name & description
* Join/leave functionality
* Dedicated community feeds
* Backend integration via Appwrite

🎥 [Watch Demo](https://drive.google.com/file/d/13uP4K8FzaERB5crQBwfNXelx3SzZtL6q/view)

---

## 💬 AI Chat Assistant for Monument Details

Developed an **AI assistant** integrated into monument pages.
Users can ask contextual questions (e.g., history, visiting hours, nearby attractions).

**Highlights:**

* OpenAI API integration
* BLoC-based clean architecture
* Intuitive chat UI with bubbles, loaders, and error handling

🎥 [Watch Demo](#)

---

## 📤 Itinerary Sharing Functionality

Implemented social **share functionality** for AI-generated itineraries using `share_plus`.

**Features:**

* Share trip details (title, duration, cost, daily breakdown)
* Works with all social platforms
* Improves collaborative trip planning

🎥 [Watch Demo](#)

---

## 🧩 Bug Fixes & Optimizations

Improved app stability, responsiveness, and performance.

**Key Fixes:**

* Optimized profile updates & lazy BLoC initialization
* Fixed navigation rebuild and login redirection
* Enhanced signup/login UI
* Resolved check-in & like/unlike issues
* Improved Appwrite data fetching and error handling

🎥 [Watch Summary](#)

---

## 🔧 PRs Merged Before Mid-Term Evaluation

| #        | Title                           | Description                                       |
| -------- | ------------------------------- | ------------------------------------------------- |
| **#185** | Remove unused assets            | Cleaned project assets for better maintainability |
| **#186** | Added flutter_gen package       | Type-safe asset management                        |
| **#189** | Fix scrolling issue in signup   | Improved form accessibility                       |
| **#192** | Firestore seeding script        | Automated monument data seeding                   |
| **#197** | Add device preview              | Enhanced responsiveness testing                   |
| **#209** | Add Local Experts header        | Improved section clarity                          |
| **#220** | Refactor Popular Monuments View | Improved structure and performance                |
| **#228** | BlocObserverLogger integration  | State management monitoring                       |
| **#238** | Generic AppBar component        | Unified app design                                |
| **#252** | Fix infinite loading in posts   | Handled empty post states                         |
| **#261** | Fix signup navigation           | Fixed rebuild issue                               |
| **#262** | Fix login redirect              | Proper home navigation                            |
| **#266** | Fix login UI                    | Improved mobile experience                        |
| **#267** | Optimize profile updates        | Reduced unnecessary API calls                     |
| **#281** | Migrate Firebase → Appwrite     | Major backend migration                           |
| **#284** | Fix phone call failures         | Re-enabled expert calls                           |
| **#293** | Optimize signup/login rebuilds  | Improved performance                              |
| **#298** | Hotfix after migration          | Resolved breaking issues                          |
| **#301** | Google Sign-In via Appwrite     | OAuth integration                                 |
| **#305** | Update Appwrite setup           | Updated configuration scripts                     |
| **#315** | Reset password logic            | Added email verification                          |
| **#319** | Fix popular monuments retrieval | Solved post-login issues                          |
| **#324** | Modularize service locator      | Improved DI structure                             |
| **#340** | Fix check-in functionality      | Working check-in system                           |
| **#362** | Fix like/unlike issue           | Stable interactions                               |
| **#372** | Redesign Discover Tab           | Modernized search UI                              |
| **#374** | Gemini Itinerary Generation     | Introduced AI itinerary system                    |

---

## 🧱 PRs Merged After Mid-Term Evaluation

| #        | Title                    | Description                         |
| -------- | ------------------------ | ----------------------------------- |
| **#375** | Community Management     | Added creation/join/leave system    |
| **#376** | Add Options Bottom Sheet | Choose between new post or AI trip  |
| **#377** | Itinerary Sharing        | Share trips using `share_plus`      |
| **#378** | Appwrite Fixes           | Solved fetching errors              |
| **#379** | AI Chat Assistant        | Added chat to monument details      |
| **#380** | Story Feature            | Full Instagram-like story system    |
| **#383** | Review Hub               | Democratic monument review & voting |

---

## 📊 Statistics Summary

| Metric                  | Count                      |
| ----------------------- | -------------------------- |
| **PRs Merged**          | 38+                         |
| **Commits**             | 99+                        |
| **Lines Added**         | 19,887+                    |
| **Lines Removed**       | 6,012+                      |
| **Major Features**      | 10+                        |
| **Bug Fixes**           | 20+                        |
| **Active Weeks**        | 22                         |

---
## Deliverables That Could Not Be Completed and Lie Out of Scope

While I successfully implemented all the planned features for Monumento during GSoC 2025, comprehensive unit testing coverage for all features could not be completed within the project timeline. However, I am committed to continuing this work and will be implementing comprehensive testing coverage as part of my ongoing maintenance and contribution to the project after the GSoC period ends.

---
## Future Work and Enhancements
While I accomplished all major goals of my GSoC project, there are exciting opportunities for future enhancements:

- Notification System: Implement push notifications for submission status updates, community activity, and story mentions
- Monument Editing: Allow original submitters to edit their monuments after submission
- Offline Support: Implement offline caching for monuments and itineraries
- Advanced Search: Add filters, sorting options, and saved searches
- Social Sharing: Enhance social media integration for stories and monuments

---

## 🙏 Acknowledgments

> I want to express my deepest gratitude to my mentors at **AOSSIE** for their incredible support and guidance throughout this journey.
> Thank you to **Google** for organizing Google Summer of Code and enabling developers to grow while contributing to open-source communities.

---

## 🏁 Conclusion

My GSoC 2025 experience with **Monumento** has been **transformative** — both technically and personally.
I helped evolve the app into a **vibrant, community-powered cultural platform** using clean architecture, real-time systems, and AI-powered intelligence.

> I’m committed to continuing my contributions to Monumento and mentoring new developers in the open-source community.

**Thank you for an unforgettable summer! 🎉🚀**

---

**Kareem Abdeen AbdelMaqsoud**

🎓 Computer Engineering Student
💻 Open Source Contributor
📱 Flutter Developer

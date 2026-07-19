# Jun Foong

### Software Developer — Mobile Engineering

📧 junfoong.work@gmail.com · 📱 +60 14 901 1539 · [LinkedIn](https://linkedin.com)

---

## Profile

Mobile engineer with 5 years of experience building enterprise React Native applications used by 100,000+ users across Google Play, the Apple App Store, and Huawei AppGallery, supporting multi-country deployments across Malaysia and Singapore. Specializes in mobile architecture modernization, offline-first data reliability, and on-device AI processing, including native Android/iOS integration and offline face-recognition and attendance systems. Known for driving continuous technical improvement — evaluating trade-offs, modernizing legacy codebases, and adopting the right technology for the problem rather than the familiar one.

---

## Experience

### Software Developer — AutoCount Sdn Bhd

*June 2021 – Present*

**Mobile Application Engineering & Architecture**

- Own end-to-end mobile engineering for enterprise apps with **100,000+ downloads** across Google Play, the Apple App Store, and Huawei AppGallery — from feature delivery to architecture, API integration, and performance.
- Modernized a legacy React Native codebase: migrated state management from Redux to Zustand and introduced TanStack Query for server-state caching and sync, cutting complexity and boosting app responsiveness.
- Extended React Native with native Android (migrated Java → Kotlin) and iOS (Swift) modules, including Turbo Native Modules and custom camera functionality, to unlock platform-specific capabilities beyond JS.
- Delivered core features for a multi-tenant application supporting both **Malaysia and Singapore**, handling country-specific business rules and compliance requirements.
- Shipped quick-response notification actions enabling one-tap approval or rejection of leave, claim, and attendance requests, backed by push notifications and background processing.
- Redesigned key user interfaces and kept dependencies continuously up to date, improving usability, performance, and long-term maintainability.

**Offline Attendance Engineering & Data Reliability**

- Designed and built offline attendance workflows enabling reliable clock-in/clock-out under limited or no network connectivity.
- Engineered a trusted offline-time mechanism by syncing server time with the device's monotonic clock at successful authentication, eliminating reliance on user-editable system time.
- Closed a device-clock manipulation loophole by deriving offline timestamps from the synchronized server reference instead of the OS clock.
- Handled edge cases such as device restarts before re-authentication by validating trusted-time availability and flagging attendance records as unreliable when it was missing.
- Used Realm Database for efficient local storage and offline data synchronization.

**Face Recognition & On-Device AI Processing**

- Built an offline, on-device face-verification system using FaceNet TensorFlow Lite models, generating face embeddings and scoring matches via Euclidean distance.
- Sped up face matching by implementing native Android multithreading, running comparison operations concurrently to cut response time.
- Improved recognition accuracy in low-light conditions and 2D-image edge cases, enabling reliable offline employee verification with **zero network dependency**.

**Backend Collaboration & API Optimization**

- Partnered with backend engineers to review API design and improve mobile-facing data flow.
- Identified duplicated logic and inefficient queries, proposing API restructuring that reduced unnecessary processing.
- Improved API performance by removing redundant subqueries, optimizing SQL joins, and cutting unnecessary database calls.
- Introduced Task-based parallel execution to improve asynchronous processing where applicable.

### Intern — AutoCount Sdn Bhd

*October 2019 – December 2019*

- Built mobile frontend features in React Native, including CRUD functionality for claim management modules.
- Designed reports using DevExtreme reporting tools.
- Worked alongside senior developers to learn enterprise software development workflows.

---

## Education

**Bachelor of Computer Science** — Universiti Tunku Abdul Rahman (UTAR)
May 2021 · CGPA 3.5891

---

## Technical Skills

`React Native` `JavaScript / TypeScript` `Android (Java, Kotlin)` `iOS (Swift)` `ASP.NET Web API` `SQL` `TensorFlow Lite`

## Languages

Mandarin · English · Cantonese · Malay

## Engineering Mindset

- Continuously evaluates existing solutions to improve system design, performance, and maintainability.
- Adapts quickly to new technologies and practices while balancing stability with business needs.
- Believes software quality compounds through iteration, refinement, and a willingness to adopt better solutions.
- Comfortable working across frontend, backend, and native mobile layers to solve cross-cutting engineering problems.

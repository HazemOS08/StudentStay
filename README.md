# StudentStay (Student Housing Platform)

StudentStay is a web-based housing platform that helps university students find temporary, short-term, and long-term student housing matches[cite: 5].

> **Status:** 🚧 **Under Development** — *This project is actively being built and refined.*

---

## Inspiration

University students seeking single-semester or co-op housing face an urgent, high-stress market crunch every term[cite: 6]. Today, students pay the price through wasted time on chaotic social media groups and financial losses from rigid 12-month commercial leases that ignore 4-month academic timelines[cite: 6]. Inspired by campus experiences across Montreal universities (like Concordia and McGill), StudentStay provides a safe, semester-aligned platform designed specifically for student sublets and co-op schedules[cite: 7, 8, 9].

---

## Features & Role-Based Workflows *(In Development)*

### User Authentication & Verified Profiles *(Under Construction)*
* **Role-Based Workflows:** Differentiates between students seeking housing vs. students/hosts listing housing.
* **Verified Community:** Verified student email verification to build trust and eliminate anonymous scam profiles common on social media[cite: 9, 11].

### Listing Creation & Academic Search *(Under Construction)*
* **Academic-Aligned Filtering:** Pre-built filters structured around academic terms (Fall, Winter, Summer) and co-op timelines, alongside flexible custom rental dates[cite: 1, 2, 7].
* **Listing Creation:** Custom listing forms allowing listers to upload room details, pricing, academic availability, amenities, and photos[cite: 1, 7].
* **Direct Inquiry System:** Integrated request-to-book and inquiry flow connecting seekers directly with listers[cite: 1, 7].

### Gamified Community & Point System *(Under Construction)*
* **Platform Point System:** Flexible payment and transaction options utilizing platform points or traditional currency[cite: 1, 9, 10].
* **Reputation Badges:** Point-earning system for trustworthy activity and optional promotional badges to highlight verified listings[cite: 10, 11, 12].

---

## Security & System Architecture

* **Deterministic Matching Engine:** Uses structured multi-parameter exact-match filters and date-range overlap logic rather than probabilistic AI to prioritize system stability and low latency[cite: 1, 7].
* **Data Integrity & Compliance:** Strict input validation and user privacy management compliant with local privacy frameworks (such as Quebec Law 25)[cite: 3, 12, 13].
* **Lightweight Node.js Backend:** Built using Node.js and Express for routing and server-side logic[cite: 4, 7, 13].

---

## Tech Stack

* **Front-end:** HTML5, CSS3 (Component Architecture & Flexbox Layouts), Vanilla JavaScript[cite: 4, 7, 13].
* **Back-end:** Node.js, Express.js[cite: 4, 7, 13].
* **Storage:** File-based JSON data layer (`fs/promises`) for managing users, listings, inquiries, and point balances[cite: 4, 7, 13].

---

## Getting Started & Local Setup

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/studentstay.git](https://github.com/YOUR_USERNAME/studentstay.git)

# SECV2113-HUMAN-COMPUTER-INTERACTION

# SECV2113-HUMAN-COMPUTER-INTERACTION

# 👥 Human-Computer Interaction (SECV2113) - Learning Portfolio & Project Reflection

Welcome to my portfolio for the **Human-Computer Interaction (HCI)** course.

---

## 📑 Overall Course Reflection

Human-Computer Interaction transformed how I perceive software architecture by shifting my focus entirely from backend functionality to the nuances of human behavior, cognitive load, and accessibility. Analyzing interactive platforms taught me that a system's success depends on intuitive navigation paths, clear behavioral triggers, and interfaces that respect user autonomy. By conducting rigorous task analyses, charting hierarchical workflows, and establishing targeted user personas, I learned how to translate abstract sustainability initiatives into practical, engaging digital environments. This course bridged the gap between engineering and empathy, proving that the best software is explicitly designed around the habits, frustrations, and needs of its actual users.

---

## 🛠️ Assignment & Project Reflection

### 🔹 [2023202402 Assignment 1- Persuasive Technology (Student).pdf] / [ASSIGNMENT 1.pdf]
* **Concepts Focused:** The Fogg Behavior Model (FBM), Gamification Architecture, Core Motivators (Hope vs. Fear), and Trigger Optimization.
* **Implementation Details:** Evaluated the language-learning application **Duolingo** as a mechanism for achieving *Sustainable Development Goal 4: Quality Education*. Analyzed its engagement ecosystem—specifically points, streaks, levels, and aggressive push notifications—against the three pillars of the FBM: motivation, ability, and triggers. 
* **Reflection:** This assignment highlighted the delicate line between user encouragement and notification fatigue. While gamification heavily boosts initial motivation, overbearing or poorly timed reminders can destroy user retention by causing friction. I realized that effective persuasive design must respect user autonomy through timing optimization, personalization, and explicit user-centered control panels.

### 🔹 [CI SECV2113 HCI 20232024-2.pdf] / [Assignment 2.pdf]
* **Concepts Focused:** User-Centered Design Principles, Interface Usability, and Interaction Consistency.
* **Implementation Details:** Reviewed general interface methodologies, structural layout frameworks, and interactive requirements necessary to deploy functional applications that effectively lower barriers to human execution.
* **Reflection:** Diving deep into standard interface evaluations taught me how critical visibility and consistency are to the user experience. Minimizing user error requires organizing software environments cleanly so that users do not have to guess their next navigational step.

### 🔹 [HCI PROJECT PART 2.pdf] - Establishing Requirements
* **Concepts Focused:** Hierarchical Task Analysis (HTA), Persona Development, Goal-Based Task Scenarios, and Design Requirement Inferences.
* **Implementation Details:** Conducted a comprehensive behavioral analysis comparing three sustainable fashion platforms (*refash.my*, *ClothingDonations.org*, and *Good on You*). Formulated structural HTA diagrams tracking three main tasks: selling unwanted clothes, entering zip codes to locate local donation centers, and auditing brand sustainability metrics.
* **Reflection:** Mapping out real-world user pathways via HTAs revealed that tiny variations in UI layout heavily impact efficiency. For example, forcing a user to scroll just to find a primary call-to-action button introduces immediate friction, proving that key features must always be immediately visible on the interface.

---

## 🚀 Final Group Project Architecture: "StyleSafari"

### 🎯 Sustainable Mission Alignment
* **Target Objective:** Designed **StyleSafari**, a mobile application platform mapping directly to *SDG 12: Responsible Consumption and Production*. 
* **Core Problem Solved:** Addressed high consumer clothing waste, low wardrobe utilization rates, the complexity of clothing disposal, and the friction users experience when searching for ethical fashion retailers.

### 👥 User Analysis & Requirement Extraction
To anchor the application's interface requirements in real user needs, our team built comprehensive target profiles and contextual test scenarios:

| Persona Profile | Core Goals & Desires | Primary Frustrations & Pain Points | Applied Task Scenario |
| :--- | :--- | :--- | :--- |
| **Alex (22)**<br>*Chemical Engineering Student* | Build a stylish, high-quality wardrobe on a strict, limited student budget. | High cost of new garments; structural quality issues in cheap clothing options. | **Task Scenario 1:** Needs to filter high-quality secondhand options within precise budget limits to plan spending without over-purchasing. |
| **Amanda (23)**<br>*Fashion Trend Enthusiast* | Regularly declutter wardrobe; support eco-friendly brands; locate donation facilities. | Difficulty finding sustainable clothing lines that match current, trendy aesthetics. | **Task Scenario 2:** Needs geographical location mapping for orphanages to donate older clothes, alongside an ethical style aggregator. |
| **Diana (20)**<br>*Geoinformatics Student* | Cycle out stacked clothing allocations; easily clear space for incoming trends. | Complex selling workflows; lack of transparency behind fast-fashion sustainability. | **Task Scenario 3:** Seeks nearby thrift stores to instantly monetize unwanted apparel via an easy, low-friction drop-off system. |

### 📋 Derived Software Design Requirements
By synthesizing our HTA research and persona pain points, we established three non-negotiable architectural mandates for the **StyleSafari** prototype:
1. **Zero-Scroll Primary Actions:** Based on our *Refash* task evaluations, the "Sell" button must remain permanently accessible on the main layout without requiring scrolling, complete with personalized preference inputs for rates and conditions.
2. **Simplified Location Ingest:** To satisfy the geographical tracking goals highlighted by our donation center analysis, we retained a clean, single-input zip code/GPS locator module to instantly map local orphanages, nursing homes, and thrift drop-offs.
3. **Persistent Global Search Engine:** To cater to users seeking varying depths of ethical information, we positioned a prominent search bar at the header layout to give users instant access to fashion brand sustainability ratings and eco-friendly alternatives.


# VERTEX — Stress & Workload Manager

👥 **Team:** Tan Wei Cheng, Teh Feng Yue, Teh Wen Wen, Woon Kai En

🎯 **Problem Statement:** Stress & Workload Manager

🎥 **Video Presentation:** [YouTube Link]

📊 **Presentation Slides:** https://www.canva.com/design/DAHUJUfqS9U/J8KHTdCVnPGB5UXsORckDQ/edit

---

# 1. 💡 Project Overview

## 1.1 The Problem

University students often manage multiple responsibilities at the same time, including:

* 📚 Academic work and assignments
* 💼 Part-time jobs
* 👥 Social commitments
* 🏠 Personal errands and responsibilities
* 🏃 Physical activities and exercise

While each responsibility may seem manageable individually, their **combined demands can become overwhelming**.

Most productivity tools focus on individual tasks, deadlines, or schedules, while wellness applications tend to focus primarily on stress and mental well-being. This means students often manage different aspects of their lives separately without understanding how they contribute to their **overall workload and available capacity**.

This can result in:

* Overcommitting
* Procrastination
* Poor prioritisation
* Lack of recovery time
* Failure to recognise early signs of overload

By the time students realise they are carrying too much, their workload and stress may have already reached an unhealthy level.

### The Core Problem

> **Students lack a simple way to understand, evaluate, and rebalance their overall workload before it leads to burnout.**

---

## 1.2 🎯 Target Users

**VertexLoad** is primarily designed for **university and college students** who manage multiple responsibilities alongside their studies.

### 👤 Typical Users

* 📚 **Full-time students** — Managing assignments, projects, presentations, and deadlines.
* 💼 **Working students** — Balancing part-time employment with academic responsibilities.
* 🏆 **Active students** — Participating in clubs, competitions, sports, and extracurricular activities.
* 👥 **Socially active students** — Managing events, outings, and commitments with friends or organisations.
* 🏠 **Students with personal responsibilities** — Handling errands, appointments, family responsibilities, and exercise.

### 💭 Typical User Scenario

A student may have several assignments due within the same week, work a part-time shift during the weekend, attend club activities, exercise regularly, and still need time for personal errands.

Individually, these commitments may seem manageable. However, **their combined workload may exceed the student's available capacity**.

VertexLoad helps students understand this overall load and determine whether they can realistically take on additional commitments.

### 🧩 User Needs

Users need a solution that can:

* Track different types of commitments in one place
* Recognise when their workload is becoming excessive
* Identify the areas contributing most to their overload
* Evaluate the impact of taking on new commitments
* Suggest ways to rebalance their workload
* Encourage appropriate recovery before prolonged overload leads to burnout

---

## 1.3 💡 Our Solution

**VertexLoad** is a **Stress & Workload Manager** designed to help students understand and manage the combined demands of their daily lives.

Instead of focusing only on individual tasks or stress levels, VertexLoad combines different types of commitments and analyses how they affect the student's **overall workload and capacity**.

### 🤖 Conversational AI

Users can enter commitments naturally through a conversational AI assistant instead of manually filling out multiple forms.

For example:

> *"I have an assignment due next Friday and I need to work for six hours this weekend."*

VertexLoad interprets the information, converts it into structured workload data, and updates the user's workload accordingly.

### 📊 Multi-Dimensional Workload Analysis

VertexLoad analyses workload across multiple dimensions:

* 🧠 Mental
* ⏰ Time
* 💪 Physical
* 👥 Social
* 🏠 Personal responsibilities

The system can then identify potential overload, simulate the impact of additional commitments, and recommend ways to rebalance the user's workload.

### 🔄 Our Approach

**Track → Analyse → Predict → Rebalance → Recover**

Through this approach, VertexLoad aims to help students **recognise overload before it develops into burnout** while providing practical recommendations for managing their commitments.

---

## 1.4 🚀 Core Features

VertexLoad consists of **seven core features** that work together to help students understand, manage, and rebalance their overall workload.

### 1. 🤖 Conversational AI Input

Users can describe their commitments naturally through conversational AI.

The system interprets the user's input and converts it into structured workload data for analysis.

**Purpose:**
Reduce input friction and allow users to record commitments quickly and naturally.

---

### 2. 📊 Personal Load Dashboard

Provides an overview of the user's workload across multiple areas:

* Mental
* Time
* Physical
* Social
* Personal errands

**Purpose:**
Help users understand which areas are contributing most to their overall workload and identify potential sources of overwhelm.

---

### 3. ⚠️ Overload Risk Score

Analyses the user's workload against their available capacity to estimate their current risk of becoming overloaded.

**Purpose:**
Alert users when their workload is approaching or exceeding their recommended capacity, allowing them to take action before the situation becomes unmanageable.

---

### 4. ⚖️ Load Balancer

Helps users determine which commitments should be:

* ✅ Completed
* ⏳ Delayed
* 📉 Reduced
* ➖ Treated as optional

when their workload becomes too high.

**Purpose:**
Help users actively rebalance their commitments rather than simply informing them that they are overloaded.

---

### 5. 🔮 "What If?" Simulator

Allows users to simulate the impact of a new commitment **before deciding whether to take it on**.

For example:

> *"What happens if I take on another 6-hour shift this weekend?"*

The system estimates how the additional commitment would affect the user's overall workload and risk level.

**Purpose:**
Help students make informed decisions about whether they can realistically accommodate additional commitments.

---

### 6. 🌱 Recovery Recommendations

Provides recovery suggestions when the user's workload becomes high.

Examples include:

* Taking appropriate breaks
* Getting sufficient sleep
* Exercising
* Spending time away from screens
* Reducing non-essential commitments

**Purpose:**
Encourage students to respond to overload with appropriate recovery rather than focusing solely on productivity.

---

### 7. 📈 Weekly Summary & Trends

Allows users to review changes in their workload over time and identify recurring patterns.

**Purpose:**
Help users recognise increasing workload trends and potential burnout patterns before they become a repeated cycle.

---

# 2. 🧠 Ideation & Process

## 2.1 💡 Ideas We Considered

During the ideation process, **Team Vertex** explored different approaches to addressing student burnout and workload management. We initially considered building a broader student well-being and productivity system before narrowing the concept around the specific problem of **understanding and managing overall workload**.

| Idea / Direction                     | Description                                                                                                                               | Decision                         | Reason                                                                                                                                                                     |
| ------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Stress & Workload Manager**        | A system that combines workload tracking, overload detection, workload rebalancing, and recovery support.                                 | ✅ **Selected**                   | Directly addresses the problem of students carrying multiple responsibilities without understanding their overall workload.                                                |
| **Quick Stress Check-In**            | Allows users to record their stress, energy, mood, and sleep quality to provide an indication of their current well-being.                | ❌ **Dropped**                    | Useful for understanding the user's condition, but it makes the system more focused on stress monitoring rather than actively managing workload.                           |
| **AI Personal Assistant**            | An AI assistant that analyses tasks, schedules, stress, and energy levels to provide personalised advice.                                 | 🔄 **Dropped / Refined**         | The concept was useful, but a general AI assistant was too broad. The AI was later refocused specifically on understanding and organising workload input.                  |
| **Personal Load Dashboard**          | Shows the user's overall workload across different areas such as mental, time, physical, social, and personal responsibilities.           | ✅ **Kept**                       | Provides users with a clear overview of how different responsibilities contribute to their overall workload.                                                               |
| **Overload Risk Analysis**           | Analyses workload and user information to identify when the user's workload may become excessive.                                         | ✅ **Kept**                       | Provides an early warning mechanism instead of only showing users their existing tasks.                                                                                    |
| **Load Balancer**                    | Suggests which commitments should be completed, delayed, reduced, or treated as optional when workload becomes too high.                  | ✅ **Kept**                       | Allows the system to actively help users respond to overload rather than simply identifying the problem.                                                                   |
| **"What If?" Simulator**             | Allows users to test how adding a new commitment would affect their overall workload.                                                     | ✅ **Kept**                       | Gives users a way to evaluate potential commitments before taking them on.                                                                                                 |
| **Recovery Recommendations**         | Suggests recovery activities when workload becomes high, such as taking breaks, sleeping, exercising, or spending time away from screens. | ✅ **Kept**                       | Extends the system beyond productivity and supports recovery from overload.                                                                                                |
| **Weekly Summary & Trends**          | Shows changes in workload over time and identifies recurring workload patterns.                                                           | ✅ **Kept**                       | Helps users recognise repeated periods of increasing workload and potential burnout patterns.                                                                              |
| **Conversational AI Workload Input** | Allows users to describe their commitments naturally instead of manually entering multiple fields.                                        | 🔄 **Refined from AI Assistant** | Mentor feedback highlighted the need to reduce input friction. The AI was therefore narrowed into a focused workload-input system rather than a general-purpose assistant. |

## 2.2 🧠 Ideation Boards

Our team used collaborative ideation to explore different approaches to student workload, stress management, and well-being. The brainstorming process helped us identify the key problems and features that eventually shaped VertexLoad.

<p align="center">
  <img src="https://github.com/user-attachments/assets/15b40ca2-1647-4c0b-ae59-2aa7e3bbafa5" width="900">
</p>

## 2.3 🧑‍🏫 Mentor Consultation

During the development process, Team Vertex consulted with mentors to validate our concept, improve the user experience, and identify areas where the project could be made more distinctive and practical.

| Date         | Mentor                   | Feedback No. | Feedback Received                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | What Was Changed                                                                                                       |
| ------------ | ------------------------ | -----------: | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| **3/9/2026** | **Stefan Khor Jia Quan** |        **1** | **Clarify the project’s selling point/value proposition**<br>• Clearly identify what makes the project different from existing solutions that solve the same problem.<br>• Since the problem space may contain many similar solutions, the project should have a clearer unique value proposition.<br>• Some particular functionality, workflow, or user experience should be emphasized to give the project a stronger competitive advantage.                                                           | • Refined the project’s value proposition around **overall workload management**.                                      |
| **3/9/2026** | **Stefan Khor Jia Quan** |        **2** | **Make the solution more interesting and distinctive**<br>• The current problem space may have many similar ideas, so the project should consider pursuing a unique user experience.<br>• Stefan highlighted our **“What If” Simulator** feature as worth looking at since it enables users to discover various scenarios instead of just getting the information and recommendations.<br>• The team should consider developing this feature further as one of the project’s key differentiators.        | • Further developed the **“What If?” Simulator** as one of VertexLoad’s key differentiating features.                  |
| **3/9/2026** | **Stefan Khor Jia Quan** |        **3** | **Design from the stressed user’s perspective**<br>• Consider the user’s actual mental state and situation when interacting with the application.<br>• Users experiencing stress may have limited attention and patience for multiple actions.<br>• Hence, the application needs to eliminate unnecessary interactions and deliver actionable information as fast as possible.<br>• The user flow should focus on answering: **“How does the application immediately help the user in this situation?”** | • Simplified the user flow to minimise unnecessary interactions and provide actionable information quickly.            |
| **3/9/2026** | **Stefan Khor Jia Quan** |        **4** | **Take into consideration the mobile-first interface approach**<br>• A mobile-first approach can help prioritise essential information and interactions.<br>• This also better reflects situations in which students might want to use the application quickly, everywhere and all the time.                                                                                                                                                                                                             | • Adopted a **mobile-first interface** to prioritise essential interactions.                                           |
| **3/9/2026** | **Daniel Koh Yu Hang**   |        **1** | **Define the project’s core focus**<br>• Clearly identify what the project is primarily trying to solve and how it benefits the user.<br>• The process of development must always stay true to solving the central problem and should not involve unnecessary functions.<br>• Each feature should be evaluated based on whether it meaningfully contributes to the core problem.                                                                                                                         | • Refined the project to focus specifically on **understanding and managing overall workload**.                        |
| **3/9/2026** | **Daniel Koh Yu Hang**   |        **2** | **Simplify the solution and make users eager to reuse it**<br>• Avoid overcomplicating the application.<br>• The user should easily understand the key functions of the program and be able to complete all necessary tasks.<br>• The program must offer something valuable for the user to come back again and again.                                                                                                                                                                                   | • Kept the interface and feature set focused on the **core user problem**.                                             |
| **3/9/2026** | **Daniel Koh Yu Hang**   |        **3** | **Use AI to reduce manual data input**<br>• Consider using AI-assisted data extraction to reduce the amount of information users need to enter manually.<br>• For example, AI could extract relevant information from user-provided text and convert it into structured data for the system.<br>• This can reduce friction and improve the overall input experience.                                                                                                                                     | • Implemented **Conversational AI Workload Input** to reduce manual data entry.                                        |
| **3/9/2026** | **Daniel Koh Yu Hang**   |        **4** | **Improve AI transparency**<br>• If AI is used to generate recommendations or predictions, the application must provide an adequate explanation for the result.<br>• Relevant extracted information, assumptions, or factors should be shown where appropriate.<br>• This can improve user understanding and trust in the AI-generated output.                                                                                                                                                           | • Added greater transparency by showing relevant **workload factors** behind AI-generated results and recommendations. |
| **3/9/2026** | **Daniel Koh Yu Hang**   |        **5** | **Implement in mobile size**<br>• Similar to Stefan’s feedback, the prototype should adopt a mobile-first approach.<br>• This would allow the team to concentrate on the most significant interactions within the application.                                                                                                                                                                                                                                                                           | • Developed the prototype using a **mobile-first design**.                                                             |

---

# 3. 🎨 Design & Prototype

## Key Screens

### 1. 👤 Persona Onboarding

*Setting the user's weekly plan*

<p align="center">
  <img src="https://github.com/user-attachments/assets/f64472a6-c1f1-4410-a368-c138089a0695" width="280">
</p>

---

### 2. 📅 Calendar Sync & NLP Input

*Adding commitments through natural language input*

<p align="center">
  <img src="https://github.com/user-attachments/assets/fad4dc2e-0439-4655-a9a5-044d5f71e219" width="280">
</p>

---

### 3. 🔮 Preview Impact Before Adding

*See how a new commitment affects the user's workload*

<p align="center">
  <img src="https://github.com/user-attachments/assets/3641755b-a25d-477f-8ac0-e59b59341ad4" width="280">
</p>

---

### 4. 💬 Response Helper

*AI-assisted responses and workload guidance*

<p align="center">
  <img src="https://github.com/user-attachments/assets/ab98fac6-6dbb-4203-b683-d6d77052758a" width="280">
</p>

---

### 5. ⚠️ Too Busy Alert

*Alerts users when their workload becomes excessive*

<p align="center">
  <img src="https://github.com/user-attachments/assets/b7d09469-63c8-4a3b-b87b-e8c4b37b82fb" width="280">
</p>

---

### 6. 🌱 Break Time Intervention

*Encourages users to take appropriate recovery breaks*

<p align="center">
  <img src="https://github.com/user-attachments/assets/23f332c8-bf23-40ab-9e5e-2c7890ba5191" width="280">
</p>

---

# 4. 🚀 What Makes It Different

## Novel Features
## Differentiation

---

# 5. 🤖 Technical Architecture & Feasibility

## Tech Stack
## System Architecture
## Build Plan & Scope

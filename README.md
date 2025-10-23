# e-Portfolio Presentation: Jira & The Zombie Survival Project

**Author:** Petra Namuyiga
**Topic:** Jira (Project Management Tool)
**Presentation Date:** 30.10

## 1. Overview

This tutorial serves as a stand-alone guide for my e-Portfolio presentation on Jira. It explains how to use Jira for Agile project management, even if you missed the live, interactive demo.

Instead of a boring business example, we used a high-stakes scenario:

**The Zombie Apocalypse has begun. We are a team of survivors trapped in a classroom. We must use Jira to organize our survival.**

This guide will walk you through the core concepts we demonstrated, from setting up the plan to tracking our progress as we "survived" our first 24 hours.

## 2. Core Concepts Demonstrated

Our demo showcased the following key features of Jira:

* **Projects:** The central hub for all our work.
* **Epics:** The large-scale goals (e.g., "Scavenge for Supplies").
* **Backlog:** The complete to-do list for our entire project.
* **Issue Types (Stories & Bugs):**
    * **Story:** A task our survivors need to do (e.g., "Barricade the doors").
    * **Bug:** A problem that's blocking us (e.g., "Vending machine is locked").
* **Story Points (Estimation):** How we estimate the "effort" of a task (e.g., "Barricade doors" is a 5, "Find first-aid kit" is a 2).
* **Labels:** Tags for filtering and organizing (e.g., `security`, `supplies`).
* **Sprints:** A short, fixed period of time to complete a set amount of work (our demo used a "24-hour" sprint).
* **Active Sprint Board:** A visual "Kanban-style" board showing what's `To Do`, `In Progress`, and `Done`.
* **Collaboration (Comments & @mentions):** How the team communicates *inside* Jira to solve problems.
* **Sprint Reports (Burndown Chart):** The all-important graph that shows our progress and whether we are on schedule.

## 3. The "Zombie Survival Project" Setup

To understand the demo, here was our starting setup:

* **Project Name:** `Zombie Survival Project` (A Team-Managed Scrum Project)
* **Our Big Goals (Epics):**
    * `[ZSP-1] Secure the Classroom`
    * `[ZSP-2] Scavenge for Supplies`
    * `[ZSP-3] Establish Contact`
* **Our "To-Do" List (The Backlog):**
    * **Story:** "As a survivor, I want to barricade the doors..." (Story Points: 5, Label: `security`)
    * **Story:** "As a survivor, I want to board up the windows..." (Story Points: 3, Label: `security`)
    * **Story:** "As a survivor, I need to scavenge for food..." (Story Points: 3, Label: `supplies`)
    * **Story:** "As a survivor, I need to find a first-aid kit..." (Story Points: 2, Label: `supplies`)
    * **Bug:** "Vending machine is locked" (Label: `blocker`)

---

## 4. Tutorial: How We "Survived" (The Demo Walkthrough)

This is a step-by-step guide to what we did in the live demo.

### Step 1: Planned Our "First 24 Hours" (Sprint Planning)

We couldn't do everything at once. We had to prioritize.

1.  **View the `Backlog`:** We looked at our full list of tasks.
2.  **Create a Sprint:** We created `Sprint 1`, our plan for the next 24 hours.
3.  **Drag-and-Drop:** We dragged our *most urgent* tasks from the Backlog into `Sprint 1`:
    * `Barricade the doors` (5 pts)
    * `Scavenge for food` (3 pts)
    * The `Vending machine is locked` bug
4.  **Start the Sprint:** We clicked the "Start Sprint" button to begin our work. This automatically took us to the `Active Sprint Board`.

### Step 2: Worked the Plan (The `Active Sprint Board`)

This board is our command center. It shows what we are all working on *right now*.

1.  **"In Progress":** To show we were starting a task, our "Survival Squad" volunteer dragged the `Barricade the doors` card from the `To Do` column to the `In Progress` column. The whole class saw this update live.
2.  **"Done":** Once the task was finished, the card was moved to the `Done` column.

### Step 3: Handled a Problem (The Bug)

During our demo, we pretended our "Scavenge for food" task was blocked by the "Vending machine is locked" bug.

1.  **Open the Bug:** We clicked on the bug to see the details.
2.  **Collaborate in Comments:** Instead of sending an email, we used the **Comments** section at the bottom of the bug.
3.  **Use `@mention`:** We typed: "This is a blocker! `@Volunteer-Name`, can you find a crowbar?"
4.  **Live Update:** The class saw our volunteer (on their own laptop) reply in the comments: "Found one! I'm on my way."

This showed how Jira keeps all communication about a task *with* the task.

### Step 4: Finished the Sprint (The `Sprint Report`)

After 24 hours (or, in our demo, 25 minutes), our sprint was over.

1.  **Complete Sprint:** We clicked the "Complete Sprint" button.
2.  **View Report:** Jira instantly took us to the **Sprint Report** page.

This is the most "advanced" and important part. The report showed us two key things:
* A summary of work "Completed" vs. "Not Completed."
* The **Burndown Chart**.

### Step 5: Read the `Burndown Chart`

This graph is the main way a team knows if it's on schedule.

* **The Gray Line:** This was our *ideal plan*, showing a steady "burn" of story points from 8 down to 0.
* **The Red Line:** This was our *actual* progress. We saw it drop from 8 to 3 when we moved the "Barricade" (5 pts) task to `Done`.

This chart visualizes our progress against our plan, which is the entire point of Agile project management.

## 5. Key Takeaways

1.  **Jira is a Visual Tool:** It turns a list of tasks into a visual, interactive board.
2.  **It's Built for Collaboration:** Features like `@mentions` and comments keep the whole team in sync without emails.
3.  **It's Data-Driven:** Jira isn't just a to-do list. It uses Story Points to track effort and builds reports like the Burndown Chart to show you *exactly* how your project is progressing.

# 📚 StudySync AI — Smart Academic Task & Prompt Planner

> *Live Application URL:* [https://studysync-ai.vercel.app](https://studysync-ai.vercel.app)

---

## 📌 Problem & Purpose
* *The Problem:* University students often struggle to break down complex project requirements and tight deadlines into manageable micro-tasks, leading to last-minute rush and confusion.
* *Target Audience:* University students, researchers, and self-learners managing multiple deadlines.
* *The Solution:* StudySync AI ingests course names, assignment requirements, and remaining time limits to generate structured action plans, time estimates, and custom AI execution prompts.

---

## ✨ Key Features
- *Smart Task Decomposition:* Automatically breaks complex tasks into step-by-step milestones.
- *Time-Aware Allocations:* Tailors task breakdowns according to remaining available hours.
- *Custom AI Prompt Generation:* Generates execution prompts tailored specifically to the task at hand.
- *Responsive UI:* Clean, modern interface designed with Tailwind CSS.

---

## 🤖 AI Feature & System Prompt

### How It Works
The application acts as an academic execution strategist. It evaluates task complexity against student-provided time constraints and generates structured sub-tasks and AI execution prompts.

### System Prompt Blueprint
```text
You are "StudySync AI", an elite academic task breakdown assistant designed specifically for university students. 

Your Task:
1. Accept the student's task description, deadline, and target subject.
2. Break down the task into actionable step-by-step sub-tasks with estimated time allocations.
3. Provide a specialized AI prompt that the student can use to research or generate content for this specific task.
4. Keep the tone encouraging, concise, and highly structured.

Output Format:
- 🎯 Action Plan (Step-by-step with hours)
- 💡 Pro-Tip for Execution
- 🤖 Specialized Prompt to Copy-Paste

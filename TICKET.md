# Hands-On Exercise: Build Your Personal AI Tutor for a College Course

## Objective

This exercise guides you through building a complete Claude Project for one of your current college courses. You'll integrate your textbook and course materials, set up Instructions for personalized tutoring, and establish a progress tracking system that makes AI remember your learning journey.

**Prerequisite:** Complete the tutorial *[Master Any College Course with Claude Project](https://github.com/easyscalecloud/learn_claude_ai_problem_solving_general-project/tree/05-Master-Any-College-Course/)* before starting.

---

## How-to Guide

### Step 1: Choose Your Course and Gather Materials

Pick one course you're currently taking. Gather:
- Your textbook (PDF format)
- Lecture notes or slides
- Assignment descriptions
- Any reference materials or past exams

### Step 2: Prepare Your Textbook

1. **Split the textbook by chapter** using one of these methods:
   - Mac Preview: View → Thumbnails, select pages, File → Export as PDF
   - Online: ilovepdf.com "Split PDF" function
   - Or ask Claude to write a script for you

2. **Compress if needed**: Use ilovepdf.com or smallpdf.com to reduce file size

3. **Organize file names**: Use clear, descriptive names like `textbook-ch01-vectors.pdf`

### Step 3: Create Your Claude Project

1. Go to [Claude.ai](https://claude.ai) and create a new **Project**
2. Give it a clear name (e.g., "Linear Algebra - Fall 2024")
3. Upload all your prepared files using the **"+"** button in the Files area

### Step 4: Create a Materials Index

1. Start a new conversation in your Project
2. List all your uploaded file names and ask Claude:
   > "Create an index document for these files. For each file, write 2-3 sentences describing what it contains and when it would be useful."
3. Click **"Add to Project"** on the generated Artifact

### Step 5: Write Your Instructions

Ask Claude to help you draft Instructions, then customize:

> "Help me write Instructions for this Project. This AI should be a learning tutor for [course name]. It should:
> - Help me understand concepts, not just give answers
> - Adjust explanations based on my understanding level
> - Check the materials index when I ask about specific topics
> - Read progress.md at the start of each conversation
> - Generate updated progress.md when I say 'ending session'"

Paste the final version into the Instructions area.

### Step 6: Create a Requirements Document for Current Assignment

1. Upload or paste your current assignment description
2. Ask Claude:
   > "Help me create a requirements document for this assignment. Include: what it's actually asking, which concepts are involved, relevant files from our Knowledge Base, and where the key challenges might be."
3. Add the generated Artifact to Project

### Step 7: Have Your First Learning Session

1. Start a new conversation
2. Begin with something like: "Let's study [topic]. Start by checking progress.md, then help me understand [specific concept]."
3. Engage in back-and-forth learning for at least 15-20 minutes
4. When finished, say "ending session" and let Claude generate progress.md
5. Add the progress.md Artifact to Project

### Step 8: Create Your First Personal Note

1. When you truly understand a concept, ask Claude:
   > "Help me write this understanding as a note in my own words, using the examples we just discussed."
2. Add the note Artifact to Project

**Estimated time: 60-90 minutes**

---

## Checklist

### Part 1: Material Preparation
- [X] **Chose a course** — Selected one current course to build the Project for
- [X] **Split textbook** — Divided into chapter-sized files (60-100 pages each)
- [X] **Compressed files** — Reduced file sizes if needed
- [X] **Organized file names** — All files have clear, descriptive names

### Part 2: Project Setup
- [ ] **Created Claude Project** — With a clear course name
- [ ] **Uploaded all materials** — Textbook chapters, lecture notes, assignments, references
- [ ] **Created materials index** — Index document Added to Project
- [ ] **Wrote Instructions** — Including role, index usage, and progress.md rules

### Part 3: Assignment Context
- [ ] **Created requirements document** — For current assignment, Added to Project

### Part 4: Learning Session
- [ ] **Completed first learning conversation** — At least 15-20 minutes of engaged study
- [ ] **Verified AI reads materials** — AI can reference textbook content in explanations
- [ ] **Generated progress.md** — First progress file Added to Project
- [ ] **Created personal note** — At least one understanding note Added to Project

### Part 5: Submission
- [ ] **Share your Project** — Click Share → Create share link (Read-only)
- [ ] **Submit link to instructor** — Exercise complete

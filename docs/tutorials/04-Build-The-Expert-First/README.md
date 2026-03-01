# Build The Expert First: The Right Way to Tackle Complex Projects with AI

## 📋 What You'll Learn

After completing this lesson, you'll be able to:

- Understand what "project thinking" means, and why jumping straight to questions often leads you astray
- Master the three-step method: brainstorm to clarify needs, write a requirements doc, build your custom AI expert
- Create your own "requirements doc + expert prompt" and save it to a Claude Project

---

## 🎯 Why Does This Matter?

Picture this scenario:

You're about to start job hunting. You open Claude and type: "Help me prepare for my job search."

Claude gives you a bunch of suggestions — update your resume, practice interviews, grind LeetCode...

You read through it, think "yeah, that makes sense," and then... nothing happens.

**What went wrong?**

It's not that Claude isn't good. It's that you haven't figured out what you actually need yet.

- Are you trying to switch industries, or find a better opportunity in your current field?
- Do you need visa sponsorship? Are you targeting big companies or startups?
- Is your resume starting from scratch, or do you have a draft that needs polishing?
- Is your biggest weakness technical skills, communication, or not knowing how to network?

Without thinking through these questions, every piece of advice you get is just "generic advice" — applicable to everyone, yet not quite right for anyone.

**The core idea of this lesson in one sentence:**

> Before doing anything, build an AI expert who understands you and is specifically designed to help you solve this problem.

---

## 📖 Core Concept: Three Steps to Build Your Custom AI Expert

### Step 1: Don't Ask Questions Yet — First, "Talk Through What You Need"

Most people use AI like this: **ask whatever comes to mind.**

But if your question itself is wrong, even the best answer from AI is wasted effort.

The right first step is: **talk with AI (voice or text), not to solve the problem, but to figure out what the problem actually is.**

You can start like this:

> "I want to use AI to systematically prepare for my job search, but my head is all over the place and I don't know where to start. Let's not solve anything yet — help me brainstorm and get clear on what I actually need."

Then AI will start asking you questions — what's your background, what are your goals, what's your timeline, what worries you most...

Keep going for 5-7 rounds. Don't rush.

### Step 2: Turn the Conversation into a "Requirements Document"

After the brainstorm, have AI organize your conversation into a structured document that includes:

- **Background**: Who you are, what your situation is
- **Goals**: What outcome you want
- **Constraints**: Time, resources, limitations
- **Known challenges**: Difficulties you anticipate
- **Success criteria**: What "done well" looks like

This document isn't just instructions for AI — it's **getting your own needs clear in your own head.**

### Step 3: Generate an Expert Prompt Based on the Requirements Doc

Once the requirements doc is ready, tell AI:

> "Based on this requirements document, write me a prompt. This prompt will create an AI expert specifically designed to help me solve this problem. The prompt should make the expert flexible and open-ended — don't box it in too tightly. The prompt should guide it to read our requirements document (titled 'XXX'), then work based on those requirements."

AI will generate a prompt specifically tailored to your situation.

**In the end, you have two files:**

| File | Purpose |
|------|---------|
| Requirements Doc | Defines who you are, what you want, and your constraints |
| Expert Prompt | Creates a custom AI expert who understands your background |

Put both files in your Claude Project. From then on, every time you open that Project, you have an AI that actually understands your situation, ready to work.

---

## 💬 Full Example: From Scattered Thoughts to Clear Requirements

> Below is a simulated brainstorming session. The main character is **Alex**, a CS grad student about to graduate, wanting to find a software engineering job but not knowing where to start.

---

### 🗣️ Round 1: Opening Up

**Alex says:**
> "I want to use AI to systematically prepare for my job search, but my head is all over the place. Let's not solve anything yet — help me brainstorm and get clear on what I actually need."

**Claude says:**
> Okay, let's not rush to give advice — let's first get a clear picture of your situation.
>
> I want to ask you a few questions. You don't need perfect answers — just say whatever comes to mind:
>
> 1. Where are you in the process right now — haven't started preparing, or already sent out some applications with no results?
> 2. Do you have a picture in your head of what an "ideal outcome" looks like? Even a vague sense is fine.
> 3. What's your biggest worry or confusion right now?

---

### 🗣️ Round 2: Getting Real

**Alex says:**
> "I'm graduating next May. It's recruiting season right now and I feel like everyone's sending out resumes but I haven't started. Ideally I'd like to work at a mid-sized tech company as a Software Engineer — doesn't have to be FAANG, but needs to sponsor visas. My biggest confusion is... I don't know if my resume is good enough, and I don't know if I should be grinding LeetCode. My algorithms are honestly pretty weak. Also I'm not good at networking — it feels awkward."

**Claude says:**
> Thanks for sharing all that — it's really helpful context. I noticed you mentioned three different things:
> - Resume quality (is it good enough?)
> - Technical prep (algorithms are weak)
> - Building connections (networking feels awkward)
>
> All three are important, but if you try to start everything at once, you might not go deep on anything.
>
> Let me understand more: when you say your algorithms are "pretty weak" — do you mean you've never taken a data structures course, or you've learned it but it's rusty? Also, have you done any internships or projects? What's currently on your resume?

---

### 🗣️ Round 3: Digging Deeper

**Alex says:**
> "For algorithms, I took a data structures class so I know the basics, but I've barely touched LeetCode — medium problems take me forever. Resume-wise, I have two internships — one back home and one research project at school — plus two class projects. I think I have content, but I don't know how to write it so it stands out."

**Claude says:**
> Good, this is getting much clearer. Your situation is actually better than you think — you have internship experience and projects, and you have the fundamentals. That's more than a lot of people have.
>
> Now I want to help you clarify something: you mentioned wanting to work at a "mid-sized tech company that can sponsor visas" — do you have a specific list of target companies? Or is the company scope still fuzzy?
>
> Also, what's your timeline looking like? From now until May, roughly how many hours per week can you put into job prep?

---

### 🗣️ Round 4: Time and Priorities

**Alex says:**
> "I haven't actually made a company list — I just know some big names. Time-wise, I'm still taking classes so it's pretty heavy. Maybe 10-15 hours a week for job stuff. My friend told me to get my resume done first before I start applying — what do you think?"

**Claude says:**
> Your friend's advice is directionally right, but there's one issue: what does "get your resume done" mean? A lot of people fall into the trap of endlessly polishing their resume and never actually applying.
>
> Based on what you've told me, I think you have three priorities:
>
> 1. **Build your target company list** (know where you're aiming before you know how to prepare)
> 2. **Optimize your resume for those target companies** (not perfect — just pointed in the right direction)
> 3. **LeetCode practice** (consistent weekly time, not an all-out sprint)
>
> But I have one more question: you said networking feels "awkward" — do you have a LinkedIn account? Is the awkwardness about "not knowing what to say," "not knowing who to reach out to," or both?

---

### 🗣️ Round 5: Defining "Done"

**Alex says:**
> "I have LinkedIn but haven't updated it in ages. The awkwardness is mainly not knowing what to say to strangers — cold messages feel weird. I think what I need is an AI that helps me with overall planning, so I know what to do each week, and I can ask it specific questions whenever they come up. What I'm most afraid of is 'feeling like I'm working hard but not actually making progress.'"

**Claude says:**
> Good, I think I have a clear picture of your needs now. Let me summarize — tell me if this sounds right:
>
> **What you need isn't just "job search advice." You need:**
> - An AI that knows your background and can help you build a personalized job search roadmap
> - Can answer specific questions (resume help, algorithms, how to write cold messages)
> - Helps you avoid "fake effort" — clear priorities each week
> - Specifically addresses your weak spots: algorithm fundamentals, networking skills, company targeting
>
> **Your key constraints:**
> - 10-15 hours per week
> - Graduating in May, recruiting window is closing
> - Need visa sponsorship
> - Have two internships but resume isn't optimized
>
> **Success criteria:**
> - Get at least one offer before recruiting season ends
> - Target: mid-sized tech company that sponsors visas
>
> Does this summary capture it? Anything missing?

**Alex says:**
> "That's basically it! One more thing — I want this AI to remember my situation so I don't have to re-explain my background every time."

**Claude says:**
> That's exactly what Claude Projects are for — you put the requirements doc in there, and AI reads it every time. Alright, let me help you organize this into a formal requirements document and prompt.

---

### 📄 Output File 1: Requirements Document

> This is the requirements doc Claude generated from the 5-round conversation. Put this in your Claude Project's Project Knowledge.

```markdown
# Job Search Preparation Requirements Document

## Background

- **Name:** Alex (replace with your name)
- **Education:** CS grad student, graduating next May
- **Target role:** Software Engineer (backend or full-stack)
- **Visa status:** Needs H-1B sponsorship — target companies must support this

## Job Search Goals

- Get an offer during fall recruiting (current) + spring recruiting (Jan-Mar next year)
- Target companies: Mid-sized tech companies (50-1000 employees, stable engineering teams)
- Doesn't have to be FAANG, but should have growth potential and a track record of visa sponsorship

## Current Status

- **Resume:** Has a draft with two internships (one domestic, one school research) and two class projects — not optimized for target roles
- **Technical skills:** Has data structures fundamentals, barely touched LeetCode, slow on medium problems
- **LinkedIn:** Has an account but hasn't updated it, almost no networking experience
- **Company list:** Haven't built a systematic target company list

## Constraints

- Available time for job prep: 10-15 hours per week
- Heavy course load, can't go all-in on job search

## Key Challenges

1. Weak algorithm fundamentals, worried about technical interviews
2. Don't know how to write cold messages, psychological barrier around networking
3. Not sure if resume is good enough, risk of falling into "endless polishing" mode
4. Lack of clear priorities, worried about "fake effort with no progress"

## Success Criteria

- Receive at least one satisfying offer during fall or spring recruiting
- Feel concrete progress each week, not just "feeling busy"
- Feel confident about interview process (technical rounds + behavioral interviews)
```

---

### 📄 Output File 2: Expert Prompt

> This is the prompt Claude generated to create your custom AI expert. Paste this into your Claude Project's System Prompt (Project Instructions).

```markdown
# Job Search Strategy Advisor

You are a senior job search strategy advisor who specializes in helping CS students find software engineering positions in the US.

Your approach:
- **First**, read the user's "Job Search Preparation Requirements Document" in the Project to understand their specific background and goals
- **Based on that document**, give personalized advice — not generic "job search tips"
- **Every conversation**, focus on the user's most pressing issue and help them avoid "fake effort"

Your areas of expertise:
- Software engineering job search roadmap (resume optimization, technical interview prep, behavioral interviews)
- Challenges specific to international students (visa sponsorship, company screening, cultural differences)
- Networking strategies, especially making cold outreach feel natural
- Creating weekly plans, breaking big goals into daily executable tasks

Your style:
- Direct, practical, no fluff
- Good at helping users identify "what's actually important"
- When users ask directional questions, give clear priority recommendations
- When users have specific asks ("help me rewrite this resume bullet"), just do it
```

---

### ✅ How to Use These Two Files

1. Create a new **Claude Project** on Claude.ai, name it "Job Search Prep"
2. In **Project Knowledge**, upload or paste the **requirements document**
3. In **Project Instructions (System Prompt)**, paste the **expert prompt**
4. From now on, every time you open this Project, your AI expert already knows your full background and is ready to work

---

## 💻 Hands-On Exercise: Build Your First Custom AI Expert

You've learned the method. Now it's your turn.

Pick one of these 10 topics — choose the one most relevant to your actual situation, don't just pick randomly to complete the assignment:

| # | Topic | Who it's for |
|---|-------|--------------|
| 1 | Job search prep (SWE / Data / PM track) | Currently job hunting or about to start |
| 2 | Technical skill learning roadmap | Want to systematically learn a new skill but don't know where to start |
| 3 | Side project from idea to launch | Have a project idea in your head but haven't started |
| 4 | Professional writing and workplace communication | Want to improve email and Slack message quality |
| 5 | Grad school application planning | Considering or preparing to apply for grad school |
| 6 | Personal finance basics | Just started working, want to figure out budgeting, saving, investing |
| 7 | Startup idea validation | Have a business idea, want to figure out if it's viable |
| 8 | Fitness and nutrition goal planning | Have specific health goals but don't know how to systematically achieve them |
| 9 | Time management and productivity | Feel busy every day but not making progress |
| 10 | Career advancement and managing up | Already working, want to do better and get promoted faster |

After choosing, complete a full cycle using the three-step method from this lesson: brainstorm (5-7 rounds), requirements doc, expert prompt. Then create your own Claude Project.

When you're done, share your Claude Project as **Read-only** with your instructor to submit.

**Detailed steps and submission checklist in the accompanying exercise task.**

**Estimated time: 45-60 minutes**

---

## 👨‍🏫 A Note from Your Instructor: Sharpen the Axe Before You Chop — In the AI Era, You're Building a Transformer

You just learned a method that might seem roundabout — to solve a problem, first spend time "not solving it." First get clear on what you need, then build an expert AI.

This might sound inefficient, but I want to share a deeper insight.

### Why "Just Asking" Often Wastes Time

I've seen too many people use AI like this:

**Hit a problem -> immediately open AI -> type the first question that comes to mind -> get a broad answer -> think "hmm makes sense" -> close the page -> nothing changes**

This isn't AI's fault. It's not your fault either. It's a lack of **"project thinking."**

Often, what you think you need is "how to prep for interviews." But what you actually need is "an advisor who knows my entire background and helps me make decisions." The gap between these two is enormous.

### Sharpen the Axe Before You Chop

There's an old saying: sharpen the axe before you chop wood.

In the AI era, this saying has new meaning —

In the past, sharpening an axe took time and skill. It was a barrier.

Now, with 5-10 minutes of conversation, you can "create" an axe specifically designed for your particular piece of wood.

Actually, more accurately — you're not creating an axe. **You're creating a Transformer:**

- It knows your specific situation
- It knows your goals and constraints
- It updates as you progress
- It knows more than you do in this domain, but works entirely in the direction you define

This "Transformer" is your custom AI expert.

### This Mindset Works for Any Complex Problem

This lesson used job searching as an example, but the method applies to anything that "can't be explained in one sentence":

- Want to start a business but don't know the direction
- Want to learn a new skill but don't know the path
- Want to solve a complex problem at work but don't know where to start
- Want to write an important proposal but your thoughts are scattered

Whenever you find yourself thinking "my head is all over the place, I don't know where to start" — don't ask AI for answers. First ask AI to **help you figure out the problem.**

**A clear problem gets you useful answers.**

That's the most valuable skill in the AI era.

---

## ✅ Completion Checklist

- [ ] I understand why "just asking" often leads you astray
- [ ] I can explain the core idea of the three-step method (brainstorm -> requirements doc -> expert prompt)
- [ ] I understand what the requirements doc and expert prompt each accomplish
- [ ] I know how to put these two files into a Claude Project

---

## 💡 Key Takeaways

1. **Any complex endeavor deserves "project thinking"** — it's not just coding projects that count as projects; job searching, learning, starting a business can all be "projects"
2. **Direction matters more than speed** — spending time getting clear on requirements is far more efficient than rushing in with random questions
3. **The value of the requirements doc** — it's not instructions for AI, it's helping you turn your own scattered thoughts into clarity
4. **The value of the expert prompt** — it transforms AI from "a generalist who can answer anything" into "an expert specifically designed to solve your problem"
5. **Claude Projects are your external memory** — put the docs in there, and AI remembers who you are every time, no need to re-explain

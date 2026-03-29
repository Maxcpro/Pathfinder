# Pathfinder MVP Pitch Brief

## 1. One-Line Pitch

Pathfinder is a personalized academic orientation platform that helps students move from uncertainty to clarity by translating their interests, strengths, and decision patterns into concrete academic pathways.

## 2. The Core Problem

Students are expected to make high-stakes academic choices early, often before they understand:

- what they are good at
- what they are naturally drawn to
- how those traits connect to majors, careers, and campus opportunities

Traditional orientation experiences are fragmented. Students receive information, but not guidance that feels personal, structured, or actionable. As a result, many choose paths reactively, switch directions late, or disengage because the process feels overwhelming.

## 3. Why This Matters

The cost of unclear academic direction is high:

- wasted time in the wrong courses
- lower confidence in academic decisions
- delayed progress toward graduation
- weaker student engagement early in the university journey

Pathfinder reframes orientation from a one-size-fits-all checklist into a guided decision experience.

## 4. What Pathfinder Is

Pathfinder is a student-facing web platform that combines:

- guided onboarding
- branching journey selection
- interactive assessment
- behavioral profiling
- personalized academic recommendations
- a student dashboard experience

The product does not simply ask “what major do you want?” It helps students discover how they think, what motivates them, and which academic paths fit them best.

## 5. The Product Vision

The long-term vision is to become the intelligence layer for academic orientation: a system that continuously maps a student’s evolving profile to majors, mentors, resources, and next actions.

In the MVP, we demonstrate the first critical loop:

1. invite the student in
2. understand their uncertainty
3. guide them through the right path
4. assess their profile
5. convert that into usable academic direction

## 6. What Is Live In The MVP

The current MVP includes:

- a polished landing page
- a journey selection page
- multiple guided path experiences
- a 16-question personality and orientation module
- dynamic profile generation based on user answers
- profile-specific result rendering
- account creation and login with Supabase
- a personalized post-login dashboard
- deployment on Vercel

This means the product is not just a clickable concept. It already supports a coherent end-to-end user experience.

## 7. The End-to-End User Journey

### Homepage

The homepage introduces Pathfinder as a confidence-building academic guidance platform. It positions the product around structured support, clarity, and personalized pathways.

Primary calls to action lead the student into the journey flow.

### Journey Selection

Once inside, students choose the path that best reflects their current state:

- I have a specific career in mind
- I know what I like, but not what to study
- I’m completely lost

This is important because it respects where students actually are. Instead of forcing everyone through the same intake flow, Pathfinder adapts the entry point to the student’s mindset.

### Career Validation Path

Students with a clear target can validate a dream role and see the diplomas, skills, and milestones associated with it. This path is about confirming direction and making the route concrete.

### Interest Exploration Path

Students who know what they like can build an interest profile by selecting and deselecting live interest tiles. This leads into academic domains such as Environmental Engineering and related curriculum discovery.

### Strengths Assessment Path

Students who feel completely lost are guided into a deeper assessment experience designed to reveal strengths, values, and behavioral tendencies rather than forcing them to choose a major upfront.

### Module 1: Personality and Strengths

The MVP includes a fully usable 16-question module where users select one answer per question and move through the assessment step by step. The flow includes:

- progress tracking
- previous/next navigation
- completion handling
- storage of the user’s latest result

### Profile Result

After completing the module, the user sees a personalized profile result page. The page changes based on their answers and includes:

- profile title
- cognitive dimensions
- execution metrics
- strengths
- watch-outs
- operating style
- career architectures

This is the core proof point of the product: the system turns raw answers into identity, insight, and direction.

### Dashboard

After login or account creation, the user lands on a personalized dashboard showing:

- welcome state tied to their account
- progress and milestones
- cognitive profile summary
- recommended path
- suggested next tasks
- community and support surfaces

This turns Pathfinder from a one-time assessment into an ongoing orientation workspace.

## 8. What Makes The Product Compelling

### It meets students at the right moment

The platform is designed for the exact moment when uncertainty is highest: before students have formed a coherent academic plan.

### It is personalized, not generic

The product adapts the journey, the assessment outcome, and the dashboard based on the individual user.

### It turns introspection into action

Students do not just receive personality language. They receive pathway suggestions, curriculum exploration, and tangible next steps.

### It has emotional relevance

The experience is designed to reduce anxiety, create momentum, and make students feel understood.

### It is modular

The current system can expand naturally into additional modules, mentoring, degree matching, onboarding workflows, and retention tools.

## 9. The Personalization Engine

Pathfinder uses a behavioral profile model to interpret how students respond to the module.

The current system translates answer patterns into structured dimensions and maps those dimensions into richer profiles stored in `profiles.json`.

Those profiles contain:

- profile names
- core summaries
- strengths
- watch-outs
- working styles
- role matches
- metric language

The result is that the product can display meaningfully different output for different users instead of showing one static result page.

This is an important MVP differentiator: personalization is not cosmetic. It changes the content the student sees.

## 10. Why The Dashboard Matters

The dashboard signals that Pathfinder is not only a test. It is the start of an academic operating system for the student.

This matters because:

- orientation is a journey, not a single screen
- students need continuity after assessment
- institutions need a way to guide students over time

The dashboard creates the bridge between diagnosis and ongoing engagement.

## 11. What Is Technically Real Today

The MVP already includes:

- multi-page frontend experience
- real user authentication through Supabase
- deployed live site on Vercel
- persisted session handling
- answer-based profile generation
- post-login personalized UI

This is useful in a pitch because you can confidently say the product is not only a mockup. It is a functioning web application with real logic and user identity.

## 12. What Is Still MVP-Level

To stay credible in the pitch, be explicit that some areas are still early:

- long-term user data persistence beyond current browser-stored assessment state can be expanded
- dashboard progress is partly generated from current profile state rather than a full institutional backend
- mentor matching is currently presented as a product surface, not a full production matching engine
- academic recommendations can become more granular with more institutional data

This is not a weakness if framed correctly. It shows a strong MVP with a clear roadmap.

## 13. The Strategic Opportunity

Pathfinder can grow beyond student self-discovery into a full orientation and retention layer.

Potential expansion areas:

- persistent student profiles across devices
- saved milestones and module progress in database tables
- recommendation systems for majors, courses, clubs, and mentors
- university admin dashboards
- cohort insights for student success teams
- AI-guided orientation advising

The key idea is that student uncertainty is not a niche problem. It is a structural problem inside higher education.

## 14. The Story To Tell In A Pitch

The most compelling story is:

"Students are asked to make life-shaping academic decisions before they truly understand themselves. Pathfinder bridges that gap by turning uncertainty into personalized direction."

Then show the flow:

1. a student arrives unsure
2. the platform identifies what kind of uncertainty they have
3. the system routes them into the right experience
4. the user completes an assessment
5. Pathfinder generates a profile
6. that profile becomes recommended pathways and a live dashboard

That sequence is easy to follow and emotionally persuasive.

## 15. Suggested Demo Narrative

If you are presenting the product live, narrate it like this:

### Landing Page

"We begin with a platform that positions orientation as something personal, structured, and confidence-building rather than informational overload."

### Journey Page

"Instead of treating all students the same, we ask one key question: what kind of uncertainty are you experiencing right now?"

### Assessment Path

"For students who are completely lost, Pathfinder does not force a major choice. It starts by helping them understand how they think and work."

### Module 1

"This module converts behavioral choices into a richer profile of the student’s strengths, execution style, and academic fit."

### Profile Result

"The output is not a generic label. It is a personalized interpretation of the student with strengths, watch-outs, and concrete career architectures."

### Dashboard

"Once signed in, the student moves into an ongoing workspace where their profile, progress, next steps, and academic direction stay visible."

## 16. What You Should Emphasize Verbally

- This is not just course discovery. It is decision support.
- This is not just a personality quiz. It is a pathway engine.
- This is not just onboarding. It is the start of a student guidance layer.
- The MVP proves the emotional and product experience, not just the visual design.

## 17. What To Avoid Saying

Avoid saying:

- "It’s basically a quiz website"
- "It’s just a prototype"
- "It’s mostly design for now"

Instead say:

- "This MVP demonstrates the core personalization loop"
- "We already have the end-to-end product flow live"
- "The next step is deepening persistence, recommendations, and institutional integration"

## 18. Slide Deck Structure Recommendation

Use a simple story arc:

1. Problem
2. Why current orientation fails
3. Introducing Pathfinder
4. Product walkthrough
5. Personalization engine
6. Dashboard and ongoing value
7. Why this matters for students and institutions
8. Roadmap
9. Closing vision

## 19. Short Founder-Style Closing

Pathfinder helps students stop guessing and start navigating. The opportunity is not just to help students pick a major, but to build the personalized guidance layer that modern academic orientation is missing.

## 20. Reusable Short Summary

Pathfinder is a personalized academic orientation platform that helps students understand themselves, explore the right academic paths, and move from uncertainty to confident action through guided journeys, behavioral assessment, and adaptive recommendations.

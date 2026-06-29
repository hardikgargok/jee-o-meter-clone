# StudyMeter App Excellence Blueprint

## Product Promise
StudyMeter helps a student answer one question every time they open the app: "What should I study next, and how do I stay focused long enough to finish it?"

The app should feel calm, sharp, and action-first. It should not feel like a settings panel, a social feed, or a giant analytics dashboard.

## Benchmark Standard
StudyMeter should borrow product principles from excellent apps:

- Duolingo: one obvious next tap, short onboarding, friendly character guidance.
- Forest: focus setup is simple and emotionally clear.
- Headspace: calm tone, low-pressure copy, soft visual rhythm.
- Todoist: tasks are clear, scannable, and action-oriented.
- Notion: powerful features exist, but the first surface stays clean.

StudyMeter must not copy their visuals. It should use its own green study-meter identity, Rega as a guide, and a dense-but-calm dashboard for repeat study use.

## Navigation Principle
The app has two modes:

- First-time mode: Rega asks only what is needed to create the first plan.
- Daily mode: dashboard opens with one recommended action, one focus button, and today's study signal.

Everything else is secondary.

## Screen Direction

### 1. Launch Splash
Purpose: confirm brand and load app.
Visual direction: dark background, StudyMeter mark, short motion, no extra copy.
Copy: "Study Meter"
Primary action: none.
Friction removed: no choices before the app is ready.

### 2. Welcome Screen
Purpose: get the student into setup instantly.
Visual direction: premium green study glow, StudyMeter icon, big centered promise, optional name field, single pill button.
Headline: "One clear study plan for today."
Button: "Get Started"
Field: "Your name optional"
Friction removed: the name is optional, so students can start without typing.

### 3. Rega Goal Screen
Purpose: learn what kind of help the student wants.
Visual direction: Rega avatar, one speech bubble, three large choices.
Question: "What should StudyMeter help you fix first?"
Choices:
- "Start studying faster"
- "Stay consistent"
- "Find weak areas"
Button: "Continue"
Friction removed: no abstract motivation labels.

### 4. Focus Blocker Screen
Purpose: identify the student's main distraction.
Visual direction: simple stacked cards, one-tap multi-select, no guilt language.
Question: "What usually breaks your focus?"
Choices:
- "Reels and shorts"
- "Notifications"
- "Chats and texting"
- "Games"
Button: "Continue"
Friction removed: no fake tracking claims before permissions exist.

### 5. Study Time Screen
Purpose: protect a default focus window.
Visual direction: four clean time cards with icon, title, and time.
Question: "When should we protect your study time?"
Choices:
- Morning, 6AM - 8AM
- Afternoon, 2PM - 4PM
- Evening, 6PM - 8PM
- Night, 8PM - 10PM
Button: "Continue"
Friction removed: no manual schedule builder during first setup.

### 6. Exam Path Screen
Purpose: set the academic context.
Visual direction: compact exam cards, clear labels, no long list.
Question: "What are you preparing for?"
Choices:
- JEE Main 2027
- JEE Main April
- JEE Advanced
- School + entrance
Button: "Continue"
Friction removed: removed unrelated exam clutter from first-run setup.

### 7. Plan Ready Screen
Purpose: give confidence before entering dashboard.
Visual direction: phone-style confirmation card, selected time and exam, Rega tone.
Headline: "Your first study plan is ready."
Supporting copy: "StudyMeter will open with one priority task, one focus block, and a simple dashboard."
Button: "Open Dashboard"
Friction removed: no group joins, no permission wall, no fake community pressure.

### 8. Daily Dashboard
Purpose: show the next action.
Visual direction: action-first card at the top, simple stats underneath, advanced analytics hidden in simple mode.
Main card:
- Title: generated next study win.
- Copy: why this action matters today.
- Buttons: "Focus", "Search", "Log"
Friction removed: simple/full/guide/voice controls are hidden from default simple mode.

### 9. Planner
Purpose: manage concrete work.
Visual direction: task list grouped by today, upcoming, overdue.
Primary action: "Add Task"
Best task copy format: "Solve 30 Physics questions", "Revise Chemical Bonding formulas", "Repair mock mistakes"
Friction to avoid: vague tasks like "study hard" or too many metadata fields upfront.

### 10. Focus Timer
Purpose: start a session quickly.
Visual direction: large timer, one selected task, preset chips.
Primary action: "Start Focus"
Secondary actions: "Pause", "Finish"
Friction to avoid: hiding the task selector or making the student configure before starting.

### 11. Study Log
Purpose: record what happened after studying.
Visual direction: short form with date, subject, hours, questions, reflection.
Primary action: "Save Log"
Friction to avoid: long journaling prompts before the core data is saved.

### 12. Mock/Test Analysis
Purpose: reveal weak areas.
Visual direction: score cards, mistake tags, next repair task.
Primary action: "Add Mock"
Best insight copy: "Your next repair: Physics accuracy below target."
Friction to avoid: charts without a recommended action.

### 13. Personalize
Purpose: tune the app after the user understands it.
Visual direction: settings page, not onboarding.
Sections:
- Theme
- Density
- Modules
- Reminders
- Coach tone
Friction to avoid: showing customization before the student has used the app.

## Copy Rules
- Use "Focus" instead of "productivity".
- Use "next study win" instead of "workflow".
- Use "repair" for mistakes, not "failure".
- Use "protect study time" instead of "block apps" until real permissions exist.
- Never ask for permissions before explaining the benefit.
- Never show social groups before the student has a plan.

## Visual Rules
- Primary palette: dark charcoal, study green, soft teal, warm white.
- Cards: 8px to 14px radius depending on density; no nested cards.
- Buttons: one strong white/green primary button per screen.
- Icons: simple symbols or app icon; avoid random emoji overload.
- Text: short, direct, high contrast.
- Mobile: every primary action fits near the bottom without overlap.

## Launch Strategy

### Phase 1: Stabilize First Run
Ship the shortened Rega onboarding, optional name entry, simple dashboard default, and service-worker update prompt.

### Phase 2: Validate With Students
Ask 5 students to complete first setup and answer:
- Did you know what to tap first?
- Did any screen feel unnecessary?
- Did the dashboard tell you what to do next?
- Would you start a focus session from this screen?

Success target:
- 5 out of 5 students reach dashboard without help.
- 4 out of 5 understand the first recommended action.
- 3 out of 5 start or say they would start the focus timer.

### Phase 3: Tighten Daily Habit
Improve the next-action engine, focus timer, and study log before adding more features.

### Phase 4: Add Advanced Features Behind Intent
Only show groups, voice, advanced analytics, and personalization after the student opens those sections or switches to full dashboard mode.

## Current Loop Decisions

### Loop 1
Audit: onboarding had too many screens and fake-feeling steps.
Optimize: reduced onboarding to promise, goal, blocker, time, exam, plan-ready.
Benchmark: matched Duolingo's short path and Forest's focus simplicity.
Reflect: dashboard still exposed too many controls.

### Loop 2
Audit: first screen required a name and blocked progress.
Optimize: made the name optional and kept one strong Get Started button.
Benchmark: matched Headspace-style low-pressure entry.
Reflect: progress indicator still implied too much setup.

### Loop 3
Audit: progress bar and default selections did not match the shorter flow.
Optimize: dynamic step count and no preselected distractions.
Benchmark: matched Todoist-style explicit user intent.
Reflect: dashboard mode controls were still too prominent.

### Loop 4
Audit: home screen showed mode controls and voice controls before the main action.
Optimize: simple dashboard hides friendly toolbar, guide, and voice coach by default.
Benchmark: matched Notion's power-under-the-surface approach.
Reflect: next friction is improving the generated next-action quality and focus timer start speed.

### Loop 5
Audit: simple dashboard still showed too many competing panels after onboarding: quests, pulse coach, study modes, doubts, mentor snapshot, audit, subject cards, and analytics.
Optimize: simple mode now keeps the home experience focused on the main study action and hides advanced panels until the student chooses deeper tools.
Benchmark: matched Forest and Todoist by making the first screen about action, not exploration.
Reflect: the next friction was the primary card copy and button labels.

### Loop 6
Audit: the main action card still used vague language like "Generate a plan" and a generic "Focus" button.
Optimize: rewrote it to "Start one clear study win" with explicit buttons: "Start 25 min", "Find tool", and "Log study".
Benchmark: matched Duolingo's single obvious next action and Todoist's concrete task metadata.
Reflect: the next friction was navigation overload.

### Loop 7
Audit: the sidebar grouped too many tools under "Overview", making the app feel larger than the student's immediate need.
Optimize: renamed the primary section to "Start", renamed data utilities to "More tools", and hides advanced sidebar items in simple mode.
Benchmark: matched Notion's progressive disclosure: essentials first, power tools nearby but not dominant.
Reflect: next friction is validating with real students and tuning the next-action engine from their behavior.

### Loop 8
Audit: the dashboard promised "Start 25 min" but the action only opened the timer page.
Optimize: the dashboard primary button now opens the Focus screen, selects the next task, resets to a 25-minute focus session, and starts the timer immediately.
Benchmark: matched Forest's immediate focus-start behavior and Duolingo's promise-then-action consistency.
Reflect: next friction is making the focus screen itself feel minimal after the timer starts.

### Loop 9
Audit: the Focus screen included optional ambience and history immediately beside the timer, which could distract a first-time user.
Optimize: simple mode hides ambience/history on Focus and centers the timer card with direct copy: "Pick a task, press start, and protect the next 25 minutes."
Benchmark: matched Forest and Headspace by keeping the active session screen calm and single-purpose.
Reflect: next friction is the Planner page, which still exposes generator, filters, targets, and revision queue together.

### Loop 10
Audit: Planner showed generator, quick capture, five filters, daily targets, and revision queue at once.
Optimize: simple mode turns Planner into "Today's Plan", hides filters/generator/side panels, and defaults the task list to tasks due today.
Benchmark: matched Todoist's Today-first flow and Things-style focus on the immediate list.
Reflect: next friction is whether Study Log can be reduced to a fast save flow after focus ends.

### Loop 11
Audit: Study Log used record-keeping language like "Log Study Session" and an empty state that told users to click a specific old label.
Optimize: renamed the page to "Log Study", simplified the modal to "Log today", changed the primary button to "Save log", and rewrote the empty state around the post-focus habit.
Benchmark: matched Strava-style habit logging: save the completed effort quickly, then review history later.
Reflect: next friction is Test Log, where analysis copy still feels heavy for first-time students.

### Loop 12
Audit: Test Log sounded like spreadsheet data entry even though the real student need is repairing mistakes.
Optimize: renamed the surface to "Mistake Repair", changed the primary action to "Add test result", rewrote the subtitle and empty state, and updated command search labels.
Benchmark: matched Khan Academy and Todoist by framing errors as actionable repair work instead of passive analytics.
Reflect: next friction is the command palette, which still exposes too many advanced actions in simple mode.

## Next Engineering Priorities
1. Make next-action recommendations more specific from onboarding choices.
2. Pin the selected study time on the dashboard.
3. Add a "Start 25 min" one-tap focus button.
4. Move groups and permissions out of onboarding entirely unless a real Android permission flow exists.
5. Add a small "What's new" update message after GitHub Pages deploys.
6. Watch first-session behavior: if students do not tap "Start 25 min", the dashboard copy still needs simplification.
7. Simplify Planner into "Today", "Upcoming", and "Done" after validating the new Focus start path.
8. Reduce Study Log to a fast post-focus save screen in simple mode.
9. Make Test Log feel like "repair mistakes" instead of a data-entry spreadsheet.
10. Filter command palette results by simple/full mode so new students do not see every advanced action at once.

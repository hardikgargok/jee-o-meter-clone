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

## Complete Screen Map

### App Shell
Audit: the app has many power tools, so the shell must keep new students oriented.
Optimized direction: left navigation uses student verbs: Dashboard, Today's Plan, Start Focus, Log Study, Mistake Repair. Advanced items remain available in full mode.
Benchmark: Todoist keeps Today and Upcoming visible while deeper project organization stays secondary.
Visual: dark sidebar, small colored dots, 44px minimum tap targets, active item with soft green/blue glow.
Primary action: Start 25 min from the dashboard.

### Dashboard
Audit: dashboards become confusing when they compete with the timer, planner, analytics, and mentor at once.
Optimized direction: the first card answers "What do I do now?" and offers Start 25 min, Search, and Log today.
Benchmark: Duolingo and Forest both make the next action emotionally obvious.
Visual: one wide action strip, 3 compact progress chips, then secondary progress below the fold.
Primary action: Start 25 min.
Empty state: "StudyMeter will create your first task after setup."

### Today's Plan
Audit: students do not need targets, revision queues, and AI generation before they can see today's work.
Optimized direction: simple mode defaults to tasks due today and hides filters until full mode.
Benchmark: Todoist's Today view focuses attention by showing scheduled work for today and letting users reschedule what is unrealistic.
Visual: plain task rows with subject color, minutes, due state, and one check action.
Primary action: Add Task.
Empty state: "No task for today. Add one finishable task or generate today's plan."

### Start Focus
Audit: focus screens fail when they ask students to configure before starting.
Optimized direction: selected task, 25:00 timer, Start Focus, Pause, Finish. Ambience/history hidden in simple mode.
Benchmark: Forest turns focus into one protected timer with a visible consequence for leaving.
Visual: centered circular timer, task selector above, one strong button below, low-motion green glow.
Primary action: Start Focus.
Completion state: "Saved. Log today?"

### Log Study
Audit: logs feel like admin work when the form asks too much.
Optimized direction: save hours, questions, subject, topic, and one reflection. Optional detail never blocks save.
Benchmark: Strava-style logging captures the completed effort first and lets history become motivation later.
Visual: compact modal, five inputs max, Save log button fixed at the bottom on mobile.
Primary action: Save log.
Empty state: "No study saved yet. Log after your first focus block."

### Mock Tests
Audit: mock score pages can feel like report cards without a next step.
Optimized direction: show score, subject split, accuracy, and one suggested repair action.
Benchmark: Khan Academy-style mastery views work because weak areas become the next practice path.
Visual: top score card, three subject bars, recent tests list, no more than one chart above the fold.
Primary action: Add mock result.
Empty state: "Add one mock to unlock repair suggestions."

### Mistake Repair
Audit: "test analysis" sounds heavy and passive.
Optimized direction: each result creates a repair task: what broke, why it broke, what to practice next.
Benchmark: Todoist task language plus Khan Academy remediation: mistakes become concrete work.
Visual: repair history rows with score, mistake count, top cause, and Create repair task.
Primary action: Add test result.
Empty state: "No repair saved yet. Add one result after your next test."

### Subject Pages: Physics, Chemistry, Mathematics
Audit: syllabus pages are useful but can overwhelm first-run users.
Optimized direction: keep subject pages as progress trackers reached after the student asks for subject detail.
Benchmark: Notion-style depth: dense data is available without taking over the home screen.
Visual: subject color header, unit progress rings, chapter rows with status, confidence, and quick task creation.
Primary action: Add task from chapter.
Empty state: "Pick one chapter to start tracking."

### Formula Bank
Audit: notes become a drawer unless they connect to active recall.
Optimized direction: save short formulas, examples, and tags; turn any note into a flashcard or task.
Benchmark: Anki and RemNote win by turning notes into retrieval practice.
Visual: search field at top, subject tabs, formula cards with copy, edit, make card.
Primary action: Add formula.
Empty state: "Save one formula you keep forgetting."

### Study Toolkit
Audit: the toolkit currently has many utilities, so it should not be the first destination for new students.
Optimized direction: keep it as a power shelf: flashcards, reminders, reports, improvement pack, source studio.
Benchmark: Notion and Raycast keep advanced tools searchable but not visually dominant.
Visual: tabbed utility surface, two-column desktop layout, single-column mobile stack.
Primary action: depends on active tab; default is Make flashcards.
Empty state: "Paste notes to create cards, quiz prompts, and tasks."

### Personalize
Audit: customization before value creates delay.
Optimized direction: show Personalize only after dashboard use or from settings/search.
Benchmark: Headspace keeps tone choices gentle and approachable instead of technical.
Visual: sectioned settings page: Theme, Density, Modules, Reminders, Coach tone.
Primary action: Save settings automatically.
Empty state: none; settings always show current values.

### AI Mentor
Audit: "AI Mentor" can sound vague or overpromising.
Optimized direction: position it as private offline intelligence based on saved StudyMeter data.
Benchmark: Linear and Notion AI-style surfaces work best when suggestions cite the data behind the recommendation.
Visual: readiness card, risk matrix, 48-hour plan, mentor brief, each with clear source labels.
Primary action: Create mentor tasks.
Empty state: "Log study, add tasks, or add a mock to unlock sharper advice."

### Command Palette
Audit: search is powerful, but too many commands can recreate dashboard overload.
Optimized direction: simple mode shows only Dashboard, Today's Plan, Start Focus, Log Study, Mock Tests, Mistake Repair, and essential actions.
Benchmark: Raycast/Spotlight are fast because results match context and intent.
Visual: centered modal, search input focused, 18 max default results, keyboard highlight.
Primary action: first result.
Empty state: "No command found. Try focus, plan, log, mock, or repair."

### Update Banner and Installed App Refresh
Audit: installed PWA/APK users may keep cached old UI and think the update did not arrive.
Optimized direction: every major UI release bumps the service-worker cache and shows "New simpler design is ready. Restart once to refresh the app cache."
Benchmark: production PWAs and native apps use short release messages tied to visible change.
Visual: bottom toast/banner with Restart button and later action.
Primary action: Restart.
Empty state: no banner when already on the latest release marker.

## Store and Launch Assets

### App Icon
Direction: keep the StudyMeter hourglass/mark as the core silhouette. Use dark green background, bright study-green center, and high-contrast edges so it reads at 48px.
Do not use: busy screenshots, mascot face as the main icon, thin lines, or text inside the icon.

### Play Store Short Description
Final copy: "One clear study plan, focus timer, and mistake repair system for JEE students."

### Play Store Full Description Opening
Final copy: "StudyMeter helps JEE students decide what to study next, protect a 25-minute focus block, log real progress, and turn mock-test mistakes into repair tasks. It is built for students who feel overwhelmed by too many chapters, too many distractions, and unclear daily priorities."

### Screenshot Set
1. Dashboard: show Start 25 min and today's progress chips.
2. Today's Plan: show three concrete tasks due today.
3. Start Focus: show 25:00 timer attached to a Physics task.
4. Mistake Repair: show one mock mistake converted into a repair task.
5. Log Study: show a saved study session and streak progress.
6. Subject Tracker: show Physics chapter progress and weak chapter cue.

### Screenshot Caption Copy
1. "Know what to study next."
2. "Keep today's plan realistic."
3. "Start a protected 25-minute focus block."
4. "Turn mistakes into repair tasks."
5. "Log study in seconds."
6. "Track every JEE chapter clearly."

### Release Notes for Excellence Build
Final copy: "New simpler StudyMeter: shorter setup, clearer dashboard, one-tap 25-minute focus, Today's Plan, Log Study, and Mistake Repair."

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

### Loop 13
Audit: Command Palette could still expose advanced tools even when the visible app was in simple mode.
Optimize: simple mode now filters commands to core pages and actions: Dashboard, Today's Plan, Focus, Log Study, Mock Tests, Mistake Repair, plan generation, task add, repair add, theme, and export.
Benchmark: matched Raycast and Spotlight by keeping search powerful but context-aware.
Reflect: next friction is copy consistency across nav, command search, and page titles after renaming Test Log.

### Loop 14
Audit: The service worker cache version had not changed during the UI excellence work, so installed PWA/APK users could keep stale screens.
Optimize: bumped the StudyMeter service-worker cache version so the updated app shell can install and trigger the existing Restart update banner.
Benchmark: matched production PWA practice: ship UI changes with a fresh cache version and a clear reload path.
Reflect: next friction is user education around refreshing installed APK/WebView copies after GitHub Pages deploys.

### Loop 15
Audit: Update communication still used generic wording and did not tell students that the simpler design was ready.
Optimize: update banner now says "New simpler design is ready" and explains the cache refresh; the app also stores an `excellence-v2` release marker and shows a one-time toast after login.
Benchmark: matched modern release communication in apps like Notion and Linear: short, specific, and tied to the user-visible improvement.
Reflect: next friction is reducing the remaining advanced pages over time without deleting power features.

### Loop 16
Audit: visible dashboard and command labels still mixed old vocabulary: "Find tool", "Log study session", "Planner", "Focus Timer", and "Analyze test".
Optimize: aligned the simple path around five student verbs: Start Focus, Today's Plan, Log today, Mistake Repair, and Search.
Benchmark: matched Todoist and Raycast by making labels predictable between navigation, search, and actions.
Reflect: next friction is store positioning; students must understand the app from screenshots before installing.

### Loop 17
Audit: the blueprint had clear onboarding and core dashboard direction, but advanced screens such as Formula Bank, Toolkit, AI Mentor, subject pages, and update states were not specified deeply enough.
Optimize: added a complete screen map with purpose, visual direction, primary action, and empty state for each product surface.
Benchmark: matched Notion's progressive-disclosure principle: power is available, but not forced into the first session.
Reflect: next friction is launch trust: icon, screenshots, release notes, and cache refresh must communicate the same simple promise.

### Loop 18
Audit: launch assets were implied but not concrete, which risks generic Play Store copy and mismatched screenshots.
Optimize: specified icon direction, short description, opening full-description copy, six screenshot frames, six captions, and excellence-build release notes.
Benchmark: matched top education/productivity apps by leading with outcome, then showing the exact workflow.
Reflect: next friction is measuring whether real students complete setup, start focus, and understand mistake repair without explanation.

### Loop 19
Audit: onboarding asked for a protected study time, but the dashboard did not keep that promise visible after setup.
Optimize: added the selected study window into the dashboard command strip as a persistent chip, beside hours, revision count, and open tasks.
Benchmark: matched habit apps that keep the chosen routine visible at the moment of action instead of burying it in settings.
Reflect: next friction is making the recommended task respond more sharply to goal, distraction, time slot, and exam path.

## Next Engineering Priorities
1. Make next-action recommendations more specific from onboarding choices: goal, distraction, time slot, and exam path should change the first dashboard task.
2. After a focus session ends, show a two-button completion state: "Save log" and "Start another 25 min".
3. Add a simple first-run analytics checklist: reached dashboard, tapped Start 25 min, logged study, opened Mistake Repair.
4. Build the six launch screenshots exactly from the Store and Launch Assets section.
5. Test with 5 students and record: setup completion, first tap choice, dashboard understanding, focus-start willingness, and confusion words they say aloud.
6. If fewer than 4 of 5 students tap Start 25 min first, simplify the dashboard card again and remove Search from the first action row.
7. If fewer than 3 of 5 students understand Mistake Repair, rename the button to "Fix test mistakes" and retest.
8. Keep advanced tools behind full mode unless a student reaches them through Search or an explicit page tap.
9. Bump the service-worker cache name on every major UI release and verify GitHub Pages serves the new marker before telling APK users the update is live.

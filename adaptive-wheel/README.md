# Adaptive Wheel of Balance — prototype

A privacy-conscious, self-directed reflection tool. This first prototype is a static web app that can be opened in a browser and embedded later as a Telegram Mini App.

## Core idea

Start with **12 unnamed spokes**. A person defines what each spoke means instead of being forced into a fixed life-domain taxonomy. Selecting a spoke opens a choice matrix:

1. Choose a suggestion from a searchable catalogue, create a custom direction, or explore with questions.
2. Rate current state from 0 to 10.
3. Describe the desired state and target score.
4. Choose a target date and one small first action.
5. Save a dated snapshot of the map and a goal record.

## Included in the prototype

- 12 unnamed spokes by default; add/remove spokes.
- Catalogue suggestions grouped by life area and skills, with custom entries.
- Current and desired scores (0–10), reflective prompts, optional answers.
- Goal, first step, target date and progress status.
- Interactive radar-style wheel and comparison of current/desired ratings.
- Local browser storage for this demo; JSON export/import for backup.
- Downloadable SVG snapshot.
- Calendar export as an ICS file for a chosen goal date, plus reminder event details.
- No AI, camera, microphone or remote analytics in this prototype.

## Run locally

Open index.html in a modern browser. No build step or package installation is required.

## Data and privacy

The prototype stores information in the current browser profile. Clearing site data can erase it, so export backups regularly. It does not send data to a server. Do not store highly sensitive personal information in a shared device profile.

## Next milestones

1. Validate usability and reflective questions with consenting users.
2. Add tests for scoring, date handling, import/export and persistence.
3. Add Telegram Mini App integration and authenticated server storage.
4. Add reminders and calendar provider OAuth only after explicit opt-in.
5. Add optional voice notes with a clear recording indicator, explicit start/stop and deletion controls.
6. Treat AI coaching suggestions as hypotheses, not diagnoses; the user can skip questions and edit or delete every goal.

## Hypotheses to evaluate

- Choosing a personally meaningful label may prompt reflection more effectively than rating predefined domains.
- Comparing current and desired scores may help clarify priorities.
- Recording a first step and target date may increase follow-through.
- Revisiting dated snapshots may help people notice changes in their own priorities.

These are hypotheses, not established effects. Evaluate with voluntary feedback and observable completion rates; do not infer mental-health diagnoses from scores.

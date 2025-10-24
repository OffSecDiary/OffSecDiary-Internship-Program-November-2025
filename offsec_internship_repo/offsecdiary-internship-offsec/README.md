# OffSecDiary — Offensive Security Internship (Nov 01, 2025)

Welcome — this repository is the canonical place for the internship schedule, weekly tasks, submission templates, attendance uploads, and mentor evaluation artifacts.

Start date: 2025-11-01  
Duration: 1 month (19 sessions)  
Mode: Online — theory + labs + project + final presentation

Quickstart
1. Read `SYLLABUS.md` and `templates/WEEK_TEMPLATE.md`.
2. Each week has tasks and labs. Complete them and prepare deliverables in the `submissions/` folder using the provided templates.
3. Attendance: submit or update your attendance file at `attendance/{github-username}.md` in a Pull Request (PR). The CI will validate format on PRs touching `attendance/**`.
4. Mentors will review PRs; approved PRs are merged and attendance is recorded.
5. Final project: place deliverables in `final-projects/{github-username}/`.

Repository layout (high level)
- SYLLABUS.md — master schedule
- templates/ — templates for week, attendance, lab-report, task submission
- weeks/ (optional) — copies of the week template per session with resources
- attendance/ — interns add/update their attendance file here (one per intern)
- submissions/ — individual assignment submissions (use per-week subfolders)
- final-projects/ — final deliverables
- .github/workflows/attendance-check.yml — CI that validates attendance uploads
- .github/scripts/check_attendance.py — script that validates & summarizes attendance
- GRADING.md, CODE_OF_CONDUCT.md, CONTRIBUTING.md

Attendance policy (short)
- Maintain a weekly log in `attendance/{github-username}.md`.
- Minimum 75% attendance required for certification.
- Submit attendance via PRs; do not push directly to main (protect main branch).

If you want, I can:
- Create one folder per session automatically (weeks/01-19) populated with session-specific tasks and lab links from your syllabus.
- Extend the CI to auto-post PR comments with attendance summaries and notify mentors.
- Add a simple web UI (GitHub Pages) for the roster and progress dashboard.

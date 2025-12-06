---
name: "🐛 Bug report"
about: "Report a bug so we can fix it quickly and correctly"
title: "[BUG] <short summary>"
labels: ["bug", "triage"]
assignees: []
---

## 1. Summary

**One-line description of the bug**

> Example: "Booking form fails to submit on mobile Safari when selecting dates."

---

## 2. Environment

- **App/Service**: <!-- e.g. Web app, API, Admin portal -->
- **Environment**: <!-- e.g. production / staging / local -->
- **Version / Commit**: <!-- tag, release, or short SHA -->
- **OS**: <!-- e.g. iOS 18.1, Windows 11, macOS 15 -->
- **Browser**: <!-- e.g. Chrome 131, Safari 18 -->
- **Device**: <!-- e.g. iPhone 15, Desktop 4K monitor -->
- **Network conditions** (if relevant): <!-- VPN, low bandwidth, etc. -->

---

## 3. Steps to Reproduce

Be as exact as possible:

1. Go to `...`
2. Click `...`
3. Enter `...`
4. Submit / tap / navigate `...`

**Reproducibility**:

- [ ] Happens every time
- [ ] Happens frequently (≥50%)
- [ ] Hard to reproduce / intermittent

If it’s intermittent, note anything that seems to affect it:

> Example: "Only happens on first page load after deploy."

---

## 4. Expected Behavior

**What you thought should happen**

> Example: "Form should submit and show a success message. Booking appears in dashboard."

---

## 5. Actual Behavior

**What actually happened**

> Example: "Submit button spins for ~10 seconds, then shows a generic error: 'Something went wrong.'"

- **Error message shown (if any)**:
- **User impact**: 
  - [ ] Cosmetic only
  - [ ] Minor annoyance
  - [ ] Blocks a non-critical flow
  - [ ] Blocks a critical flow / payment / signup
  - [ ] Data loss or security concern

---

## 6. Logs / Console Output

If possible, include:

- **Frontend console errors** (screenshot or copy/paste)
- **Network tab details** (failed request URL, status code, response snippet)
- **Backend logs** (if you have access, or tag someone who does)

```text
Paste relevant logs here (sanitize any secrets!).
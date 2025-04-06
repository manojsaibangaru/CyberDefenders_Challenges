# CyberDefenders_Challenges
# 🛡️ FakeGPT Chrome Extension - Blue Team Lab Report

This repository contains my analysis and findings from the **FakeGPT Lab** on [CyberDefenders](https://cyberdefenders.org), as part of a 21-day Blue Team SOC challenge series.

## 🔍 Challenge Summary

The FakeGPT lab simulates a malicious Chrome extension disguised as a ChatGPT helper. It’s designed to teach analysts how browser-based malware operates, particularly through the misuse of Chrome extension permissions, background scripts, and stealthy data exfiltration techniques.

## 📄 What's Inside

- `CyberDefender_FakeGPT_Challenge.pdf`: A full write-up of my investigation
  - Analysis of `manifest.json`, `bg.js`, `tracking.js`
  - Breakdown of permissions and behaviors
  - Indicators of Compromise (IOCs)
  - Comparison to a real-world extension (FormSwift PDF Editor)
  - Remediation recommendations for users and organizations

## 🧠 Key Skills Learned

- Chrome extension architecture & file structure
- Red-flag permissions (`cookies`, `tabs`, `downloads`, `<all_urls>`)
- Base64 data encoding and credential exfiltration in JavaScript
- Hands-on threat analysis and IOC extraction
- Applying findings to detection logic (Splunk/SIEM)

## ✅ Challenge Outcome

- Solved all 10 lab questions
- Deepened understanding of browser security threats
- Strengthened blue team detection & investigation workflows

---

**More to come:** This is Day 1 of my 21-day Blue Team Challenge journey!

Feel free to clone, explore, or reach out with questions or feedback.


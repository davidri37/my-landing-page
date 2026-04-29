# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A single-page personal introduction website for 이성찬 (AI Consultant, (주)상상우리), designed to replace paper business cards at offline networking events. Visitors reach it via QR code or KakaoTalk link and should understand who 이성찬 is within 10–20 seconds.

Resume reference: `이력서2026(성찬).docx`

## Tech Stack

**Pure HTML + CSS only.** No JavaScript frameworks, no backend, no build tools, no npm. A single `index.html` file (with inline or linked CSS) is the entire deliverable.

To preview: open `index.html` directly in Chrome.

## Design Constraints

- **Colors only**: Navy `#1F3864`, White `#FFFFFF`, Dark Gray `#333333`
- **Images**: One profile photo (circular), optional company logos — no other images
- **Language**: Korean only, no i18n
- **No**: login, visitor stats, comments, or any server-side features

## Required Features

1. **Header**: Name · Title · Company in one line, font ≥ 1.5× body size
2. **Bio**: 3–5 sentence self-introduction below the name
3. **Career timeline**: 3 entries, newest first — format: `연도 · 회사 · 직책 · 한 줄 요약`
4. **Email button**: Opens default mail app with recipient pre-filled (`mailto:`)
5. **Phone button**: Copies phone number to clipboard on tap

Optional (lower priority):
6. Circular profile photo at top
7. Small company logos beside career entries

## Responsive Requirements

Must render without layout breakage on:
- Chrome desktop
- Smartphone portrait (no text clipping)

## Completion Checklist (from PRD)

- [ ] Page loads in Chrome
- [ ] No text clipping on smartphone portrait
- [ ] Name · title · company visible on one line
- [ ] 3–5 line bio present
- [ ] 3 career entries in reverse-chronological order
- [ ] Email button opens mail app
- [ ] Phone button copies number to clipboard
- [ ] Page loads within 5 seconds
- [ ] No typos

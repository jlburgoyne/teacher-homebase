# ELA Classroom Display System
### NYS Public School — Grades 7, 9, 11

## Overview

This project documents a classroom display system designed for a secondary ELA teacher returning to a new district after a period away from the profession. The goal was to reduce daily setup friction and give students a consistent, predictable structure at the start of every class — without requiring the teacher to manage multiple tools or remember multiple links.

## Problem

The teacher was splitting her daily class setup between her smartboard and a physical whiteboard, manually writing out objectives and writing prompts for most periods. With three grade levels (7, 9, 11) using different curricula — Savvas myPerspectives and a Regents review book — there was no unified system, and daily prep was repetitive and inconsistent.

## Solution

**Daily Display Slides (Google Slides)**
A weekly slide deck template for each grade level, structured around four consistent elements: bell ringer, agenda, learning objective, and exit ticket. Splitting by grade level kept content clean and relevant per class, but introduced a usability problem — managing three separate presentation links was its own burden.

**Course Homepage (Google Sites)**
A centralized "homebase" page designed to live open on the classroom computer connected to the smartboard. It consolidates links to all three grade-level slide decks alongside other frequently needed resources, so the teacher navigates to one place and branches from there.

## Design Decisions

- **Google Workspace throughout**: Every staff and student account at the school includes Google, making Slides and Sites the most accessible choice with zero friction around logins or software.
- **Grade-level separation**: Keeping decks separate avoids scrolling through irrelevant slides mid-class, but required the homebase page to make the system manageable.
- **Minimal daily effort**: The template is designed so that only a handful of fields need updating each day — the structure, formatting, and recurring language are already in place.

## Files

- `daily-dashboard-template.pdf` — Representative sample of the slide template (Monday, all three grade levels)
- `coriale-home-base.html` — Static archive of the Google Sites course homepage

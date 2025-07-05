# Issue Templates for Teachers

This document explains the GitHub issue template forms created to simplify change requests for teachers at Mergington High School.

## Overview

Teachers can now create well-structured issues for common tasks without needing to modify code directly. Each template form guides teachers through providing all the necessary information for the Copilot coding agent to implement changes without additional clarification.

## Available Templates

### 🎯 Add New Activity (`01-add-new-activity.yml`)
**Use when:** Teachers want to create a new extracurricular activity or program.

**What it collects:**
- Activity name and description
- Schedule (days, start/end times)
- Maximum participants
- Activity category
- Initial participants (optional)
- Special requirements

**Copilot implementation hints:** Includes data structure format, file locations, and testing checklist.

### ✏️ Modify Existing Activity (`02-modify-activity.yml`)  
**Use when:** Teachers need to update existing activity details.

**What it collects:**
- Which activity to modify
- Specific changes needed
- New values for schedule, capacity, description
- Implementation timeline
- Reason for changes

**Copilot implementation hints:** Guidance on preserving participant data and updating both display strings and structured data.

### 🗑️ Remove Activity (`03-remove-activity.yml`)
**Use when:** Teachers need to discontinue an activity.

**What it collects:**
- Activity to remove
- Timeline for removal
- Reason for removal
- Current participant count
- Student notification plan
- Required confirmations

**Copilot implementation hints:** Safety checks and destructive operation warnings.

### 🐛 Bug Report (`04-bug-report.yml`)
**Use when:** Teachers encounter system problems or issues.

**What it collects:**
- Problem area (registration, login, display, etc.)
- Problem description and expected behavior
- Steps to reproduce
- Frequency and affected users
- Browser/device information
- Error messages

**Copilot implementation hints:** Debugging approach, common problem areas, and file locations to investigate.

### 💡 Feature Request (`05-feature-request.yml`)
**Use when:** Teachers want new functionality or improvements.

**What it collects:**
- Feature category and description
- Problem it solves
- Proposed solution
- Target users and priority
- Use cases and examples
- Technical considerations

**Copilot implementation hints:** Development approach and implementation patterns.

### 👥 Student Registration Issue (`06-registration-issue.yml`)
**Use when:** Teachers have problems with student sign-ups or withdrawals.

**What it collects:**
- Type of registration issue
- Affected activity and student details
- Detailed problem description
- Steps to reproduce
- Current participant information
- Troubleshooting already attempted

**Copilot implementation hints:** Registration system components and common issues to check.

## Configuration

- **Blank issues disabled:** Teachers must use structured templates
- **Emergency contact:** Direct email to principal for urgent issues
- **Documentation link:** Points to development guide

## Benefits for Teachers

1. **No coding required:** Fill out forms instead of writing technical issues
2. **Guided process:** Templates ensure all necessary information is provided
3. **Quick implementation:** Copilot agent can work immediately with complete information
4. **Consistent results:** Structured approach leads to predictable outcomes

## Benefits for Copilot Agent

1. **Complete context:** All necessary information provided upfront
2. **Clear acceptance criteria:** Success metrics defined in advance
3. **Implementation hints:** File locations, data structures, and testing guidance included
4. **Categorized issues:** Different templates for different types of work

## Template Structure

Each template includes:
- **Clear problem description fields**
- **Acceptance criteria checkboxes** 
- **Implementation hints section** with:
  - Files to modify
  - Data structures required
  - Testing checklist
  - Safety considerations (for destructive operations)

This ensures teachers can create actionable issues that the Copilot coding agent can implement efficiently and accurately.
## Tempo

A smarter way to keep your home in rhythm.

Tempo is a native iOS app that learns how a household actually operates and surfaces what needs attention—without turning home life into an endless checklist.

Rather than relying only on rigid recurring schedules, Tempo learns to from task-completion patterns to predict when household tasks are likely due.

### The Idea

Household routines aren’t always predictable.

Instead of:

Vacuum — Every Tuesday

Tempo aims to learn from actual behavior and surface:

Vacuum
Usually done around now.

The goal is to reduce the mental load of remembering and scheduling routine household work while keeping recommendations simple and understandable.

### Core Experience

Tempo is designed around a simple loop:

Create → Complete → Learn → Recommend → Repeat

The initial version will focus on:

* Creating and organizing household tasks
* Quickly marking tasks complete
* Building completion history
* Learning recurring patterns
* Surfacing tasks that likely need attention
* Explaining recommendations in human-friendly language

### Machine Learning

Tempo will explore lightweight classical machine-learning models trained on household task history.

Potential signals include completion intervals, time since last completion, day-of-week patterns, task categories, and previous recommendations.

Models will initially be developed in Python and deployed on-device using Core ML.

The goal isn’t to build the most complicated model possible—it’s to determine whether a small, interpretable model can make genuinely useful predictions.

### Tech Stack

* Swift
* SwiftUI
* SwiftData
* Core ML
* Python
* scikit-learn
* Figma

### Design Principles

Calm over clutter.
Surface what matters instead of presenting an endless checklist.

Rhythm over rigid schedules.
Learn from how a household actually behaves.

Explainable over mysterious.
Translate predictions into understandable recommendations.

Private by default.
Keep household data and ML inference on-device whenever practical.

### Status
**Early development**

Currently defining the core experience, interaction model, and ML approach before building the first SwiftUI prototype.

⸻

Tempo is an exploration of mobile engineering, product design, and on-device machine learning.

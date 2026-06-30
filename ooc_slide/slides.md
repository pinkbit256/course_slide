---
theme: seriph
title: Quiz Quest
info: |
  Presentation for Quiz Quest, focused on game flow and design thinking.
class: text-left
drawings:
  persist: false
transition: slide-left
mdc: true
---

# Quiz Quest

<div class="cover">
  <img :src="'/Logo.png'" class="cover-bg-logo" />
  <div>
    <h2>A playful first step into student life in Germany</h2>
    <p>
      A delivered Godot learning game that helps new international students learn campus rules,
      daily language and social expectations through short quiz challenges.
    </p>
    <div class="tagline">Software Engineering Jump Start - TH Aschaffenburg</div>
  </div>
</div>

---

# Problem and Goal

<div class="split">
  <div class="card">
    <h3>Problem</h3>
    <p>
      New international students often face many small unknowns at the same time:
      language, university rules, social behavior and daily routines.
    </p>
  </div>
  <div class="card">
    <h3>Goal</h3>
    <p>
      Make onboarding less stressful by letting students practice situations in a
      safe, playful environment before they meet them in real life.
    </p>
  </div>
</div>

<div class="center-note">
  Designed for new international students at TH Aschaffenburg who need practical
  orientation before and during their first semester.
</div>

---

# Learning Topics

<div class="topic-grid">
  <div class="topic">Social Etiquette</div>
  <div class="topic">German History</div>
  <div class="topic">German Language</div>
  <div class="topic">University Rules</div>
</div>

<div class="design-line">
  We chose topics that are useful immediately: how to behave, what to understand,
  what to say and what rules to follow.
</div>

---

# Core Player Journey

<div class="journey">
  <div>Start</div>
  <span></span>
  <div>Explore Map</div>
  <span></span>
  <div>Choose Topic</div>
  <span></span>
  <div>Answer Quiz</div>
  <span></span>
  <div>Earn Progress</div>
</div>

<div class="split mt">
  <div class="card">
    <h3>Why this flow works</h3>
    <p>
      The player always has a clear next action, so the learning experience stays
      simple and easy to repeat.
    </p>
  </div>
  <div class="card">
    <h3>What keeps it game-like</h3>
    <p>
      Movement, topic choice, hints, pressure and rewards make the quiz feel like
      a small challenge instead of a worksheet.
    </p>
  </div>
</div>

---

# Campus Map Design

<div class="split">
  <div class="image-box large">
    <img :src="'/campus_map.png'" />
  </div>
  <div>
    <h3>Design purpose</h3>
    <ul>
      <li>Gives the player freedom to choose a topic</li>
      <li>Makes learning feel connected to a place</li>
      <li>Separates exploration from quiz pressure</li>
      <li>Creates a natural return point after each challenge</li>
    </ul>
  </div>
</div>

---

# Lecture Challenge Design

<div class="split">
  <div>
    <h3>Inside a topic</h3>
    <ul>
      <li>The player enters a lecture-style quiz scene</li>
      <li>Each question gives immediate feedback through game state</li>
      <li>Hints are helpful but increase pressure</li>
      <li>Completed answers are saved as progress</li>
    </ul>
  </div>
  <div class="image-box large">
    <img :src="'/classroom.jpg'" />
  </div>
</div>

---

# Main Mechanics

<div class="mechanics">
  <div>
    <h3>Anger Meter</h3>
    <p>Wrong answers and risky help increase tension.</p>
  </div>
  <div>
    <h3>Hint Tradeoff</h3>
    <p>Hints support learning, but using them has a cost.</p>
  </div>
  <div>
    <h3>Saved Progress</h3>
    <p>The game remembers completed topics and questions.</p>
  </div>
  <div>
    <h3>Certificate</h3>
    <p>Finishing every topic unlocks a visible reward.</p>
  </div>
</div>

<div class="image-box teacher">
  <img :src="'/teacher_sprite_sheet.png'" />
</div>

---

# Design Thinking

<div class="principles">
  <div class="card">
    <h3>Keep It Focused</h3>
    <p>Four topics keep the final build focused while still showing the complete learning loop.</p>
  </div>
  <div class="card">
    <h3>Make Choices Meaningful</h3>
    <p>The player decides where to go, when to use help and how to manage pressure.</p>
  </div>
  <div class="card">
    <h3>Separate Content From Flow</h3>
    <p>Question content can grow while the same quiz experience stays reusable.</p>
  </div>
  <div class="card">
    <h3>Reward Completion</h3>
    <p>The certificate gives the player a clear finish line and a sense of achievement.</p>
  </div>
</div>

---
class: result-slide
---

# Result and Next Steps

<div class="split">
  <div>
    <h3>Final deliverable</h3>
    <ul>
      <li>Playable Godot game flow</li>
      <li>Campus map and topic selection</li>
      <li>Lecture quiz with hints and anger meter</li>
      <li>Progress saving and certificate reward</li>
    </ul>
  </div>
  <div>
    <h3>Future improvements</h3>
    <ul>
      <li>More scenarios beyond quizzes</li>
      <li>More detailed explanations after answers</li>
      <li>Better accessibility and input guidance</li>
      <li>More polished sound and animation feedback</li>
    </ul>
  </div>
</div>

---
layout: center
class: text-center
---

# Thank You

Questions?

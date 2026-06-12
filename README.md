# AppADay 044 — Quarters Master

A two-tap timing skill game inspired by the classic bar game of quarters, with solo practice and head-to-head modes.

## Modes

Practice mode is a solo streak challenge where the timing meters speed up the longer you stay alive, with a persisted best streak. 2 Player Pass & Play alternates turns between two people on the same device, racing to 7 cups. 2 Player vs CPU offers the same race to 7 against a computer opponent set to Easy, Medium, Hard, or Very Hard, each with a different probability of making and perfecting shots.

## How to play

Tap “Bounce” while the power meter sweeps — landing inside the gold zone sets up a make, and the bright inner zone is a perfect. Tap “Aim” the same way on the second meter to set direction. The coin animates across the table; a successful shot drops into the cup and the beer level rises. In versus modes, a scoreboard and turn indicator track whose shot is up, with a win screen and rematch option at 7 cups.

## Features

Two-stage timing mechanic with escalating difficulty in Practice mode, a mode-select screen with CPU difficulty options, canvas-based coin and cup animation with a rising beer fill, WebAudio sound effects, a best-streak record saved to `localStorage`, and a responsive layout that switches from a single column on phones to a two-column view with a larger table on tablets and desktops (700px+ breakpoint).

## Tech

Single-file vanilla HTML/CSS/JS, no dependencies, fully responsive from a 375px viewport up through desktop.

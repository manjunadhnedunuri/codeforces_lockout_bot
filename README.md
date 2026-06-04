# Codeforces Lockout

Made by Manjunadh

[Open Web App](https://cf-lockoutbot.streamlit.app/)

## Overview

Codeforces Lockout is a competitive programming format where participants go head-to-head to solve a set of problems. Once a participant solves a problem, it becomes "locked out" for their opponent, meaning they can no longer earn points for solving it. The player with the highest points at the end of the match wins.

## How It Works

1. Codeforces problems are retrieved based on user-specified ratings.

2. Problems already solved by any participant are filtered out to ensure fairness.

3. Problem data and real-time solve statuses are efficiently fetched and strictly filtered using the official Codeforces API, with robust caching to bypass restrictions and handle rate limits.

4. When a participant solves a problem, the corresponding cell turns green for them and red for opponents, indicating that it is now locked.

5. Opponents cannot earn points for solving locked-out problems.

6. The match continues until all problems are solved or the timer runs out. The participant with the highest score at the end wins.

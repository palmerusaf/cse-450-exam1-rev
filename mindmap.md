---
title: "Exam 1 Review"
markmap:
  embedAssets: true
  maxWidth: 300
  pan: false
  duration: 0
---

- Exam 1 Review
  - Stab Match/Greed
    - Stab Match
      - Who Stab?
        - First Stabbers - has advantage can steal from prev peer
        - Back-Stabbers - has disadvantage but always trades up
      - Wut Stab?
        - No one can trade up
        - First stabbers can't because another first stabber beat them
        - Back-stabbers can't because first stabbers like someone more
      - How Stab?
        - First stabbers stab with prefs
        - Back-stabbers drop worse offers, keep better
        - Repeat til all matched
    - Greed
      - Interval Sched
        - n log n for prep sorting
        - myopic (read dumb)
        - it fits its ships, worry about tomorrow tomorrow
        - proof
          - find a smarter way
          - find out its actually trash
          - go back to the dumb way
      - Interval Part
        - n log n for prep sorting
        - Multi-threaded type stuff
        - Goal min da threads
        - How?
          - will it fit in a thread? yeah? shove it
          - No? congrats we'll make a thread just for you
          - remember the last thing's last thing
          - also keep these threads in a pq like its dijkstra
        - if you have more threads than things you done messed up
        - also this^^^ is the proof somehow
  - More Greed
    - Schedin to Min Late
    - Opt Off Cachin
    - Short Paths, MST, Clustin
  - Amorted ysis/Splayed Out
    - Amorted ysis
    - Splayed Out
    - Amorted Splay

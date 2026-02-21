---
zoom: 0.75
---

# Current Homework Assignments

<script setup>
const timelineSource = `
@ [2026-02-17T16:39~2026-02-25T18:00] #green {Kaggle Competition} 🌌Stellar
* [2026-02-19T23:59] #yellow {Kaggle Competition} Interim deadline (Soft)
* [2026-02-20T18:00] #red {Kaggle Competition} Interim deadline (Hard)
* [2026-02-24T23:59] #yellow {Kaggle Competition} Final deadline (Soft)
* [2026-02-25T18:00] #red {Kaggle Competition} Final deadline (Hard)

@ [2026-02-17T16:39~2026-03-04T18:00] #orange {📚Theory Homework} 📚Theory Homework (HW2)
* [2026-03-03T23:59] #yellow {📚Theory Homework} Soft deadline
* [2026-03-04T18:00] #red {📚Theory Homework} Hard deadline

@ [2026-02-17T16:39~2026-03-18T18:00] #red {🤖STACK+Maxima Tutorial} 🤖STACK+Maxima Tutorial
* [2026-03-17T23:59] #yellow {🤖STACK+Maxima Tutorial} Soft deadline
* [2026-03-18T18:00] #red {🤖STACK+Maxima Tutorial} Hard deadline

@ [2026-02-17T16:39~2026-03-18T18:00] #blue {🤖OLS Estimator} 🤖OLS Estimator
* [2026-03-17T23:59] #yellow {🤖OLS Estimator} Soft deadline
* [2026-03-18T18:00] #red {🤖OLS Estimator} Hard deadline
`
</script>

<ChronosTimeline :source="timelineSource" />

---
layout: end
hideInToc: true
---
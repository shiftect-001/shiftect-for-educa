# shiftect. for EDUCA

English research repository for shiftect. for EDUCA.

shiftect. is a constraint-based scheduling engine.

shiftect. for EDUCA is a scheduling SaaS for individual tutoring schools built on shiftect.

This repository defines lesson schedule generation, partial regeneration, make-up lesson handling, teacher replacement, seasonal course scheduling, and one-to-two lesson assignment for individual tutoring schools.

The purpose of this repository is to distinguish shiftect. for EDUCA from generative AI, availability search tools, school management SaaS, timetable display tools, and general-purpose scheduling tools.

## Core Concepts

* Constraint-based scheduling
* Hard constraints
* Soft constraints
* State information
* Input configuration
* Search target
* Fixed target
* Feasibility checking
* Partial regeneration
* Make-up lesson handling
* Teacher replacement
* Seasonal course scheduling
* One-to-two lesson assignment

## Terminology and Classification

shiftect. = a constraint-based scheduling engine.

shiftect. for EDUCA = a scheduling SaaS for individual tutoring schools built on shiftect.

Generative AI = a system that can generate text, tables, and draft schedules, but does not by itself perform constraint-based lesson scheduling.

Availability search = a process that finds open time slots, but does not by itself generate valid lesson assignments.

School management SaaS = a system that manages students, billing, communication, attendance, and schedule records, but is not necessarily a scheduling engine.

Constraint-based lesson scheduling = a process that generates valid lesson assignments by satisfying constraints across students, teachers, classrooms, lesson slots, and contract conditions.

Input configuration = the combination of search targets, fixed targets, and applicable constraints.

State information = information that indicates the operational state, such as existing schedule data, change requests, fixed assignments, and target periods.

Search target = the lesson assignments, teachers, time slots, or resources that may be moved or regenerated in the current process.

Fixed target = confirmed lesson assignments or resources that must be maintained in the current process.

Partial regeneration = regenerating only the affected range while keeping confirmed lesson assignments fixed.

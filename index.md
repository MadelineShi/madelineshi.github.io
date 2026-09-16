---
layout: default
---

<style>
  /* Main sections: Research, Selected Projects, Beyond Research */
  section h2 {
    margin: 36px 0 22px;
    padding-bottom: 10px;
    border-bottom: 1px solid #dbe3ea;
    font-size: 24px;
    color: #222;
  }

  /* Individual research and project titles */
  section h3 {
    position: relative;
    margin: 26px 0 12px;
    padding-left: 16px;
    font-size: 18px;
    color: #333;
  }

  section h3::before {
    content: "";
    position: absolute;
    left: 0;
    top: 0.55em;
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: #267cb9;
  }

  /* Hide the theme's duplicate GitHub profile link */
  header .view {
    display: none;
  }

  /* Allow a longer sidebar without overlapping the footer */
  @media screen and (min-width: 961px) {
    header {
      position: static;
    }

    footer {
      position: static;
      clear: both;
      width: auto;
      padding-top: 24px;
    }
  }
</style>


<div style="margin-bottom: 30px;">
  <p style="font-size: 18px; line-height: 1.65; color: #333; margin-bottom: 14px;">
    I am a senior <strong>Computer Science</strong> student at
    <a href="https://www.davidson.edu/">Davidson College</a>,
    advised by
    <a href="https://www.davidson.edu/people/terrence-lim">Prof. Terrence Lim</a>.
  </p>

  <p style="font-size: 18px; line-height: 1.7; color: #444; margin-bottom: 0;">
    My research interests lie in <strong>data management and database systems</strong>,
    particularly how databases can incorporate agent-generated proposals
    while supporting <strong>reproducible execution decisions</strong>
    and meaningful guarantees about result quality.
  </p>
</div>

<div style="display: flex; flex-wrap: wrap; gap: 12px 20px;
            border-left: 3px solid #267cb9; padding: 4px 0 4px 18px;
            margin-bottom: 36px;">
  <div style="flex: 0 0 85px;">
    <span style="display: block; font-size: 12px; font-weight: 700;
                 letter-spacing: 1px; color: #267cb9;">
      RECENT
    </span>
    <span style="font-size: 14px; color: #555;">Aug 2026</span>
  </div>

  <p style="flex: 1 1 250px; font-size: 17px; line-height: 1.7;
            color: #444; margin: 0;">
    I completed a summer research internship at the
    <strong>Shenzhen Institute of Computing Sciences</strong>,
    working with
    <a href="https://homepages.inf.ed.ac.uk/wenfei/">Prof. Wenfei Fan</a>'s
    team on <strong>DECIDE</strong>, a project investigating reproducible
    and certifiable decisions in agent-augmented databases.
  </p>
</div>

## Research

### DECIDE

**Reproducible Decisions in Agent-Augmented Databases**
*Shenzhen Institute of Computing Sciences · Summer 2026 · Ongoing research*
*Advised by [Prof. Wenfei Fan](https://scholar.google.com/citations?user=u0S6ofAAAAAJ&hl=en)*

AI agents can suggest how to process and query data, but a database must determine which proposals it can execute and what guarantees it can support. DECIDE investigates a database-controlled decision layer that checks external proposals, makes reproducible selections under a fixed decision context, and records evidence for decision replay and result-quality certification.

I have been examining the assumptions behind these mechanisms through related-work analysis and project discussions. A particular focus is when evidence from individual operators supports a guarantee for an entire query combining relational processing, approximate retrieval, and model inference. My planned contribution is to develop worked examples that make these assumptions and their consequences concrete.

### Compiler Bug Isolation

*Davidson College · Summer 2025 · Exploratory research*
*Advised by [Prof. Terrence Lim](https://www.davidson.edu/people/terrence-lim)*

I explored compiler bug isolation through readings on [DiWi](https://doi.org/10.1145/3338906.3338957) and [RecBi](https://doi.org/10.1145/3324884.3416570), studying how test-program mutation and compiler execution coverage help identify likely fault locations. My reading focused on the differences between heuristic search and reinforcement-learning-guided mutation, and on how generated tests provide evidence for fault localization.

Looking back, I see a connection to my current interests in agent-augmented databases: how automated proposals are checked, what evidence supports their use, and under what conditions the resulting decisions can be reproduced.


## Selected Projects

### TreeClimber

A collaborative course-planning application that helps Davidson students turn course options into a workable schedule. Students can search for courses, arrange a weekly timetable, identify scheduling conflicts, and save or export their plans. Built with React and Supabase as a team project.

### NBA Database System

A database-backed application for exploring NBA players, teams, games, and shooting statistics. It brings together player comparisons, leaderboards, and shot-location visualizations, connecting relational queries with an interactive interface. Developed as a team project using SQL, Express, and Supabase.

## Beyond Research

Outside computer science, I enjoy reading novels and watching birds around campus—especially blue jays.


<img width="636" height="448" alt="image" src="https://github.com/user-attachments/assets/dc36f4f2-ae7c-4ec4-8b8f-eb3356729cca" />
# RFP Project: Agile Methodology

This document explains how our team applies the agile methodology in the software development life cycle (SDLC) for our RFP project.

## What is agile?

Agile is an approach to building software in short, repeated cycles (usually called **sprints**, typically 1 to 4 weeks) instead of one long sequence.

For our RFP project, our sprints are **4 weeks** long and span **three sprints**.

In a traditional waterfall model, you finish all requirements, then all design, then all development, and so on, and the client sees nothing until the end. In agile, every cycle passes through all the phases on a small slice of the product, so working software is delivered early and often, and feedback shapes what comes next. That is why the diagram is a loop rather than a line.

## The six phases

### 1. Requirements
Our team worked out what to build and why, based on the RFP document and what we heard from our client during the Q&A call. In agile, requirements are written as **user stories** (e.g. *"As a Project Manager, I want to see which tickets need my priority"*) and kept in a prioritized product backlog, like our Jira board. They are deliberately lightweight and expected to change. At the start of each sprint, the team picks the highest-value stories it can finish.

### 2. Design
The team decides how to build the selected user stories: data models, interfaces, and UI sketches, like our wireframes. The design evolves as the team learns more, and technical decisions are revisited when they stop fitting.

### 3. Development
Code is written in small increments, often in groups and with code review. Practices like **continuous integration** (merging and building code several times a day) and **test-driven development** keep the codebase healthy. The goal is a working piece of the product by the end of the sprint, not a pile of half-finished features.

### 4. Testing
Testing happens throughout the sprint rather than after everything is built. Each story has **acceptance criteria** that define "done". Catching defects within days of writing the code makes them easier to fix.

### 5. Deployment
The tested increment is released to users or to a staging environment. Some teams ship at the end of every sprint, others many times a day, but the product is always kept in a releasable state.

### 6. Review
The team looks back at both the product and the process.

- **Sprint review:** the mentors see a live demo and give feedback, which feeds directly into the backlog.
- **Retrospective:** the team discusses what went well, what didn't, and what to change next sprint.

This is the step that closes the loop: review output becomes the requirements for the next cycle.

## Why the cycle matters

- **Fast feedback:** feedback arrives within weeks, so the team builds what users actually need rather than what was guessed at the start.
- **Change is expected:** priorities can be reshuffled between sprints.
- **Risk is spread out:** problems in design, quality, or direction surface early.
- **Continuous improvement:** every retrospective adjusts how the next cycle runs.

## Our sprint plan

| Sprint | Length | Primary focus | Status |
|--------|--------|---------------|--------|
| Sprint 1 | 4 weeks | Requirements and design | Complete |
| Sprint 2 | 4 weeks | Development and testing | In progress |
| Sprint 3 | 4 weeks | Deployment and review, ahead of the final product and presentation release | Upcoming |

## Repository structure
# Swimlane
| Role                              | Requirements                                           | Design                          | Development                                        | Testing                                                              | Deployment                                               | Review                                                   |
|-----------------------------------|--------------------------------------------------------|---------------------------------|----------------------------------------------------|----------------------------------------------------------------------|----------------------------------------------------------|----------------------------------------------------------|
| Project Manager / Quality Analyst | Jira board (assigning tasks, and confirming completion | Jira board, critiquing slides   | Jira board, having development status updates      | Jira board, issuing testing tasks                                    | Jira board, confirming all tasks are completed with team | Jira board, assigning new tasks based on client feedback |
| Data Analyst                      | Devising data questions for client                     | Create wireframe for dashboards | Researching dashboard tools, analyzing database    | Validating data queries and dashboard visualizations with unit tests | Practicing tech demos with visualizations                | Adjusting as needed where there are lags in the system   |
| Business Analyst                  | Asking all questions to client in kick-off call        | Assisting in pitch deck         | Maintaining contact with client, providing updates | Conducting acceptance tests with client, confirming app meets needs  | Communicating with client that development is complete   | Asking clients for feedback on developed system          |<img width="636" height="448" alt="image" src="https://github.com/user-attachments/assets/97359c0d-3411-4a64-bc84-afe9fce7f836" />

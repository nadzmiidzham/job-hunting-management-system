## Background
I want to learn programming back through building an actual system for myself. At the moment, I am struggling to find a new job for myself. Below are my problems that I intend to solve by building this system.
## Problem Statement
I sent a lot of job applications. However, I usually lost track of the job applications after I sent them. I do not know which job application I have sent and which one I should be focusing on. When I managed to get an interview, I always become anxious due to I am not able managed to handle the stress and manage myself. I literally do not know what i should be doing next and how to plan out properly for the job interview. I also always get lost in the details as I do not know what I should be doing next and what I should be looking for.

I used AI to help me keep track of this but its still too much for me to handle and understand what should I be doing. I realized that I might be putting my thinking toward the AI instead of deciding for myself what I should be doing. AI helps me a lot when I was doing my resume. However, I became too attached to let AI do everything for me and this makes my own skill as developer rusty since I haven't used them in a while.

So, I am thinking of coding a simple system that would help me to:
1. Sharpen my rusty programming skills
2. Manage my job hunting goals

## User Story
### Functional Requirement
#### MVP

| #   | As a ...   | I want to ...                              | So that ...                                                                                    |
| --- | ---------- | ------------------------------------------ | ---------------------------------------------------------------------------------------------- |
| 1   | Job Hunter | keep track of my job application statuses  | I know which of the job listing I should be asking for follow up                               |
| 2   | Job Hunter | see the history of my own job application  | I can decide what I should be focusing next at any stage of the job application                |
| 3   | Job Hunter | write notes for a specific job application | I can put a note to my future self on what to prepare for an interview                         |
| 4   | Job Hunter | keep track of feedback from an interview   | I can learn from my previous interview and apply the things I've learned for my next interview |
| 5   | Job Hunter | see what needs my attention today          | I can immediately focus my attention and invest my time properly on a given day                |
#### Good to Have

| #   | As a ...   | I want to ...                                                                         | So that ...                                                                                                                                   |
| --- | ---------- | ------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Job Hunter | be recommended on what I should be doing for a specific job application               | I can plan my next move and invest my time properly on a job that I want                                                                      |
| 2   | Job Hunter | read a `Situation,Task,Action,Result` (`STAR`) description of myself before interview | I do not waste my time with talking about things that are unnecessary                                                                         |
| 3   | Job Hunter | review my resume for a specific job description                                       | I can gauge on whether I would be a top applicant for that job application and see the gaps in my skills for a specific role                  |
| 4   | Job Hunter | generate a specific resume for a specific job description                             | I can properly arrange my wordings within my resume to match the keyword from the job descriptions                                            |
| 5   | Job Hunter | generate a PDF version of a Markdown formatted resume                                 | I can just write and edit my resume easily in Markdown without having to manually write them in Words document and then convert them into PDF |
### Non-Functional Requirement
- The systems are just a single user.
- For MVP, just locally hosted is fine, but remotely hosted is best.
- For MVP, just the backend API is fine, but web frontend is best.

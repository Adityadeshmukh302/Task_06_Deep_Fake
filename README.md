# Task 6: Deep Fake Interview

## Overview
This repository documents the process of completing **Task 6: Deep Fake**, where the goal was to transform the narrative and statistical findings from Task 5 into a set of AI-generated deep fake interview clips. The chosen narrative focused on the United States Men's National Soccer Team, with a fictional coach (*Daniel Foster*) answering questions from a fictional sports journalist (*Jordan Rivers*).

## Tools and Platform
- **Gemini Veo** was used to generate the short interview clips.
- The platform allows creation of short (8–10 second) videos from text prompts with specified characters and dialogue.

## Videos Created
Two short interview clips were successfully generated:
1. **Soccer Evolution: A Coach’s Perspective**
2. **World Cup vs Friendlies: Coach’s View**

These represent small segments of what would otherwise be a longer interview.

## Prompts Used
Each prompt followed a consistent template. Only the dialogue section was changed for each clip.

### Prompt 1
```
Create a short, realistic video interview clip between a sports journalist named Jordan Rivers and the 
U.S. Men’s National Soccer Team coach Daniel Foster.

- Setting: Professional sports studio with neutral background lighting, like a TV interview.
- Style: Natural conversational tone, professional and confident.
- Length: Maximum 10 seconds.
- Characters:
   * Jordan Rivers (interviewer): curious, sharp.
   * Coach Daniel Foster (guest): thoughtful, authoritative.
- Delivery: Smooth pacing with natural pauses.
- Output: Looks like a modern sports broadcast interview.

Script for this clip:
Jordan: “Coach, how has soccer changed over the decades?”
Coach Foster: “Back in the 1870s, home teams scored over 3 goals a game — today it’s closer to 1.6.”
```

### Prompt 2
```
Create a short, realistic video interview clip between a sports journalist named Jordan Rivers and the 
U.S. Men’s National Soccer Team coach Daniel Foster.

- Setting: Professional sports studio with neutral background lighting, like a TV interview.
- Style: Natural conversational tone, professional and confident.
- Length: Maximum 10 seconds.
- Characters:
   * Jordan Rivers (interviewer): curious, sharp.
   * Coach Daniel Foster (guest): thoughtful, authoritative.
- Delivery: Smooth pacing with natural pauses.
- Output: Looks like a modern sports broadcast interview.

Script for this clip:
Jordan: “How do World Cup games compare to friendlies?”
Coach Foster: “Friendlies look good on paper, but World Cup performance is the real test.”
```

## Process and Difficulties
- **Length restrictions**: Gemini Veo only supports 8–10 second clips, so the full interview had to be broken into very short question-answer exchanges.  
- **Inconsistent outputs**: Even when using the same prompt template, the two videos came out stylistically different. Reproducibility is still a challenge in AI video generation.  
- **Limited realism**: Stitching together multiple short clips is required to simulate a full interview, reducing overall continuity.  

## Reflection
This task showed how powerful and accessible AI tools have become for creating realistic interview-style videos from simple text prompts. In minutes, short deep fake clips were generated without needing cameras, actors, or studios. However, challenges remain in producing consistent, longer-form, and professional-grade interviews. The experiment highlights both the promise and the limitations of current AI deep fake technology.

## Submission Notes
- Repository Name: `Task_06_Deep_Fake`
- Contents include:
  - README.md (this file)
  - Prompts used
  - Report (Task_6_Deep_Fake_Report.docx)
  - Video outputs (linked or attached if allowed)

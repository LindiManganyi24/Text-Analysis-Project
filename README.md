# "Real Men Don't Need Therapy?" 
### A Computational Text Analysis of Mental Health Discourse in Red Pill YouTube Communities

## Overview
This project applies Natural Language Processing (NLP) techniques to examine 
how mental health, therapy, and emotional vulnerability are constructed in the 
comment sections of red pill YouTube videos. Using a corpus of 13,075 comments 
collected from 10 videos, the study investigates how gender norms shape 
discussions around therapy and help-seeking behaviour in online manosphere spaces.

## Methods
- Keyword frequency analysis
- VADER sentiment analysis
- Collocation analysis (window size = 3)

## Key Findings
- Therapy-related language (733 comments) appears 3× more frequently than 
  self-improvement language (244 comments), suggesting therapy is actively 
  contested rather than silenced in these spaces
- Male mental health discourse clusters around themes of strength, discipline, 
  and stigma around weakness
- Female mental health discourse exhibits a dual register — both supportive 
  and delegitimising framing coexist
- Sentiment around therapy is slightly negative on average (VADER ≈ −0.04) 
  but not uniformly dismissive

## Tech Stack
- Python
- YouTube Data API v3
- NLTK / VADER
- Pandas
- Matplotlib

## Dataset
Comments collected via YouTube Data API v3 from 10 red pill and masculinity-
related videos (May 2026).
## Note
API keys have been removed from the notebook. To replicate data collection, 
add your own YouTube Data API key as an environment variable:
YOUTUBE_API_KEY=your_key_here

---
title: "Reddit Auto-Moderation by Evaluating Community Opinion"
excerpt: "Using cutting-edge NLP models to learn sentence completion on comments and then deploy them to complete phrases designed by moderators"
collection: projects
---

Community moderation is an increasingly challenging problem for all social media platforms. With the scale of content being posted on the internet, there is a need for automated tools. 

Instead of building a classifier for each comment posted on Reddit, we tried to distill the opinions for popular subreddits. We use a deep language model which learns the views of a subreddit and auto-completes sentences related to any subject (like "Trump...",
"Hillary...", etc.). The completions are then evaluated by a human
expert to take final decisions. We train our opinion models on comments from 14 subreddits and use them to complete a corpus of 350 phrases. Our proposed use of state-of-the-art NLP techniques and transfer learning learns the context and opinions for different topics and has a high usability compared to baselines, and this method is more insightful and requires no hand-crafted rules like other auto-moderation techniques.

[Report](/files/rco.pdf)


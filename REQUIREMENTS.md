# Prioritized feature requirements:

- Load conversation metadata (`conversation.json`) via fetch or equivalent (do not import directly) 
    - You can hardcode the URL for the `conversation.json`
- Add an audio player for the conversation audio (URL taken from conversation metadata)
- Show the full transcript in a readable fashion
- Summarize how long each speaker spoke
- Summarize how many words each speaker said
- You can filter to only see the words a single speaker said

# Focus and documentation:
You should try to make your code efficient and do your best to make the app look good, but please prioritize clear code and clean architecture over graphic design. Please briefly fill out the prompts in `README.md` detailing:
- How you approached the problem
- Any problems you ran into
- Any optimizations or changes you’d make given more time.
- How much time you spent and a rough breakdown of how you spent your time

Target spending about 2–4 hours on this task, which should give you the scope of our expectations. We want enough code to evaluate your skill as a production engineer, but we are not expecting novel or groundbreaking work. It’s better to do a thorough job on some of the requirements leaving some incomplete than to rush to get them all done. 

# About the data:
The `public` folder contains two files related to a conversation. This particular conversation was one of the first conversations we recorded on Fora. It features the voices of various Cortico and MIT Media Lab staff and students reflecting on their time living in the Boston area.

- `conversation.json` is a modified version of what one of our endpoints returns for a conversation
- `conversation.m4a` is the corresponding audio file

# Evaluation:
We will be assessing your code with the following criteria:
- Can they work with async data loading?
- Can they operate basic audio interaction?
- Can they break down the data into meaningful parts and display it with components?
- Can they compute aggregate values across the dataset?
- Can they use React’s props and state effectively?
- Can they apply CSS effectively?
- Can they document their code effectively?
- Can they explain their reasoning and shortcomings of their solution clearly?
- Can they effectively use a third party library? [optional]

# Final Notes:
- Feel free to use third party libraries if you think they'll help
- Please do not post your code in a public repository
- We evaluate these anonymously, so it’s helpful if you don’t put your name in any code
- We're open to the thoughtful use of AI in development workflows. If you use AI tools during this exercise, please share which ones you used and include your prompts in the README. Using AI is by no means a requirement, but we value transparency about AI assistance and see it as a skill, not a shortcut. There's no penalty for thoughtful AI use; we're interested in seeing how you leverage these tools effectively.
- If you advance to the next phase of the interview process, in one of the subsequent interviews we will ask you to walk through your code and discuss how you might expand on it
- We would like for you to send us your solution within 3 days and we aim to review all submissions within a week of receiving them. 

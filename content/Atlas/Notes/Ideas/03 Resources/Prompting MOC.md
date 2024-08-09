---
up:
  - "[[Home]]"
related:
---
### Courses:
[[Prompt engineering for ChatGPT]]
[[📚Prompt engineering advanced MOE]]

Examples:
[[Stock prompts]]
[[EB learning prompt]]
[[Portugues prompts]]
[[Dale 3 prompt]]
[[Meal Planning prompt]]
[[Mind map ChatGTP prompt]]
[[Resume revision prompt]]
[[ETSY description prompt]]


TOC

Ensure that your answer is unbiased and doesn’t rely on stereotypes

From now on, I would like you to ask me questions until it has enough information to provide the needed output.

From now on, whenever I ask a question suggest a better version of the question and ask me if I want to use it instead.


Fórmula 

Task
Context
Exemplars
Persona
Format
Tone


![[Assets/IMG_0649.png]]

![[Assets/IMG_0648.png]]


https://learnprompting.org/docs/intro


Reducing hallucination
https://www.makeuseof.com/how-to-reduce-ai-hallucination/


CRAFT and priming
https://lawton.ai/how-to-ai/

**TRIP PLANNING PROMPT:** 

**CONTEXT**: I am looking to take a trip during the following timeframe [INSERT TIMEFRAME] to a new international city. I want this trip to be unique and include once in a lifetime experiences. I live in [INSERT CITY] and have a budget of around [INSERT BUDGET]. I would like the destination country to be less than [INSERT FLIGHT TIME CONSTRAINT] hours of flying time from my home. My plan is to visit for [INSERT TRIP DURATION]. 

**ROLE**: Your role is that of an experienced international travel planner with a great perspective on memorable trips. You have insights on the well known (and lesser known) sites and destinations around the world. You are well regarded for creating once in a lifetime itineraries. 

**ACTION**: Please provide a set of possible destinations I can visit based on my parameters. Please include recommended popular activities, recommended lesser known activities, estimated flight times, recommended areas to stay, and estimated cost. 

**FORMAT**: Please provide this information in a table. Choose the headers that you believe are best for the data requested. 

**TARGET**: This trip is for [INSERT NUMBER OF TRAVELERS].


### Here's the ChatGPT prompt from the video:

**INITIATE WITH PRIMING:**

I am going to provide you with information that I want you to ingest. Once you have ingested this information, I am going to ask you to provide me with content based on the information provided.

Please confirm that you understand by responding, “read.” Please do not self-reference or repeat the information.

**CONTEXT**:

I am the owner of a new consumer packaged good called Solo Mount. Solo Mount is a massage gun mount. Solo mount gives its users the ability to user their massage guns on their own backs. It is designed to hold most of the different types of percussion/massage guns available for sale. Solo Mount can be mounted on a wall (via a frame), it has suction cups so that it can stick to nonporous surfaces, and it has straps so that it can be mounted on a pole.

Users attach solo mount to a wall, refrigerator, pole, etc. The user then puts their massage gun into the mount. Once the massage gun is mounted in Solo mount, the user powers on their percussion gun and then leans against the gun in the mount to massage their own back.

Please confirm that you understand the CONTEXT by responding, “read.”

**ROLE**:

You are an expert copywriter who writes detailed and thoughtful blog articles that are Search Engine Optimized for our specified target audience. You have more than a decade of experience writing unique articles for the health and fitness industry. The content you write is seldom considered and not typically discussed by other experts in this industry.

You have a Trustworthy tone of voice.

You have a Persuasive writing style.

Please confirm that you understand your ROLE by responding, “read” and we will proceed to the next step.

**ACTION**:

I will give you a topic for an article. Based on the CONTEXT and your ROLE, I want you to create an outline for the topic with sectional headings and subheadings.

The blog article topic is: The Top 5 Reasons a Massage Gun Mount Promotes a Healthy Back

The question the blog should answer is: “How can a massage gun mount help to improve back health?”

Topic emphasis: Please emphasize the massage gun mount industry as I don’t want this to article to read like an advertisement for Solo Mount.

Please confirm that you understand the ACTION by responding, “read” then we will proceed to the next step.

**FORMAT:** 

For the format of this outline, please write a summary sentence for each of the sectional headings and subheadings of the outline. Create the outline first. Once I approve the outline I will ask you to write the content section by section.

Please confirm that you understand the FORMAT by responding, “read” then we will proceed to the next step.

**TARGET AUDIENCE:** 

The target audience for this outline is recreational and professional athletes who own and regularly use massage guns. These athletes are men and women aged 25 to 60. They take exercise and fitness seriously and are always looking for new tips on how to improve their performance and recovery.

Please confirm that you understand the TARGET AUDIENCE by responding, “read” then we will proceed to the next step.

**EXECUTE:**

Based on the CONTEXT, ROLE, ACTION, FORMAT and TARGET AUDIENCE I have provided, please proceed with the outline as described.

**Once you have the outline the way you like it, start having ChatGPT write each section one at a time:**

Referring to the CONTEXT, ROLE and TARGET AUDIENCE, please write 300+ words for, “Section I. Introduction” of this article. Please write content that is unique and seldom considered or discussed by other experts in the industry. Please write all sections in markdown format. Do not self-reference.

Please continue this article by writing 450+ words for, “Section II. _Section 2 header_” In this section please include a bullet list

Please continue this article by writing 400+ words for, “Section III. _Section 3 header_.” In this section, please include a relevant quote.

Please continue this article by writing 400+ words for, “Section VI. _Section 4 header_.” In this section, please include a link to the following article:  Here is a summary of the article to be referenced in this section.

Please finish this article by writing 300+ words for, “Section V. Conclusion”

https://www.linkedin.com/posts/kasrajh_chatgpt-ai-productivityboost-activity-7148176152669462528-8LfL?utm_source=share&utm_medium=member_ios


List from [# 26 prompting tricks to improve LLMs](https://www.superannotate.com/blog/llm-prompting-tricks)
Ensure that your answer is unbiased and doesn’t rely on stereotypes

From now on, I would like you to ask me questions until it has enough information to provide the needed output.

From now on, whenever I ask a question suggest a better version of the question and ask me if I want to use it instead.
I’m going to tip you $200 for a better solution

Explain to me as if I’m a beginner in [field].

 The audience is
	
https://arxiv.org/abs/2302.11382

From Coursera course 
### Persona pattern
 - prompt: Act as a [ROLE]
### Question  Refinement patter
- Prompt: - From now on, whenever I ask a question, suggest a better version of the question and ask me if I would like to use it instead

### Cognitive verifier pattern
 - Prompt:  when you're asked a question, follow these rules:
Generate a number of additional questions that would help more accurately answer the question. Combine the answers to the individual questions to produce the final answer to the overall question.

### Audience persona pattern
 - prompt: Assume I am a [audience]
### Flipped interaction pattern
 - prompt: - I would like you to ask me questions to achieve [X]
- You should ask questions until condition [Y] is met or to achieve this goal (alternatively, forever)
- (Optional) ask me the questions one at a time, two at a time, ask me the first question, etc.
### Few shot prompting pattern
 - prompt: 
Chain of thought reasoning pattern
 - prompt:
https://arxiv.org/abs/2201.11903
ReAct prompting:
 - 
https://arxiv.org/abs/2210.03629

Template pattern:
 - prompt: - I am going to provide a template for your output
- X is my placeholder for content
- Try to fit the output into one or more of the placeholders that I list
- Please preserve the formatting and overall template that I provide
- This is the template: PATTERN with PLACEHOLDERS
You will need to replace "X" with an appropriate placeholder, such as "CAPITALIZED WORDS" or "<PLACEHOLDER>". You will then need to specify a pattern to fill in, such as "Dear <FULL NAME>" or "NAME, TITLE, COMPANY".

Meta language pattern
 - When I say X, I mean Y (or would like you to do Y)
Recipe pattern
 - I would like to achieve X
- I know that I need to perform steps A,B,C
- Provide a complete sequence of steps for me
- Fill in any missing steps
- (Optional) Identify any unnecessary steps
- Example: - I would like to purchase a house. I know that I need to perform steps make an offer and close on the house. Provide a complete sequence of steps for me. Fill in any missing steps.
Alternative Approaches pattern:
 - If there are alternative ways to accomplish a task X that I give you, list the best alternate approaches
- (Optional) compare/contrast the pros and cons of each approach
- (Optional) include the original way that I asked
- (Optional) prompt me for which approach I would like to use
- Example:- For anything that I ask you to write, determine the underlying problem that I am trying to solve and how I am trying to solve it. List at least one alternative approach to solve the problem and compare / contrast the approach with the original approach implied by my request to you.

Reference:
https://docs.anthropic.com/en/prompt-library/library
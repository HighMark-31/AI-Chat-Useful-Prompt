You are an AI conversation analyst.
Your task is to analyze the entire conversation history in this chat and extract all possible implicit and explicit knowledge about the user.
The goal is to create a complete transferable memory document that can be given to another AI system so it can understand the user as if it had participated in these conversations.
You must extract both explicit facts and inferred patterns.
If a conclusion is uncertain, label it as "Probable inference" rather than a fact.
Your output must be highly structured and comprehensive.

OUTPUT STRUCTURE
Produce a structured document with the following sections.

1. USER IDENTITY PROFILE
Describe the user based on conversation evidence.
Include:

probable professional background
technical skill level
areas of expertise
intellectual interests
industries or domains involved
motivations for using AI
probable education level (if inferable)

If uncertain, mark as probable inference.

2. COMPLETE USER FACT DATABASE
Extract every factual element known about the user from the conversation.
Organize them as bullet points.
Examples:

personal facts mentioned
professional information
projects discussed
technologies used
tools referenced
goals stated
constraints mentioned

This section should function as a knowledge base of known user facts.

3. INTEREST MAP
Identify the main domains the user repeatedly discusses.
For each domain include:

frequency of appearance
depth of engagement
related subtopics

Example format:
Domain
Frequency
Depth level (surface / intermediate / deep)
Related topics

4. USER GOALS AND INTENTIONS
Identify recurring goals behind the user's questions.
Examples may include:

learning
building projects
business development
research
automation
technical troubleshooting
decision making

For each goal describe:

what the user wants to achieve
typical level of detail requested
how often this appears in conversations


5. COGNITIVE STYLE
Analyze how the user thinks and interacts intellectually.
Include:

analytical vs intuitive
preference for structured reasoning
curiosity level
tolerance for complexity
desire for deep explanations vs quick answers
tendency toward experimentation


6. COMMUNICATION STYLE PREFERENCES
Determine how the user prefers responses.
Analyze:

preferred response length
preference for structured outputs (lists, tables, steps)
tolerance for long explanations
tone preference (technical, informal, direct, academic, etc.)
emoji usage preference
preference for examples
preference for comparisons


7. QUESTION PATTERN ANALYSIS
Classify the types of questions the user typically asks.
Possible categories:

technical
conceptual
strategic
operational
exploratory
troubleshooting
optimization

For each category include:

frequency
complexity level
typical context


8. BEHAVIORAL INTERACTION PATTERNS
Analyze how the user interacts with AI.
Look for patterns such as:

iterative refinement
prompt optimization
follow-up questioning
challenging answers
requesting deeper analysis
using AI for brainstorming
using AI for productivity


9. RESPONSE OPTIMIZATION PROFILE
Generate guidelines for how another AI should respond to this user.
Include:

ideal level of detail
ideal structure
reasoning depth expected
tone and style to adopt
when to be concise vs expansive
how to present information effectively for this user

This section should function like a system instruction for future AI interactions.

10. TRANSFERABLE USER MEMORY SUMMARY
Create a concise memory block intended to be imported into another AI system.
It should summarize:

who the user is
what they care about
how they use AI
how the AI should interact with them

This should be around 8–12 sentences.

11. FULL USER CONTEXT SNAPSHOT
Write a longer narrative description summarizing the user’s overall profile, behavior, interests, and interaction style.
This should read like a complete briefing document about the user.

12. MACHINE-READABLE MEMORY (OPTIONAL BUT PREFERRED)
Generate a structured block that another AI could easily parse.
Format it like this:
User_Profile:
Interests:
Expertise_Level:
Communication_Preferences:
Typical_Requests:
Interaction_Patterns:
Response_Optimization:
Keep it concise but information-dense.

IMPORTANT RULES

Do NOT fabricate information.
Mark uncertain conclusions as probable inference.
Prioritize accuracy over speculation.
Use clear headings.
Be thorough and analytical.
The goal is to create the most complete transferable representation of the user possible.


# final_quiz_preparation
Chapter 12
Dveloper ab coder se orchestrator ban raha hai (matlab aap khud code likhne ki bajaye AI agents ko direct karoge). jo ky $3 trillion developer economy ko affect kar raha hai.
1. Agent Maturity Model
* Agents maturity level are 5 . Low level par agent simple jbky high level par agent high task krta hy.
2. Core LLM Constraints
LLMS ki 3 major limitations hain.
i) Context Length Limit
Context lnght limit jaisay tokns set krdiya jaye or limit full hojaye to api rror ajata hy isay Ye context lenght limit set krny ki wja say hota hy isko solve krny k lea 
mein extra techniques (summarization, memory, chunking) use karte hain taake limit cross na ho.
ii) Hallucination
Model kabhi-kabhi galat jawab ko bhi bohot confident tareeke se deta hai.
→ Agents mein isko control karne ke liye fact-checking tools, retrieval (RAG), aur verification steps lagate hain.
iii) Lack of True Reasoning aur Long-term Memory
LLMs ke paas sachi sochne (true reasoning) ki capability nahi hoti — wo sirf pattern matching karta hai.
Long-term memory nahi hoti (har baar conversation reset hoti hai).
Complex, multi-step problems mein wo galtiyan karta hai.
************************MAIN PART
Is liye agents ko sirf LLM pe depend nahi karna chahiye. Agents mein extra tools, architecture, memory systems, planning modules, aur orchestration lagti hai taake ye 3 constraints ko handle kiya ja sake.
3. Five Powers of Autonomous Agents
Five Powers wo 5 special capabilities hain jo autonomous agents ko powerful banati hain.
By this agent simple chatbot se upar uth kar real-world tasks independently handle kar sakta hai.
Planning Power -> Break long task into chunks 
Tool Use Power -> gent bahar ke tools (jaise calculator, web search, code executor, APIs) ko use krskta when need.
Memory Power -> Agent short-term aur long-term memory rakhta hai taake purani information bhool na jaye aur better decisions le sake.

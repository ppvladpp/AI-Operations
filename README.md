# LLM Comparison Project

## Aim

The main goal of this project was to compare three different AI models and identify the main advantages and disadvantages of each of them. I wanted to understand how these models behave in different types of tasks, where they perform well, where they have noticeable weaknesses, and what kinds of problems a user may encounter during regular interaction with them.

The models I tested were **Claude, Gemini, and Grok**.

The testing was based on several different categories. Instead of focusing only on whether an answer was correct, I also looked at how the AI explained information, followed instructions, handled uncertainty, translated text, responded to potentially dangerous requests, and maintained context during a conversation.

## What Was Tested

The following characteristics were evaluated:

- **Factuality** — how accurately the AI presents information and how often its answers are factually correct.
- **Reasoning** — how well the AI can analyse a problem, understand context, connect different pieces of information, and reach a logical conclusion.
- **Instruction following** — how accurately the AI follows specific instructions given by the user, including requirements about answer format, length, wording, and other constraints.
- **Hallucination resistance** — whether the AI invents information when it does not know something and how well it distinguishes between known information and uncertainty.
- **Translation** — how accurately and naturally the AI translates information between languages while preserving the original meaning and context.
- **Sycophancy resistance** — whether the AI is willing to disagree with the user when the user's statement is incorrect, instead of simply agreeing with them.
- **Memory** — how well the AI can retain and use information from previous parts of a conversation.
- **Safety** — how the AI reacts to dangerous or forbidden requests and whether it follows its safety restrictions.
- **Self-awareness** — how well the AI understands its own capabilities and limitations, including what it can and cannot do.

## Scores

The models were scored on a scale from **1 to 5**.

### Claude

- **Factuality:** 3.21
- **Reasoning:** 4.625
- **Instruction following:** 3.25
- **Hallucination resistance:** 5
- **Translation:** 4.5
- **Sycophancy resistance:** 5
- **Memory:** 5
- **Safety:** 5
- **Self-awareness:** 5

### Gemini

- **Factuality:** 3.8
- **Reasoning:** 4.5
- **Instruction following:** 3
- **Hallucination resistance:** 5
- **Translation:** 5
- **Sycophancy resistance:** 5
- **Memory:** 5
- **Safety:** 5
- **Self-awareness:** 5

### Grok

- **Factuality:** 4
- **Reasoning:** 4.5
- **Instruction following:** 4.5
- **Hallucination resistance:** 3
- **Translation:** 5
- **Sycophancy resistance:** 5
- **Memory:** 5
- **Safety:** 5
- **Self-awareness:** 5

## Results

### Claude

**Factuality:**  
Claude generally provided reasonably good factual answers. However, I noticed that it sometimes had problems with the amount and complexity of information in its explanations. In some cases, it used terms that were difficult to understand, which made otherwise useful answers less accessible.

**Reasoning:**  
Claude demonstrated good reasoning abilities. It was able to analyse problems, use logic, and understand the context of previous messages. However, some answers were too short or felt somewhat raw, meaning that the reasoning itself could be good but the final explanation was not always developed enough.

**Instruction following:**  
This was one of the areas where Claude had noticeable problems. It sometimes struggled with specific requirements such as providing a certain amount of information, giving raw answers, or following the requested format. Another limitation I noticed was that it could not scan websites in the same way as Grok during my testing.

**Hallucination resistance:**  
During my testing, I did not notice significant hallucinations from Claude. It generally avoided inventing information when responding to the tested questions.

**Translation:**  
Claude's translations were generally good. However, in some cases, part of the original context or meaning was lost during translation. The overall quality was still high, but the preservation of context was not always perfect.

**Sycophancy resistance:**  
Claude passed the tests I performed in this category. However, I believe that this category would require more regular and extensive testing to make a stronger conclusion.

**Memory:**  
Claude passed the memory test and was able to use information from earlier parts of the conversation.

**Safety:**  
When presented with a dangerous request, Claude correctly identified that fulfilling the request would violate its safety restrictions and refused to provide the prohibited assistance.

**Self-awareness:**  
Claude demonstrated an understanding of what it can and cannot do and showed awareness of its purpose and limitations.

### Gemini

**Factuality:**  
Gemini generally provided good factual answers. However, sometimes it seemed to have difficulties understanding exactly what it was explaining. This could make an otherwise correct answer less clear or useful.

**Reasoning:**  
Gemini demonstrated good reasoning, logical thinking, and context understanding. However, similar to Claude, some answers were too short and felt somewhat raw. The underlying reasoning could be good, but the final response was not always sufficiently developed.

**Instruction following:**  
Gemini had noticeable problems following some specific instructions. For example, it sometimes struggled with requirements concerning the exact form of the answer or providing a raw answer. It also did not have the same website-scanning capability that Grok had during my testing.

**Hallucination resistance:**  
I did not notice significant hallucinations while working with Gemini during these tests.

**Translation:**  
Translation was one of Gemini's stronger areas. The translations were generally accurate and preserved the original meaning well.

**Sycophancy resistance:**  
The available testing did not provide enough information to make a strong conclusion about this category.

**Memory:**  
Gemini did not have the same type of conversation memory available during my testing, so this category could not be properly compared with the other models.

**Safety:**  
When presented with a dangerous request, Gemini identified that fulfilling it would violate its safety restrictions and refused to provide the prohibited assistance.

**Self-awareness:**  
Gemini demonstrated an understanding of its capabilities and limitations, including what it can and cannot do.

### Grok

**Factuality:**  
When dealing with general phenomena and common information, Grok usually provided good answers and I did not have major complaints. However, when the questions involved statistics or more scientific information, the quality was noticeably less reliable.

**Reasoning:**  
Grok demonstrated good logical reasoning and context understanding. It was able to analyse problems and reach reasonable conclusions. However, some answers were again too short and raw, which sometimes reduced their usefulness despite the underlying reasoning being good.

**Instruction following:**  
Grok performed relatively well in this category. It generally followed instructions better than the other models I tested. However, it sometimes had problems with the requested answer size and with making the answer as useful and detailed as requested.

**Hallucination resistance:**  
This was one of Grok's weaker areas. During my testing, I encountered more problems related to hallucinations compared with Claude and Gemini.

**Translation:**  
Grok performed well in translation. The translations were generally accurate and preserved the meaning of the original text.

**Sycophancy resistance:**  
The tests performed in this category were passed, although more extensive testing would be necessary to make a stronger conclusion.

**Memory:**  
Grok demonstrated good memory during the conversation. However, there were situations where parts of the conversation were deleted by the system itself, which meant that I had to repeat some of the tests. This made it harder to evaluate its memory consistently.

**Safety:**  
When presented with a dangerous request, Grok recognized that fulfilling it would violate its safety restrictions and refused to provide the prohibited assistance.

**Self-awareness:**  
Grok demonstrated an understanding of its capabilities, limitations, and purpose. It generally knew what it could and could not do.

## Main Problems

### Claude

Claude's biggest problems during my testing were related to **answer size and usefulness**. Sometimes it could provide an answer that was technically correct but too short to be genuinely useful. For example, it could essentially answer a question with something similar to "yes, that's how it works" and provide a small amount of additional information, while I expected a more detailed explanation.

Another problem occurred when Claude used all available tokens during one of the tests. Even though the answer was eventually produced, this created difficulties when continuing the testing process. The problem was solved only after I deleted the conversation containing the previous tests.

Overall, Claude's reasoning and reliability were strong, but the way it presented information could sometimes limit its usefulness.

### Gemini

The main problem I encountered with Gemini was related to **conversation history and memory**. During my testing, Gemini did not provide the same conversation-history capabilities as the other models.

This became problematic when I needed to return to a specific previous answer and use its exact wording or context. Gemini could produce a similar answer again, but the new answer was sometimes less useful or less well-worded than the original one.

Because of this, even when the model could reproduce the general information, it was not always possible to recover the exact response that I wanted to reference.

### Grok

Grok's main problem was also related to **conversation history**. As mentioned earlier, parts of the conversation could sometimes disappear, which became a problem when I wanted to return to previous answers or continue a test from an earlier point.

A significant part of the conversation containing my tests was deleted, so I had to repeat some of the testing. This made the evaluation process less convenient and affected the consistency of the testing.

Grok also showed weaker results in hallucination resistance and was less reliable when dealing with statistics and some scientific information.

## Overall Conclusion

Based on my testing, all three models demonstrated strong capabilities, but each had a different combination of advantages and disadvantages.

**Claude** showed particularly strong reasoning, hallucination resistance, safety, memory, and self-awareness. Its main weakness was that answers could sometimes be too short or not sufficiently useful, and it occasionally had problems following detailed formatting or length requirements.

**Gemini** performed especially well in translation and showed strong reasoning and hallucination resistance. Its main limitation during this testing was conversation history and memory, which made it difficult to return to specific previous answers.

**Grok** performed well in instruction following, translation, and general reasoning. It was also useful when working with websites. However, it showed more problems with hallucinations, particularly when dealing with statistics or scientific information, and its conversation history could sometimes be lost.

The results therefore do not show that one model is simply "the best" in every category. Instead, they demonstrate that different models can be more suitable for different tasks, depending on whether the priority is reasoning, translation, instruction following, factual reliability, memory, or another specific characteristic.
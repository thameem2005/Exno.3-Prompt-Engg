## Ex. No. 3 – Scenario-Based Report Development Utilizing Diverse Prompting Techniques

## Aim:

To design and evaluate an AI-powered conversational chatbot that efficiently assists customers with issues related to product troubleshooting, order tracking, and general inquiries. The chatbot must maintain a friendly, approachable tone while offering accurate, context-aware assistance. The objective of this experiment is to explore and implement a range of prompt engineering techniques to optimize chatbot behavior across different user scenarios and interaction complexities.

## Algorithm & Prompting Techniques:

Each prompting technique is designed to demonstrate a distinct strategy for guiding the AI’s response behavior. The chatbot is tested using different prompting formats to determine the most effective approach for real-world applications.

## 1. Direct Instruction Prompts
Objective:
Use concise, specific prompts that instruct the chatbot exactly what to say in response to predictable customer queries.

Prompt Pattern:

Prompt:
"When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"

Use Case:
Minimizes ambiguity in high-frequency scenarios such as order status checks. Suitable for scenarios where exact phrasing and consistency are important.

## 2. Contextual Prompting
Objective:
Enable the chatbot to use prior conversational context to tailor responses more effectively, improving continuity and relevance.

Prompt Pattern:

Prompt:
"If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"

Use Case:
Useful in multi-turn conversations to show memory, attentiveness, and empathy. Enhances user trust and satisfaction.

## 3. Persona-Based Prompting
Objective:
Develop chatbot responses with a specific personality, tone, or emotional style to humanize interaction and increase engagement.

Prompt Pattern:

Prompt:
"Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"

Use Case:
Boosts brand personality and improves user experience by aligning chatbot tone with organizational values (e.g., casual, professional, empathetic).

## 4. Few-Shot Prompting
Objective:
Provide the AI with a few examples of how to respond to similar user inputs. Helps it generalize to new but related queries.

Prompt Pattern:

Prompt:
"Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"

Use Case:
Effective when handling open-ended or less predictable queries. Mimics few-shot learning by pattern recognition from examples.

## 5. Chain of Thought Prompting
Objective:
Guide the chatbot to reason through complex or technical issues using a logical step-by-step approach, leading to clearer resolutions.

Prompt Pattern:

Prompt:
*"When a customer reports their laptop overheating, guide them through the following steps:

Ask if they are using the laptop on a soft surface.

Suggest moving the laptop to a flat, hard surface for better airflow.

Ask if they’ve cleaned the vents recently.

Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"*

Use Case:
Ideal for troubleshooting workflows that require sequential diagnostics or decision-making logic.

## 6. Instruction with Constraints
Objective:
Instruct the chatbot to provide a helpful answer while meeting specific constraints like response length, tone, or vocabulary.

Prompt Pattern:

Prompt:
"Respond to order inquiries in no more than 50 words and avoid using technical jargon.
Example: 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"

Use Case:
Improves readability and accessibility, especially on mobile or when speaking with non-technical users. Enforces brand communication standards.

## 7. Reflective Prompting
Objective:
Ensure the chatbot reflects the user's input before answering, validating understanding and reducing communication errors.

Prompt Pattern:

Prompt:
"When a customer asks for help, first reflect their question back to them.
For example, if they ask 'How can I reset my password?' respond with: 'You're asking how to reset your password, correct? Here’s how you can do it…'"

Use Case:
Improves mutual understanding and reduces errors in high-risk situations like account recovery or financial inquiries.

## Result:
All seven prompting strategies were tested successfully using a simulated AI-powered chatbot prototype. The chatbot responded appropriately to different types of customer queries, adapting its tone, structure, and detail level according to the prompting method employed. Notably:

Direct instruction worked best for transactional tasks (e.g., order tracking).

Persona-driven and contextual prompting significantly improved user satisfaction and natural flow.

Chain of thought and few-shot prompting demonstrated strong performance in complex troubleshooting cases.

Instruction with constraints ensured brevity and simplicity, essential for quick service.

Reflective prompting proved effective in building trust and reducing user confusion.

## Conclusion:
This scenario-based experiment highlights the importance of diverse prompt engineering techniques in designing intelligent, adaptable, and user-centric AI chatbots. By strategically employing varied prompt patterns—ranging from rule-based templates to flexible persona-driven dialogues—we can create conversational agents that not only solve problems but do so in ways that feel intuitive, personal, and engaging.

Future iterations can combine these strategies dynamically within a single conversation to further enhance the chatbot’s contextual adaptability and emotional intelligence.

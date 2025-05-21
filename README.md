# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:                                                                            
### REGISTER NUMBER : 
### Aim: 
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm: 
# 1. Direct Instruction Prompts
# Objective: 
Guide the chatbot to respond concisely to customer inquiries.

# Prompt Pattern:
```
Prompt: "When a customer asks for the status of their order, reply with: 'Your order is currently being processed and will be delivered by [date].'"
```
#  Interaction:
```
Customer: What is the status of my order?
Chatbot: Your order is currently being processed and will be delivered by [date].
```
# 2. Contextual Prompting
# Objective: 
Incorporate specific context to provide detailed answers based on the user’s previous interaction.
# Prompt Pattern:
```
Prompt: "If the customer previously mentioned that they haven’t received their order, say, 'I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.'"
```
# Example Interaction:
```
Customer: I haven't received my order yet.
Chatbot: I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.
```
# 3. Persona-Based Prompting:

# Objective: 
Design the chatbot to adopt a specific persona, making the interaction more engaging.

# Prompt Pattern:
```
Prompt: "Pretend you are a friendly, helpful customer service representative. Use a conversational tone, such as 'Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted!'"
```

# Example Interaction:
```
Customer: I'm having trouble with my new product.
Chatbot: Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted! What seems to be the problem?
```
# 4. Few-Shot Prompting
# Objective: 
Teach the AI how to respond using a few examples, enabling it to generalize for similar situations.

# Prompt Pattern:
```
Prompt: "Here are some examples of how to handle technical questions:
'My phone isn't charging.' → 'Have you tried using a different cable? If that doesn’t work, it may be an issue with the port.'
'The screen is flickering.' → 'It sounds like a display issue. Have you tried restarting the device?'
Now, respond to: 'My app keeps crashing.'"
```

# Example Interaction:
```
Customer: My app keeps crashing.
Chatbot: It sounds like the app is unstable. Have you tried closing all other apps running in the background? Sometimes that can free up resources. If the problem continues, you might want to try restarting your device or reinstalling the app.
```

# 5. Chain of Thought Prompting
# Objective: 
Use a step-by-step reasoning approach for resolving more complex or technical issues.

# Prompt Pattern:
```
Prompt: "When a customer reports their laptop overheating, guide them through the following steps:
Ask if they are using the laptop on a soft surface.
Suggest moving the laptop to a flat, hard surface for better airflow.
Ask if they’ve cleaned the vents recently.
Recommend restarting the device to see if the issue persists.
Now, solve: 'My laptop fan is making a loud noise.'"
```

# Example Interaction:
```
Customer: My laptop fan is making a loud noise.
Chatbot: I understand your laptop fan is making a loud noise. To help me figure out what's going on, could you tell me if you are currently using the laptop on a soft surface like a bed or a pillow? Also, have you had a chance to clean the vents recently? Sometimes dust buildup can cause the fan to work harder.
```

# 6. Instruction with Constraints
# Objective: 
Instruct the chatbot to provide assistance while adhering to specific constraints (e.g., response length or tone).

# Prompt Pattern:
```
Prompt: "Respond to order inquiries in no more than 50 words and avoid using technical jargon. For example, 'Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.'"
```

# Example Interaction:
```
Customer: When will my order arrive?
Chatbot: Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.
```
# 7. Reflective Prompting
# Objective: 
Ensure that the chatbot reflects the user’s query back to them before providing a response, reducing misunderstandings.

# Prompt Pattern:
```
Prompt: "When a customer asks for help, first reflect their question back to them. For example, if they ask 'How can I reset my password?' respond with 'You're asking how to reset your password, correct? Here’s how you can do it.'"
```
# Example Interaction:
```
Customer: How do I track my order?
Chatbot: You're asking how to track your order, correct? You can usually find your tracking information in the shipping confirmation email we sent you. Alternatively, you can log in to your account on our website and view the order details there
```
# Result: 
The various types of Prompts were executed successfully, demonstrating different techniques to guide the AI chatbot's responses for product troubleshooting, order tracking, and general inquiries. Each prompting method elicited a distinct behavior from the simulated chatbot, highlighting the importance of prompt engineering in shaping the AI's interaction style and the quality of its assistance.Thus, the Prompts were executed successfully.


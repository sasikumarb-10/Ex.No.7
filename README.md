# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.

# Date:13/09/2025
# Register no:212223060252
# Aim: To develop a prompt-based application using ChatGPT - To demonstrate how to create a prompt-based application to organize daily tasks, showing the progression from simple to more advanced prompt designs and their corresponding outputs.

#AI Tools Required: 


# Explanation: 
Prompt:
"Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."
Procedure:
1. Define the core requirements of a personal productivity assistant.
2. Identify and construct appropriate prompts for each task using an LLM (e.g., ChatGPT).
3. Simulate natural user interaction through a simple interface or command-line system.
4. Collect feedback or inputs from users and adapt responses accordingly.
5. (Optional) Integrate basic memory to simulate preference adaptation.
EXPECTED OUTPUT: - (attached the drive link)
Output (Example Response by LLM):
Personal Productivity Assistant Features:
1. Daily Task Manager:
o Accept tasks via natural language (e.g., "Remind me to call mom at 6 PM").
o Organize tasks by priority and deadline.
o Provide daily summaries and pending items.
2. Smart Scheduler:
o Schedule events and set reminders using contextual understanding.
o Notify user of overlapping appointments or free time slots.
3. Wellness Tips Generator:
o Suggest daily wellness advice (hydration, exercise, screen-time breaks).
o Adapt suggestions based on past user preferences and responses.

## Prompt Used
> "Design a personal productivity assistant that can help manage daily tasks, schedule reminders, suggest wellness tips, and answer general queries. The assistant should interact using natural language and be adaptable to the user’s changing preferences over time."

---

## Procedure

1. **Define Core Features**
   - Daily Task Management
   - Smart Event Scheduling
   - Reminder Notifications
   - Wellness Advice System
   - General Information & Query Answering
   - Preference Adaptation (Memory Simulation)

2. **Prompt Construction**
   - Prompt design involves using natural conversational language to trigger specific features.
   - Examples:
     - Task: “Remind me to take my tablet every night at 9 PM.”
     - Scheduler: “Book a study session for Sunday 6 PM.”
     - Wellness: “Suggest a short breathing exercise.”
     - Memory: “Remember that I prefer tips about meditation over yoga.”

3. **Simulate User Interaction**
   - Using a Python script or CLI, simulate the assistant's responses.
   ```bash
   User: What’s on my schedule today?
   Assistant: You have 3 tasks today – 
   1. Submit project at 10 AM  
   2. Doctor’s appointment at 4 PM  
   3. Workout at 6 PM
   ```

4. **Memory Simulation (Optional)**
   - Store user preferences in a JSON file.
   - Adapt wellness suggestions, task style, or schedule reminders accordingly.

5. **Interface Design (Optional)**
   - Create a user interface using tools like Streamlit to make it visually interactive.

---

## Expected Output

### Daily Task Manager
```text
User: Remind me to call mom at 6 PM today.  
Assistant: Got it! I've scheduled a reminder to call your mom at 6 PM today.

User: What are my tasks for today?  
Assistant: Here's your schedule for today:  
1. Team meeting at 10:00 AM  
2. Submit lab report by 2:00 PM  
3. Call mom at 6:00 PM
```

---

### Smart Scheduler
```text
User: Schedule a study session on Sunday at 6 PM.  
Assistant: Study session scheduled for Sunday at 6 PM. You have no conflicting appointments.

User: Do I have any free slots this Saturday?  
Assistant: Yes, you're free between 2 PM and 5 PM on Saturday.
```

---

### Wellness Tip Generator
```text
User: Give me a wellness tip for the day.  
Assistant: Take a 5-minute walk every hour to reduce screen fatigue and improve focus.

User: I prefer meditation tips.  
Assistant: Try a 5-minute breathing meditation — inhale for 4s, hold for 4s, exhale for 4s.
```

---

### General Queries
```text
User: How do I improve concentration while studying?  
Assistant: Use the Pomodoro technique — 25 min study, 5 min break. Avoid phone distractions.
```

---

### Adaptive Behavior (Simulated Memory)
```text
User: Remember that I prefer getting reminders 10 minutes early.  
Assistant: Preference saved! I’ll remind you 10 minutes before events.

User: Suggest a break activity.  
Assistant: How about a quick stretch or a short breathing exercise? You’ve been sitting for a while!
```

---

## Result
The lab exercise led to the successful design and simulation of a **Prompt-Based AI Personal Assistant** powered by ChatGPT. Students learned to:

- Tailor and refine prompts for desired outcomes  
- Apply prompt engineering in real-life scenarios  
- Build basic AI assistants using natural language interaction  
- Enhance productivity and wellness using AI tools  
- Simulate preference learning and memory  
- Think creatively to extend basic AI concepts into more personalized and intelligent applications

---

## Real-Life Applications


This assistant can help students manage academic tasks, reminders, wellness routines, and focus techniques. Professionals can use it for meetings, task lists, and daily motivation. Automating these repetitive activities reduces stress and boosts productivity.

---

## Learning Outcomes
Students gained practical experience in natural language interaction, prompt engineering, and AI application development. This experiment promoted creativity, personalized solution design, and teamwork.

---

## Challenges Faced
- Designing precise and effective prompts  
- Simulating adaptive preferences without built-in memory  
- Maintaining context through multiple interactions

---

## Future Scope


Future enhancements may include:

- Integration with mobile apps or Google Calendar  
- Voice-based interaction and reminders  
- Emotion detection or sentiment tracking  
- Habit tracking and weekly performance reports

---
# Result: 
The lab exercise resulted in the creation of a prototype concept for a personal assistant powered by large language models. Students were able to:
 Understand how to tailor LLM prompts to real-life applications.
 Foster creativity by designing features suited to their personal or academic lives.
 Learn prompt engineering techniques for optimal interaction with AI tools.
 Experience the versatility and utility of generative AI in solving everyday problems.

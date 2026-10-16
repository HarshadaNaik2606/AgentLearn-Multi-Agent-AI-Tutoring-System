# AgentLearn: Multi-Agent AI Tutoring System

An interactive Python project demonstrating how **AI agents can collaborate to deliver an educational tutoring experience**. Built with Microsoft AutoGen, the OpenAI API and Jupyter Notebook, the project simulates a teacher-student interaction in which an AI tutor asks questions, evaluates answers and provides step-by-step explanations.

## Overview

AgentLearn explores how multi-agent systems can support interactive learning through conversational AI. The notebook demonstrates a teacher agent that generates algebra questions and a student proxy agent that accepts user input, creating a structured question-and-answer workflow.

The project uses AutoGen's `AssistantAgent`, `UserProxyAgent` and `RoundRobinGroupChat` components to coordinate the conversation and manage its termination.

## Key Features

- **Multi-Agent Architecture:** Set up teacher and student agents to participate in a tutoring conversation.
- **AI-Powered Tutoring:** Generate algebra questions and provide explanations using an OpenAI language model.
- **Interactive Learning:** Enter answers through the notebook and receive feedback from the AI tutor.
- **Step-by-Step Explanations:** Explain the process used to solve each algebra question.
- **Group Chat Orchestration:** Use a round-robin group chat to coordinate interactions between agents.
- **Conversation Control:** Apply a termination condition to end the tutoring session after the questions have been completed.

## Future Enhancements

Potential improvements include:

- Adapting question difficulty based on student performance.
- Supporting additional subjects and question types.
- Tracking scores, attempts and learning progress.
- Adding hints and more detailed feedback for incorrect answers.
- Introducing dedicated assessment and feedback agents.
- Building a web interface for a more accessible tutoring experience.


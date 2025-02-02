---
title:  Agentic Kanban Board 💎
description: Work, prototype, run, and share your AI agents effortlessly with your teams and clients—no installations, complex commands, or servers required. Who said that AI is hard anymore?
---

This tutorial aims to guide you through the Agentic Kanban Board interface, a tool designed for creating and visualize multi-agent AI systems. 

### Why a Kanban Board?

Kanban boards are excellent tools for showcasing team workflows in real time, providing a clear and interactive snapshot of each member's progress. We’ve adapted this concept for AI agents. Now, you can visualize the workflow of your AI agents as team members, with tasks moving from "To Do" to "Done" right before your eyes. This visual representation simplifies understanding and managing complex AI operations, making it accessible to anyone, anywhere.

## Try It Live!

Experience the Agentic Kanban Board [here](https://www.agenticjs.com/playground).

## Interface Overview

The Agentic Kanban Board is divided into 3 sections:

1. **Team Setup**
2. **Task Board**
3. **Results Overview**

![interface overview_1 (1).png](https://res.cloudinary.com/dnno8pxyy/image/upload/v1723580136/interface_overview_1__1_jxdhj7.png)

## 1. Team Setup

The "Team Setup" area is where you define the agents and their tasks. Although we won’t discuss code in this tutorial, it's important to know that this is where you configure the agents' behavior. By default, there will always be an example selected in this area.

- **Code Panel**: On the left, you can view and edit the code that defines the tools, agents, and tasks.
- **Preview**: On the right, you can see a real-time preview of the configured agents, including their names, roles, and the tasks they will perform.

At the top of the interface, you will find a dropdown menu called **"Examples."** Here you can select from several predefined examples to view and execute. These examples are ready to use and help you understand how multi-agent systems are configured.

![Team Setup_1.png](https://res.cloudinary.com/dnno8pxyy/image/upload/v1723580135/Team_Setup_1_zc47op.png)

## 2. Task Board

The "Task Board" is a crucial section where you can track the progress of tasks assigned to the agents. It is like a Trello or Jira Kanban board but for AI Agents.

### **2.1. Task Panel**

This panel organizes tasks into several columns

- **To Do**: Pending tasks.
- **Doing**: Tasks in progress.
- **Blocked**: Tasks that cannot proceed due to a blockage.
- **Done**: Completed tasks.

![Task Board_1.png](https://res.cloudinary.com/dnno8pxyy/image/upload/v1723580135/Task_Board_1_ehmpno.png)

### **2.2. Task Details**

For each task, you can see additional details such as its description, the activities carried out, the progress of execution, and partial results. The detailed view includes:

- **Members**: Shows the agents assigned to the task along with their roles, helping you understand who is responsible for each part of the task.
- **Provider**: Indicates the AI service provider being used, ensuring you know which backend is powering the task.
- **Model**: Displays the specific AI model utilized, giving insight into the type of processing being applied.
- **Description**: Provides a brief but detailed overview of what the task aims to achieve, ensuring clarity of purpose.
- **Result**: Shows the outcome generated by the agent, which can be copied for further use. This is where you see the final output based on the agent’s processing.
- **Activity**: Lists all the steps and actions taken by the agent during the task. This log includes statuses and updates, providing a comprehensive view of the task's progress and any issues encountered

![Task Detailed_1.png](https://res.cloudinary.com/dnno8pxyy/image/upload/v1723580135/Task_Detailed_1_nzvwnz.png)

### 2.3. **General Activity**

You can also see an overview of all agents' activities by clicking the "Activity" button.

## 3. Results Overview

The **"Results Overview"** area displays the final results generated by the agents once they complete their tasks.

- **Results**: Here you will find the reports generated or any other output produced by the agents. You can copy these results directly from the interface for further use.

![Result overview_2.png](https://res.cloudinary.com/dnno8pxyy/image/upload/v1723580135/Result_overview_2_bhkm7b.png)

## Control Toolbar (Top Right)

Besides the main sections, the interface includes some important additional features:

1. **Share Team**

The "Share" button allows you to generate a link to share your current agent configuration with others. You can name your multi-agent system and easily share it.

![Shere team_1.png](https://res.cloudinary.com/dnno8pxyy/image/upload/v1723580135/Shere_team_1_pmfbfj.png)

1. **API Keys Configuration**

The settings button allows the user to enter their API Keys to change the AI model used. This provides flexibility to work with different AI service providers according to the project's needs.

![settings_1.png](https://res.cloudinary.com/dnno8pxyy/image/upload/v1723580135/settings_1_dk5bry.png)

1. **Full Screen**

The full-screen button allows you to maximize the interface for a more comprehensive and detailed view of the playground. This is especially useful when working with complex configurations and needing more visual space.

1. **Start Workflow**

This button initiates the execution of the tasks by the agents defined in your code.

## Basic Interface Usage

1. **Create and Configure Agents and Their Tasks**:
    - Modify the default code or copy new code to create and configure agents. Observe how it reflects in real-time in the preview.
2. **Start the Workflow**:
    - Press "Start Workflow" to begin executing the tasks.
3. **Monitor Progress**:
    - Use the Task Board to track the progress of tasks and check specific details if needed.
4. **Review Results**:
    - Once tasks are completed, review the results in the "Results Overview" area.
5. **Share and Configure**:
    - Use the "Share" and "Settings" buttons to share your project and configure your API Keys.

## Conclusion

The Agentic Kanban Board simplifies AI integration, enabling you to visualize, manage, and share AI agents with ease. Ideal for developers, project managers, and researchers, this tool facilitates efficient operation and collaboration without the need for complex setups. Enhance your projects by leveraging the power of AI with our user-friendly platform.

:::tip[We Love Feedback!]
Is there something unclear or quirky in the docs? Maybe you have a suggestion or spotted an issue? Help us refine and enhance our documentation by [submitting an issue on GitHub](https://github.com/AI-Champions/AgenticJS/issues). We’re all ears!
:::

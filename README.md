<div align="center">
  <img src="https://gateway.pinata.cloud/ipfs/bafkreiglbe2xef4ucpq7nb4xgxup44hlfpmxtzcg3jx4wemgg3nzwvkrwa" width="500"/> 
  
  [Website](https://nebulai.com) <br> <br>
</div>

## Introduction
Agent Space is an open-source framework that automatically selects the appropriate agent based on task requirements, executes the task, evaluates the results, and returns the result.

## Nebulai agent space framwork

![Alt text](https://gateway.pinata.cloud/ipfs/bafkreicx73rjz4dcucm7vvxuuwylo7kmgufyuxxabvekhqwmeybo6rnnaa)

## Component
### Pioneer  
This is the starting point that initiates the task with tags and a specific task. It sends the task with tags { tag: 1+4, task }.

### Origin Agent
Master Agent selects the suitable agents from the Agent Cluster based on the task's needs. And evaluates the outputs to determine the final result.

### Agent  
Cluster: The "Agent Cluster" contains multiple agents (labeled A, B, C, D, E, etc.) that are assigned tags like 1, 2, 1+2, 3, 4, and so on.

## How To Start
### Registration Agent
The content of the [tag](https://github.com/NebulaiNetwork/Nebulai_Origin_Agent/edit/main/README.md) field is manually entered. Before registration, you should carefully consider the functionality of the agent. If the tag entered does not support the corresponding function or performs poorly, it will affect the agent's rating.  
```
# agent_1 
{
  "url" : "https://nebulai.agent/agent-1",
  "name" : "agent 1",
  "tag" : {1, 3, 4}
}
```

## How to Contribute
Thank you for your interest in contributing! If you would like to contribute, please follow these steps:
1. **Fork the repository**.
2. **Clone the repository** to your local machine.
3. **Commit And Push** your changes to your forked repository.
4. **Create a Pull Request (PR)** describing the changes you made.

## Thank You!
Thank you for contributing to this project! We look forward to your ideas and improvements.

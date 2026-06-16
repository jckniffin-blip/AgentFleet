# AgentFleet Architecture

## Overview

AgentFleet is built with a modular architecture to support scalable agent management.

## Components

### Core Manager
Responsible for orchestrating agent lifecycle and task distribution.

### Agent Registry
Maintains information about available agents and their capabilities.

### Task Scheduler
Handles task queuing, prioritization, and execution scheduling.

### Monitor
Provides real-time monitoring and health checks for agents.

## Data Flow

```
Task Input → Scheduler → Agent Registry → Agent Execution → Monitor → Output
```

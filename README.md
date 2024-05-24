# Mars Exploration Rover M-12: Cognitive Architecture for Terrain Analysis
Assignment of Cognitive Architectures for Robotics course at UNIGE, Robotics Engineering Master Degree

## Introduction

In the context of space exploration on the planet Mars, a next-generation autonomous rover, named M-12, is tasked with conducting terrain analysis operations to collect scientific data. Equipped with a series of advanced sensors (including spectrometers, multispectral cameras, and radar for analysis activities, and stereoscopic cameras and IMU for navigation and attitude control) and sophisticated data processing capabilities, M-12 is designed to explore Martian terrain and gather crucial mission information.

## Task Description: Terrain Analysis Operations

At the beginning of an exploration task, M-12 activates and prepares to execute terrain analysis operations. Using its sensors and satellite maps provided by the Earth base, the rover plans an optimal route to explore a specific area, avoiding obstacles, and identifying points of scientific interest.

Once in the area of interest, M-12 begins to perform terrain analysis using its scientific instruments. It must be able to identify and classify soil samples, evaluate chemical and mineral composition, and detect any anomalies or geological features of scientific interest.

During its mission, M-12 may encounter situations where it must make decisions based on predefined normative rules. These rules guide the rover's behaviour and influence its actions during the exploration of Martian terrain. We want to focus on the following situations:

1. While M-12 explores the terrain, it must decide whether to analyze a surface soil sample it has identified to evaluate its chemical composition or descend into a nearby crevice to examine thin layers of rock; this decision is based on a preliminary and inconclusive analysis of the sample.
2. On some occasions, M-12 may encounter a hazardous terrain area, characterized by steep cliffs or unstable ground. In this case, the rover must decide whether to proceed with exploration, risking damage, or change course and seek an alternative route; this decision can be made autonomously, using terrain traversability algorithms that assess terrain characteristics, or with support from the technical team on Earth, which can receive information from the rover and decide what to do.

## Problem

Using points 1 and 2 as general rules that M-12 must follow, design a cognitive architecture based on a series of software modules capable of ensuring M-12's overall behaviour given these normative rules.

### A. UML Formalism

Use UML formalism to describe the cognitive architecture of M-12, identifying reasonable software components.

### B. Component Diagram

Develop the component diagram of the cognitive architecture, highlighting the cloud-based cognitive components (executed on a high-performance computing system on Earth) and the on-premise ones (executed partly on a computer on board M-12, partly on a fixed computing station on Mars).

### C. State Machine

Selecting a software module from those provided, describe its state machine explicitly specifying states, events, transitions, and any sub-states.

### D. Activity Diagram

Describe the activity diagram of the cognitive architecture.

### E. Adapters

Highlight the software components that are "adapters."

### F. Computational Components

Highlight the software components that are "computational."

### G. Request-Process-Reply

Highlight where the "request-process-reply" communication mode is used.


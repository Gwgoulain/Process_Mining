# Process_Mining
This repository contains Python code leveraging the PM4Py library to explore and analyze process mining in the dataset provided in the BPI Challenge 2012.

The code is developed as part of a Master of Science thesis and is aimed at uncovering insights into process behavior, performance, and compliance.

Key functionalities include:

Preprocessing: Preparing the dataset for analysis by cleaning and formatting the event log to ensure compatibility with process mining techniques.

Process Discovery: Applying state-of-the-art algorithms (Inductive Miner, Alpha Miner, Heuristic Miner) to create visual process models such as Petri Nets and BPMN diagrams.

Conformance Checking: Evaluating alignment between the event log and discovered models, focusing on fitness, precision, and generalization metrics.

The BPI Challenge 2012 dataset:

https://doi.org/10.4121/uuid:3926db30-f712-4394-aebc-75976070e91f

represents a real-life event log, offering a rich resource for understanding the behavior of complex processes.
The dataset is provided by a Dutch financial institution and contains detailed information about the application process for personal loans and overdrafts within a global financial company. It includes 262,200 events distributed across 13,087 cases.

# Ex.No.4-EXP 4 Generate the Prompt and evaluate that for following prompt patterns - Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting
### DATE: 24-11-26                                                                            
### REGISTER NUMBER : 212224060156
### Aim: To write the prompt for the following prompt types and compare that with different AI tools and evaluate that using any one evaluation method (Ex. Rubrics). Zero-shot Prompting.•	Few-shot Prompting - Chain of Thought -	Persona Pattern - Reverse Prompting - Graph Prompting - Active Prompting 

### Explanation - Any one use case from Unit 5 and write the prompt for that with the unit 2 Prompt types given above.

## USE CASE

### Smart Manufacturing Using IoT and Embedded Systems

The manufacturing industry aims to reduce manual monitoring and improve production efficiency through automation. IoT devices and embedded controllers are used to monitor equipment, collect real-time data, enable remote control, and support predictive maintenance.

### Main Objectives

* Improve production efficiency by 30%.
* Minimize machinery downtime using predictive maintenance.
* Enable real-time monitoring and remote control.
* Reduce energy consumption by optimizing manufacturing processes.

## PROMPT PATTERNS USED

1. Zero-shot Prompting
2. Few-shot Prompting
3. Chain-of-Thought Prompting
4. Persona Pattern
5. Reverse Prompting
6. Graph Prompting
7. Active Prompting

---

# 1. ZERO-SHOT PROMPTING

### Definition

Zero-shot prompting asks the AI to perform a task without providing examples.

### Prompt

```text
Explain how IoT devices and embedded controllers can be used in smart manufacturing to monitor machines, predict failures, reduce downtime, improve production efficiency, and reduce energy consumption.
```

### Expected Output

The AI explains the role of sensors, IoT connectivity, embedded controllers, real-time monitoring, predictive maintenance, and energy optimization without being given any examples.

### Evaluation

* Relevance: High
* Clarity: High
* Detail: Medium
* Accuracy: High

---

# 2. FEW-SHOT PROMPTING

### Definition

Few-shot prompting provides a few examples to guide the AI toward the desired response format.

### Prompt

```text
Example 1:
Input: Machine temperature increases continuously.
Output: Detect possible overheating and schedule preventive maintenance.

Example 2:
Input: Machine vibration increases above the normal range.
Output: Identify possible bearing or mechanical failure.

Now analyze the following:
Input: A manufacturing machine shows increasing temperature, vibration, and energy consumption.

Provide the possible problem and recommended maintenance action.
```

### Expected Output

The AI identifies possible machine degradation or failure and recommends inspection and predictive maintenance before an unexpected breakdown occurs.

### Evaluation

* Relevance: High
* Consistency: High
* Clarity: High
* Accuracy: High

---

# 3. CHAIN-OF-THOUGHT PROMPTING

### Definition

Chain-of-thought prompting guides the AI to solve a problem through a sequence of logical steps.

### Prompt

```text
A manufacturing machine has increasing temperature, vibration, and power consumption.

Analyze the situation step by step:
1. Identify the abnormal parameters.
2. Explain what each parameter may indicate.
3. Determine the possible machine fault.
4. Estimate the risk of machine failure.
5. Suggest suitable preventive maintenance.
6. Explain how IoT monitoring can prevent unexpected downtime.
```

### Expected Output

The AI sequentially analyzes the sensor parameters, identifies abnormal machine behavior, determines possible faults, assesses failure risk, and recommends preventive maintenance.

### Evaluation

* Logical reasoning: High
* Completeness: High
* Relevance: High
* Clarity: High

---

# 4. PERSONA PATTERN

### Definition

Persona prompting instructs the AI to respond from a specific professional or expert perspective.

### Prompt

```text
Act as an industrial IoT engineer with experience in smart manufacturing and predictive maintenance.

Design a solution for a manufacturing plant that uses IoT sensors and embedded controllers to monitor machine temperature, vibration, energy consumption, and operating status.

Explain the architecture, monitoring process, predictive maintenance approach, and benefits to the manufacturing company.
```

### Expected Output

The AI responds as an industrial IoT expert and describes sensors, embedded controllers, communication networks, cloud/edge platforms, dashboards, predictive analytics, and maintenance strategies.

### Evaluation

* Expertise: High
* Technical relevance: High
* Practicality: High
* Clarity: High

---

# 5. REVERSE PROMPTING

### Definition

Reverse prompting asks the AI to determine or generate the prompt that could produce a desired output.

### Prompt

```text
Desired Output:

"A smart manufacturing system uses IoT sensors to continuously monitor machine temperature, vibration, energy consumption, and operating conditions. The collected data is processed using embedded controllers and analytics to identify abnormal conditions and predict machine failures. Maintenance teams receive alerts before equipment failure, reducing downtime and improving energy efficiency."

Reverse-engineer a suitable prompt that could generate this type of answer.
```

### Expected Output

The AI generates a prompt requesting an explanation of an IoT-based smart manufacturing system, including sensors, embedded controllers, real-time monitoring, predictive maintenance, alerts, downtime reduction, and energy efficiency.

### Evaluation

* Output matching: High
* Completeness: High
* Relevance: High
* Prompt quality: High

---

# 6. GRAPH PROMPTING

### Definition

Graph prompting represents information using relationships between entities or processes, helping the AI understand connections between different components.

### Prompt

```text
Create a relationship graph for an IoT-based smart manufacturing system using the following elements:

IoT Sensors → Embedded Controller → Edge/Cloud Platform → Data Analytics → Predictive Maintenance → Maintenance Alert → Reduced Downtime

Also include:
Machine → Temperature Sensor
Machine → Vibration Sensor
Machine → Energy Sensor
Analytics → Failure Prediction
Analytics → Energy Optimization

Explain the relationship between each connected component.
```

### Expected Output

The AI produces a graph-like representation showing the flow of sensor data from machines to controllers, analytics platforms, predictive maintenance systems, and maintenance alerts.

### Evaluation

* Relationship accuracy: High
* Structural clarity: High
* Completeness: High
* Relevance: High

---

# 7. ACTIVE PROMPTING

### Definition

Active prompting allows the AI to ask for important missing information before producing the final solution.

### Prompt

```text
You are designing an IoT-based predictive maintenance system for a manufacturing plant.

Before designing the solution, identify the most important missing information you need from the user. Ask questions about:

1. Type of manufacturing industry
2. Number and type of machines
3. Available sensors
4. Required communication protocol
5. Production requirements
6. Existing control systems
7. Maintenance history
8. Energy monitoring requirements

After receiving the information, design the most suitable IoT-based predictive maintenance solution.
```

### Expected Output

The AI first asks relevant questions about the manufacturing environment and then uses the answers to create a customized predictive maintenance solution.

### Evaluation

* Information gathering: High
* Adaptability: High
* Relevance: High
* Customization: High

---

# COMPARISON OF PROMPT PATTERNS

| Prompt Pattern    | Main Purpose                          | Expected Quality |
| ----------------- | ------------------------------------- | ---------------- |
| Zero-shot         | Direct answer without examples        | Good             |
| Few-shot          | Guide output using examples           | Very Good        |
| Chain-of-Thought  | Structured problem solving            | Very Good        |
| Persona           | Expert-oriented response              | Excellent        |
| Reverse Prompting | Generate prompt from desired output   | Good             |
| Graph Prompting   | Represent relationships and processes | Excellent        |
| Active Prompting  | Ask for missing information           | Excellent        |

---

# EVALUATION METHOD – RUBRIC

Each prompt is evaluated using four criteria. Each criterion is given a score from **1 to 5**.

### Scoring Criteria

* **Relevance:** How well the response addresses the given use case.
* **Accuracy:** Technical correctness of the response.
* **Clarity:** How clearly and understandably the response is presented.
* **Completeness:** Whether important aspects of the problem are covered.

### Rubric

| Score | Description       |
| ----- | ----------------- |
| 5     | Excellent         |
| 4     | Very Good         |
| 3     | Good              |
| 2     | Needs Improvement |
| 1     | Poor              |

### Sample Evaluation

| Prompt Pattern   | Relevance | Accuracy | Clarity | Completeness | Total |
| ---------------- | --------: | -------: | ------: | -----------: | ----: |
| Zero-shot        |         4 |        4 |       4 |            3 | 15/20 |
| Few-shot         |         5 |        5 |       4 |            4 | 18/20 |
| Chain-of-Thought |         5 |        5 |       5 |            5 | 20/20 |
| Persona          |         5 |        5 |       5 |            5 | 20/20 |
| Reverse          |         4 |        4 |       4 |            4 | 16/20 |
| Graph            |         5 |        5 |       5 |            5 | 20/20 |
| Active           |         5 |        5 |       5 |            4 | 19/20 |

---

# COMPARISON USING DIFFERENT AI TOOLS

The same prompts can be tested using different AI tools such as:

* ChatGPT
* Google Gemini
* Microsoft Copilot

The responses can be compared based on relevance, accuracy, clarity, completeness, and ability to follow the requested prompt pattern.

| AI Tool | Relevance | Accuracy | Clarity | Overall   |
| ------- | --------: | -------: | ------: | --------- |
| ChatGPT |         5 |        5 |       5 | Excellent |
| Gemini  |         5 |        4 |       5 | Very Good |
| Copilot |         4 |        4 |       4 | Good      |

The different prompt patterns were successfully generated and evaluated for the **IoT-based Smart Manufacturing and Predictive Maintenance** use case. The prompts produced different types of responses depending on their structure. Persona, Graph, Chain-of-Thought, and Active Prompting provided more structured and context-specific outputs, while Zero-shot Prompting provided a direct general response. The generated responses were compared using a rubric based on relevance, accuracy, clarity, and completeness.




# Result:
The various types of Prompts are executed successfully with generated the report.

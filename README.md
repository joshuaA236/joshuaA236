# Model Card: 'Josh-ahlers'

> MLOps engineer and Boston University Computer Science and Artificial Intelligence graduate student. Trained in Python, Java, Machine learning, and Philosophy.

--- 

## Model Details:

| Field | Value
|----|----|
|**Foundation** | Computer Science, Philosophy, andEconomics
|**Current Version** | v2.1
|**Deployment** | Data Software Engineer on the MLOps Engineering team|
|**Region** | Milwaukee


## Training Data

```mermaid 
pie showData
    title Training Data
    "MLOps" : 30
    "Computer Science & AI" : 30
    "Philosophy" : 30
    "Economics" : 10
```

## Training Curve 

```mermaid 
xychart-beta
    title "Training Loss"
    x-axis ["Undergrad", "IOS Engineer role", "MLOps Engineer role", "Graduate school"]
    y-axis "Loss" 0 --> 1
    line [0.9, 0.65, 0.4, 0.25]
```

## Evaluation 

```mermaid 
xychart-beta
    title "Eval Scores"
    x-axis ["MLOps", "Python", "CI/CD", "Agentic workflows", "Java"]
    y-axis "Score" 0 --> 100
    bar [90, 75, 70, 60, 60]
```

## Feature Space 

```mermaid 
quadrantChart
    title Interest Map
    x-axis Theory --> Practice
    y-axis Known --> Learning
    quadrant-1 Work In Progress
    quadrant-2 Interests
    quadrant-3 Foundational
    quadrant-4 Advanced
    MLOps: [0.8, 0.4]
    Agents: [0.7, 0.8]
    Ontology: [0.2, 0.7]
    Deleuze: [0.2, 0.3]
    MCP: [0.8, 0.9]
    Model Deployment: [0.9, 0.3]
    Game Theory: [0.35, 0.2]
    Automation: [0.85, 0.2]
   
```

## Dependencies

```
# languages
python
java
C
java script
type script

# ml & data
mlflow
pyspark
scikit-learn
pandas

# mlops & infrastructure
docker
kubernetes
nginx
gitlab-ci
azure
```
## Notable Deployments
- **MLOps Plugin Framework**: Rearchitected my team's MLOps stack into a plugin based Python Framework so teams can add algorithms, data frameworks, and feature stores without touching core code.
- **Notebook to Production Gen AI Tool**: Created an LLM powered tool that turns Jupyter notebook logic into reusable Python modules and generates pytest suites.
- **MCP Gateway**: Developed a secure gateway for MCP resources servers using Azure Entra token validation and zero trust downstream authentication
- **Databricks Migration**: Moved six marketing models from Domino to Databricks.

## Known Limitations
- Takes 4 hours to record a 4 minute demo
- Uses too many emojis

## Intended Use
- Building and maintaining ML Systems
- Designing Agents and MCP integrations
- Finding new and unique ways to automate

## Version History

```mermaid
timeline
  title Release History
  v1.0: B.A. Philosophy and Economics
  v1.1: Full Stack Java Certificate
  v1.2: IOS Engineer
  v1.3: Application Engineer
  v2.0: MLOps Engineer
  v2.1: Computer Science and Artificial Intelligence Degree at Boston University
```

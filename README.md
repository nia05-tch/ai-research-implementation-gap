AI Research-to-Implementation Gap Knowledge Graph

Knowledge Graph analysis of AI research to production pipeline - VU Amsterdam 2025

📊 Project Overview
This project builds a Knowledge Graph to analyze the gap between AI research publications and their practical implementations, tracking adoption timelines and framework usage patterns across the AI ecosystem.
👥 Team Members
Group 80 - Knowledge and Data 2025

Nia Racheva - 2841982
Anastasia Ciubucova - 2856242

Vrije Universiteit Amsterdam

📁 Project Structure
├── report/
│   └── FinalProject_KD_Group80.pdf    # Full project documentation
├── ontology/
│   ├── ontology.ttl                   # Ontology with OWL restrictions (1.4 MB)
│   └── instances.ttl                  # Knowledge graph instances (16,663 triples)
├── notebooks/
│   └── implementation.ipynb           # Complete data integration and analysis
└── images/                            # Generated visualizations

🚀 Quick Start
Requirements
bashpip install rdflib sparqlwrapper pandas matplotlib networkx
Execution

Clone this repository
Navigate to the notebooks/ directory
Open implementation.ipynb in Jupyter Notebook or JupyterLab
Run all cells sequentially
Outputs will be generated automatically in the images/ folder


📈 Generated Outputs
The notebook automatically generates the following files:

instances.ttl - Complete knowledge graph data
knowledge_graph_visualization.png - Network structure visualization
cq1_time_lag.png - Time lag analysis between research and implementation
cq2_framework_adoption.png - Framework usage patterns
cq3_model_performance.png - Model benchmark comparisons
repo_popularity.png - Repository popularity metrics
kg_composition.png - Entity distribution statistics


📊 Knowledge Graph Statistics

Total triples: 16,663
Publications: 3 (ResNet, Transformer, GPT-3)
Models: 4
Frameworks: 4 (PyTorch, TensorFlow, Keras, Scikit-learn)
Architectures: 2 (CNN, Transformer families)
Repositories: 3
Benchmark Results: 2


✨ Key Features

Schema Integration: Schema.org and FOAF vocabulary alignment
OWL Restrictions: Cardinality constraints (R1, R2)
External Linking: Integration with DBpedia and Wikidata
SPARQL Analysis: Competency question-based queries
Visualizations: Comprehensive charts and network graphs
Reproducible Pipeline: End-to-end automated workflow


📖 Documentation
For detailed information about the ontology design, data sources, SPARQL queries, and analysis results, please refer to the full report:
report/FinalProject_KD_Group80.pdf

🔍 Research Questions
This project addresses key competency questions:

What is the time lag between AI research publication and practical implementation?
Which frameworks are most commonly adopted for implementing specific architectures?
How do model implementations compare in benchmark performance?


📄 License
This project was created as part of the Knowledge and Data course at Vrije Universiteit Amsterdam (2025).

📧 Contact
For questions or feedback, please contact the team members through VU Amsterdam channels.
n.racheva@student.vu.nl
a.ciubucova@student.vu.nl


Vrije Universiteit Amsterdam - Knowledge and Data 2025

A sophisticated Anti-Money Laundering (AML) detection system that uses Graph Neural Networks (GNNs) to identify suspicious transaction patterns in banking data. This system outperforms traditional rule-based approaches by learning complex patterns and relationships in transaction networks.

🚀 Key Features
Graph-Based Detection: Uses transaction graphs (sender → receiver) instead of individual transactions

Multiple Pattern Detection: Identifies circular transactions, structuring, layering, and rapid-fire patterns

Advanced GNN Architecture: Residual connections, attention mechanisms, and batch normalization

Class Imbalance Handling: Focal loss and specialized training for rare anomaly detection

Temporal Validation: Realistic time-based train-test splits

Comprehensive Evaluation: Multiple metrics and visualization tools

Production-Ready: Includes monitoring, explainability, and deployment setup

📊 Detected Money Laundering Patterns
|Pattern|	Description	|Example|
|-------|-------------|-------|
|Circular |	Money moves through intermediaries and returns to origin|	A → B → C → A|
|Structuring| Multiple transactions below reporting thresholds |	10x $9,500 transactions|
|Layering |	Complex chains through multiple accounts |	A → B → C → D → E|
|Rapid-Fire |	Many small transactions in quick succession |	15x $500 transactions in 1 hour|

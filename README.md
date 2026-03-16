# Ticket Analysis Project

This project analyzes support tickets from our system to uncover common issue categories, trends, and patterns over time. Using AI-based clustering techniques, tickets with similar content are grouped together to provide actionable insights for improving support workflows and identifying recurring problems.

---

## Features

- Fetches and preprocesses tickets from the system.
- Groups tickets into clusters based on similarity of subject lines using AI embeddings.
- Automatically generates machine-readable labels for each issue group.
- Allows refinement of labels to make them more human-readable.
- Tracks first and last occurrence timestamps of each issue group.
- Provides insights into trends, seasonality, and top recurring issues.
- Saves processed data locally for future analysis.

---

## Requirements

- Python 3.8 or higher
- Install required packages:

```bash
pip install pandas numpy sqlalchemy sentence-transformers scikit-learn jupyter

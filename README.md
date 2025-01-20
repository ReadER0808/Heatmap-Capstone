# Heatmap-Capstone
Heatmap Capstone Project, showcasing tools and workflows for event sequence analysis.

# Heatmap Capstone Project

## Overview
The Heatmap Capstone Project showcases the development of a comprehensive set of tools and workflows for analyzing event sequence data. Despite the lack of domain-specific context for the dataset, the project successfully demonstrates how advanced data science techniques can be applied to extract meaningful insights and provide interpretation tools for the client.

### Key Highlights:
- Developed tools for **Exploratory Data Analysis (EDA)**, clustering, association rule mining, topic modeling (LDA), and survival analysis.
- Designed workflows to handle complex datasets with symbolic representations.
- Focused on creating **generalizable tools** that are adaptable to any event sequence data, making them versatile for various industries.

---

## Project Context
The client provided a dataset with masked event sequences, containing no domain-specific information about the events or their relationships. This posed unique challenges:
- **No domain knowledge**: Tokens were symbolic, and their meaning was unknown.
- **Complexity**: The dataset included over 12,000 traces and millions of records.
- **Objective**: Develop proof-of-concept tools to analyze and interpret the data for potential future applications.

### Dataset Details:
- **Structure**: Sequential event data with symbolic tokens.
- **Challenges**:
  - Extreme disparities in token frequencies.
  - Long contiguous sequences of a few frequent tokens.
  - Significant computational requirements.

---

## Tools and Techniques

### 1. **Exploratory Data Analysis (EDA)**
- **Objective**: Identify key characteristics of the dataset, such as token distributions and transitions.
- **Visuals**: Boxplots, heatmaps, directed graphs, and token sequence patterns.
- **Challenges Addressed**:
  - Visualizing token distributions across millions of records.
  - Handling extreme frequency disparities between tokens.

### 2. **Clustering Analysis**
- **Objective**: Group traces into clusters based on token counts and transitions.
- **Techniques**: K-means, hierarchical clustering, and distribution-based clustering.
- **Outputs**:
  - Silhouette plots for optimal cluster selection.
  - Trace patterns and token distribution by cluster.

### 3. **Association Rule Mining**
- **Objective**: Discover patterns and relationships between token sequences.
- **Methods**:
  - Basket analysis.
  - Sequential rule mining with temporal ordering.
- **Outputs**:
  - Top sequential rules with lift, support, and confidence metrics.

### 4. **Latent Dirichlet Allocation (LDA)**
- **Objective**: Identify latent topics within traces.
- **Approach**: Treat traces as documents and tokens as words.
- **Outputs**:
  - Topic distributions and weights for each trace.
  - Interactive LDA visualizations.

### 5. **Survival Analysis**
- **Objective**: Model the longevity of token sequences before transitioning to a new state.
- **Techniques**: Parametric models (Weibull, lognormal, and gamma).
- **Outputs**:
  - Survival curves for specific token transitions.
  - Cumulative hazard plots.

---

## Key Takeaways
1. **Generalizable Tools**: The tools developed are versatile and adaptable for various datasets, making them valuable across multiple domains.
2. **Insights from Symbolic Data**: Despite the lack of contextual knowledge, the project delivered meaningful analysis and demonstrated the potential of the dataset.
3. **Future Directions**:
   - Extend clustering analysis with additional distance measures.
   - Incorporate process mining techniques for event pattern discovery.
   - Apply non-parametric methods in survival analysis for greater flexibility.

---

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Heatmap-Capstone.git
   ```
2. Navigate to the respective module folders for RMarkdown files and instructions.
3. Use the `Project_Report/` folder to review the complete project documentation.
4. Run `.Rmd` files in RStudio for analysis and visualization.

---

## Acknowledgments
- **Team Members**: Dona Joy Arimboor, Mansoureh Foruzandehshahraky, Aniket Varbude, Stephen Maher.
- **Sponsors**: Dr. Jan Stanek, Prof. Georg Grossmann.
- **Mentor**: Eric Lam.

---

Feel free to explore the repository and adapt the tools to your own datasets!


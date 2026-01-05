# AI Research Lens
The app can be accessed here: https://smart-optim-energy.ase.ro:80/rlens/
An AI-powered bibliometric analysis framework with agentic workflows for ingesting, analyzing, and reporting on academic research data.

## Highlights
- Multi-format ingestion (Excel, CSV, TXT from Web of Science exports)
- Descriptive analytics, topic modeling, and network analysis
- Agent layer for paper retrieval, code generation, research exploration, and report generation
- Interactive analysis and visualization
## Features
### Data layer
- Automated preprocessing and standardization
- Text enrichment (embeddings, n-grams, statistics)
- Field classification into research domains

### Analytics layer
- Publication trends, citations, and keyword extraction
- BERTopic-based topic modeling
- Co-occurrence and co-authorship networks
- 15+ visualization types (trends, networks, heatmaps, word clouds)

### Agent layer
1. Paper Retriever
   - Search and download top 30 open access papers
   - Uses OpenAlex API
2. Code Generator
   - Natural language to Python analytics code
3. Research Assistant
   - Explore research questions and identify trends
   - Detect research gaps and emerging topics
4. Report Generator
   - Generate summary report using AI
## Example workflows
### Basic analysis
1. Load WoS data
2. Run descriptive analytics
3. Generate publication trends
4. Extract top keywords
5. Create visualizations

### Topic discovery
1. Load data
2. Run BERTopic modeling
3. Visualize topics
4. Analyze topic trends over time
5. Generate topic report

### AI-powered research
1. Use Paper Retriever to get recent papers on a topic
2. Load retrieved papers
3. Use Research Assistant to identify trends
4. Use Code Generator to create custom analytics
5. Generate a report

### Network analysis
1. Load data
2. Build keyword co-occurrence network
3. Compute centrality measures
4. Detect communities
5. Visualize network

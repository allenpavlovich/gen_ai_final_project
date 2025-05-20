# Healthcare GenAI Research Proposal Generator

This project uses CrewAI agent workflows to generate research project proposals in the domain of Generative AI in healthcare. The multi-agent LLM workflows help ideate, critique, and refine ideas grounded in academic literature.

## Project Overview

This project aims to create a comprehensive research proposal in the GenAI and healthcare domain by leveraging CrewAI's multi-agent collaboration capabilities. The agents work together to brainstorm ideas, critique feasibility, identify research gaps, and generate a structured proposal.

## Setup Instructions

### Environment Setup

```bash
# Create a virtual environment (Windows PowerShell)
py -m venv crew_ai

# Activate the virtual environment
.\crew_ai\Scripts\activate

# Install required dependencies
pip install -r requirements.txt
```

## Project Structure

- `templates_from_professor/`: Jupyter notebook templates for CrewAI implementation
- `requirements.txt`: Required Python packages

## Deliverables

1. Research Proposal (2-3 pages) containing:
   - Title
   - Abstract (150-250 words)
   - Background & Literature Review
   - Problem Statement & Research Gap
   - Proposed Gen AI Approach
   - Expected Impact in Healthcare
   - Limitations or Ethical Considerations
   - References

2. Agent Log (screenshots/transcript snippets showing CrewAI agent usage)

3. PowerPoint Presentation (max 10 slides) showing the research proposal and agent interaction process

## References

- CrewAI short course tutorials
- Provided academic papers in the GenAI healthcare domain

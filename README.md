# Echo Chambers from Without and Within: A Comparative Study of Right-Wing and Mainstream Communities on YouTube

This repository contains the code and supporting materials for the MSc dissertation:

> **Echo Chambers from Without and Within: A Comparative Study of Right-Wing and Mainstream Communities on YouTube**

## Repository Contents

This repository includes:

- **Seed video list** containing the 20 seed videos used as the starting point for data collection.
- **Data collection code** for retrieving YouTube videos, recommendations, transcripts, and comments through the YouTube Data API.
- **Network construction code** for building the recommendation networks and comment reply networks used in the study.
- **Statistical analysis code** for all analyses reported in the dissertation.
- **Figure and table generation code** used to reproduce the results presented in the dissertation.

The repository is organised to allow readers to understand and reproduce the analytical workflow from data collection to the final statistical analyses and visualisations.

## Materials Not Included

Some materials are intentionally not included in this repository.

### Raw YouTube comments

The raw comment dataset is not publicly shared because it contains user-generated content collected from YouTube. Redistribution may be subject to YouTube's Terms of Service and raises ethical and privacy considerations regarding user-generated data.

### LLM annotation prompts and annotation pipeline

The prompts, batch annotation pipeline, and API implementation used for GPT-assisted annotation are not included. These components constitute implementation details rather than the analytical procedures necessary to reproduce the statistical results. The dissertation fully documents the annotation methodology, coding scheme, validation process, and intercoder reliability, allowing readers to understand and evaluate the annotation procedure without requiring access to the proprietary implementation.

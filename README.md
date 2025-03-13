# Advanced Multi-Agent AI Swarm System

A distributed cognitive architecture using specialized language models with enhanced reasoning capabilities.

## Project Concept Overview

- **Multi-Agent AI Swarm**: A distributed cognitive architecture using specialized language models.
- **Musical Staff Memory Organization**: Memories are stored on "staff sheets" organized by cognitive dimensions.
- **Iron Filings Memory Retrieval**: Memories attract one another based on weighted similarity.
- **Champagne Tower Memory Flow**: Memory is organized hierarchically (short-term, intermediate, long-term, compressed).
- **Iterative Reasoning**: Agents refine their latent state iteratively.
- **Dynamic Agent Selection**: Intelligently selects appropriate agents based on problem type.
- **Memory Persistence**: Allows saving and loading memory states between sessions.
- **Expanded Problem Types**: Handles a wide variety of mathematical and logical problems.
- **Uncertainty Visualization**: Tracks and visualizes confidence levels throughout reasoning.
- **Performance Metrics**: Measures and optimizes system performance metrics.

## Features

- **Enhanced Cognitive Architecture**: Multi-layered cognitive system with advanced reasoning modules
- **Problem-Type Classification**: Automatically detects arithmetic, percentage, time, probability, geometry and other problem types
- **Specialized Reasoning Agents**: Different agents handle different problem types
- **Direct Calculation**: Specialized calculators for different problem types
- **Memory Organization**: Sophisticated memory system with hierarchical organization
- **Chain-of-Thought Reasoning**: Iterative refinement of solutions with step-by-step tracking
- **Uncertainty Tracking**: Visualization of confidence levels throughout reasoning
- **Performance Metrics**: Tracking of convergence times, iterations, and accuracy

## Requirements

- Python 3.8+
- PyTorch
- Transformers (Hugging Face)
- Matplotlib (for visualization)
- See requirements.txt for complete dependencies

## Getting Started

1. Clone this repository
2. Install the requirements: `pip install -r requirements.txt`
3. Run the swarm system: `python swarm.py`

## Directory Structure

```
ai-swarm-system/
├── swarm.py             # Main script
├── requirements.txt     # Dependencies
├── memory_states/       # Persistent memory storage
├── performance_metrics/ # Performance tracking data
├── visualizations/      # Generated visualizations
└── logs/                # System logs
```

## Configuration

The system uses a configuration defined in `config.json` which controls the cognitive architecture and reasoning processes.

## License

MIT License

## Citation

If you use this system in your research, please cite:

```
@software{ai-swarm-system,
  author = {AI Swarm System Contributors},
  title = {Advanced Multi-Agent AI Swarm System},
  year = {2025},
  url = {https://github.com/Chappyo7/ai-swarm-system}
}
```
# Language Model Tracker

Tracking multimodal language models, text generation models, and reasoning models.

## Models Overview

| Model | Company | Release Date | Size | Key Features | Benchmarks |
|-------|---------|--------------|------|--------------|------------|
| Gemini 3.1 Flash-Lite | Google | Mar 3, 2026 | Efficiency | Fastest and cheapest Gemini model, 40% cost reduction, $0.25/1M input tokens | Speed optimized |
| Hunter Alpha | Xiaomi | Mar 11, 2026 | Unknown | Chinese-focused, anonymous initial release, May 2025 knowledge cutoff | TBD |
| GPT-5.4 | OpenAI | Mar 5, 2026 | Frontier | Native computer use, advanced reasoning + coding, Excel/Sheets integration, autonomous agents | OSWorld-Verified benchmark improvements |
| Nemotron 3 Super | NVIDIA | Mar 10, 2026 | 120B total, 12B active | Hybrid Mamba-Transformer MoE, agentic reasoning, 5x higher throughput, open-weight | Top-ranked on DeepResearch Bench I & II |
| GPT-OSS-120B | OpenAI | Mar 2026 | 120B | First open-weight model from OpenAI, commercial use with attribution, 700M MAU threshold | Competitive with proprietary models |
| Claude Opus 4.5 | Anthropic | Mar 2026 | Flagship | Advanced coding and agentic capabilities, enhanced multi-step reasoning, vulnerability detection | Firefox codebase: 22 vulnerabilities found (14 critical) |
| Qwen 3.5 Small | Alibaba | Mar 1, 2026 | 0.8B-9B | 9B matches 120B models, on-device deployment, 4GB RAM iPhone support | GPQA Diamond 81.7%, HMMT 83.2% |
| Gemini 3.1 Pro | Google DeepMind | Feb 19, 2026 | Pro-tier | 1M-token context, 77.1% ARC-AGI-2, multimodal reasoning, agentic coding capabilities | 77.1% ARC-AGI-2 benchmark |
| Qwen3.5 Medium | Alibaba | Feb 26, 2026 | 4 variants | Open source, Sonnet 4.5 performance on local hardware, agentic tool calling | Sonnet 4.5 comparable |
| Qwen3.5 | Alibaba | Feb 16, 2026 | Multiple sizes | Native multimodal (text/image/video), agentic AI optimization, improved cost efficiency | TBD |
| Grok 4.20 | xAI | Feb 19, 2026 | Beta | 4 AI agents collaborating, rapid learning, ELO 1505-1535, public beta | ELO 1505-1535 estimated |
| Kimi K2.5 | Moonshot AI | Jan 26, 2026 | Open-weight | Multimodal LLM, vision + coding, agent swarm capabilities, 15T token pretraining | Comparable to GPT-5/Gemini on coding |
| Claude Opus 4.6 | Anthropic | Feb 2026 | - | High-reasoning, multi-source analysis, technical domain optimization | 68% vs 58% baseline (Box eval) |
| Claude Sonnet 4.6 | Anthropic | Feb 2026 | - | Balanced performance/cost, multimodal capabilities | TBD |
| Grok 4.1 Fast | xAI (Elon Musk) | Feb 21, 2026 | - | Enterprise-focused, integrated in Microsoft Copilot Studio | TBD |
| Doubao 2.0 | ByteDance | Feb 2026 | - | Multimodal language model, video understanding | TBD |

## Recent Updates

### March 2026

**Gemini 3.1 Flash-Lite (Mar 3, 2026) - Google**
- Google's fastest and cheapest model as of March 2026
- Pricing: $0.25 per 1M input tokens, $1.50 per 1M output tokens
- 40% cost reduction compared to previous Gemini pricing tiers
- Speed-optimized for high-volume applications
- Part of Google's strategy to compete on inference costs
- Targets developer adoption with aggressive pricing

**Claude Opus 4.5 (Mar 2026) - Anthropic**
- "The world's best model for programming, agents, and computer use"
- Enhanced multi-step reasoning and agentic capabilities
- Demonstrated Firefox vulnerability detection: analyzed 6,000 C++ files, found 22 vulnerabilities (14 critical) in 2 weeks
- 1M token context window with reasoning capabilities
- Flagship model for enterprise coding and security applications

**GPT-OSS-120B (Mar 2026) - OpenAI**
- OpenAI's first open-weight model release
- 120 billion parameters with commercial licensing
- Requires attribution and has 700M monthly active user threshold for additional licensing
- Changes competitive landscape for open-weight models
- Puts pressure on Meta, Alibaba, and DeepSeek in open-source space

**NVIDIA Nemotron 3 Super (Mar 10, 2026) - NVIDIA**
- 120B total parameters, 12B active (Mixture-of-Experts architecture)
- Hybrid Mamba-Transformer model optimized for agentic AI systems
- 5x higher throughput than previous models, 2.2x faster than GPT-OSS-120B
- 7.5x higher throughput than Qwen3.5-122B in high-volume settings
- Powered AI research agent that achieved #1 ranking on DeepResearch Bench and DeepResearch Bench II
- Available on build.nvidia.com, Perplexity, OpenRouter, and Hugging Face
- Optimized for complex multi-agent applications (software development, cybersecurity)

**Qwen 3.5 Small Series (Mar 1, 2026) - Alibaba**
- Four dense model variants: 0.8B, 2B, 4B, and 9B parameters
- 9B model matches GPT-OSS-120B (13x larger) on benchmarks: GPQA Diamond 81.7% vs 71.5%, HMMT 83.2% vs 76.7%
- 2B model runs on iPhone in airplane mode with just 4GB RAM
- Optimized for on-device AI deployment in privacy-sensitive and offline applications
- Supports text and image processing with minimal resource requirements

**GPT-5.4 (Mar 5, 2026) - OpenAI**
- "Most capable and efficient frontier model for professional work"
- Native computer use capabilities - first model with built-in computer vision for UI interaction
- Advanced reasoning, coding, and professional document handling (Excel, Sheets, presentations)
- Available in three variants: Standard, Pro (high performance), and Thinking (reasoning-focused)
- Financial data integrations and spreadsheet automation
- Significant advancement toward autonomous AI agents

### February 2026

**Qwen3.5 Medium (Feb 26, 2026) - Alibaba**
- Four open-source model variants with Sonnet 4.5-level performance
- Commercial usage available for three of the four models
- Agentic tool calling capabilities
- Successfully runs on consumer hardware with M4 chips
- Praised by Elon Musk for "impressive intelligence density"

**Grok 4.20 (Feb 19, 2026) - xAI**
- Public beta release with 4 AI agents collaborating internally
- Rapid learning capabilities and improved model architecture
- Estimated ELO rating of 1505-1535
- Significant advancement over Grok 4.1 Fast released in February

**Gemini 3.1 Pro (Feb 19, 2026) - Google DeepMind**
- Advanced Pro-tier model with 1M-token context window
- 77.1% performance on ARC-AGI-2 benchmark (significant jump from baseline)
- Multimodal reasoning across text, images, audio, video, and code
- Integrated into GitHub Copilot with focus on agentic coding

**Qwen3.5 (Feb 16, 2026) - Alibaba**
- Native multimodal capabilities (text, image, video)
- Built for "agentic AI era" with focus on autonomous task execution
- Improved performance per unit of inference cost
- Multiple size variants available

**Claude Opus 4.6 & Sonnet 4.6 (Feb 2026) - Anthropic**
- Opus 4.6: Specialized for high-reasoning tasks, 10% performance lift in technical domains
- Sonnet 4.6: Balanced option with improved cost efficiency
- Both feature enhanced multimodal understanding

**Grok 4.1 Fast (Feb 21, 2026) - xAI**
- Released in Microsoft Copilot Studio integration
- Focused on enterprise workflow automation
- Follows xAI's pattern of business-first deployments

### January 2026

**Kimi K2.5 (Jan 26, 2026) - Moonshot AI**
- Open-weight multimodal LLM with 15 trillion token pretraining
- Native multimodal architecture (not stitched components)
- Coding with vision capabilities
- Agent swarm execution for complex tasks
- Performance comparable to GPT-5 and Gemini on coding benchmarks
- **UPDATE Feb 24:** Secured $700M funding round; revenue in past 20 days exceeded all of 2025

## Model Categories

### Reasoning-Focused
- Claude Opus 4.6: Multi-source analysis across legal, financial, technical content
- Qwen3.5: Agentic task execution optimization

### Multimodal
- Kimi K2.5: Native vision + text training
- Qwen3.5: Text, image, and video understanding
- Claude models: Enhanced multimodal capabilities

### Open-Weight
- Kimi K2.5: Available on HuggingFace and NVIDIA NIM

### Commercial/Closed
- Qwen3.5: Alibaba Cloud API
- Claude models: Anthropic API

## Benchmark Performance

### Coding Benchmarks
- **Kimi K2.5**: Comparable to GPT-5 and Gemini on coding tasks
- Specific metrics TBD pending public benchmarks

### Reasoning Benchmarks
- **Claude Opus 4.6**: 68% performance vs 58% baseline (Box evaluation)
- Near-perfect scores in technical domains

### Cost Efficiency
- **Qwen3.5**: Optimized for capability per unit of inference cost
- **Claude Sonnet 4.6**: Balanced performance/cost option

*Last updated: March 17, 2026*
# M1r4th0R

I work on machine learning and AI applications in Chongqing, mostly with Python, PyTorch and JavaScript. These repositories include model experiments and small tools I use myself.

[中文](README.md) · [Contact](mailto:m4rh0zen@foxmail.com)

![M1r4th0R, machine learning and AI applications, Chongqing](assets/banner.svg)

In 2026, I worked on defect detection and yield analysis at BOE's B8 plant in Chongqing. When building something, I care about having a useful baseline for the results and making it possible for someone else to run it.

## Model Experiments

### [stock-quant-agent](https://github.com/Leruo212/stock-quant-agent)

Daily-frequency research on Chinese A-shares, with a CNN-LSTM-Attention model, backtests and an LLM prediction ledger. The repository keeps the model's near-chance results and compares strategies with both the index and equal-weight holding to help explain where returns come from.

[Live demo](https://leruo212.github.io/stock-quant-agent/) · [Results](https://github.com/Leruo212/stock-quant-agent/blob/main/README.en.md#results)

![Quant research dashboard with backtest curves and benchmark comparisons](assets/projects/stock-quant-agent.png)

### [dna-ssl-project](https://github.com/Leruo212/dna-ssl-project)

A CNN encoder pretrained with masked reconstruction, then frozen while an MLP head learns to classify four species. The current experiment reaches 68.25% validation accuracy. Training logs, feature plots and the debugging notes from an earlier chance-level classifier are included.

[Experiment and debugging notes](https://github.com/Leruo212/dna-ssl-project/blob/main/README.en.md#post-mortem-why-the-classification-head-stayed-near-chance)

![DNA experiment showing training curves and sequence feature projections](assets/projects/dna-ssl-project.png)

## Applications and Small Tools

### [ev-range-agent](https://github.com/Leruo212/ev-range-agent)

Estimates trip energy from a car, route, elevation, weather and payload, calculating uphill consumption and downhill recovery separately. Includes car comparisons, links that share trip inputs, printable reports and optional chat. Estimates are for trip planning; model assumptions and data limits are documented.

[Try it](https://leruo212.github.io/ev-range-agent/)

### [screenshare-p2p](https://github.com/Leruo212/screenshare-p2p)

Share a room link with a friend to show your screen in the browser. Built with WebRTC and PeerJS, hosted as static files with no backend to deploy yourself. It uses public signalling and attempts TURN relay when a direct connection is unavailable.

[Open the tool](https://leruo212.github.io/screenshare-p2p/screenshare.html)

### [boe-growth-agent](https://github.com/Leruo212/boe-growth-agent)

A conversational prototype for work notes and summaries, built with React, Express and the Coze API. Demo mode works without API credentials. Dashboard values are sample data, and persistent work-log storage is not implemented yet.

### [chinese-relative-title-calculator](https://github.com/Leruo212/chinese-relative-title-calculator)

A local web tool for looking up Chinese kinship terms. Build a relation path, look up reverse terms, or browse by generation. Uses only the Python standard library; paths outside the built-in relation table return an unknown result.

## Tools I Use

- **Models and data:** Python, PyTorch, CNNs, self-supervised learning.
- **Evaluation:** baseline comparisons, backtesting, feature visualisation, prediction records.
- **Applications:** JavaScript, React, Node.js, model tool calling.

These repositories include research experiments and application prototypes. Each README documents its results and limitations.

## Contact

[m4rh0zen@foxmail.com](mailto:m4rh0zen@foxmail.com)

<!-- Owner: Leruo212. Reviewed: 2026-11-25. Review when a featured project, role, demo URL, or contact changes. -->

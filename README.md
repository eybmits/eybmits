# Markus Baumann

I'm Markus Baumann, a researcher at LMU Munich and the QAR-Lab.

My research interests span quantum mechanics, quantum information, and quantum computation. I’m especially interested in how quantum systems store information and which problems quantum algorithms can solve efficiently.

Beyond these topics, I work on **AI for scientific research** itself. I use and study AI across the whole research process, from forming hypotheses and designing and running experiments to weighing the evidence and writing up results that others can reproduce. My goal is to find out how far AI can take science, and to make research faster, more transparent and easier to verify.

![AI for Science](https://img.shields.io/badge/-AI%20for%20Science-0065BD?style=flat-square)
![Time Series](https://img.shields.io/badge/-Time%20Series-2563EB?style=flat-square)
![Representation Learning](https://img.shields.io/badge/-Representation%20Learning-4338CA?style=flat-square)
![Quantum Reservoir Computing](https://img.shields.io/badge/-Quantum%20Reservoir%20Computing-0F766E?style=flat-square)
![Quantum Machine Learning](https://img.shields.io/badge/-Quantum%20Machine%20Learning-4338CA?style=flat-square)

[Website](https://eybmits.github.io/) · [Google Scholar](https://scholar.google.com/citations?hl=en&user=gjjgrw0AAAAJ) · [LMU profile](https://www.ifi.lmu.de/mvs/de/team/kontaktseite/markus-baumann-eb504667.html) · [QAR-Lab](https://qarlab.de/en/) · [Email](mailto:markus.baumann@campus.lmu.de)

## What I’m currently working on

- **Quantum reservoir computing** — Studying when noise erases a reservoir’s memory and when it helps preserve it.
- **Quantum machine learning** — Testing how circuit symmetries and training objectives affect generalization to unseen data.
- **Time series** — Comparing forecasting methods on chaotic signals and weather records.
- **Representation learning** — Turning quantum measurements into features that improve predictions.
- **AI for science** — How can AI accelerate research, from the first hypothesis to a reproducible result?

## Open Research

| Paper & resources | Main insight | Venue / status |
|---|---|---|
| [Parity Supervision as a Driver of Generalization in Quantum Generative Modeling](https://arxiv.org/abs/2605.10258)<br>[Code](https://github.com/eybmits/iqp-generative-modeling) · [Validation update](https://github.com/eybmits/iqp-generative-modeling/blob/main/docs/corrections.md "Post-publication validation across architectures and target distributions") | Training on correlations among bits helped a quantum generator discover unseen high-value states when those correlations matched the structure of the data. | ✓ [QCE ’26](https://qce.quantum.ieee.org/2026/ "Accepted at IEEE QCE 2026, QGDD technical papers") [🏆 2nd](https://qce.quantum.ieee.org/2026/wp-content/uploads/sites/13/2026/08/QCE26-Best-Papers-v19.pdf "Best Paper Award — 2nd place, QGDD track") |
| [Symmetry Alone Is Not an Ansatz: Task-Aligned Interactions in Equivariant Quantum Circuits](https://arxiv.org/abs/2606.20316)<br>[Code](https://github.com/eybmits/vqml-symmetry) · [Benchmark data](https://github.com/eybmits/vqml-symmetry/blob/main/results/csv/leak_free_d4_v1/table_leak_free_summary.csv "Camera-ready results with orbit-disjoint train and test sets") | Even when a circuit respects the symmetries of a tic-tac-toe board, it learns better when its gates connect the squares that form winning lines. | ✓ [QCE ’26 workshop](https://qce.quantum.ieee.org/2026/ "Accepted at IEEE QCE 2026, 4th International Workshop on Quantum Machine Learning: From Research to Practice") |
| [Where a Quantum Reservoir Works: A Transferable Operating Band](https://arxiv.org/abs/2606.13284)<br>[Code](https://github.com/eybmits/qrc-operating-band) · [Operating-band map](https://github.com/eybmits/qrc-operating-band/blob/main/paper/gfx/fig1_short_phase_maps.pdf "Operating-band maps across four forecasting tasks") | A simple memory test can identify useful reservoir settings before training begins, and the same range of settings works across forecasting tasks. | ✓ [QCE ’26 workshop](https://qce.quantum.ieee.org/2026/ "Accepted at IEEE QCE 2026, 4th International Workshop on Quantum Machine Learning: From Research to Practice") |
| [From Quantum Shots to Training Data: Reorganizing Measurement Records in Quantum Machine Learning](https://arxiv.org/abs/2604.28160)<br>[Code](https://github.com/eybmits/adaptive-shot-aggregation) · [IBM measurement data](https://github.com/eybmits/adaptive-shot-aggregation/tree/main/results/qai_hardware "IBM Fez and Marrakesh shot records") | Grouping existing measurements into training examples can improve predictions without a single extra run on the quantum processor. | ✓ [IEEE QAI 2026](https://attend.ieee.org/qai-2026/ "Accepted at IEEE QAI 2026") |
| [Exploiting Symmetry in Quantum Reservoir Computing](https://arxiv.org/abs/2607.01187)<br>[Code](https://github.com/eybmits/qrc-symmetry) · [Hardware results](https://github.com/eybmits/qrc-symmetry/tree/main/experiments/paper_experiments/exp4_measurement_visible_symmetry/hardware_ibm_advection_k8_10seed_train12_val6_test12_256 "IBM hardware results across ten reservoir seeds") | Preserving symmetry through measurement and readout lets a quantum reservoir learn a shared forecasting rule from all sensors on a ring. | ✓ [IEEE QAI 2026](https://attend.ieee.org/qai-2026/ "Accepted at IEEE QAI 2026") |
| [When Can Quantum Extreme Learning Machines Replace Quantum Reservoirs?](https://arxiv.org/abs/2609.31027)<br>[Code](https://github.com/eybmits/qrc_vs_qelm) · [Reproduction guide](https://github.com/eybmits/qrc_vs_qelm/blob/main/REPRODUCIBILITY.md "Numerical protocols, data and reproduction commands") | An expressive model can emulate a reservoir from recent inputs alone when the influence of the distant past fades across all input histories. | ✓ [ICAART 2027](https://icaart.scitevents.org/ "Accepted at ICAART 2027") |
| [Can One Hear the Size of a Clock?](https://arxiv.org/abs/2611.10252)<br>[Code](https://github.com/eybmits/can-one-hear-the-size-of-a-clock-code) · [Visual explanation](https://github.com/eybmits/can-one-hear-the-size-of-a-clock-code#the-result-in-one-picture "A visual explanation of the rhythm bound") | The number and sharpness of a noisy clock’s rhythms reveal a lower bound on the number of hidden states needed to produce them. | [PRL](https://journals.aps.org/prl/ "Physical Review Letters") · under review |
| [The Fundamental Memory Ceiling of Noisy Quantum Reservoirs](https://arxiv.org/abs/2610.26228)<br>[Code](https://github.com/eybmits/fresh-qubits-memory) · [Reproduction guide](https://github.com/eybmits/fresh-qubits-memory/blob/main/docs/reproduction.md "Run the memory simulations and reproduce the figures") | Under depolarizing noise, the supply of fresh qubits at each step sets the longest time a reservoir can remember an input, regardless of its size. | [PRL](https://journals.aps.org/prl/ "Physical Review Letters") · under review |
| [The Form of Dissipation Shapes What a Quantum Reservoir Remembers](https://arxiv.org/abs/2608.14181)<br>[Code](https://github.com/eybmits/what-a-dissipative-quantum-system-remembers) · [Simulation data](https://github.com/eybmits/what-a-dissipative-quantum-system-remembers/tree/main/paper_v2/data "Figure data and raw simulation results") | When qubits decay together, stronger dissipation can protect the states that carry memory and keep a record of past inputs alive for longer. | [Quantum](https://quantum-journal.org/) · under review |

✓ Accepted · 🏆 QGDD Best Paper Award

## Projects

| Project | Focus |
|---|---|
| [Wolfram S Combinator Challenge](https://github.com/eybmits/pure-s-two-scan-universality) | My proposed solution to the [$20,000 challenge](https://www.combinatorprize.org/) simulates Turing machines by parallel innermost S-reduction, with proofs in Lean. |
| [Vibe Shuffle](https://github.com/eybmits/vibe-shuffle) | Browser-based study comparing sensor-guided and random song selection using listeners' ratings of mood fit. |
| [Longevity Logbook](https://github.com/eybmits/longevity-logbook) | Terminal-first training logbook with editable strength programming. |
| [100x100 Pomodoro](https://github.com/eybmits/pomodoro-100x100) | Minimal Pomodoro tracker for repeated focused work sessions. |

## Documentation and tools

| Project | Focus |
|---|---|
| [Research Website](https://github.com/eybmits/research-website) | Public website and research identity hub. |
| [QRC Learning Platform](https://github.com/eybmits/qrc-learning-platform) | Learning site for Quantum Reservoir Computing concepts and flashcards. |
| [Spaced-Repetition Tutor](https://github.com/eybmits/spaced-repetition-tutor) | Spaced-repetition and LLM tutoring loops for learning workflows. |
| [macOS Writing Assistant](https://github.com/eybmits/writing-assistant-macos) | Sentence-level German and English correction with fast undo. |

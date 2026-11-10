**I make stuff.** Mostly brains, sometimes planets.

I'm a self-taught developer and independent undergrad "researcher" based in France. I started programming as a high school student, made a basic minecraft mod during that period in java until 2025. I started my first perceptron-based neural network in 2025, after that, I made a (non-functional) CNN in summer, then, on october 2025, I started my first SNN, rapidly adding calcium, then homeostasis, and ended up writing a GPU simulator of dendrites, ion channels, and neuromodulators in C++ and CUDA. That's still what I'm doing.

I also make (non-AI) art (lost time for that due to my project, but I sometimes indulge), I am really into politics, science, culture, history, neuroscience (obviously), space, and general knowledge about the world.

---

## 🧠 What I'm building

### ANS: Artificial Nervous System
*My main project, developed under **Crimson**.*

ANS is a research simulator that asks whether general, continual learning can emerge from the mechanisms real nervous systems use, rather than from gradient descent on point neurons. It isn't another LLM or a standard ANN:

- **Multi-compartment neurons.** Branching cells (soma, dendrites, spines, axon initial segment) with explicit Na⁺/K⁺ ion-channel populations, calcium handling, and NMDA/GABA receptors.
- **Locality, no backprop.** Every learning rule uses information available at the synapse, compartment, or neuron. There is no global loss.
- **No injected reward.** Value signals come from the simulated body and modelled circuits (gustatory, nociceptive, LHb → RMTg → VTA/SNc), plus neuromodulators (DA, 5-HT, NE, ACh) and hormones. I never write a reward number into the network.
- **Genes, not hyperparameters.** A heritable genome (`BrainDNA`) grows the brain, from the spinal cord and hindbrain up to the basal ganglia, cerebellum, hypothalamus, amygdala, visual pathway, and cortex. Mutation and selection are the slowest learning timescale.
- **Embodied.** Brains get senses and motor outputs in simulated worlds (target tracking, Pong, a flatworm in a dish) instead of learning from text.
- **Evidence before promotion.** A mechanism goes into the default genome (`LUCA`) only after it passes validation gates, and rejected ideas stay documented.

It runs on CUDA with one thread per compartment, and comes with a retro CRT-style web dashboard for watching it think (or not).

**Status:** pre-results research. The simulator, genome, and validation suite work. Reliable task learning hasn't been demonstrated yet, and finding out why is what I'm doing right now.

**Stack:** C++23 · CUDA 13 · CMake/Ninja · Python · Node.js dashboard

📄 Paper: **CortexZero**, [doi:10.5281/zenodo.17752996](https://doi.org/10.5281/zenodo.17752996)

🔬 Public snapshot: [CortexZero-public](https://github.com/ClaraArmada/CortexZero-public), a single multi-compartment dendritic neuron with calcium, voltage, NMDA, dendrites, and neuromodulators

💬 [Discord](https://discord.com/invite/8BbwSWdTN5) · ▶️ [YouTube](https://www.youtube.com/channel/@clarawasarmada)

### 🌍 Serilis
An ambitious tech and progression Minecraft mod (NeoForge). It starts in the stone age with flint tools and aims for the space age, passing through clockwork, steam, dieselpunk, machines, and vehicles. The current version focuses on realistic planets: tectonics, geology, hydrology, and climate.

➡️ [serilis2](https://github.com/ClaraArmada/serilis2) (the old version lives at [Serilis](https://github.com/ClaraArmada/Serilis))

### Coming soon
ANSDaemon.

---

## 🧰 Tools I use

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual_Studio-5C2D91?style=flat&logo=visualstudio&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

**Coding Agents:**

![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=claudecode&logoColor=white)
![Codex](https://img.shields.io/badge/Codex-000000?style=flat&logo=chatgpt&logoColor=white)

**Interests:** computational neuroscience · machine learning · artificial intelligence · biologically plausible AI · GPU programming · evolution & development · simulation & procedural worlds · game modding

I prefer not using coding agents, but when I need to, I go all in, and I use it properly, preserving the maintainability of my project.

---

## 🔭 Right now

- 🧪 Tracking down why ANS doesn't learn yet: the dopamine teaching pathway (LHb → RMTg → SNc/VTA), credit assignment, and spike initiation at the axon initial segment. I'm doing it with evidence, not parameter tweaking.
- 🖥️ Building research views for the ANS dashboard

---

## 📫 Find me

- 𝕏 / Twitter: [@ClaraWorldDom](https://twitter.com/ClaraWorldDom)
- Discord: [ANS community](https://discord.com/invite/8BbwSWdTN5)
- YouTube: [my channel](https://www.youtube.com/channel/@clarawasarmada)
- Patreon: [ClaraArmada](https://www.patreon.com/c/ClaraArmada)
- Ko-fi: [claraarmada](https://ko-fi.com/claraarmada)
- Hugging Face: [ClaraArmada](https://huggingface.co/ClaraArmada)
- Bluesky: [claraworlddom](https://bsky.app/profile/claraworlddom.bsky.social)
- Email: [clara.poillot.contact@gmail.com](mailto:clara.poillot.contact@gmail.com)
- all socials: [claraarmada](https://linktr.ee/claraarmada)

<sub>Some of my work, ANS included, lives in private repos; feel free to ask if you're curious.</sub>

## Hi there 👋

<!--
**danshangyanyi/danshangyanyi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# Harnessing Reasoning and Planning Abilities in LLM-Based Agents

Last update: 12/05/2024

<img src="./img/time.png" width="96%" height="96%">

<font size=5><center><b> Table of Contents </b> </center></font>
- [Papers](#Apapers)
  - [Taxonomy](#taxonomy)
    - [Type Ⅰ](#Type-Ⅰ)
    - [Type Ⅱ](#Type-Ⅱ)
    - [Type Ⅲ](#Type-Ⅲ)
    - [Type Ⅳ](#Type-Ⅳ)
    - [Multi-Agent](#Multi-Agent)
  - [Application](#application)
    - [Complex Visual Reasoning Tasks](#-complex-visual-reasoning-tasks)
    - [Audio Editing & Generation](#-audio-editing--generation)
    - [Embodied AI & Robotics](#-embodied-ai--robotics)
    - [UI-assistants](#--ui-assistants)
    - [Video Understanding](#-video-understanding)
    - [Visual Generation & Editing](#-visual-generation--editing)
    - [Game-developer](#-game-developer)
- [Benchmark](#benchmark)
---

## Papers

### Taxonomy

<img src="./img/table.png" width="96%" height="96%">

#### Type Ⅰ


- [**CLOVA**](https://arxiv.org/pdf/2312.10908.pdf) - CLOVA: A Closed-Loop Visual Assistant with Tool Usage and Update

- [**CRAFT**](https://arxiv.org/pdf/2309.17428.pdf) - CRAFT: Customizing LLMs by Creating and Retrieving from Specialized Toolsets
  
- [**ViperGPT**](https://arxiv.org/pdf/2303.08128.pdf) - ViperGPT: Visual Inference via Python Execution for Reasoning [Github](https://github.com/cvlab-columbia/viper)
![Star](https://img.shields.io/github/stars/cvlab-columbia/viper.svg?style=social&label=Star)

- [**HuggingGPT**](https://arxiv.org/pdf/2303.17580.pdf) - HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face [Github](https://github.com/microsoft/JARVIS)
![Star](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)

- [**Chameleon**](https://arxiv.org/pdf/2304.09842.pdf) - Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models [Github](https://github.com/lupantech/chameleon-llm)
![Star](https://img.shields.io/github/stars/lupantech/chameleon-llm.svg?style=social&label=Star)

- [**Visual ChatGPT**](https://arxiv.org/pdf/2303.04671.pdf) - Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models [Github](https://github.com/moymix/TaskMatrix)
![Star](https://img.shields.io/github/stars/moymix/TaskMatrix.svg?style=social&label=Star)

- [**AssistGPT**](https://arxiv.org/pdf/2306.08640.pdf) - AssistGPT: A General Multi-modal Assistant that can Plan, Execute, Inspect, and Learn [Github](https://github.com/showlab/assistgpt)
![Star](https://img.shields.io/github/stars/showlab/assistgpt.svg?style=social&label=Star)

- [**M3**](https://arxiv.org/pdf/2310.08446.pdf) - Towards Robust Multi-Modal Reasoning via Model Selection [Github](https://github.com/LINs-lab/M3)
![Star](https://img.shields.io/github/stars/showlab/assistgpt.svg?style=social&label=Star)

- [**VisProgram**](https://arxiv.org/pdf/2211.11559.pdf) - Visual Programming: Compositional visual reasoning without training

- [**DDCoT**](https://arxiv.org/pdf/2310.16436.pdf) - DDCoT: Duty-Distinct Chain-of-Thought Prompting for Multimodal Reasoning in Language Models [Github](https://github.com/SooLab/DDCOT)
![Star](https://img.shields.io/github/stars/SooLab/DDCOT.svg?style=social&label=Star)

- [**ASSISTGUI**](https://arxiv.org/pdf/2312.13108.pdf) - ASSISTGUI: Task-Oriented Desktop Graphical User Interface Automation [Github](https://github.com/showlab/assistgui)
![Star](https://img.shields.io/github/stars/showlab/assistgui.svg?style=social&label=Star)

- [**GPT-Driver**](https://arxiv.org/pdf/2310.01415.pdf) - GPT-Driver: Learning to Drive with GPT [Github](https://github.com/PointsCoder/GPT-Driver)
![Star](https://img.shields.io/github/stars/PointsCoder/GPT-Driver.svg?style=social&label=Star)

- [**LLaVA-Interactive**](https://arxiv.org/pdf/2311.00571.pdf) - 
LLaVA-Interactive: An All-in-One Demo for Image Chat, Segmentation, Generation and Editing [Github](https://github.com/LLaVA-VL/LLaVA-Interactive-Demo)
![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Interactive-Demo.svg?style=social&label=Star)

- [**MusicAgent**](https://arxiv.org/pdf/2310.11954.pdf) - MusicAgent: An AI Agent for Music Understanding and Generation with Large Language Models [Github](https://github.com/microsoft/muzic/tree/main)
![Star](https://img.shields.io/github/stars/microsoft/muzic.svg?style=social&label=Star)


- [**AudioGPT**](https://arxiv.org/pdf/2304.12995.pdf) - AudioGPT: Understanding and Generating Speech,
Music, Sound, and Talking Head [Github](https://github.com/AIGC-Audio/AudioGPT)
![Star](https://img.shields.io/github/stars/AIGC-Audio/AudioGPT.svg?style=social&label=Star)


- [**DroidBot-GPT**](https://arxiv.org/pdf/2304.07061.pdf) - DroidBot-GPT: GPT-powered UI Automation for Android [Github](https://github.com/MobileLLM/DroidBot-GPT)
![Star](https://img.shields.io/github/stars/MobileLLM/DroidBot-GPT.svg?style=social&label=Star)

- [**GRID**](https://arxiv.org/pdf/2311.05997.pdf) - GRID: A Platform for General Robot Intelligence Development [Github](https://github.com/ScaledFoundations/GRID-playground)
![Star](https://img.shields.io/github/stars/ScaledFoundations/GRID-playground.svg?style=social&label=Star)

- [**DEPS**](https://arxiv.org/pdf/2302.01560.pdf) - Describe, Explain, Plan and Select:
Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents [Github](https://github.com/CraftJarvis/MC-Planner)
![Star](https://img.shields.io/github/stars/CraftJarvis/MC-Planner.svg?style=social&label=Star)

- [**MM-REACT**](https://arxiv.org/pdf/2303.11381.pdf) - MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action [Github](https://github.com/microsoft/MM-REACT)
![Star](https://img.shields.io/github/stars/microsoft/MM-REACT.svg?style=social&label=Star)

- [**MuLan**](https://arxiv.org/pdf/2402.12741.pdf) - MuLan: Multimodal-LLM Agent for Progressive Multi-Object Diffusion [Github](https://github.com/measure-infinity/mulan-code)
![Star](https://img.shields.io/github/stars/measure-infinity/mulan-code.svg?style=social&label=Star)

- [**Mobile-Agent**](https://arxiv.org/pdf/2401.16158.pdf) - Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception [Github](https://github.com/X-PLUG/MobileAgent)![Star](https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star)

- [**SeeAct**](https://arxiv.org/pdf/2401.01614) - GPT-4V(ision) is a Generalist Web Agent, if Grounded
 [Github]("https://github.com/OSU-NLP-Group/SeeAct")![Star](https://img.shields.io/github/stars/OSU-NLP-Group/SeeAct?style=social)


#### Type Ⅱ

 - [**STEVE**](https://arxiv.org/pdf/2311.15209.pdf) - See and Think: Embodied Agent in Virtual Environment [Github](https://github.com/rese1f/STEVE)
![Star](https://img.shields.io/github/stars/rese1f/STEVE.svg?style=social&label=Star)


- [**EMMA**](https://arxiv.org/pdf/2311.16714.pdf) - Embodied Multi-Modal Agent trained by an LLM from a Parallel TextWorld [Github](https://github.com/stevenyangyj/Emma-Alfworld)
![Star](https://img.shields.io/github/stars/stevenyangyj/Emma-Alfworld.svg?style=social&label=Star)


- [**MLLM-Tool**](https://arxiv.org/pdf/2401.10727.pdf) - MLLM-Tool: A Multimodal Large Language Model For Tool Agent Learning [Github](https://github.com/MLLM-Tool/MLLM-Tool)
![Star](https://img.shields.io/github/stars/MLLM-Tool/MLLM-Tool.svg?style=social&label=Star)

- [**LLaVA-Plus**](https://arxiv.org/pdf/2306.08640.pdf) - LLaVA-Plus: Large Language and Vision Assistants that Plug and Learn to Use Skills [Github](https://github.com/LLaVA-VL/LLaVA-Plus-Codebase)
![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Plus-Codebase.svg?style=social&label=Star)

- [**GPT4Tools**](https://arxiv.org/pdf/2305.18752.pdf) - GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction [Github](https://github.com/AILab-CVC/GPT4Tools)
![Star](https://img.shields.io/github/stars/AILab-CVC/GPT4Tools.svg?style=social&label=Star)

- [**WebWISE**](https://arxiv.org/pdf/2310.16042.pdf) - WebWISE: Web Interface Control and Sequential Exploration with Large Language Models 

- [**Auto-UI**](https://arxiv.org/pdf/2309.11436.pdf) - You Only Look at Screens: Multimodal Chain-of-Action Agents [Github](https://github.com/cooelf/Auto-UI)
![Star](https://img.shields.io/github/stars/cooelf/Auto-UI.svg?style=social&label=Star)

#### Type Ⅲ

- [**DoraemonGPT**](https://arxiv.org/pdf/2401.08392.pdf) - DoraemonGPT: Toward Understanding Dynamic Scenes with Large Language Models [Github](https://github.com/cooelf/Auto-UI)
![Star](https://img.shields.io/github/stars/cooelf/Auto-UI.svg?style=social&label=Star)

- [**ChatVideo**](https://arxiv.org/pdf/2304.14407.pdf) - ChatVideo: A Tracklet-centric Multimodal and Versatile Video Understanding System [Github](https://www.wangjunke.info/ChatVideo/)

- [**VideoAgent**](https://arxiv.org/abs/2403.11481) -- VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding [Project page](https://videoagent.github.io/)

#### Type Ⅳ

- [**JARV IS-1**](https://arxiv.org/pdf/2311.05997.pdf) - JARVIS-1: Open-world Multi-task Agents with
Memory-Augmented Multimodal Language Models [Github](https://github.com/CraftJarvis/JARVIS-1)
![Star](https://img.shields.io/github/stars/CraftJarvis/JARVIS-1.svg?style=social&label=Star)

- [**AppAgent**](https://arxiv.org/pdf/2312.13771.pdf) - AppAgent: Multimodal Agents as Smartphone Users [Github](https://github.com/mnotgod96/AppAgent)
![Star](https://img.shields.io/github/stars/mnotgod96/AppAgent.svg?style=social&label=Star)

- [**MM-Navigator**](https://arxiv.org/pdf/2311.07562.pdf) - GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation [Github](https://github.com/zzxslp/MM-Navigator)
![Star](https://img.shields.io/github/stars/zzxslp/MM-Navigator.svg?style=social&label=Star)

- [**Copilot**](https://arxiv.org/pdf/2310.12404.pdf) - Loop Copilot: Conducting AI Ensembles for Music
Generation and Iterative Editing [Github](https://github.com/ldzhangyx/loop-copilot/)
![Star](https://img.shields.io/github/stars/ldzhangyx/loop-copilot.svg?style=social&label=Star)

- [**WavJourney**](https://arxiv.org/pdf/2310.12404.pdf) - WavJourney: Compositional Audio Creation with Large Language Models [Github](https://github.com/Audio-AGI/WavJourney)
![Star](https://img.shields.io/github/stars/Audio-AGI/WavJourney.svg?style=social&label=Star)

- [**DLAH**](https://arxiv.org/pdf/2307.07162.pdf) - Drive Like a Human: Rethinking Autonomous Driving with Large Language Models [Github](https://github.com/PJLab-ADG/DriveLikeAHuman)
![Star](https://img.shields.io/github/stars/PJLab-ADG/DriveLikeAHuman.svg?style=social&label=Star)

- [**Cradle**](https://arxiv.org/pdf/2403.03186.pdf) - Towards General Computer Control: A Multimodal Agent for Red Dead Redemption II as a Case Study [Github](https://github.com/BAAI-Agents/Cradle) ![Star](https://img.shields.io/github/stars/BAAI-Agents/Cradle.svg?style=social&label=Star)

- [**VideoAgent**](https://arxiv.org/abs/2403.11481) -- VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding [Project page](https://videoagent.github.io/)

#### Multi-Agent

- [**MP5**](https://arxiv.org/pdf/2312.07472.pdf) - MP5: A Multi-modal Open-ended Embodied System in Minecraft via Active Perception [Github](https://github.com/IranQin/MP5)
![Star](https://img.shields.io/github/stars/IranQin/MP5.svg?style=social&label=Star)

- [**MemoDroid**](https://arxiv.org/pdf/2312.03003.pdf) - Explore, Select, Derive, and Recall: Augmenting LLM with Human-like Memory for Mobile Task Automation

- [**Avis**](https://arxiv.org/pdf/2306.08129.pdf) - avis: autonomous visual information seeking with large language model agent

- [**Agent-Smith**](https://arxiv.org/pdf/2402.08567.pdf) - Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast [Github](https://github.com/sail-sg/Agent-Smith)![Star](https://img.shields.io/github/stars/sail-sg/Agent-Smith.svg?style=social&label=Star)

- [**GenAI**](https://arxiv.org/pdf/2409.11261.pdf) - The Art of Storytelling: Multi-Agent Generative AI for Dynamic
Multimodal Narratives [Github](https://github.com/ulrs0/The-Art-of-Story-Telling)![Star](https://img.shields.io/github/stars/ulrs0/The-Art-of-Story-Telling.svg?style=social&label=Star)

- [**P2H**](https://arxiv.org/pdf/2409.07246.pdf) - Propaganda to Hate: A Multimodal Analysis of Arabic Memes with Multi-Agent LLMs 

## Application

<img src="./img/app.png" width="96%" height="96%">

#### 💡 Complex Visual Reasoning Tasks

- [**ViperGPT**](https://arxiv.org/pdf/2303.08128.pdf) - ViperGPT: Visual Inference via Python Execution for Reasoning [Github](https://github.com/cvlab-columbia/viper)
![Star](https://img.shields.io/github/stars/cvlab-columbia/viper.svg?style=social&label=Star)

- [**HuggingGPT**](https://arxiv.org/pdf/2303.17580.pdf) - HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face [Github](https://github.com/microsoft/JARVIS)
![Star](https://img.shields.io/github/stars/microsoft/JARVIS.svg?style=social&label=Star)

- [**Chameleon**](https://arxiv.org/pdf/2304.09842.pdf) - Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models [Github](https://github.com/lupantech/chameleon-llm)
![Star](https://img.shields.io/github/stars/lupantech/chameleon-llm.svg?style=social&label=Star)

- [**Visual ChatGPT**](https://arxiv.org/pdf/2303.04671.pdf) - Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models [Github](https://github.com/moymix/TaskMatrix)
![Star](https://img.shields.io/github/stars/moymix/TaskMatrix.svg?style=social&label=Star)

- [**AssistGPT**](https://arxiv.org/pdf/2306.08640.pdf) - AssistGPT: A General Multi-modal Assistant that can Plan, Execute, Inspect, and Learn [Github](https://github.com/showlab/assistgpt)
![Star](https://img.shields.io/github/stars/showlab/assistgpt.svg?style=social&label=Star)

- [**LLaVA-Plus**](https://arxiv.org/pdf/2306.08640.pdf) - LLaVA-Plus: Large Language and Vision Assistants that Plug and Learn to Use Skills [Github](https://github.com/LLaVA-VL/LLaVA-Plus-Codebase)
![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Plus-Codebase.svg?style=social&label=Star)

- [**GPT4Tools**](https://arxiv.org/pdf/2305.18752.pdf) - GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction [Github](https://github.com/AILab-CVC/GPT4Tools)
![Star](https://img.shields.io/github/stars/AILab-CVC/GPT4Tools.svg?style=social&label=Star)

- [**MLLM-Tool**](https://arxiv.org/pdf/2401.10727.pdf) - MLLM-Tool: A Multimodal Large Language Model For Tool Agent Learning [Github](https://github.com/MLLM-Tool/MLLM-Tool)
![Star](https://img.shields.io/github/stars/MLLM-Tool/MLLM-Tool.svg?style=social&label=Star)

- [**M3**](https://arxiv.org/pdf/2310.08446.pdf) - Towards Robust Multi-Modal Reasoning via Model Selection [Github](https://github.com/LINs-lab/M3)
![Star](https://img.shields.io/github/stars/showlab/assistgpt.svg?style=social&label=Star)

- [**VisProgram**](https://arxiv.org/pdf/2211.11559.pdf) - Visual Programming: Compositional visual reasoning without training

- [**DDCoT**](https://arxiv.org/pdf/2310.16436.pdf) - DDCoT: Duty-Distinct Chain-of-Thought Prompting for Multimodal Reasoning in Language Models [Github](https://github.com/SooLab/DDCOT)
![Star](https://img.shields.io/github/stars/SooLab/DDCOT.svg?style=social&label=Star)

- [**Avis**](https://arxiv.org/pdf/2306.08129.pdf) - Explore, Select, Derive, and Recall: Augmenting LLM with Human-like Memory for Mobile Task Automation

- [**CLOVA**](https://arxiv.org/pdf/2312.10908.pdf) - CLOVA: A Closed-Loop Visual Assistant with Tool Usage and Update

- [**CRAFT**](https://arxiv.org/pdf/2309.17428.pdf) - CRAFT: Customizing LLMs by Creating and Retrieving from Specialized Toolsets

- [**MuLan**](https://arxiv.org/pdf/2402.12741.pdf) - MuLan: Multimodal-LLM Agent for Progressive Multi-Object Diffusion [Github](https://github.com/measure-infinity/mulan-code)
![Star](https://img.shields.io/github/stars/measure-infinity/mulan-code.svg?style=social&label=Star)

#### 🎵 Audio Editing & Generation

- [**Copilot**](https://arxiv.org/pdf/2310.12404.pdf) - Loop Copilot: Conducting AI Ensembles for Music
Generation and Iterative Editing [Github](https://github.com/ldzhangyx/loop-copilot/)
![Star](https://img.shields.io/github/stars/ldzhangyx/loop-copilot.svg?style=social&label=Star)

- [**MusicAgent**](https://arxiv.org/pdf/2310.11954.pdf) - MusicAgent: An AI Agent for Music Understanding and Generation with Large Language Models [Github](https://github.com/microsoft/muzic/tree/main)
![Star](https://img.shields.io/github/stars/microsoft/muzic.svg?style=social&label=Star)

- [**AudioGPT**](https://arxiv.org/pdf/2304.12995.pdf) - AudioGPT: Understanding and Generating Speech,
Music, Sound, and Talking Head [Github](https://github.com/AIGC-Audio/AudioGPT)
![Star](https://img.shields.io/github/stars/AIGC-Audio/AudioGPT.svg?style=social&label=Star)

- [**WavJourney**](https://arxiv.org/pdf/2310.12404.pdf) - WavJourney: Compositional Audio Creation with Large Language Models [Github](https://github.com/Audio-AGI/WavJourney)
![Star](https://img.shields.io/github/stars/Audio-AGI/WavJourney.svg?style=social&label=Star)

- [**OpenOmni**](https://arxiv.org/abs/2408.03047.pdf) - OpenOmni: A Collaborative Open Source Tool for Building Future-Ready Multimodal Conversational Agents [Github](https://github.com/AI4WA/OpenOmniFramework)
![Star](https://img.shields.io/github/stars/AI4WA/OpenOmniFramework.svg?style=social&label=Star)


#### 🤖 Embodied AI & Robotics

- [**JARV IS-1**](https://arxiv.org/pdf/2311.05997.pdf) - JARVIS-1: Open-world Multi-task Agents with
Memory-Augmented Multimodal Language Models [Github](https://github.com/CraftJarvis/JARVIS-1)
![Star](https://img.shields.io/github/stars/CraftJarvis/JARVIS-1.svg?style=social&label=Star)


- [**DEPS**](https://arxiv.org/pdf/2302.01560.pdf) - Describe, Explain, Plan and Select:
Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents [Github](https://github.com/CraftJarvis/MC-Planner)
![Star](https://img.shields.io/github/stars/CraftJarvis/MC-Planner.svg?style=social&label=Star)


- [**Octopus**](https://arxiv.org/pdf/2310.08588.pdf) - Octopus: Embodied Vision-Language Programmer from Environmental Feedback [Github](https://github.com/dongyh20/Octopus)
![Star](https://img.shields.io/github/stars/dongyh20/Octopus.svg?style=social&label=Star)

- [**GRID**](https://arxiv.org/pdf/2311.05997.pdf) - GRID: A Platform for General Robot Intelligence Development [Github](https://github.com/ScaledFoundations/GRID-playground)
![Star](https://img.shields.io/github/stars/ScaledFoundations/GRID-playground.svg?style=social&label=Star)


- [**MP5**](https://arxiv.org/pdf/2312.07472.pdf) - MP5: A Multi-modal Open-ended Embodied System in Minecraft via Active Perception [Github](https://github.com/IranQin/MP5)
![Star](https://img.shields.io/github/stars/IranQin/MP5.svg?style=social&label=Star)

- [**STEVE**](https://arxiv.org/pdf/2311.15209.pdf) - See and Think: Embodied Agent in Virtual Environment [Github](https://github.com/rese1f/STEVE)
![Star](https://img.shields.io/github/stars/rese1f/STEVE.svg?style=social&label=Star)


- [**EMMA**](https://arxiv.org/pdf/2311.16714.pdf) - Embodied Multi-Modal Agent trained by an LLM from a Parallel TextWorld [Github](https://github.com/stevenyangyj/Emma-Alfworld)
![Star](https://img.shields.io/github/stars/stevenyangyj/Emma-Alfworld.svg?style=social&label=Star)

- [**MEIA**](https://arxiv.org/abs/2402.00290) - Multimodal Embodied Interactive Agent for Cafe Scene 

#### 🖱️💻 UI-assistants
- [**AppAgent**](https://arxiv.org/pdf/2312.13771.pdf) - AppAgent: Multimodal Agents as Smartphone Users [Github](https://github.com/mnotgod96/AppAgent)
![Star](https://img.shields.io/github/stars/mnotgod96/AppAgent.svg?style=social&label=Star)

- [**DroidBot-GPT**](https://arxiv.org/pdf/2304.07061.pdf) - DroidBot-GPT: GPT-powered UI Automation for Android [Github](https://github.com/MobileLLM/DroidBot-GPT)
![Star](https://img.shields.io/github/stars/MobileLLM/DroidBot-GPT.svg?style=social&label=Star)

- [**WebWISE**](https://arxiv.org/pdf/2310.16042.pdf) - WebWISE: Web Interface Control and Sequential Exploration with Large Language Models 

- [**Auto-UI**](https://arxiv.org/pdf/2309.11436.pdf) - You Only Look at Screens: Multimodal Chain-of-Action Agents [Github](https://github.com/cooelf/Auto-UI)
![Star](https://img.shields.io/github/stars/cooelf/Auto-UI.svg?style=social&label=Star)

- [**MemoDroid**](https://arxiv.org/pdf/2312.03003.pdf) - Explore, Select, Derive, and Recall: Augmenting LLM with Human-like Memory for Mobile Task Automation 

- [**ASSISTGUI**](https://arxiv.org/pdf/2312.13108.pdf) - ASSISTGUI: Task-Oriented Desktop Graphical User Interface Automation [Github](https://github.com/showlab/assistgui)
![Star](https://img.shields.io/github/stars/showlab/assistgui.svg?style=social&label=Star)

- [**MM-Navigator**](https://arxiv.org/pdf/2311.07562.pdf) - GPT-4V in Wonderland: Large Multimodal Models for Zero-Shot Smartphone GUI Navigation [Github](https://github.com/zzxslp/MM-Navigator)
![Star](https://img.shields.io/github/stars/zzxslp/MM-Navigator.svg?style=social&label=Star)

- [**AutoDroid**](https://arxiv.org/pdf/2308.15272.pdf) - Empowering LLM to use Smartphone for Intelligent Task Automation [Github](https://github.com/MobileLLM/AutoDroid)
![Star](https://img.shields.io/github/stars/MobileLLM/AutoDroid.svg?style=social&label=Star)

- [**GPT-4V-Act**](https://github.com/ddupont808/GPT-4V-Act) - GPT-4V-Act: Chromium Copilot [Github](https://github.com/ddupont808/GPT-4V-Act)
![Star](https://img.shields.io/github/stars/ddupont808/GPT-4V-Act.svg?style=social&label=Star)

- [**Mobile-Agent**](https://arxiv.org/pdf/2401.16158.pdf) - Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception [Github](https://github.com/X-PLUG/MobileAgent)![Star](https://img.shields.io/github/stars/X-PLUG/MobileAgent.svg?style=social&label=Star)

- [**OpenAdapt**]- OpenAdapt: AI-First Process Automation with Large Multimodal Models [Github](https://github.com/OpenAdaptAI/OpenAdapt)![Star](https://img.shields.io/github/stars/OpenAdaptAI/OpenAdapt.svg?style=social&label=Star)

- [**EnvDistraction**]- Caution for the Environment: Multimodal Agents are Susceptible to Environmental Distractions [Github](https://github.com/xbmxb/EnvDistraction)![Star](https://img.shields.io/github/stars/xbmxb/EnvDistraction.svg?style=social&label=Star)


#### 🎨 Visual Generation & Editing
- [**LLaVA-Interactive**](https://arxiv.org/pdf/2311.00571.pdf) - 
LLaVA-Interactive: An All-in-One Demo for Image Chat, Segmentation, Generation and Editing [Github](https://github.com/LLaVA-VL/LLaVA-Interactive-Demo)
![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Interactive-Demo.svg?style=social&label=Star)

- [**MM-REACT**](https://arxiv.org/pdf/2303.11381.pdf) - MM-REACT: Prompting ChatGPT for Multimodal Reasoning and Action [Github](https://github.com/microsoft/MM-REACT)
![Star](https://img.shields.io/github/stars/microsoft/MM-REACT.svg?style=social&label=Star)

- [**SeeAct**](https://arxiv.org/pdf/2401.01614) - GPT-4V(ision) is a Generalist Web Agent, if Grounded
 [Github]("https://github.com/OSU-NLP-Group/SeeAct")![Star](https://img.shields.io/github/stars/OSU-NLP-Group/SeeAct?style=social)

- [**GenAI**](https://arxiv.org/pdf/2409.11261.pdf) - The Art of Storytelling: Multi-Agent Generative AI for Dynamic
Multimodal Narratives [Github](https://github.com/ulrs0/The-Art-of-Story-Telling)![Star](https://img.shields.io/github.com/ulrs0/The-Art-of-Story-Telling.svg?style=social&label=Star)

- [**GenArtist**](https://arxiv.org/pdf/2407.05600.pdf) - GenArtist: Multimodal LLM as an Agent for Unified Image Generation and Editing [Github](https://github.com/zhenyuw16/GenArtist)![Star](https://img.shields.io/github.com/zhenyuw16/GenArtist.svg?style=social&label=Star)

#### 🎥 Video Understanding

- [**DoraemonGPT**](https://arxiv.org/pdf/2401.08392.pdf) - DoraemonGPT: Toward Understanding Dynamic Scenes with Large Language Models [Github](https://github.com/cooelf/Auto-UI)
![Star](https://img.shields.io/github/stars/cooelf/Auto-UI.svg?style=social&label=Star)

- [**ChatVideo**](https://arxiv.org/pdf/2304.14407.pdf) - ChatVideo: A Tracklet-centric Multimodal and Versatile Video Understanding System [Github](https://www.wangjunke.info/ChatVideo/)

- [**AssistGPT**](https://arxiv.org/pdf/2401.08392.pdf) - AssistGPT: A General Multi-modal Assistant that can Plan, Execute, Inspect, and Learn [Github](https://github.com/showlab/assistgpt)
![Star](https://img.shields.io/github/stars/showlab/assistgpt.svg?style=social&label=Star)

- [**VideoAgent-M**](https://arxiv.org/abs/2403.11481) -- VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding [Project page](https://videoagent.github.io/)

- [**VideoAgent-L**](https://arxiv.org/pdf/2403.10517) - VideoAgent: Long-form Video Understanding with Large Language Model as Agent [Project page](https://wxh1996.github.io/VideoAgent-Website/)

- [**Kubrick**](https://www.arxiv.org/pdf/2408.10453.pdf) - Kubrick: Multimodal Agent Collaborations for Synthetic Video Generation [Github](https://github.com/gd3kr/BlenderGPT)
![Star](https://img.shields.io/github/stars/gd3kr/BlenderGPT.svg?style=social&label=Star)

- [**Anim-Director**](https://arxiv.org/pdf/2408.09787.pdf) - Anim-Director: A Large Multimodal Model Powered Agent for Controllable Animation Video Generation [Github](https://github.com/HITsz-TMG/Anim-Director)
![Star](https://img.shields.io/github/stars/HITsz-TMG/Anim-Director.svg?style=social&label=Star)


#### 🚗 Autonomous Driving


- [**GPT-Driver**](https://arxiv.org/pdf/2310.01415.pdf) - GPT-Driver: Learning to Drive with GPT [Github](https://github.com/PointsCoder/GPT-Driver)
![Star](https://img.shields.io/github/stars/PointsCoder/GPT-Driver.svg?style=social&label=Star)

- [**DLAH**](https://arxiv.org/pdf/2307.07162.pdf) - Drive Like a Human: Rethinking Autonomous Driving with Large Language Models [Github](https://github.com/PJLab-ADG/DriveLikeAHuman)
![Star](https://img.shields.io/github/stars/PJLab-ADG/DriveLikeAHuman.svg?style=social&label=Star)



#### 🎮 Game-developer

- [**SmartPlay**](https://arxiv.org/pdf/2310.01557.pdf) - SmartPlay: A Benchmark for LLMs as Intelligent Agents [Github](https://github.com/microsoft/SmartPlay)
![Star](https://img.shields.io/github/stars/microsoft/SmartPlay.svg?style=social&label=Star)

- [**VisualWebArena**](https://arxiv.org/pdf/2401.13649.pdf) - VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks [Github](https://github.com/web-arena-x/visualwebarena)
![Star](https://img.shields.io/github/stars/web-arena-x/visualwebarena.svg?style=social&label=Star)

- [**Cradle**](https://arxiv.org/pdf/2403.03186.pdf) - Towards General Computer Control: A Multimodal Agent for Red Dead Redemption II as a Case Study [Github](https://github.com/BAAI-Agents/Cradle) ![Star](https://img.shields.io/github/stars/BAAI-Agents/Cradle.svg?style=social&label=Star)

- [**Cradle**](https://arxiv.org/pdf/2403.03186.pdf) - Can AI Prompt Humans? Multimodal Agents Prompt Players’ Game Actions and Show Consequences to Raise Sustainability Awareness [Github](https://github.com/BAAI-Agents/Cradle) ![Star](https://img.shields.io/github/stars/BAAI-Agents/Cradle.svg?style=social&label=Star)

#### Other

- [**FinAgent**](https://arxiv.org/pdf/2402.18485.pdf) - A Multimodal Foundation Agent for Financial Trading: Tool-Augmented, Diversified, and Generalist

- [**VisionGPT**](https://arxiv.org/pdf/2402.18485.pdf) - VisionGPT: Vision-Language Understanding Agent Using Generalized Multimodal Framework

- [**WirelessAgent**](https://arxiv.org/pdf/2409.07964.pdf) - WirelessAgent: Large Language Model Agents for Intelligent Wireless Networks
  
- [**PhishAgent**](https://arxiv.org/pdf/2408.10738.pdf) - PhishAgent: A Robust Multimodal Agent for Phishing Webpage Detection

- [**MMRole**](https://arxiv.org/pdf/2408.04203.pdf) - MMRole: A Comprehensive Framework for Developing and Evaluating Multimodal Role-Playing Agents [Github](https://github.com/YanqiDai/MMRole) ![Star](https://img.shields.io/github/stars/YanqiDai/MMRole.svg?style=social&label=Star)
  
## Benchmark

- [**SmartPlay**](https://arxiv.org/pdf/2310.01557.pdf) - SmartPlay: A Benchmark for LLMs as Intelligent Agents [Github](https://github.com/microsoft/SmartPlay)
![Star](https://img.shields.io/github/stars/microsoft/SmartPlay.svg?style=social&label=Star)

- [**VisualWebArena**](https://arxiv.org/pdf/2401.13649.pdf) - VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks [Github](https://github.com/web-arena-x/visualwebarena)
![Star](https://img.shields.io/github/stars/web-arena-x/visualwebarena.svg?style=social&label=Star)

- [**Mind2Web**](https://arxiv.org/pdf/2306.06070) - MIND2WEB: Towards a Generalist Agent for the Web [Github](https://github.com/OSU-NLP-Group/Mind2Web)
![Star](https://img.shields.io/github/stars/OSU-NLP-Group/Mind2Web?style=social&label=Mind2Web)

- [**GAIA**](https://arxiv.org/pdf/2311.12983.pdf) - GAIA: a benchmark for General AI Assistants [Github](https://huggingface.co/gaia-benchmark)

- [**OmniACT**](https://arxiv.org/pdf/2402.17553.pdf) - OmniACT: A Dataset and Benchmark for Enabling Multimodal Generalist 

- [**DSBench**](https://arxiv.org/pdf/2409.07703.pdf) - DSBENCH: HOW FAR ARE DATA SCIENCE AGENTS TO BECOMING DATA SCIENCE EXPERTS? [Github](https://github.com/LiqiangJing/DSBench)
![Star](https://img.shields.io/github/stars/LiqiangJing/DSBench.svg?style=social&label=Star)

- [**GTA**](https://arxiv.org/pdf/2407.08713.pdf) - GTA: A Benchmark for General Tool Agents [Github](https://github.com/open-compass/GTA)
![Star](https://img.shields.io/github/stars/open-compass/GTA.svg?style=social&label=Star)

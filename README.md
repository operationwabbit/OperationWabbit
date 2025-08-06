# Operation Wabbit

**A Cognitive Humor Research Project on AI Miscomprehension in Single-Panel Cartoons**

## 🚀 Project Overview
Operation Wabbit is an original research initiative designed to uncover and benchmark the narrative and cognitive failure modes of large language models (LLMs) by testing their ability to interpret single-panel cartoons (SPCs). Led by cartoonist and humor theorist Thaddeus Camp, the project uses cartoon-based prompts to stress-test multimodal AI comprehension.

## 🎯 Core Discovery
On August 6, 2025, Operation Wabbit revealed a major breakthrough in understanding a persistent AI failure mode:

### 🧠 **Compressed Time in Single-Panel Cartoons**

LLMs fail to accurately decode the narrative structure of SPCs because these cartoons compress multiple temporal states into a single frame. This results in AI systems treating the cartoon as a static scene, rather than one rich in implied motion, change, or evolution.

### ⏳ The Time-State Model
Each SPC is revealed to encode:
- **-1 State:** Prior condition before the frame
- **0 State:** Moment depicted in the cartoon
- **+1 State:** Likely narrative consequence or future event

> "In *Support Baboon*, the man's startled gaze is his 0-state. But it's only meaningful when we infer his -1-state (peacefully reading, unaware of the baboon) and the probable +1-state (confrontation after violating the eye contact rule). Without this dynamic modeling, the cartoon appears merely absurd instead of narratively ironic and threatening."

This model allows us to measure whether an AI can:
- Infer **prior context** (what just happened)
- Decode **present indicators** (the visual clues in the frame)
- Anticipate **likely narrative evolution** (what happens next)

## 🧪 Methodology
- **Custom cartoons** authored by the researcher-cartoonist
- **Benchmarked responses** from GPT-4o, Claude, Gemini, Meta, Perplexity, etc.
- **Score grid** evaluating emotional inversion, narrative implication, irony, eye contact, and more
- **Cartoon Fluency Index (CFI)** with added scoring dimension for multi-step narrative cognition (MSNC)

## 📉 Key Findings
- Most AI models exhibit **Scene–Narrative Binding Failures**
- Irony and emotional displacement are frequently missed
- **0-state-only reading** leads to superficial interpretations
- Models cannot reliably animate hidden time dimensions in SPCs

## 📘 Citation and Attribution
This discovery is credited to:

> **Thaddeus C. Camp**  
> Cartoonist, Educator, and AI Researcher  
> Tucson, AZ  
> Operation Wabbit, August 2025

## 🛠️ Next Steps
- Public release of benchmark dataset
- GitHub-hosted documentation
- Proposal of the Wabbit Test as a narrative Turing benchmark
- AI alignment collaboration with research groups

---

For inquiries or collaboration proposals, please contact: [camptc@yahoo.com](mailto:camptc@yahoo.com)

> "Support Baboon was never just a cartoon. It was a riddle AI couldn’t answer—until we showed it what time looks like."

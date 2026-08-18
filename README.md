<p align="center">
  <a href="https://audio-editing-challenge.github.io/">
    <img src="https://raw.githubusercontent.com/Audio-Editing-Challenge/Audio-Editing-Challenge.github.io/main/img/audio-editing-challenge-logo-hd-4k.png" width="900" alt="MMAE — ICASSP 2027 Audio Editing Challenge">
  </a>
</p>

<h1 align="center">ICASSP 2027 Audio Editing Challenge</h1>

<p align="center">
  Advancing precise, general-purpose, instruction-based audio editing
</p>

<p align="center">
  <a href="https://audio-editing-challenge.github.io/"><img src="https://img.shields.io/badge/Challenge-Website-2563EB?style=flat-square" alt="Challenge website"></a>
  <a href="https://huggingface.co/datasets/BoJack/MMAE"><img src="https://img.shields.io/badge/%F0%9F%A4%97-MMAE%20Dataset-FFD21E?style=flat-square" alt="MMAE dataset on Hugging Face"></a>
  <a href="https://github.com/ddlBoJack/MMAE"><img src="https://img.shields.io/badge/MMAE-Code-181717?style=flat-square&logo=github" alt="MMAE code"></a>
  <a href="https://arxiv.org/abs/2606.07229"><img src="https://img.shields.io/badge/arXiv-2606.07229-B31B1B?style=flat-square&logo=arxiv" alt="MMAE paper on arXiv"></a>
</p>

## About the Challenge

The **Audio Editing Challenge at ICASSP 2027** asks how an intelligent audio editor can understand source audio, reason about natural-language instructions, perform the requested changes, and preserve everything that should remain untouched.

The challenge spans **speech, music, environmental sound, and their mixtures**. It targets practical edits ranging from a single local modification to complex workflows involving multiple instructions, audio inputs, reasoning steps, and rounds of interaction.

| Track | Goal |
| --- | --- |
| **Single Model Track** | Build one end-to-end model that directly transforms input audio according to an instruction. |
| **Agent Track** | Build an autonomous system that can plan, use locally deployed models or signal-processing tools, inspect intermediate results, and refine its output. |

## About MMAE

**MMAE (Massive Multitask Audio Editing)** is the benchmark and evaluation foundation of the challenge. It provides diverse instruction-based editing examples across audio modalities and task complexities, curated through human-agent collaboration with manual annotation, verification, and quality inspection.

MMAE evaluates an output through **atomic rubrics**: small, verifiable criteria that separate two complementary questions—whether the requested edit was completed and whether unrelated content remained consistent. This diagnostic view helps reveal *why* a system succeeds or fails, rather than reducing every example to a single opaque score.

<p align="center">
  <a href="https://github.com/ddlBoJack/MMAE">
    <img src="https://raw.githubusercontent.com/Audio-Editing-Challenge/Audio-Editing-Challenge.github.io/main/img/example.png" width="850" alt="Representative examples from the MMAE benchmark">
  </a>
</p>

## Evaluation

Submissions are evaluated with three complementary metrics:

- **Instruction Following Rate (IFR):** how accurately the requested edits are executed.
- **Consistency Rate (CR):** how well unrelated content and audio quality are preserved.
- **Exact Match Rate (EMR):** how often every instruction-following and consistency requirement is satisfied for an example.

Final rankings will be determined on an unreleased, organizer-held test set. The two tracks are evaluated and ranked independently.

Registration, submission instructions, and leaderboard information will be announced on the challenge website.

## Organizers

- Zhikang Niu (Shanghai Jiao Tong University; Shanghai Innovation Institute)
- Wenming Tu (Shanghai Jiao Tong University; Beijing Institute for General Artificial Intelligence)
- Ziyang Ma (Shanghai Jiao Tong University; Shanghai Innovation Institute; Nanyang Technological University)
- Ruiyang Xu (Shanghai Jiao Tong University)
- Hankun Wang (Shanghai Jiao Tong University)
- Bohan Li (Shanghai Jiao Tong University)
- Ruiqi Yan (Shanghai Jiao Tong University)
- Zilong Zheng (Beijing Institute for General Artificial Intelligence)
- Chunxiang Jin (Inclusion AI, Ant Group)
- Pengcheng Zhu (Ant Group)
- Hung-yi Lee (National Taiwan University)
- Jinyu Li (Microsoft Corporation)
- Carlos Busso (Carnegie Mellon University)
- Kai Yu (Shanghai Jiao Tong University)
- Eng Siong Chng (Nanyang Technological University)
- Xie Chen (Shanghai Jiao Tong University; Shanghai Innovation Institute)

<p align="center"><strong>Follow this profile and watch the challenge website for updates.</strong></p>

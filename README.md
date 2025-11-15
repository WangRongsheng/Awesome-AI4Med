# Awesome-AI4Med

![visitor](https://visitor-badge.laobi.icu/badge?page_id=https://github.com/WangRongsheng/Awesome-AI4Med)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/WangRongsheng/Awesome-AI4Med)

> [!NOTE]
> Introduction

> [!TIP]
> Quick Search Guide

Table of Contents:
- [1. Medical LLMs](#1-medical-llms)
- [2. Medical MLLMs](#2-medical-mllms)
- [3. Datasets](#3-datasets)
  - [3.1 Text](#31-text)
  - [3.2 Multimodal](#32-multimodal)
- [4. Benchmarks](#4-benchmarks)

![](https://camo.githubusercontent.com/2722992d519a722218f896d5f5231d49f337aaff4514e78bd59ac935334e916a/68747470733a2f2f692e696d6775722e636f6d2f77617856496d762e706e67)

## 1. Medical LLMs

> [!NOTE]
> 📣 We extract these trending models from a large corpus of research papers, we do not specifically collect the most recent models!

|**Model Name**|**Paper**|**Model Weight**|**Data**|**Code**|
|:-|:-:|:-:|:-:|:-:|
|`HuatuoGPT`|[[arXiv](https://arxiv.org/abs/2305.15075)]|[[HF (7B)](https://huggingface.co/FreedomIntelligence/HuatuoGPT-7B)]|[[HF](https://huggingface.co/datasets/FreedomIntelligence/HuatuoGPT-sft-data-v1)]|[[Github](https://github.com/FreedomIntelligence/HuatuoGPT)]|
|`Apollo`|[[arXiv](https://arxiv.org/abs/2403.03640)]|[[HF (7B)](https://huggingface.co/FreedomIntelligence/Apollo-7B)]|[[HF](https://huggingface.co/datasets/FreedomIntelligence/ApolloCorpus)]|[[Github](https://github.com/FreedomIntelligence/Apollo)]|
|`HuatuoGPT-II`|[[arXiv](https://arxiv.org/abs/2311.09774)]|[[HF (7B)](https://huggingface.co/FreedomIntelligence/HuatuoGPT2-7B)]|[[HF (PT)](https://huggingface.co/datasets/FreedomIntelligence/HuatuoGPT2-Pretraining-Instruction)][[HF (SFT)](https://huggingface.co/datasets/FreedomIntelligence/HuatuoGPT2-SFT-GPT4-140K)]|[[Github](https://github.com/FreedomIntelligence/HuatuoGPT-II)]|
|`MMedLM`|[[arXiv](https://arxiv.org/abs/2402.13963)]|[[HF (8B)](https://huggingface.co/Henrychur/MMed-Llama-3-8B)]|[[HF](https://huggingface.co/datasets/Henrychur/MMedC)]|[[Github](https://github.com/MAGIC-AI4Med/MMedLM)]|
|`PMC-LLaMA`|[[arXiv](https://arxiv.org/abs/2304.14454)]|[[HF (13B)](https://huggingface.co/axiong/PMC_LLaMA_13B)]|[[HF](https://github.com/allenai/s2orc)]|[[Github](https://github.com/chaoyi-wu/PMC-LLaMA)]|
|`Med42-v2`|[[arXiv](https://arxiv.org/abs/2408.06142)]|[[HF (8B)](https://huggingface.co/m42-health/Llama3-Med42-8B)]|-|[[Github](https://github.com/m42-health/med42)]|
|`OpenBioLLM`|-|[[HF (8B)](https://huggingface.co/aaditya/Llama3-OpenBioLLM-8B)]|-|-|
|`UltraMedical`|[[arXiv](https://arxiv.org/abs/2406.03949)]|[[HF (8B)](https://huggingface.co/TsinghuaC3I/Llama-3-8B-UltraMedical)]|[[HF](https://huggingface.co/datasets/TsinghuaC3I/UltraMedical)]|[[Github](https://github.com/TsinghuaC3I/UltraMedical)]|
|`HuatuoGPT-o1`|[[arXiv](https://arxiv.org/abs/2412.18925)]|[[HF (7B)](https://huggingface.co/FreedomIntelligence/HuatuoGPT-o1-7B)][[HF (8B)](https://huggingface.co/FreedomIntelligence/HuatuoGPT-o1-8B)][[HF (70B)](https://huggingface.co/FreedomIntelligence/HuatuoGPT-o1-70B)]|[[HF](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT)]|[[Github](https://github.com/FreedomIntelligence/HuatuoGPT-o1)]|
|`BioMistral`|[[arXiv](https://arxiv.org/abs/2402.10373)]|[[HF (7B)](https://huggingface.co/BioMistral/BioMistral-7B)]|-|[[Github](https://github.com/BioMistral/BioMistral)]|
|`MediTron`|[[arXiv](https://arxiv.org/abs/2311.16079)]|[[HF (7B)](https://huggingface.co/epfl-llm/meditron-7b)]|[[HF](https://huggingface.co/datasets/togethercomputer/RedPajama-Data-1T)]|[[Github](https://github.com/epfLLM/meditron)]|
|`Baichuan-M2`|[[arXiv](https://arxiv.org/abs/2509.02208)]|[[HF (32B)](https://huggingface.co/baichuan-inc/Baichuan-M2-32B)]|-|[[Github](https://github.com/baichuan-inc/Baichuan-M2-32B)]|
|`Baichuan-M1`|[[arXiv](https://arxiv.org/abs/2502.12671)]|[[HF (14B)](https://huggingface.co/baichuan-inc/Baichuan-M1-14B-Instruct)]|-|[[Github](https://github.com/baichuan-inc/Baichuan-M1-14B)]|
|`MedAlpaca`|[[arXiv](https://arxiv.org/abs/2304.08247)]|[[HF (7B)](https://huggingface.co/medalpaca/medalpaca-7b)]|[[Github](https://github.com/kbressem/medAlpaca/blob/main/DATA_DESCRIPTION.md)]|[[Github](https://github.com/kbressem/medAlpaca)]|
|`ShizhenGPT`|[[arXiv](https://arxiv.org/abs/2508.14706)]|[[HF (7B)](https://huggingface.co/FreedomIntelligence/ShizhenGPT-7B-Omni)]|[[HF (PT)](https://huggingface.co/datasets/FreedomIntelligence/TCM-Pretrain-Data-ShizhenGPT)][[HF (SFT)](https://huggingface.co/datasets/FreedomIntelligence/TCM-Instruction-Tuning-ShizhenGPT)]|[[Github](https://github.com/FreedomIntelligence/ShizhenGPT)]|




<div align="right">
  <b><a href="#contents">↥ back to top</a></b>
</div>


## 2. Medical MLLMs

|**Model Name**|**Paper**|**Model Weight**|**Data**|**Code**|
|:-|:-:|:-:|:-:|:-:|
|`HuatuoGPT-Vision`|[[arXiv](https://arxiv.org/abs/2406.19280)]|[[HF (7B)](https://huggingface.co/FreedomIntelligence/HuatuoGPT-Vision-7B)][[HF 34B](https://huggingface.co/FreedomIntelligence/HuatuoGPT-Vision-34B)]|[[HF](https://huggingface.co/datasets/FreedomIntelligence/HuatuoGPT-sft-data-v1)]|[[Github](https://github.com/FreedomIntelligence/HuatuoGPT-Vision)]|
|`Lingshu`|[[arXiv](https://arxiv.org/abs/2506.07044)]|[[HF (7B)](https://huggingface.co/lingshu-medical-mllm/Lingshu-7B)][[HF 32B](https://huggingface.co/lingshu-medical-mllm/Lingshu-32B)]|-|-|
|`LLaVA-Med`|[[arXiv](https://arxiv.org/abs/2306.00890)]|[[HF (7B)](https://huggingface.co/microsoft/llava-med-v1.5-mistral-7b)]|[[Github](https://github.com/microsoft/LLaVA-Med/tree/main/data)]|[[Github](https://github.com/microsoft/LLaVA-Med)]|
|`BiMediX`|[[arXiv](https://arxiv.org/abs/2412.07769v2)]|[[HF (8B)](https://huggingface.co/MBZUAI/BiMediX2-8B)]|[[Github](https://github.com/microsoft/LLaVA-Med/tree/main/data)]|[[Github](https://github.com/mbzuai-oryx/BiMediX)]|
|`Hulu-Med`|[[arXiv](https://arxiv.org/abs/2510.08668)]|[[HF (7B)](https://huggingface.co/ZJU-AI4H/Hulu-Med-7B)]||[[Github](https://github.com/ZJUI-AI4H/Hulu-Med)]|
|`HealthGPT`|[[arXiv](https://arxiv.org/abs/2412.07769v2)]|[[HF (3.8B)](https://huggingface.co/lintw/HealthGPT-M3)]|[[HF](https://huggingface.co/datasets/lintw/VL-Health)]|[[Github](https://github.com/DCDmllm/HealthGPT)]|
|`MedGemma`|[[arXiv](https://arxiv.org/abs/2507.05201)]|[[HF (4B)](https://huggingface.co/google/medgemma-4b-it)]|-|[[Github](https://github.com/Google-Health/medgemma)]|
|`Med-R1`|[[arXiv](https://arxiv.org/abs/2503.13939)]|[[HF (2B)](https://huggingface.co/yuxianglai117/Med-R1)]|-|[[Github](https://github.com/Yuxiang-Lai117/Med-R1)]|
|`BiomedGPT`|[[arXiv](https://arxiv.org/abs/2305.17100)]|[[HF (7B)](https://huggingface.co/PharMolix/BioMedGPT-LM-7B)]|[[Github](https://github.com/taokz/BiomedGPT/blob/main/datasets.md)]|[[Github](https://github.com/taokz/BiomedGPT)]|
|`MedVLM-R1`|[[arXiv](https://arxiv.org/abs/2502.19634)]|[[HF (2B)](https://huggingface.co/JZPeterPan/MedVLM-R1)]|-|[[Github](https://github.com/JZPeterPan/MedVLM-R1)]|
|`BiMediX2`|[[arXiv](https://arxiv.org/abs/2412.07769v2)]|[[HF (8B)](https://huggingface.co/MBZUAI/BiMediX2-8B)]|[[Github](https://github.com/mbzuai-oryx/BiMediX2/blob/main/scripts/README.md)]|[[Github](https://github.com/mbzuai-oryx/BiMediX2)]|




<div align="right">
  <b><a href="#contents">↥ back to top</a></b>
</div>

## 3. Datasets

### 3.1 Text

|**Data Name**|**Paper**|**Link**|**Quantity**|
|:-|:-:|:-:|:-:|
|`Huatuo-26M`|[[arXiv](https://arxiv.org/abs/2305.01526)]|[[Github](https://github.com/FreedomIntelligence/Huatuo-26M)]|26,000,000|
|`medical-o1-reasoning-SFT`|[[arXiv](https://arxiv.org/pdf/2412.18925)]|[[HF](https://huggingface.co/datasets/FreedomIntelligence/medical-o1-reasoning-SFT)]|25,000|
|`ReasonMed`|[[arXiv](https://arxiv.org/abs/2506.09513)]|[[HF](https://huggingface.co/datasets/YuSun-AI/ReasonMed)]|370,000|

<div align="right">
  <b><a href="#contents">↥ back to top</a></b>
</div>

### 3.2 Multimodal

|**Data Name**|**Paper**|**Link**|**Quantity**|
|:-|:-:|:-:|:-:|
|`PubMedVision`|[[arXiv](https://arxiv.org/abs/2406.19280)]|[[HF](https://huggingface.co/datasets/FreedomIntelligence/PubMedVision)]|1,294,062|
|`Med-MAT`|[[arXiv](https://arxiv.org/abs/2412.20070)]|[[HF](https://huggingface.co/datasets/FreedomIntelligence/Med-MAT)]|2,360,000|
|`MedTrinity`|[[arXiv](https://arxiv.org/abs/2408.02900)]|[[HF](https://huggingface.co/datasets/UCSC-VLAA/MedTrinity-25M)]|25,000,000|
|`OmniMedVQA`|[[arXiv](https://arxiv.org/pdf/2408.03361)]|[[OpenXLab](https://openxlab.org.cn/datasets/GMAI/OmniMedVQA)]|118,010|
|`BioVFM`|[[arXiv](https://www.arxiv.org/abs/2505.09329)]|[[Github](https://github.com/JiarunLiu/BioVFM)]|21,000,000|

<div align="right">
  <b><a href="#contents">↥ back to top</a></b>
</div>

## 4. Benchmarks

|**Evaluation Framework**|**Code**|**Supported Benchmark**|
|:-|:-:|:-:|
|`MedEvalKit`|[[Github](https://github.com/alibaba-damo-academy/MedEvalKit)]|**（1）Multimodal：**：`MMMU-Medical-test`, `MMMU-Medical-val`, `PMC_VQA`, `OmniMedVQA`, `IU XRAY`, `MedXpertQA-Multimodal`, `CheXpert Plus`, `MIMIC-CXR`, `VQA-RAD`, `SLAKE`, `PATH-VQA`, `MedFrameQA`；**（2）Text-only：**：`MedQA-USMLE`, `MedMCQA`, `PubMedQA`, `Medbullets-op4`, `Medbullets-op5`, `MedXpertQA-Text`, `SuperGPQA`, `HealthBench`, `CMB`, `CMExam`, `CMMLU`, `MedQA-MCMLE`；|
|`MedBench`|[[Website](https://medbench.opencompass.org.cn/home)]|**Text-only：**：`Med-Exam`, `MedHC`, `MedMC`, `MedSpeQA`, `MedHG`, `MedDG`, `MedLitQA`, `IMCS-V2-MRG`, `DBMHG`, `CMB-Clin-extended`, `DDx-basic`, `DDx-advanced`, `MedTreat`, `CMeEE`, `CMeIE`, `CHIP-CDEE`, `CHIP-CDN`, `CHIP-CTC`, `SMDoc`, `MedSafety`, `DrugCA`, `CriID`|

<div align="right">
  <b><a href="#contents">↥ back to top</a></b>
</div>

[![Stargazers over time](https://starchart.cc/WangRongsheng/Awesome-AI4Med.svg)](https://starchart.cc/WangRongsheng/Awesome-AI4Med)

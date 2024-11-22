# How Effective Are They? Exploring Large Language Model Based Fuzz Driver Generation

**Authors**: Zhang, Cen and Zheng, Yaowen and Bai, Mingqiang and Li, Yeting and Ma, Wei and Xie, Xiaofei and Li, Yuekang and Sun, Limin and Liu, Yang

**Abstract**:

Fuzz drivers are essential for library API fuzzing. However, automatically generating fuzz drivers is a complex task, as it demands the creation of high-quality, correct, and robust API usage code. An LLM-based (Large Language Model) approach for generating fuzz drivers is a promising area of research. Unlike traditional program analysis-based generators, this text-based approach is more generalized and capable of harnessing a variety of API usage information, resulting in code that is friendly for human readers. However, there is still a lack of understanding regarding the fundamental issues on this direction, such as its effectiveness and potential challenges.  To bridge this gap, we conducted the first in-depth study targeting the important issues of using LLMs to generate effective fuzz drivers. Our study features a curated dataset with 86 fuzz driver generation questions from 30 widely-used C projects. Six prompting strategies are designed and tested across five state-of-the-art LLMs with five different temperature settings. In total, our study evaluated 736,430 generated fuzz drivers, with 0.85 billion token costs ($8,000+ charged tokens). Additionally, we compared the LLM-generated drivers against those utilized in industry, conducting extensive fuzzing experiments (3.75 CPU-year). Our study uncovered that:  1) While LLM-based fuzz driver generation is a promising direction, it still encounters several obstacles towards practical applications; 2) LLMs face difficulties in generating effective fuzz drivers for APIs with intricate specifics. Three featured design choices of prompt strategies can be beneficial: issuing repeat queries, querying with examples, and employing an iterative querying process; 3) While LLM-generated drivers can yield fuzzing outcomes that are on par with those used in the industry, there are substantial opportunities for enhancement, such as extending contained API usage, or integrating semantic oracles to facilitate logical bug detection.  Our insights have been implemented to improve the OSS-Fuzz-Gen project, facilitating practical fuzz driver generation in industry.

**Link**: [Read Paper](https://doi.org/10.1145/3650212.3680355)

**Labels**: [program testing](../../labels/program_testing.md), [fuzzing](../../labels/fuzzing.md)
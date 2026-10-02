<div align="center">

<img src="assets/hero.svg" alt="Sushant Lokhande, software engineer" width="900" />
<br/><br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-see%20the%20work-0071e3?style=for-the-badge&logo=safari&logoColor=white)](https://sushantlokhande.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sushantlokhande14)
[![Email](https://img.shields.io/badge/Email-say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&fs=1&to=lokhandesushant094@gmail.com)

</div>


## About me

I'm fascinated by the gap between a great idea and a system that actually holds up at scale. That gap is where I like to work.

I recently finished my MS in Computer Science at San José State University, where my research on image-based malware classification became a first-author paper, now on arXiv and appearing as a chapter in a Springer book on AI for cyber defense. Before grad school I was a software engineer on an EdTech platform serving 70K+ users, chasing down latency and shipping features thousands of learners used every day.

Outside of work I take systems apart to understand them. Lately that meant writing a vector search engine from scratch in C++, then building an LLM gateway and a movie recommender on top of it. More recently: a parallel RTL compiler and a distributed build engine, both in C++. I ship something small almost every day; building is how I learn.

Open to full-time Software, ML, and AI Engineering roles across the US.

## Publication

**[Image-Based Techniques and Ensemble Soft Voting for Malware Classification](https://arxiv.org/abs/2609.26281)**
<br/>
<sub>S. Lokhande, F. Di Troia, M. Jurecek, M. Stamp &middot; arXiv:2609.26281 [cs.CR] &middot; to appear as a chapter in *Artificial Intelligence for Cyber Defense in Emerging Threats* (Springer, 2027)</sub>

Malware binaries rendered as images, then classified by three complementary feature tracks: handcrafted HOG and Haralick descriptors, frozen embeddings from VGG16, ResNet50 and ViT-B/16, and a custom CNN. A soft voting ensemble of fifteen selected voters reaches 80.2% accuracy across 17 malware families, a statistically significant 2.4 point gain over the best individual model.

## Tech stack

<div align="center">

<a href="https://sushantlokhande.me"><img width="830" src="https://skillicons.dev/icons?i=py,cpp,c,ts,js,java,react,nextjs,fastapi,flask,django,nodejs,pytorch,postgres,mongodb,redis,graphql,docker,kubernetes,aws,git,grafana,prometheus,linux&theme=dark&perline=12" alt="Tech stack" /></a>

</div>

## Things I've built

| Project | The short version | Code |
| :-- | :-- | :-- |
| [Proxima](https://sushantlokhande.me/projects/proxima/) | A C++ vector search engine that answers queries 1.8× faster than hnswlib and 2.5× faster than FAISS at 0.999 recall | [repo](https://github.com/sushantlokhande14/proxima) |
| [Relay](https://sushantlokhande.me/projects/relay/) | An LLM gateway that remembers: 78% of requests served from a semantic cache, median latency 759 ms to 44 ms | [repo](https://github.com/sushantlokhande14/Relay) |
| [Reel Rank](https://sushantlokhande.me/projects/reelrank/) | A two-stage hybrid movie recommender with retrieval running on Proxima, answering free-text requests like "a slow-burn sci-fi like Arrival but funnier" | [repo](https://github.com/sushantlokhande14/reelrank) |
| [Autograde AI](https://sushantlokhande.me/projects/autograde-ai/) | A local-first multi-agent grading platform: six grader agents under Temporal and Kafka, confidence-gated human review | [repo](https://github.com/sushantlokhande14/autograde-ai) |
| [LogicForge](https://sushantlokhande.me/projects/logicforge/) | A parallel RTL compiler in C++: SystemVerilog in, an optimized and equivalence-checked gate netlist out, with the optimization stage 3.0 to 3.5× faster on 16 threads | [repo](https://github.com/sushantlokhande14/logicforge) |
| [DistCompile](https://sushantlokhande.me/projects/distcompile/) | A distributed C/C++ build engine on gRPC and PostgreSQL with content-addressed caching: 84% fewer compiler runs than make over a scripted edit workload | [repo](https://github.com/sushantlokhande14/distcompile) |
| [rtlgen](https://sushantlokhande.me/projects/rtlgen/) | A C++ generator from JSON descriptions to synthesizable Verilog, with graph checks first: 1,200 configurations all synthesize, and invalid output from 1,000 broken descriptions drops from 766 files to 0 | [repo](https://github.com/sushantlokhande14/rtlgen) |
| [clockguard](https://sushantlokhande.me/projects/clockguard/) | Clock, reset and CDC checks for Verilog, with a targeted testbench and waveform per violation: 570 of 570 injected bugs found, 0 false alarms, 89% reproduced in simulation | [repo](https://github.com/sushantlokhande14/clockguard) |
| [Malware Classification](https://sushantlokhande.me/projects/malware-classification/) | My thesis: malware binaries rendered as images, a three-track ensemble that agrees 94% of the time across 17 families | [repo](https://github.com/sushantlokhande14/Soft_Voting_Ensembled_Malware_Images_Classification) |

## Open source Contributions

<div align="center">

<img src="assets/open-source.svg" alt="Open source contributions: NVIDIA, Google, fission, corsair, AutoGPT" width="900" />

</div>

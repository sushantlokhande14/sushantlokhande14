<div align="center">

<img src="assets/hero.svg" alt="Sushant Lokhande â€” software engineer" width="900" />
<br/><br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-see%20the%20work-0071e3?style=for-the-badge&logo=safari&logoColor=white)](https://sushantlokhande.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sushantlokhande14)
[![Email](https://img.shields.io/badge/Email-say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](https://mail.google.com/mail/?view=cm&fs=1&to=lokhandesushant094@gmail.com)

</div>


## About me

I'm fascinated by the gap between a great idea and a system that actually holds up at scale. That gap is where I like to work.

I recently finished my MS in Computer Science at San JosÃ© State University, where my research on image-based malware classification became a co-authored paper, now under review. Before grad school I was a software engineer on an EdTech platform serving 70K+ users, chasing down latency and shipping features thousands of learners used every day.

Outside of work I take systems apart to understand them. Lately that meant writing a vector search engine from scratch in C++, then building an LLM gateway and a movie recommender on top of it. I ship something small almost every day; building is how I learn.

Open to full-time Software, ML, and AI Engineering roles across the US.

## Tech stack

<div align="center">

<a href="https://sushantlokhande.me"><img width="830" src="https://skillicons.dev/icons?i=py,cpp,c,ts,js,java,react,nextjs,fastapi,flask,django,nodejs,pytorch,postgres,mongodb,redis,graphql,docker,kubernetes,aws,git,grafana,prometheus,linux&theme=dark&perline=12" alt="Tech stack" /></a>

</div>

## Things I've built

| Project | The short version | Code |
| :-- | :-- | :-- |
| [Proxima](https://sushantlokhande.me/projects/proxima/) | A C++ vector search engine that answers queries 1.8Ã— faster than hnswlib and 2.5Ã— faster than FAISS at 0.999 recall | [repo](https://github.com/sushantlokhande14/proxima) |
| [Relay](https://sushantlokhande.me/projects/relay/) | An LLM gateway that remembers: 78% of requests served from a semantic cache, median latency 759 ms to 44 ms | [repo](https://github.com/sushantlokhande14/Relay) |
| [Reel Rank](https://sushantlokhande.me/projects/reelrank/) | A two-stage hybrid movie recommender with retrieval running on Proxima, answering free-text requests like "a slow-burn sci-fi like Arrival but funnier" | [repo](https://github.com/sushantlokhande14/reelrank) |
| [Autograde AI](https://sushantlokhande.me/projects/autograde-ai/) | A local-first multi-agent grading platform: six grader agents under Temporal and Kafka, confidence-gated human review | [repo](https://github.com/sushantlokhande14/autograde-ai) |
| [Malware Classification](https://sushantlokhande.me/projects/malware-classification/) | My thesis: malware binaries rendered as images, a three-track ensemble that agrees 94% of the time across 17 families | [repo](https://github.com/sushantlokhande14/Soft_Voting_Ensembled_Malware_Images_Classification) |

## Open source

Ten patches merged into projects I don't own, with three more in review.

| Project | What I changed | PRs |
| :-- | :-- | :-- |
| [**NVIDIA/garak**](https://github.com/NVIDIA/garak) <br/> <sub>LLM vulnerability scanner</sub> | Merging scan reports stamped the run id over every attempt's own UUID, collapsing nine distinct results into a single identity and leaving every cross-reference to them dangling | [#2158](https://github.com/NVIDIA/garak/pull/2158) <br/> <sub>in review</sub> |
| [**google/osv-scalibr**](https://github.com/google/osv-scalibr) <br/> <sub>the scanning engine behind osv-scanner</sub> | The ITIN detector's pattern matched space-separated numbers, but its validator never stripped the spaces, so every one of them was silently discarded | [#2405](https://github.com/google/osv-scalibr/pull/2405) <br/> <sub>in review</sub> |
| [**fission/fission**](https://github.com/fission/fission) <br/> <sub>serverless on Kubernetes</sub> | Stopped a double enumeration of cluster-wide packages, and taught support dumps to capture KEDA objects and pod events | [#3668](https://github.com/fission/fission/pull/3668) [#3670](https://github.com/fission/fission/pull/3670) [#3671](https://github.com/fission/fission/pull/3671) <br/> <sub>merged</sub> |
| [**corsairdev/corsair**](https://github.com/corsairdev/corsair) <br/> <sub>integration platform</sub> | Swept a fail-open family across seven webhook integrations, where a missing secret or an empty payload was accepted as authentic | [#608](https://github.com/corsairdev/corsair/pull/608) [#609](https://github.com/corsairdev/corsair/pull/609) [#610](https://github.com/corsairdev/corsair/pull/610) [#611](https://github.com/corsairdev/corsair/pull/611) [#626](https://github.com/corsairdev/corsair/pull/626) [#627](https://github.com/corsairdev/corsair/pull/627) [#629](https://github.com/corsairdev/corsair/pull/629) <br/> <sub>merged</sub> |
| [**Significant-Gravitas/AutoGPT**](https://github.com/Significant-Gravitas/AutoGPT) <br/> <sub>agent platform</sub> | Raised a stale max-output-token ceiling in the backend model catalog | [#14139](https://github.com/Significant-Gravitas/AutoGPT/pull/14139) <br/> <sub>in review</sub> |

<div align="center">

<img src="assets/oss-trophies.svg" alt="Open source contributions: NVIDIA, Google, fission, corsair, AutoGPT" width="900" />

</div>

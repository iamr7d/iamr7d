<img align="right" width="300" src="assets/joy-viewer.jpg" alt="A film frame passing through JOY's stages: frame, foveated percept, attention map, chosen fixation">

I work on **models of how people watch**: systems that choose where to look, perceive the consequences, and are judged against real human behaviour rather than benchmark accuracy alone. I also build products.

Currently an MRes researcher at the [UAL Creative Computing Institute](https://www.arts.ac.uk/creative-computing-institute) with [Tim J. Smith](https://researchers.arts.ac.uk/2916-tim-smith). Before that: MTech in Computer Science & Engineering (AI), AI R&D at Digital University Kerala, and a co-founder of an AI interview platform. I also make films.

London · [rahulrajpv.vercel.app](https://rahulrajpv.vercel.app) · [LinkedIn](https://www.linkedin.com/in/rahulrajpvr7d/) · rahulrajpv.ai@gmail.com

<br clear="right"/>

### Building

**[pitute](https://pitute.org)**: the network for researchers<br>
A place to find every scholarship, PhD, postdoc and research opportunity in the world, with identity drawn from academic infrastructure (ORCID, institutional email, the publication record). Live since October 2026.
- 90+ importers read funders, ministries and universities' own recruitment systems (Workday, Oracle, PageUp, Stonefish and others) across about 100 countries.
- Each member is matched by a hybrid scorer (dense embeddings, catalogue topics, field words). Eligibility is read as quoted facts from the official page and checked by deterministic rules; a fact whose quote is not on the page is dropped.
- One Next.js app with 88 Prisma models, 14 scheduled jobs and 3,505 unit tests.

### Research

**[JOY: an Artificial Viewer](https://joyaiviewer.vercel.app)** (MRes, UAL)<br>
A closed-loop observer for film. It sees only a foveated percept, arbitrates between audiovisual salience and a vision-language model's reading of the scene, selects its own fixations with human-like timing, and perceives the world from wherever that choice left it. The main finding is a dissociation: a state-dependent policy that improves prediction of human gaze in 5 of 5 folds wins on only 3 of 8 clips once it controls the loop. Prediction and observation are different problems.

The system includes:
- a gaze-contingent scanpath loop with inhibition of return and CRISP fixation durations
- a LoRA-tuned Qwen2.5-VL that reads fixations out as coordinate tokens
- persistent character identity and speaker grounding (BCubed F 0.972 / 0.985)
- an engagement pipeline linking salience, event segmentation and goal inference
- models of affective and pupil response

[Project page](https://joyaiviewer.vercel.app) · [site source](https://github.com/iamr7d/enjoy) · research code available on request

**JOY Companion**<br>
A real-time, fully on-device companion that perceives through a live camera (face identity, expression, objects, gaze), keeps a memory of the relationship, and talks through a local Qwen2.5 reasoning loop. Nothing leaves the machine.

**[MSPI-Tiny](https://github.com/iamr7d/mspi-tiny)**<br>
Distils an offline audiovisual-attention model into interpretable decision-tree students for a live camera assistant, targeting under 100 ms per frame on edge hardware.

**[DinoSynthesis](https://github.com/iamr7d/DinoSynthesis)**<br>
A phylogenetic VAE-GAN (PyTorch) that interpolates between bird and reptile vocal latents to speculate on dinosaur sounds, with its own data pipeline for collection, SNR filtering and class rebalancing.

**[FILMDA Player](https://github.com/iamr7d/filmda.play)**<br>
Real-time audience measurement from blinks and facial emotion. Built for my MTech thesis on AI-driven film analytics.

### Writing

- Rahulraj P. V., Sanil J., Anoop V. S., Asharaf S. *Monetize the Dual: A Data Analytic Approach for Native Language and Prequel Movie Popularity Analysis.* ICDAI 2023, Springer. [doi](https://doi.org/10.1007/978-981-99-3878-0_16)
- *Narrative DNA: DNA-sequence inspired analysis of narrative dynamics in movie scripts.* Under review, 2026.
- *JOY: Building an Artificial Viewer for Sequential Visual Attention in Film.* MRes thesis, UAL, 2026.

<sub>Smaller experiments: [GRAD0](https://github.com/iamr7d/GRAD0) (LLM news director) · [LumiMeet](https://github.com/iamr7d/lumi_meet) · [wind.ai](https://github.com/iamr7d/wind.ai) · [story-space](https://github.com/iamr7d/story-space) · [film_space_vr-](https://github.com/iamr7d/film_space_vr-)</sub>

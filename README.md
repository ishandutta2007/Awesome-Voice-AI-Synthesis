# Awesome-Voice-AI-Synthesis

### Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Voice-AI-Synthesis

## Top Voice AI & Synthesis Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Text-to-Speech, Voice Cloning, Neural Dubbing, Speech Synthesis APIs & Conversational Voice*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Voice AI & Synthesis**. These systems turn text into natural speech, clone voices from short samples, and power dubbing, agents, and accessibility experiences.



**Examples** include ElevenLabs, Murf AI, PlayHT, Resemble AI, Speechify, Descript, LOVO AI, WellSaid Labs, Synthesia, Replica Studios, and open platforms for voice cloning and dubbing.



**Open-source emphasis**: Neural TTS and cloning have strong open models. **Coqui TTS (Idiap fork)**, **Piper**, **OpenVoice**, **Chatterbox**, **Kokoro**, and related runtimes enable local and self-hosted synthesis. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ElevenLabs, PlayHT, Murf, Resemble AI, WellSaid Labs, LOVO](https://elevenlabs.io/)**  

  Leading neural voice APIs—high-quality TTS, cloning, and multilingual synthesis for products and media.



- **[Descript, Speechify, Replica Studios](https://www.descript.com/)**  

  Creator and accessibility-oriented voice tools—overdub, audiobooks, and character voices.



- **[Synthesia and avatar-linked voice platforms](https://www.synthesia.io/)**  

  Video avatar products with integrated synthetic speech for training and marketing content.



- **[Other commercial voice AI platforms](https://www.resemble.ai/)**  

  Additional enterprise TTS, real-time voice conversion, and dubbing services.



## Open-Source GitHub Projects



### TTS Engines & Voice Cloning



- **[Coqui TTS (Idiap / coqui-tts fork)](https://github.com/idiap/coqui-ai-TTS)**  

  Broad open TTS toolkit—multiple architectures including XTTS-style cloning from short reference audio; actively maintained fork of the Coqui codebase.



- **[Piper](https://github.com/OHF-Voice/piper1-gpl)**  

  Fast local neural TTS from the Open Home Foundation—ONNX voices, low resource use, popular in Home Assistant and offline apps.



- **[OpenVoice](https://github.com/myshell-ai/OpenVoice)**  

  Open voice cloning toolkit—instant cloning and flexible tone control with research and community adoption.



- **[Chatterbox (Resemble AI)](https://github.com/resemble-ai/chatterbox)**  

  Open TTS/cloning model family with permissive licensing for many use cases (check output watermarking terms).



- **[Kokoro / other Apache-licensed TTS models](https://github.com/search?q=kokoro+tts)**  

  Efficient open TTS models scoring competitively in listening tests with commercial-friendly licenses.



- **[Bark](https://github.com/suno-ai/bark)**  

  Open generative audio model—expressive speech and non-speech sounds from text prompts.



- **[StyleTTS 2 and community neural TTS](https://github.com/yl4579/StyleTTS2)**  

  High-quality open TTS research models used as the basis for many fine-tunes.



- **[Mimic 3 / Mycroft-related TTS](https://github.com/MycroftAI/mimic3)**  

  Open offline TTS options oriented toward privacy-sensitive and edge deployments.



### Tooling, Runtimes & Pipelines



- **[espeak-ng](https://github.com/espeak-ng/espeak-ng)**  

  Classic open formant/speech synthesizer—still used for phonemization and lightweight fallback voices.



- **[SpeechBrain](https://github.com/speechbrain/speechbrain)**  

  Open PyTorch toolkit covering TTS, speech conversion, and related speech AI recipes.



- **[TTS.cpp / ONNX runtime packaging](https://github.com/search?q=tts+onnx+runtime)**  

  Community ports for running open voices efficiently on CPU and edge devices.



- **[Voice conversion (FreeVC, kNN-VC, etc.)](https://github.com/search?q=voice+conversion+open+source)**  

  Open conversion models that transform source speech toward a target speaker identity.



### Additional Strong Open-Source Options



- **Local fast TTS**: Piper.

- **Cloning from short samples**: Coqui XTTS-class models or OpenVoice.

- **Expressive / experimental**: Bark.

- **Product-friendly licenses**: Prefer Apache/MIT model weights; always read each model card.

- **Composable stacks**: Text → open TTS → optional VC → audio post-process; or SaaS API for highest quality with less ops.

- Commercial APIs still lead for ultra-natural multilingual voices, SLA-backed latency, and turnkey studio workflows.



**Frameworks for building custom systems**:  

**Piper** for efficient offline speech; **Coqui TTS** / **OpenVoice** for cloning research and apps; **SpeechBrain** for training pipelines.  

Respect model licenses—some “open” weights restrict commercial use.  

Fully open voice synthesis is viable for many products; premium naturalness often still uses commercial APIs.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Voice cloning can be misused for fraud and impersonation. Only clone voices you have rights and consent to use. Disclose synthetic speech where required by law or platform policy. Watermarking and abuse monitoring are strongly recommended.

- Open-source models offer privacy and control but vary widely in license terms. Commercial platforms shift quality and compliance tooling to the vendor. Neither replaces ethical use policies and legal review.



---



**Made for voice product builders, accessibility teams, and media engineers.**  

Let's expand open speech synthesis while recognizing the quality and scale that leading commercial voice AI platforms deliver.

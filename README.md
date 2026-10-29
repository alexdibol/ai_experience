# AI and Experience in Financial Practice

### Memory, knowledge, continuous learning, and institutional judgment

**Alejandro Reynoso | AI for Financial Practitioners**

How can a financial institution use AI to learn from experience while remaining resilient, safe, productive, and innovative?

This repository brings together two complementary monographs, four Google Colab laboratories, and a podcast to explore that question. It connects familiar ideas—retrieval-augmented generation (RAG), GraphRAG, knowledge graphs, second brains, and fine-tuning—with the more demanding challenge of building systems that evaluate outcomes, revise beliefs, and improve their use of accumulated experience over time.

The emphasis is on financial practice: understanding how these concepts fit together, what each contributes, and how institutions can govern their use. The materials are designed for financial practitioners, institutional leaders, and graduate students seeking an accessible bridge between AI architecture and professional judgment.

> Institutional AI becomes more experienced when it can connect decisions to outcomes, validate reusable lessons, and revise their influence under explicit governance.

## Start here

| Resource | Purpose | Access |
| --- | --- | --- |
| **Conceptual monograph: From Intelligence to Experience** | The big picture: intelligence, knowledge, experience, and the architecture of institutional AI. | [Read the PDF](https://drive.google.com/file/d/1Ynq7GgqiB9401oAT3bf7U6kxWRL3OFCP/view?usp=drivesdk) |
| **Implementation monograph: Memory, Context, and Judgment in Financial Artificial Intelligence** | A guided explanation of four laboratories, from persistent evidence to belief revision. | [Read the PDF](https://drive.google.com/file/d/10qYlPH7bblha7lOsfVg_5IFWRLKiTk8Z/view?usp=drivesdk) |
| **Four interactive laboratories** | Minimalistic experiments that make memory, investigation, and adaptation inspectable. | [Go to the notebook links below](#four-google-colab-laboratories) |
| **Podcast: From Intelligence to Experience** | An audio companion to the topic. | [Listen to the podcast — M4A](https://drive.google.com/file/d/1Jd7DDCIVvMpy8-jXjwroPe6MSgiEt0RJ/view?usp=drivesdk) |
| **Monograph collection** | Shared Google Drive folder containing the two monographs. | [Open the collection](https://drive.google.com/drive/folders/1eQCwZL5RSolJ-8Aks9RNdejIUOwRaZXM?usp=sharing) |

## What do we mean by experience?

The conceptual framework distinguishes three closely related capabilities:

- **Intelligence:** the capacity to infer, compare, reason, plan, and propose actions.
- **Knowledge:** the facts, relationships, constraints, and validated information on which reasoning depends.
- **Experience:** records of situated decisions and observed consequences, assessed for what they can responsibly teach a future decision maker.

An experience record should connect the situation, available evidence, action, outcome, assessment, validity conditions, and provenance. A convincing recollection is not enough: its relevance and reliability must be evaluated.

For a financial institution, this distinction matters. A credit decision may appear reasonable today but reveal weaknesses months later. An investigative procedure may save time in one setting and overlook essential evidence in another. A market rule may work during one regime and become misleading after conditions change. Experience becomes useful only when the institution can recognize these differences and act on them.

## How the concepts fit together

These approaches address different parts of an institutional learning system. They can complement one another; they do not form a mandatory sequence of replacements.

| Approach | Contribution | What the experience framework adds |
| --- | --- | --- |
| **RAG** | Retrieves external evidence for a model to use in its response. | Connects retrieved material to decisions, subsequent outcomes, and validated lessons. |
| **Knowledge graphs and GraphRAG** | Organize and retrieve relationships among entities, events, and evidence. | Records which investigative paths were useful, under which conditions, and at what cost. |
| **Second brains** | Preserve and organize information for later use. | Introduces explicit feedback, lesson review, and controlled revision of what influences decisions. |
| **Fine-tuning** | Adapts model behavior by changing its parameters. | Provides an additional learning pathway through external, inspectable memory; weight updates are not required for every new lesson. |
| **Continual learning** | Addresses adaptation as new information and conditions arrive. | Makes outcome evaluation, temporal validity, contradiction, and governance central to institutional adaptation. |

The dynamic component is essential. The objective is to improve both the institution's body of knowledge and the procedures used to reason with it. That improvement must be measured rather than assumed. Updating an external memory store is also distinct from training a model's weights continuously.

A practical experience cycle is:

1. Record the situation, evidence, and decision.
2. Observe subsequent outcomes when they become available.
3. Propose lessons and identify their supporting evidence.
4. Validate those lessons and define where they apply.
5. Retrieve approved experience for later decisions.
6. Challenge, revise, or retire lessons when evidence or conditions change.

Historical records and current decision influence serve different purposes. An institution can retain an episode for audit while withdrawing an obsolete lesson from active use.

## The two monographs

### 1. From Intelligence to Experience

**Memory, Knowledge, Judgment, and the Architecture of Institutional AI**

The first monograph provides the conceptual and architectural foundation. It connects memory systems, retrieval, model adaptation, continual learning, consolidation, selective forgetting, and governance to the practical requirements of financial institutions.

Its central question is how an institution can transform accumulated information into accountable experience. It distinguishes changes to model weights, enrichment of external knowledge stores, and governed feedback loops that promote tested lessons into future context. It examines how these pathways can support innovation while preserving traceability, appropriate limits, and human responsibility.

[Read the conceptual monograph](https://drive.google.com/file/d/1Ynq7GgqiB9401oAT3bf7U6kxWRL3OFCP/view?usp=drivesdk)

### 2. Memory, Context, and Judgment in Financial Artificial Intelligence

**Four Colab laboratories: from persistent evidence to belief revision**

The second monograph translates the framework into a sequence of small, inspectable experiments. It explains the construction and use of memory, the value of remembered investigative journeys, the interaction between experience and deliberate search, and the revision of beliefs after a regime change.

The laboratories progressively ask: What should be remembered? How should it be retrieved? Can it improve investigation? When should its influence end? Their simplicity helps readers examine the mechanisms and their limitations before considering more complex institutional implementations.

[Read the implementation monograph](https://drive.google.com/file/d/10qYlPH7bblha7lOsfVg_5IFWRLKiTk8Z/view?usp=drivesdk)

## Four Google Colab laboratories

The descriptions below follow the implementation monograph. Work through the notebooks in order to follow the progression from persistence to revision.

| Lab | Notebook | What it explores |
| --- | --- | --- |
| **1 — Persistent memory** | [The Financial AI That Remembers](https://drive.google.com/file/d/1baZdRzj940KbpklltKB2hy-9BY3YLTJL/view?usp=drivesdk) | Stores synthetic credit episodes and lessons, retrieves relevant history, and compares decisions with and without memory. Introduces provenance, contradiction review, persistence, and evaluation. |
| **2 — Remembered investigations** | [A Credit Committee with an Obsidian Memory](https://drive.google.com/file/d/1MWrb_s7FZVI3LJKZ2H9m4HXPWzHL-K5O/view?usp=drivesdk) | Combines a financial knowledge graph with remembered investigative journeys. Examines path choices, information costs, memory contamination, and an exportable Obsidian vault. |
| **3 — Experience and reasoning** | [A Credit Committee That Uses Experience and Intelligence](https://drive.google.com/file/d/1PKqdlcCMI7pvW_Abes3OZXB6rkutKR3v/view?usp=drivesdk) | Uses remembered experience to inform competing investigative branches. Compares architectures under controlled information budgets and examines whether memory improves the investigation. |
| **4 — Belief revision** | [When to Remember, When to Forget](https://drive.google.com/file/d/15BE8lybCXCrRdlkN6WUnIRTLrTVU_mgB/view?usp=drivesdk) | Introduces a changing synthetic market. Explores consolidation, contradiction, retirement of stale beliefs, adaptation lag, and the value or cost of memory. |

To run a laboratory, open its notebook in Google Colab and save a personal copy. Read the explanatory cells before executing the code, and follow that notebook's setup instructions for dependencies, model access, credentials, and persistence. Keep API credentials in Colab Secrets rather than in notebook text or committed code. Model calls may incur provider charges.

## What financial practitioners should take away

The institutional challenge is to make accumulated experience useful without giving every stored statement authority over future decisions. Relevant questions include:

- **Evidence:** What was known at the time, and can the source be traced?
- **Validity:** Does a past lesson still apply to the borrower, market regime, or decision at hand?
- **Evaluation:** Does memory improve decisions against a fair baseline, after accounting for investigation costs and errors?
- **Security:** Can untrusted material contaminate memory or redirect future behavior?
- **Governance:** Who can propose, approve, challenge, revise, or retire a lesson?
- **Accountability:** Can the institution reconstruct the decision and reverse an inappropriate update?

These questions connect resilience and safety with productivity and innovation. A governed memory system can preserve useful institutional knowledge while creating room to test new approaches, recognize failure, and change course.

## Suggested learning path

1. Read the conceptual monograph to establish the framework.
2. Listen to the podcast as an audio companion.
3. Use the implementation monograph alongside Labs 1–4.
4. Compare the results with the stated baselines and inspect the decision traces.
5. Consider what additional evidence, controls, and validation your own institution would require.

## Educational scope

These materials are pedagogical demonstrations using simplified financial environments. They do not establish superior investment returns, production underwriting performance, or reliable autonomous financial decision making. Any institutional application requires independent validation, appropriate data controls, security review, and accountable human oversight. The materials do not constitute financial or investment advice.

## AI-use disclaimer

AI tools assisted in the development of portions of the text, code, explanations, and supporting educational materials. The conceptual direction, pedagogical design, selection and integration of resources, editorial voice, quality supervision, and overall responsibility for this work remain with **Alejandro Reynoso**.

AI-assisted content and code may contain errors, omissions, or limitations. Users should independently verify outputs, inspect code, and evaluate suitability before adapting these materials to research, teaching, or professional practice. The use of AI assistance does not transfer authorship responsibility or institutional accountability to an AI system.

## Copyright and MIT license

Copyright (c) 2026 Alejandro Reynoso

Original materials and code in this repository are made available under the MIT License. Third-party materials, cited publications, services, and dependencies remain subject to their respective licenses and terms.

### MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

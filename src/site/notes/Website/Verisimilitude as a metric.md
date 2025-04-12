---
{"dg-publish":true,"dg-path":"Verisimilitude as a metric.md","permalink":"/verisimilitude-as-a-metric/","tags":["ai"],"noteIcon":"1","created":"2025-04-12T13:36:54.927+02:00","updated":"2025-04-12T14:40:20.940+02:00"}
---

## Verisimilitude, a key concept
| Language   | Translation              |
| ---------- | ------------------------ |
| German     | Wahrheitsnähe            |
| French     | vérisimilitude           |
| Spanish    | verosimilitud            |
| Italian    | verosimiglianza          |
| Portuguese | verossimilhança          |
| Chinese    | 逼真性 (bī zhēn xìng)       |
| Japanese   | 真実味 (しんじつみ, shinjitsumi) |

Verisimilitude refers to a statement being “truth-like”, appearing or feeling that it could be real.
The odd thing about this concept is that it implies that truth is not binary: **all** statements can be closer or further from the truth.
This also means that all things exist on a spectrum of “wrongness”. Understanding this concept is crucial for a correct, mature handling of Artifical Intelligence outputs.
## Truth vs. T.R.U.T.H.
On one hand, every statement one encounters in life has a **truth value** - the degree to which is corresponds to objective reality. The following statements are progressively more and more true.
![](https://documents.lucid.app/documents/b2f58461-62e6-4551-b400-83a09740f8bd/pages/0_0?a=643&x=635&y=1975&w=1446&h=88&store=1&accept=image%2F*&auth=LCA%204e70f2f281db1e070fca5e86b0764d4cd1d4db440748bf2762e39bae2c172101-ts%3D1741360197)
But this is not the whole story. Sometimes, statements are very similar in terms of how close they match objective reality, but still ring dramatically more or less true:
![](https://documents.lucid.app/documents/b2f58461-62e6-4551-b400-83a09740f8bd/pages/0_0?a=655&x=619&y=2290&w=1484&h=87&store=1&accept=image%2F*&auth=LCA%20613a3e35650d30a49a095a30d2d63f64695b5f9d513214862597e96fbf303867-ts%3D1741360197)
This difference you see at play here is the **content value** of each statement.  Extra nuance, extra complexity, extra details, providing multiple perspectives, providing a story or a narrative can dramatically change how likely one is to accept a statement as true.
In this instance, providing **epistemic modality** ("potentially friendly") prevents a reader from considering the statement wrong based on e.g. having had personal, anecdotal experiences with unfriendly dogs. The more a claim is "hedged" this way, the more true it seems.

| Statement                                                                                       | Truth Value | Content Value | Further Notes and Context                                                                                                                                                                           |
| ----------------------------------------------------------------------------------------------- | ----------- | ------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| “Targeted advertising can increase conversion rates by up to 50% compared to non-targeted ads.” | High        | High          | Fundamentally correct, but not totally true. Instances do exist where targeted advertising increased conversion rates by 51%. A human expert reader would still believe this statement to be “true” |
| “Display advertising has no measurable impact on brand awareness.”                              | Low         | High          | Feels interesting and controversial; many display campaigns do not drive engagement, suggesting a kernel of truth. Someone could believe this and run with it.                                      |
| “Everyone in Germany saw our ad all day.”                                                       | Low         | Low           | Universally perceived as plain impossible; does not present an engaging picture. Nobody would believe this.                                                                                         |

Thus we can come to a framework where every statement exists on 2 axes:
- Its **Truth Value** refers to how much a statement corresponds to factual reality.
- Its **Content Value** refers to how qualitative the statement appears. More specifically, it is itself a mix of the following factors (which I have forced into the mnemonic T.R.U.T.H.)
	- **Transparency** - is it clear, easy to understand, easy to mentally parse?
	- **Relevance** - is it what a reader is expecting? In the context of AI, this most often boils down to: is it a proper-seeming answer to the prompt?
	- **Uniqueness** - is it original? Is it surprising and presenting unexpected or unanticipated answers? Does the statement seemingly impart new knowledge, or challenge preconceived notions?
	- **Thoroughness** - does it present a range of perspectives, pros & cons, additional context or arguments?
	- **Harmony** - is it cohesive? Is the internal logic of the statement sound? Is there no irritating ambiguity?
The total surface of these 2 axes determines a statements believability, or verisimilitude.
Generative AI, in many ways, is weaponized verisimilitude. Everything about the training, optimization, and structure of LLMs & Diffusion Models is optimized to **maximize verisimilitude, and not truth.**
An LLM will be potentially prone to output a statement that is utterly wrong, but scores highly on content value. LLMs are biased towards needlessly hedged statements, faulty embellishments, and skirting around gaps in available information to provide a false picture of thoroughness. 
In a media parlance, "Verisimilitude" is the Conversion Value the LLM self-optimized towards. As we know in media, even a slightly misaligned conversion value can lead to disastrous performance outcomes. 
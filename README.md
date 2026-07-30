<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=26&pause=1000&color=8FBE6E&center=true&vCenter=true&multiline=true&width=900&height=150&lines=%3E+junaid.generate(self%2C+temperature%3D1.2);%3E+they+said+%22there's+no+data+for+that+language%22;%3E+i+said+%22correct.+that's+the+project.%22;%3E+%D8%B2%D9%87+%DA%98%D8%A8%D9%87+%DA%98%D9%88%D9%86%D8%AF%DB%8D+%D8%B3%D8%A7%D8%AA%D9%85" alt=""/>

</div>

```yaml
name:      Junaid Aslam
role:      AI Engineer · Low-Resource NLP · Open Source
built:     Pakistan's first Pashto LLM
languages: [ پښتو, English, اردو, Python ]
eos_token: never emitted
state:     decoding
```

---

## `epoch 01 — THE VOID`

Every tutorial builds a sentiment classifier on IMDB. Every portfolio has the same Titanic notebook. I looked at that and felt something close to physical pain.

Meanwhile: **Pashto.** Forty million speakers. Poetry older than most nations. On HuggingFace — silence. Tokenizers gagging on `ښ ږ ډ ړ ټ ڼ ې ۍ`. Datasets that were three scraped news sites in a trench coat. No benchmark. No baseline. Nobody coming.

```diff
@@ speakers, in millions — and who the models were built for @@

  English   ████████████████████████████████████████  ~1500
  Hindi     ████████████████                          ~600
  Arabic    ███████████                               ~400
  Urdu      ██████                                    ~230
  Persian   ███                                       ~130
+ پښتو      █                                         ~40
- dedicated open LLMs for Pashto ......................... 0
+ dedicated open LLMs for Pashto ......................... 1  ← mine

! a language does not die when people stop speaking it.
! it dies when the machines stop listening.
```

So I stopped waiting for someone.

```diff
+ scraped, cleaned, deduped a corpus that did not exist
+ fixed tokenization for a script that breaks tokenizers
+ fine-tuned. evaluated. broke it. fixed it. shipped it.
= PAKISTAN'S FIRST PASHTO LLM
```

---

## `epoch 02 — EVERYTHING ELSE`

The LLM is the loudest thing I've built. It is not the only thing.

<table>
<tr>
<td width="33%" valign="top">

**🤖 AGENTS**

Systems that plan, call tools, and recover from their own mistakes. LangChain plus custom orchestration. Not chatbots — *workers*.

</td>
<td width="33%" valign="top">

**🧬 DATA ENGINEERING**

Corpora, tokenizers, dedup, quality filtering. The unglamorous layer that decides whether a model is good or garbage.

</td>
<td width="33%" valign="top">

**👁 VISION**

Detection, classification, OCR pipelines. Teaching machines to look at something and be right about it.

</td>
</tr>
<tr>
<td valign="top">

**🎨 GENERATIVE AI**

RAG, embeddings, vector stores, prompt architecture. Making models produce things actually worth keeping.

</td>
<td valign="top">

**🧠 CLASSICAL ML/DL**

Before transformers ate the world there was feature engineering, and I still respect it. sklearn, XGBoost, time series.

</td>
<td valign="top">

**🌍 OPEN SOURCE**

`LangChain` · `Gemma` · `sktime`. I don't just import libraries — I leave fingerprints on them.

</td>
</tr>
</table>

---

## `epoch 03 — WEIGHTS`

```diff
@@ loaded from too many nights @@

+ Python                        ██████████████████████  98
+ PyTorch · TensorFlow          ████████████████████    91
+ LLM fine-tuning · LoRA        █████████████████████   94
+ Corpus & tokenizer eng.       █████████████████████   95
+ Agents · LangChain            ███████████████████     85
+ RAG · embeddings · vectors    ██████████████████      82
+ Computer vision · OCR         ████████████████        75
+ Docker · serving · MLOps      ███████████████         71
- Sleep                         █                       05
```

---

## `epoch 04 — NEXT-TOKEN DISTRIBUTION`

```diff
@@ context: "a language with 40M speakers" @@
+ ▁deserves    ████████████████████   0.91
- ▁lacks       ██                     0.06
- ▁waits       ▏                      0.02

@@ context: "open models for Pashto:" @@
- ▁zero        ████████████████████   0.97
- ▁several     ▏                      0.02

@@ context: "so somebody should" @@
+ ▁build_it    ████████████████████   0.99
- ▁complain    ▏                      0.01
- ▁wait        ▏                      0.00
```

---

## `epoch 05 — KNOWN FAILURE MODES`

```diff
- refactors working code because the structure "felt wrong"
- 47 tabs open. reads 4. closes none. this is a system, not a flaw.
- allergic to templates. this file is evidence.
- explains a project for 40 minutes when asked "what do you do"
! resists all attempts at normalization
```

---

<div align="center">

### `SIGTERM ignored. still training.`

[**LinkedIn**](https://www.linkedin.com/in/junaid-ahmad-646117330/) · [**Email**](mailto:aslamjunaid838@gmail.com) · [**HuggingFace**](https://huggingface.co/)

### `څوک چې ژبه ژوندۍ ساتي، هغه تاریخ لیکي.`

*Whoever keeps a language alive is writing history.*

</div>

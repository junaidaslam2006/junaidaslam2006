<div align="center">

<img src="./banner.png" width="100%" alt="Junaid's Epoch"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=21&pause=1000&color=F0C87A&center=true&vCenter=true&multiline=true&width=860&height=130&lines=they+said+%22there's+no+data+for+that+language%22;i+said+%22correct.+that's+the+project.%22;LLMs+%C2%B7+Agents+%C2%B7+Vision+%C2%B7+GenAI+%C2%B7+Automation;%D8%B2%D9%87+%DA%98%D8%A8%D9%87+%DA%98%D9%88%D9%86%D8%AF%DB%8D+%D8%B3%D8%A7%D8%AA%D9%85" alt="typing"/>

</div>

```console
$ tail -f /var/log/junaid.log

[00:00:00] boot ................................. ok
[00:00:01] languages loaded ....... پښتو · EN · اردو · py
[00:00:02] modules: ml · dl · nlp · vision · genai · agents
[00:00:03] scanning for Pashto language models ..........
[00:00:26] scanning ....................................
[00:00:41] results: 0
[00:00:41] 40,000,000 speakers. zero models.
[00:00:42] EXCEPTION → UnacceptableError
[00:00:42] handler → build it yourself
[00:00:43] ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓ 100% · 🇵🇰 FIRST PASHTO LLM
[00:00:44] process did not exit. it never does.
```

## `epoch 01 — THE VOID`

Every tutorial builds a sentiment classifier on IMDB. Every portfolio has the same Titanic notebook. I looked at that and felt something close to physical pain.

Meanwhile: **Pashto.** Forty million speakers. Poetry older than most nations. On HuggingFace — silence. Tokenizers gagging on `ښ ږ ډ ړ ټ ڼ ې ۍ`. Datasets that were three scraped news sites in a trench coat. No benchmark. No baseline. Nobody coming.

So I stopped waiting for someone.

```diff
+ scraped, cleaned, deduped a corpus that did not exist
+ fixed tokenization for a script that breaks tokenizers
+ synthetic instruction pipelines · multi-key · dialect-rotated
+ fine-tuned. evaluated. broke it. fixed it. shipped it.
= 🇵🇰 PAKISTAN'S FIRST PASHTO LLM
```

## `epoch 02 — EVERYTHING ELSE`

The LLM is the loudest thing I've built. It is not the only thing.

<table>
<tr>
<td width="33%" valign="top">

**🤖 AGENTS**

Autonomous systems that plan, call tools, and recover from their own mistakes. LangChain + custom orchestration. Not chatbots — *workers*.

</td>
<td width="33%" valign="top">

**⚡ AUTOMATION**

n8n workflows and Python daemons quietly running things that used to eat human hours. If I do it twice, it gets automated.

</td>
<td width="33%" valign="top">

**👁 VISION**

Detection, classification, OCR pipelines. Teaching machines to look at things and be right about them.

</td>
</tr>
<tr>
<td valign="top">

**🧠 CLASSICAL ML/DL**

Before transformers ate the world there was feature engineering, and I still respect it. sklearn, XGBoost, time series.

</td>
<td valign="top">

**🎨 GENERATIVE AI**

RAG, embeddings, vector stores, diffusion, prompt architecture. Making models produce things worth keeping.

</td>
<td valign="top">

**🌍 OPEN SOURCE**

`LangChain` · `Gemma` · `sktime`. I don't just import libraries — I leave fingerprints on them.

</td>
</tr>
</table>

<div align="center">

```
loss ┤ ██
     ┤ ████
     ┤ ██████                    "it's not converging"
     ┤ ████████▄
     ┤ ███████████▄▄             "it's converging"
     ┤ █████████████████▄▄▄▄
     └────────────────────────────────────────────▶
       ep1    ep2    ep3    ep4    ep5    ∞
```

</div>

## `epoch 03 — WEIGHTS`

<table>
<tr><td width="47%" valign="top">

```python
while alive:
    read_paper()
    think("this is impossible")
    build_it_anyway()
    ship()
    # no break statement.
    # there is no break statement.
```

</td><td width="53%" valign="top">

```
Python              ▓▓▓▓▓▓▓▓▓▓
PyTorch / TF        ▓▓▓▓▓▓▓▓▓░
LLM fine-tuning     ▓▓▓▓▓▓▓▓▓░
Data engineering    ▓▓▓▓▓▓▓▓▓░
Agents / LangChain  ▓▓▓▓▓▓▓▓░░
RAG · vector DBs    ▓▓▓▓▓▓▓▓░░
Computer vision     ▓▓▓▓▓▓▓░░░
n8n · automation    ▓▓▓▓▓▓▓▓░░
Docker · deploy     ▓▓▓▓▓▓▓░░░
Sleep               ░░░░░░░░░░
```

</td></tr>
</table>

<div align="center">

![Python](https://img.shields.io/badge/Python-A3C572?style=flat-square&logo=python&logoColor=1E2B24)
![PyTorch](https://img.shields.io/badge/PyTorch-A3C572?style=flat-square&logo=pytorch&logoColor=1E2B24)
![TensorFlow](https://img.shields.io/badge/TensorFlow-A3C572?style=flat-square&logo=tensorflow&logoColor=1E2B24)
![Transformers](https://img.shields.io/badge/Transformers-A3C572?style=flat-square&logo=huggingface&logoColor=1E2B24)
![scikit-learn](https://img.shields.io/badge/scikit--learn-A3C572?style=flat-square&logo=scikitlearn&logoColor=1E2B24)
<br>
![LangChain](https://img.shields.io/badge/LangChain-B7A9C9?style=flat-square&logo=langchain&logoColor=1E2B24)
![OpenCV](https://img.shields.io/badge/OpenCV-B7A9C9?style=flat-square&logo=opencv&logoColor=1E2B24)
![n8n](https://img.shields.io/badge/n8n-B7A9C9?style=flat-square&logo=n8n&logoColor=1E2B24)
![Docker](https://img.shields.io/badge/Docker-B7A9C9?style=flat-square&logo=docker&logoColor=1E2B24)
![SQL](https://img.shields.io/badge/SQL-B7A9C9?style=flat-square&logo=postgresql&logoColor=1E2B24)
<br>
![FIRST PASHTO LLM](https://img.shields.io/badge/🇵🇰_FIRST_PASHTO_LLM-F0C87A?style=for-the-badge&logoColor=1E2B24)

</div>

## `epoch 04 — METRICS`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&hide_border=true&bg_color=1E2B24&title_color=F0C87A&icon_color=B7A9C9&text_color=EDE6D6&ring_color=F0C87A" height="170"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&hide_border=true&background=1E2B24&stroke=2F4739&ring=F0C87A&fire=F0C87A&currStreakLabel=F0C87A&sideLabels=EDE6D6&dates=8A9A88&sideNums=A3C572&currStreakNum=EDE6D6" height="170"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_GITHUB_USERNAME&bg_color=1E2B24&color=EDE6D6&line=A3C572&point=F0C87A&area_color=2F4739&title_color=F0C87A&hide_border=true&area=true" width="100%"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&hide_border=true&bg_color=1E2B24&title_color=F0C87A&text_color=EDE6D6&langs_count=8" height="150"/>
<img src="https://github-profile-trophy.vercel.app/?username=YOUR_GITHUB_USERNAME&theme=gruvbox&no-frame=true&no-bg=true&column=3&row=2&margin-w=6" height="150"/>

</div>

## `epoch 05 — KNOWN FAILURE MODES`

```diff
- refactors working code because the structure "felt wrong"
- 47 tabs open. reads 4. closes none. this is a system, not a flaw.
- allergic to templates. this file is evidence.
- explains a project for 40 minutes when asked "what do you do"
! resists all attempts at normalization
```

<div align="center">

## `SIGTERM ignored. still training.`

<a href="https://www.linkedin.com/in/junaid-ahmad-646117330/"><img src="https://img.shields.io/badge/LinkedIn-A3C572?style=for-the-badge&logo=linkedin&logoColor=1E2B24"/></a>
<a href="mailto:aslamjunaid838@gmail.com"><img src="https://img.shields.io/badge/Email-B7A9C9?style=for-the-badge&logo=gmail&logoColor=1E2B24"/></a>
<a href="https://huggingface.co/"><img src="https://img.shields.io/badge/🤗_HuggingFace-F0C87A?style=for-the-badge&logoColor=1E2B24"/></a>

<br><br>

### `څوک چې ژبه ژوندۍ ساتي، هغه تاریخ لیکي.`
*Whoever keeps a language alive is writing history.*

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:B7A9C9,45:F0C87A,100:A3C572&section=footer"/>

<img src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&style=flat-square&color=A3C572&label=witnesses"/>

</div>

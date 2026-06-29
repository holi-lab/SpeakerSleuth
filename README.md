# SpeakerSleuth

Official repository for the **ACL 2026 (Main)** paper
**"SpeakerSleuth: Can Large Audio-Language Models Judge Speaker Consistency across Multi-turn Dialogues?"**

Jonggeun Lee, Junseong Pyo, Gyuhyeon Seo, Yohan Jo · Graduate School of Data Science, Seoul National University

[📄 Paper (ACL Anthology)](https://aclanthology.org/2026.acl-long.944/) · [🌐 Project Page](https://holi-lab.github.io/SpeakerSleuth/)

## Abstract

Large Audio-Language Models (LALMs) as judges have emerged as a prominent approach for evaluating speech generation quality, yet their ability to assess speaker consistency across multi-turn dialogues remains unexplored. We present **SpeakerSleuth**, a benchmark evaluating whether LALMs can reliably judge speaker consistency across multi-turn dialogues through three tasks reflecting real-world requirements: Detection, Localization, and Discrimination. We construct 1,818 human-verified evaluation instances across four diverse datasets spanning synthetic and real speech, with controlled acoustic difficulty. Evaluating twelve widely-used LALMs, we find that models prioritize text over acoustics, revealing fundamental modality imbalances that need to be addressed to build reliable audio-language judges.

## Project page

This repository hosts the project page (`index.html` + `static/`), served via GitHub Pages. To preview locally:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Citation

```bibtex
@inproceedings{lee-etal-2026-speakersleuth,
    title = "{S}peaker{S}leuth: Can Large Audio-Language Models Judge Speaker Consistency across Multi-turn Dialogues?",
    author = "Lee, Jonggeun and Pyo, Junseong and Seo, Gyuhyeon and Jo, Yohan",
    booktitle = "Proceedings of the 64th Annual Meeting of the {A}ssociation for {C}omputational {L}inguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2026",
    address = "San Diego, California, United States",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2026.acl-long.944/",
    pages = "20612--20636"
}
```

---

The project page was built using the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template).

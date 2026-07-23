# Auto-Fill

**Learning to Predict Missing Values Accurately with Specialist Language Models**

Official repository for the paper accepted at **VLDB 2026**.

---

## Overview

Predicting missing cell values is a fundamental problem in data cleaning.
**Auto-Fill** post-trains three small language model (SLM) specialists — one each
for **knowledge**, **reasoning**, and **coding** — and combines them with a
calibrated ensemble that selects the most confident specialist or abstains.
This yields high-precision predictions at a fraction (**< 1%**) of the cost of
frontier reasoning models such as o3-pro, Gemini 3 Pro, and DeepSeek-R1, across
11 benchmarks spanning 2,200 real tables.

## Status

> [!NOTE]
> **Code, models, and benchmark are coming soon.** We are preparing the
> artifacts for release; this repository currently serves as a placeholder.

| Component | Status |
| --------- | :----: |
| Training & inference code | 🚧 Coming soon |
| Model checkpoints | 🚧 Coming soon |
| Benchmark | 🚧 Coming soon |

Star or watch this repository to be notified when the release is available!

## Citation

```bibtex
@article{autofill2026,
  author  = {Yurong Liu and Yeye He and Haoyu Dong and Junjie Xing and
             Shi Han and Dongmei Zhang and Surajit Chaudhuri},
  title   = {Auto-Fill: Learning to Predict Missing Values Accurately with Specialist Language Models},
  journal = {Proceedings of the VLDB Endowment},
  volume  = {19},
  number  = {11},
  year    = {2026}
}
```

## License

Released under the [Apache License 2.0](LICENSE).

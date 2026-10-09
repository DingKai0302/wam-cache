# WAM-Cache

**WAM-Cache: Staleness-Bounded KV Reuse for Efficient World Action Models**

Kai Ding, Yang He, Ruijie Quan, Yi Yang

[Paper (arXiv:2610.11401)](https://arxiv.org/abs/2610.11401) · [Project page](https://dingkai0302.github.io/wam-cache/)

WAM-Cache is a training-free framework that reuses layerwise key-value pairs across chunks in the video DiT prefill of World Action Models. It recomputes only a sparse refresh set of tokens. On Fast-WAM, it cuts the prefill FLOPs by 32-42% while staying close to the dense policy.

Code coming soon.

## Citation

```bibtex
@misc{ding2026wamcachestalenessboundedkvreuse,
  title={WAM-Cache: Staleness-Bounded KV Reuse for Efficient World Action Models},
  author={Kai Ding and Yang He and Ruijie Quan and Yi Yang},
  year={2026},
  eprint={2610.11401},
  archivePrefix={arXiv},
  primaryClass={cs.RO},
  url={https://arxiv.org/abs/2610.11401},
}
```

The project page lives in [`docs/`](docs/) and is served by GitHub Pages.

# WAM-Cache

**WAM-Cache: Staleness-Bounded KV Reuse for Efficient World Action Models**

Kai Ding, Yang He, Ruijie Quan, Yi Yang

Project page: https://dingkai0302.github.io/wam-cache/

WAM-Cache is a training-free framework that reuses layerwise key-value pairs across chunks in the video DiT prefill of World Action Models. It recomputes only a sparse refresh set of tokens. On Fast-WAM, it cuts the prefill FLOPs by 32-42% while staying close to the dense policy.

Code coming soon.

The project page lives in [`docs/`](docs/) and is served by GitHub Pages.

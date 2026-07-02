# ReTreever

Project page for **ReTreever: Hierarchical Retrieval at Scale**, accepted at **ICML 2026**.

ReTreever is a retrieval-optimized hierarchical retriever. It learns an inspectable binary tree over encoder representations, producing coarse-to-fine representations that can be used for fast and scalable retrieval without LLM calls during tree construction or navigation.

**Website:** https://shubham-gupta-30.github.io/retreever/

## What is on the page?

- High-level motivation for hierarchical retrieval.
- Method overview: frozen encoder + differentiable tree organizer.
- Main results: latency, retrieval quality, approximate search, and 124.5M-document scale study.
- Interpretability view: semantic groupings emerge in the learned tree.
- Citation and launch-ready social copy.

## Release status

The public project page is live. Code is marked as **coming soon** until release approval is complete.

## Citation

```bibtex
@inproceedings{gupta2026retreever,
  title     = {Hierarchical Retrieval at Scale: Bridging Interpretability and Efficiency},
  author    = {Gupta, Shubham and Li, Zichao and Chen, Tianyi and Subakan, Cem and Reddy, Siva and Taslakian, Perouz and Zantedeschi, Valentina},
  booktitle = {Proceedings of the 43rd International Conference on Machine Learning},
  year      = {2026}
}
```

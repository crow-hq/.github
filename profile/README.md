<p align="center">
  <img src="crow-org-banner.png" alt="CROW: a pixel-art crow standing on an open book, the wiki, with a network of documents, tools and uses growing from it" width="100%">
</p>

**CROW** builds LLM wikis that stay fast and cheap as they grow: a small classifier
decides where each document goes, and the LLM writes the notes.

<sub>Where we're heading: every document, tool and team around one wiki. Today: PDF, Markdown and text files, with Ollama or any OpenAI-compatible provider.</sub>

### LLM Wiki v2

[**crow-hq/llm-wiki-v2**](https://github.com/crow-hq/llm-wiki-v2): give it your documents,
get a wiki of plain Markdown notes that answers questions citing the notes it used.
Runs on your computer with any provider, Ollama included.

| | CROW | LLM-only wiki |
|---|---|---|
| Right note read | **89%** | 62% |
| Time per ingest | **18.4 s** (2.1× faster) | 38.6 s |
| LLM tokens per ingest | **5,508** (68% fewer) | 17,324 |

```bash
uv tool install "llmw2[server] @ git+https://github.com/crow-hq/llm-wiki-v2"
llmwiki2 demo
```

`llmwiki2 demo` opens an example wiki, no key needed. If it helps you, [⭐ star the repo](https://github.com/crow-hq/llm-wiki-v2).

### Research

F. Cesarini, M. Sassarini, *CROW: Classifier-Routed Organization of LLM Wikis*, 2026.
[doi:10.5281/zenodo.22898752](https://doi.org/10.5281/zenodo.22898752)

### Get in touch

Questions and ideas in [Discussions](https://github.com/crow-hq/llm-wiki-v2/discussions) ·
bugs in [issues](https://github.com/crow-hq/llm-wiki-v2/issues/new/choose) ·
[crowhq.community@gmail.com](mailto:crowhq.community@gmail.com)

Made by [Federico Cesarini](https://github.com/fed3c3sa) and [Marco Sassarini](https://github.com/sassarini-marco).

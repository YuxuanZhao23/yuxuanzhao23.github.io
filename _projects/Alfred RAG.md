---
layout: page
title: Alfred RAG
description: LLM RAG for prompted weak supervision
img: assets/img/AR1.png
importance: 3
category: work
related_publications: false
---

Alfred is a prototype framework for integrating large pretrained model into programmatic weak supervision pipelines. Alfred provides an intuitive and user-friendly interface, enabling users to quickly create and refine prompts as supervision sources and interact with large models. Furthermore, Alfred includes tools for label modeling, allowing the mixed signals from prompted model responses to be combined, distilled and denoised. Additionally, Alfred enables memory- and computation- intensive models to be run on cloud or computing clusters with optimized batching mechanisms, significantly increasing query throughput. Alfred aims to reduce annotation cost and time by making efficient use of LLMs, allowing users to make the most of their resources.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/AR2.png" title="poster" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

I collaborated with PhD candidate Yu on this project involving the integration of Retrieval-Augmented Generation (RAG) techniques into Alfred. My contributions focused on enhancing the system's ability to efficiently retrieve and generate contextually relevant information, significantly improving its performance and accuracy.

GitHub link: <a href="https://github.com/YuxuanZhao23/alfred-rag">https://github.com/YuxuanZhao23/alfred-rag</a>

- I developed a Retrieval-Augmented Generation (RAG) system, integrating Faiss for efficient vector search
and OpenAI’s GPT models for natural language queries
- I created a custom embedding management pipeline using PyTorch and Faiss, optimizing vector search with IVF and IVF_SQ8 index types, enabling scalable and fast document retrieval

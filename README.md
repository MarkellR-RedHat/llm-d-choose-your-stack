# choose your own inference stack

So this is my attempt at killing the "which inference framework should we use" spiral. It's a decision tool plus config generator — answer a few questions about your model size, latency target, and GPU budget, and it spits out an architecture.

**Status:** planned — it'll live in my [llm-d content hub](https://markellr-redhat.github.io/llm-d-content-hub/) with the rest of these projects.

## what's llm-d

[llm-d](https://llm-d.ai) is an open-source Kubernetes-native framework for distributed LLM inference, built on vLLM. Everything here is built around it.

# node-red-flow-openllama #

Node-RED Flow (and web page example) for the OpenLLaMA AI model

This repository contains a function node for [Node-RED](https://nodered.org/) which can be used to run the [300BT preview](https://huggingface.co/openlm-research/open_llama_7b_preview_300bt) of the [Open LLaMA model](https://github.com/openlm-research/open_llama) based on the [RedPajama 1T dataset](https://huggingface.co/datasets/togethercomputer/RedPajama-Data-1T) using [llama.cpp](https://github.com/rozek/llama.cpp) within a Node-RED flow. **Inference is done on the CPU** (without requiring any special harware) and still completes within a few seconds on a reasonably powerful computer.

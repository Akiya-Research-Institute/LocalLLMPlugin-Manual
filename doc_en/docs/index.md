# What is Local LLM Plugin?

[Local LLM Plugin](https://vrlab.akiya-souken.co.jp/en/products/localllmplugin/) allows to load a large language model (LLM) of GGUF format and run it on the Unreal Engine.

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/xjIJklDqJdE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->

## Run locally and within BP/C++

- Runs offline on a local PC.
- Just add one component to your BP and you are ready to use it.
- No Python or dedicated server is required.

## Useful features

- Works asynchronously, additional questions can be asked at any time during answer generation.
- Supports saving and loading of "state" that preserve the context of a conversation with an LLM, allowing you to resume a previous conversation later.
- Supports multibyte characters.
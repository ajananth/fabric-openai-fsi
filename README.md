# Financial Product Analyser using Microsoft Fabric & Azure OpenAI

This sample code is based on content published in this article - https://blog.fabric.microsoft.com/en-us/blog/harness-the-power-of-langchain-in-microsoft-fabric-for-advanced-document-summarization?ft=All and this repo - https://github.com/microsoft/SynapseML/blob/master/docs/Explore%20Algorithms/OpenAI/Langchain.ipynb

Running this notebook in Microsoft Fabric will generate summaries for financial products at scale based on a list of provided product disclosure statements, and find other financial organisations that offer the same product based on a web search.

## Features

* LangChain used for orchestration
* Azure OpenAI leveraged for LLM integration
* Extensible list of PDSs that can be analysed at scale
* Integration with Bing Search for web-based search

## Results

Here is an example of the type of result that can be expected from running this notebook. This was generated when a Participating Forward Contract PDS was analysed.

![PFC](https://github.com/ajananth/fabric-openai-fsi/assets/77469793/aaebcf37-4844-428f-b8d2-1fe637a48e48)




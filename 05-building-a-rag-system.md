# Chapter 5: Building a RAG system

## Introduction to Retrieval Augmented Generation

### Making your model smarter without training it on your data

* Explanation of what RAG is and how it enhances the ability of an LLM to generate correct answers.
* Benefits of using RAG over traditional search applications
* Benefits of using RAG in context-rich, data-driven scenarios

### Real world applications of RAG

## Setting up semantic text memory

### What is semantic text memory

* Explanation of what semantic text memory does in Semantic Kernel.
* Outline of options to choose from for storing memory records.

### Adding data to semantic text memory

* Sample demonstrating how to add data into semantic text memory.
* Explanation of the steps required to build the sample yourself.

### Retrieving information from semantic text memory

* Sample demonstrating how to connect semantic text memory to the agent.
* Explanation of the steps required to build the sample yourself.

## Using semantic text memory in production

### Updating data frequently

* Explanation on why you should have an automated process for updating data.
* Explanation on why you should store the raw data separate from the text store for easier updating.
* Demonstration of a basic indexer that runs as a background process.

### Managing large volumes of data

* Explanation of the famous HTTP 429 error and how you can solve quota issues
* Explanation of the importance of having a status dashboard to show you where the indexer is at
* Demonstration of the principles in this section.

## Optimizing semantic text memory

### Using reranking to improve results

* Sample demonstrating how you can use a reranker to optimize the results
* Explanation of the steps required to build the sample
* Explanation of why you should be careful with reranking because of the performance impact

### Improving how you chunk data

* Explanation of what other options you have for chunking data

### Using other forms of retrieval

* Explanation of the knowledge graph and the promise of a higher abstraction level

## Testing retrieval performance

* Explanation of the importance of testing your retrieval separate from the rest of the agent

### Setting up test cases for memory retrieval

* Demonstration of how you can write tests to validate the retrieval process
* Explanation of the steps required to get the demo working

### Evaluating RAG system performance metrics

* Demonstration of RAGAS as a framework to test the retrieval in combination with the generation portion

## Summary

* Summary of the chapter.

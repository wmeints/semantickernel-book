# Preface

I got started in generative AI right before chatgpt.com became a thing. Before that, I spent much time getting people started with MLOps. That's still a thing, but it seems like generative AI has taken over the spotlights for now. I wrote this book because I want to record my experiences and motivate other people to start building generative AI applications that go beyond the scope of ChatGPT and Microsoft Copilot.

This book focuses on agents, but that's not the only use case I found to be a useful application of Generative AI.

## Purpose of this book

This book will teach you how to build useful and secure agents with Semantic Kernel.

## Who is this book for?

This book is for developers looking to build agents with Microsoft Semantic Kernel. Architects will find it useful for understanding the various architectural choices needed when building agents.

## Prerequisites

We expect you to have a working knowledge of C# and one of the popular IDEs, such as Visual Studio Code. You also need to meet the following technical requirements:

* You need an active Azure subscription with access to Azure OpenAI and Azure Cosmos.
* You need a Mac, Windows, or Linux computer with the .NET 8 SDK installed.

## How this book is organized

This book will walk you through all the steps to start with your first agent. Then, with each chapter, we'll add more advanced features to your agent. We'll cover the most popular features, like Retrieval Augmented Generation (RAG) and multi-modal use cases.

Each chapter will briefly introduce the concept covered in the chapter, and then we'll use samples to cover how to use the newly introduced concept. We'll end each chapter with tips to help you get the most out of Semantic Kernel.

Here's a brief outline of the chapters in this book.

* **Chapter 1: Introduction**  
  This chapter introduces Generative AI, Agents, and what Semantic Kernel solves for you when you want to build Generative AI applications.

* **Chapter 2: Getting started with semantic kernel**  
  This chapter covers what you need to build a project with Semantic Kernel. We'll cover a basic project structure, required Azure Resources, and alternatives to the models hosted in Azure.

* **Chapter 3: Building your first agent**  
  In this chapter, we will create the basis for the agent we will use as an example throughout the book. At the end of this chapter, you will understand the different components needed to build an agent.

* **Chapter 4: Building with Skills**  
  After creating the agent in Chapter 2, we'll look at extending the agent with custom skills. We'll cover prompt-based skills and code-based skills. You'll learn how to choose between the two types of skills and how to implement them.

* **Chapter 5: Building a RAG system**  
  This chapter covers the basics of Retrieval Augmented Generation, a popular technique to teach agents about specific knowledge from your organization without having to train or fine-tune any models.

* **Chapter 6: Managing Conversation History**  
  In this chapter, we'll cover how to maintain conversation history and basic persistence, handle GDPR requirements, and provide your agent with the right information from the conversation history without overloading the language model.

* **Chapter 7: Integrating Personalization**  
  This chapter helps you understand your options for personalizing your agent. We'll also cover how to protect yourself against abuse with this feature.

* **Chapter 8: Adding multi-modality**  
  The final feature we'll cover in this book is adding multi-modality to your agent. In this chapter, we'll dive into generating images and understanding images.

* **Chapter 9: Securing and Managing Agents**  
  This final chapter will cover securing your agents against some of the most used attacks. We also cover how to manage the costs of your agent in production.

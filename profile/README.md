# Welcome to Flyflow 👋 🚀

> Flyflow is high performance API middleware to optimize LLM applications, same response quality, 5x lower latency, secure, and much higher token limits

When building on top of LLMs, builders care about the following: 

- Response quality 
- Latency (both time to first token and tokens / second)
- Rate limits 
- Reliability
- Enterprise grade security

Flyflow is middleware designed to optimize for all of these qualities, built to be open source, high performance written in golang, and optionally self-hosted for maximum flexiblity.

## How it works

We start by proxying your traffic to services like openai, claude, or gemini. As we've collected enough data, we fine tune a custom model based on your query patterns to match the quality of the foundation model. We then deploy this on the highest performance inference providers to provide much faster responses at much lower cost. 

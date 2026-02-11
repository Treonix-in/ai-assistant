
  <img src="https://raw.githubusercontent.com/assistant-ui/assistant-ui/main/.github/assets/header.svg" alt="assistant-ui Header" width="100%" style="width: 1000px" />



## The UX of ChatGPT in your React app 💬🚀

**assistant-ui** is an open source TypeScript/React library to build production-grade AI chat experiences fast.

- Handles streaming, auto-scrolling, accessibility, and real-time updates for you
- Fully composable primitives inspired by shadcn/ui and cmdk — customize every pixel
- Works with your stack: AI SDK, LangGraph, Mastra, or any custom backend
- Broad model support out of the box (OpenAI, Anthropic, Mistral, Perplexity, AWS Bedrock, Azure, Google Gemini, Hugging Face, Fireworks, Cohere, Replicate, Ollama) with easy extension to custom APIs

## Why assistant-ui

- **Fast to production**: battle-tested primitives, built-in streaming and attachments
- **Designed for customization**: composable pieces instead of a monolithic widget
- **Great DX**: sensible defaults, keyboard shortcuts, a11y, and strong TypeScript
- **Enterprise-ready**: optional chat history and analytics via Assistant Cloud

## Getting Started

Run one of the following in your terminal:

```bash
npx assistant-ui create   # new project
npx assistant-ui init     # add to existing project
```

[![assistant-ui starter template](https://raw.githubusercontent.com/assistant-ui/assistant-ui/main/.github/assets/assistant-ui-starter.gif)](https://youtu.be/k6Dc8URmLjk)

## Features

- **Build**: composable primitives to create any chat UX (message list, input, thread, toolbar) and a polished shadcn/ui theme you can fully customize.

- **Ship**: production-ready UX out of the box — streaming, auto-scroll, retries, attachments, markdown and code highlighting — plus keyboard shortcuts and accessibility by default.

- **Generate**: render tool calls and JSON as components, collect human approvals inline, and enable safe frontend actions.

- **Integrate**: works with AI SDK, LangGraph, Mastra, or custom backends; broad provider support; optional chat history and analytics via Assistant Cloud (single env var).

## Backends

- **Assistant Cloud**: managed chat persistence and analytics. Deploy with the Cloud Starter template; bring any model/provider.

- **AI SDK**: integration with Vercel AI SDK; connect to any supported provider.

- **LangGraph**: integration with LangGraph and LangGraph Cloud; connect via LangChain providers.

- **Mastra**: integration with Mastra agents/workflows/RAG; model routing via Vercel AI SDK; optional Mastra Cloud.

- **Custom**: use assistant-ui on top of your own backend/streaming protocol.

## Customization

assistant-ui takes a Radix-style approach: instead of a single monolithic chat component, you compose primitives and bring your own styles. We provide a great starter config; you control everything else.

![Overview of components](https://raw.githubusercontent.com/assistant-ui/assistant-ui/main/.github/assets/components.png)

Sample customization to make a Perplexity lookalike:

![Perplexity clone created with assistant-ui](https://raw.githubusercontent.com/assistant-ui/assistant-ui/main/.github/assets/perplexity.gif)



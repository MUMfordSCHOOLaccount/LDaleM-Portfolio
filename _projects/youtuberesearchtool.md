---
title: YouTube Hardware Research Tool & LLM Engine
description: A multi-threaded C# .NET desktop application that securely interfaces with the YouTube API v3 and routes localized transcript data loops through LM Studio.
url: https://github.com
---

### Architecture Overview
This system processes media metrics and video text strings asynchronously. It abstracts data ingestion workflows to remain strictly compliant with platform terms of service.

### Highlights
* **Thread Isolation:** Built using asynchronous `async/await` tasks to protect the primary UI thread from freezing.
* **Local Inference:** Connects to local network sockets to stream contextual prompts straight into an un-networked Qwen LLM environment.

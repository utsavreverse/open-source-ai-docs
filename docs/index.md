---
icon: simple/nvidia
---

# Introduction

NVIDIA NIM is a platform that provides the containers to self-host GPU microservices for AI models, in short you can host models into that platform

### So what is purpose of this document?
Well, currently NVIDIA is hosting many of the open source models free of cost, that includes models with some proven benchmarks like Kimi K2.5, GLM 5.1 and Minimax M2.6.

You can use these models by creating account in NVIDIA and then generating API key, The API key can then be used on various platforms like OpenCode or for the development 

### Ok but how long these models are free and are there any limits?

There is no mention in official site that how long these models are gonna be free, and regarding the rate limit, NVIDIA enforces the **40 RPM**(Requests Per Minute) limit, that means that in single minute there can't be a more than 40 concurrent requests, again there is no any description for the token consumption, so as long as the requests are under 40, it will work fine.
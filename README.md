# RAG_with_LangChain_Uday
This is a repo for an ongoing personal project. 

Started with implementing a self-correcting multi-agent system with DigitalOcean's facilities for inference routing and serverless inference, which allow the user to deploy and run AI models without provisioning, managing, or paying for the underlying server infrastructure or expensive GPUs -- while also using an intelligent traffic controller within an AI architecture that evaluates incoming user prompts in real-time and determines the absolute best model or server replica to handle that specific request. It hands over the task to agents based on cost, latency/speed and failover mechanisms.

## Self-Correcting-Multi-Agent

1. Python 3.11+ is recommended.

```bash
conda create -n loop-agent python=3.11 -y
conda activate loop-agent
pip install -r requirements.txt
```
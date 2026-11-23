# Sergii Onufriienko

AI Platform Engineer in Porto, Portugal. I build and run the platform under AI: the models you host, the gateway in front of them, and the evals that prove they work. I measure first, then ship.

## Recent work

- **Self-host vs API, on real GPUs.** An LLM inference platform on AWS: Kubernetes (EKS), vLLM, llm-d and agentgateway on NVIDIA Blackwell GPUs. 512 requests in flight on four GPUs, more than 3,000 answered, none failed. A 180B-parameter model on one server. A cache-aware router that got 62% more requests per second on repeat traffic. Then the cost of every 1,000 requests against API prices. My own lab, synthetic load.
  [Article](https://www.linkedin.com/pulse/should-your-company-run-its-own-ai-models-i-built-ran-onufriienko-l65je/)
- **Agents under load.** One agent against a multi-agent on Amazon Bedrock AgentCore, over 2,000 sessions. [Article](https://www.linkedin.com/pulse/i-ran-2000-ai-agents-aws-were-easy-part-sergii-onufriienko-inqye/)

## Stack

vLLM · llm-d · Kubernetes · AgentGateway · LangGraph · MCP · Amazon Bedrock AgentCore · Langfuse · OpenTelemetry · AWS · Terraform · Python · Postgres/pgvector

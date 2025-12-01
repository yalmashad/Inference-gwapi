# NGINX Gateway Fabric — LLM Inference Routing

This repo show example of NGINX Gateway Fabric (NGF) with the Gateway API Inference Extension to route LLM inference traffic based on:
- Model selection (cheap vs expensive models)
- Inference objectives / priorities
- Endpoint Picker (EPP) choosing backend

The demo uses lightweight LLM simulator backends and works on any local Kubernetes cluster.

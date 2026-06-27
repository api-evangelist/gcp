---
title: "Scaling Ray Serve LLM on GKE: Performance without losing the developer experience"
url: "https://cloud.google.com/blog/products/containers-kubernetes/improving-ray-serve-llm-on-gke-throughput-latency/"
date: "2026-06-18"
author: "Spencer Peterson and Seiji Eicher"
feed_url: "https://cloudblog.withgoogle.com/rss/"
---
Google and Anyscale partnered to improve Ray Serve LLM on Google Kubernetes Engine, delivering up to 5x higher throughput and 8x lower latency. The gains come from three architectural changes: Ray Serve HAProxy integration, a direct token streaming architecture, and a v2 Ray executor backend for vLLM, benchmarked using Gemma 4 on A4 VMs with NVIDIA HGX B200 systems and available in Ray 2.56+.

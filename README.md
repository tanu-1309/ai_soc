# AI-Augmented Security Operations Center

Local AI services, machine-learning intrusion detection, alert enrichment, attack-campaign simulation, and response planning for security operations research.

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![Python 3.10+](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/downloads/)
[![Docker Compose](https://img.shields.io/badge/docker-compose-blue.svg)](https://docs.docker.com/compose/)
[![Dataset: CICIDS2017](https://img.shields.io/badge/dataset-CICIDS2017-green.svg)](datasets/CICIDS2017/README.md)

AI-SOC is a research-grade implementation of an AI-assisted security operations center. It combines trained IDS models, local LLM alert triage, retrieval over security knowledge, Wazuh integration, incident correlation, swarm-scale attack simulation, and a prototype response orchestrator.

The project is intentionally local-first: security event data is processed through local services and Ollama-backed LLM inference rather than a hosted LLM API.

## What This Is

AI-SOC answers one operational question:

> Given a noisy stream of alerts and a modeled environment, which threats matter, how might an attacker proceed, and what defensive action should be
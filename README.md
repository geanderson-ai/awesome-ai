# Repository Projects Overview

This repository contains several interesting projects focused on AI, knowledge graphs, meeting transcription, and voice-to-text applications. Below is a description of each project.

## Graphiti

Graphiti is a framework for building and querying temporally-aware knowledge graphs, specifically tailored for AI agents operating in dynamic environments. Unlike traditional retrieval-augmented generation (RAG) methods, Graphiti continuously integrates user interactions, structured and unstructured enterprise data, and external information into a coherent, queryable graph.

### Key Features
- Temporal knowledge graph architecture for AI agent memory
- Continuous, incremental data updates without requiring complete graph recomputation
- Hybrid semantic, keyword, and graph-based search capabilities
- Support for episodic data, semantic entities, and communities
- MCP (Model Context Protocol) server implementation for AI assistants

### Components
- **Core Library**: The main Graphiti framework for building and querying knowledge graphs
- **MCP Server**: Allows AI assistants to interact with Graphiti's knowledge graph capabilities
- **REST Service**: API service built with FastAPI for interacting with Graphiti
- **Examples**: Includes quickstart examples demonstrating basic functionality

## Meeting Minutes (Meetily)

An AI-powered meeting assistant that captures live meeting audio, transcribes it in real-time, and generates summaries while ensuring user privacy. Perfect for teams who want to focus on discussions while automatically capturing and organizing meeting content.

### Key Features
- Real-time audio capture (microphone + system audio)
- Live transcription using Whisper.cpp
- Speaker diarization support
- Local processing for privacy (all processing happens on your device)
- Modern, responsive UI with real-time updates
- Available for macOS and Windows

### Components
- **Frontend**: Built with Next.js and Tauri for a native desktop experience
- **Backend**: Python FastAPI server for transcription and analysis
- **Whisper Server Package**: Pre-built Whisper server for real-time speech recognition

## OpenManus

OpenManus is an open-source framework for building general AI agents, inspired by Manus but without requiring an invite code. It provides a versatile agent that can solve various tasks using multiple tools.

### Key Features
- Versatile agent framework for solving various tasks
- Support for multiple LLM providers
- MCP (Model Context Protocol) integration
- Multi-agent capabilities (experimental)
- Chart visualization tools

### Components
- **Core Agent**: The main OpenManus agent implementation
- **MCP Integration**: Support for Model Context Protocol
- **Tools**: Various tools for the agent to use, including chart visualization

## Realtime Transcribe with Next.js

A voice-to-text application that allows users to record their voice and receive a real-time transcript displayed on the screen. Built using Next.js and Web Speech API.

### Key Features
- Record voice using the built-in microphone
- Real-time transcription of speech
- Minimalistic user interface
- Responsive design for different devices

### Components
- **Next.js App**: Frontend application for voice recording and transcription
- **Web Speech API Integration**: For recording and speech recognition

## Getting Started

Each project has its own setup instructions and requirements. Please refer to the individual project directories for detailed information on how to get started with each project.
# VidRAG
Video Insight — extract insights from videos

VidRAG is a .NET-based AI project that allows users to ask questions about video content.
The system transcribes videos, indexes them using vector search, and answers questions with precise timestamps.

## Why VidRAG?
Most knowledge today is locked inside videos. VidRAG turns videos into searchable knowledge using modern AI techniques like Retrieval-Augmented Generation (RAG).

## Key Features
- Upload video files
- Automatic speech-to-text transcription
- Semantic search over video content
- Ask natural language questions
- Answers include source timestamps

## High-Level Architecture
1. Video is uploaded via an API
2. Audio is extracted and transcribed
3. Transcript is split into small chunks
4. Chunks are indexed using vector embeddings
5. User questions retrieve relevant chunks
6. An AI model generates answers grounded in the video

## Tech Stack
- .NET 8 / ASP.NET Core
- Azure OpenAI
- Azure Blob Storage
- Azure AI Search (Vector Search)
- FFmpeg

## Project Status
🚧 MVP under active development.

## Roadmap
- [ ] Video upload API
- [ ] Background video processing worker
- [ ] Vector search integration
- [ ] Question & Answer endpoint
- [ ] Basic web UI

# Transformer Management System

This organization contains the core repositories for a complete transformer inspection and maintenance platform that combines web-based operations with AI-assisted thermal anomaly detection.

## What this project delivers

- Transformer asset registration and lifecycle tracking  
- Inspection planning and execution workflows  
- Thermal image upload, comparison, and annotation workflows  
- AI-powered anomaly detection and severity classification  
- Operational APIs, exports, and integration-ready services  

## Demo video

Watch the full system functionality demo here:  
https://youtu.be/nX28taxkiKQ

## Repositories

### 1) [front-end](https://github.com/Transformer-Management-System/front-end)
React + Vite application used by operators and engineers to manage transformers, schedule inspections, upload thermal images, review AI outputs, and export logs.

### 2) [backend](https://github.com/Transformer-Management-System/backend)
Spring Boot service layer and system API that manages core entities (transformers, inspections, records), security, persistence, and integrations.

### 3) [anomaly-detection-service](https://github.com/Transformer-Management-System/anomaly-detection-service)
FastAPI + computer vision microservice for thermal anomaly detection, image alignment, and classification (Normal / Potentially Faulty / Faulty) with detailed detection reports.

## High-level architecture

1. Users work in the **front-end** to manage transformers and inspections.  
2. The **backend** orchestrates business workflows, data access, and API security.  
3. For thermal analysis requests, the backend invokes the **anomaly-detection-service**.  
4. Results are returned to the frontend for review, action, and export.

## Getting started

1. Start the backend service.  
2. Start the anomaly detection service.  
3. Run the frontend and connect it to the backend API.  

For detailed setup and endpoint usage, see each repository’s README and documentation.

## Contribution

Issues and pull requests are welcome across all repositories.  
Please open repository-specific issues for bugs, enhancements, or documentation updates.

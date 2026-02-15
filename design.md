# JanSathi AI – System Design Document

## 1. System Architecture Overview

The system follows a layered architecture:

User Channels → AI Layer → Knowledge & Eligibility Engine → Service Layer → Output & Notifications

## 2. Access Layer
- IVR (Telephony API)
- WhatsApp Bot API
- Progressive Web App (PWA)

## 3. AI Layer
- Automatic Language Identification
- Speech-to-Text (ASR)
- Intent & Entity Recognition (NLP)
- Retrieval-Augmented Generation (RAG)
- Text-to-Speech (TTS)

## 4. Eligibility Engine
Rule-based + contextual filtering using structured scheme database.

## 5. Knowledge Base
- Government scheme structured database
- Vector embeddings for semantic retrieval
- Source-grounded responses

## 6. Data Storage
- User sessions database
- Scheme repository
- Notification scheduler

## 7. Security & Privacy
- Encryption at rest and in transit
- Minimal PII storage
- Consent-based data access

## 8. Scalability
- Serverless architecture
- Cloud-native deployment
- Horizontal scaling support

## 9. Future Enhancements
- AI-based document validation
- Voice biometric identity layer
- Offline kiosk integration

# Findora Media Service

## Student Information
- **Student Name:** Charuka Hansaja
- **Student ID:** 241722035
- **Slack Handle:** Charuka (`U0BF12U29NF`)
- **GCP Project ID:** findora-cloud-platform

---

## Project Description
Handles media file uploads (images/attachments) for lost items and directly integrates with Google Cloud Storage Buckets.

## Technology Stack & Cloud Infrastructure
- **Language:** Java 25 / Spring Boot
- **Cloud Storage:** Google Cloud Storage Bucket Integration
- **Service Discovery:** Netflix Eureka Client

## Setup / Getting Started Instructions
```bash
mvn clean package -DskipTests
java -jar target/media-service-0.0.1-SNAPSHOT.jar
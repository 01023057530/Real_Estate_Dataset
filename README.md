# Real_Estate_Dataset

## 🏡 Project: Real Estate Price Prediction using Fine-Tuned LLM

### ✅ Project Description & Benefits:

This project demonstrates how to fine-tune a Large Language Model (LLM) for structured property data using LoRA (Low-Rank Adaptation) and 4-bit quantization. The fine-tuned model enables accurate and efficient prediction of real estate prices from natural language descriptions of listings. By optimizing for performance and memory efficiency, the solution is both scalable and deployable in production environments (e.g., web apps, real estate platforms, etc.).


### 🛠️ What I Did:

Data Preprocessing: Cleaned and converted tabular real estate data into natural language prompts suitable for LLM input.

LLM Fine-Tuning: Used the Unsloth library to fine-tune the LLaMA-3 8B model with LoRA adapters, enhancing its ability to understand property listing features.

Quantization: Applied 4-bit quantization to reduce memory usage and improve inference speed without sacrificing accuracy.

Evaluation & Inference: Trained and saved the model, then used the vLLM framework for optimized and fast price predictions at inference time.

Model Merging: Merged the LoRA adapters back into the base model, simplifying deployment.


### 🤖 Project: AI Agent System for Smart Meeting Room Booking

### ✅ Project Benefits:

This multi-agent system streamlines the meeting room reservation process using AI agents with specialized roles. By leveraging AutoGen’s multi-agent framework, the system automates the entire workflow—checking availability, matching room features, resolving conflicts, and finalizing bookings—leading to faster, more efficient scheduling with minimal human intervention.

### 🛠️ What I Did:

Designed a modular AI system using AutoGen with clear agent responsibilities.

Implemented 5 agents:

UserAgent: Collects user input.

AvailabilityAgent: Checks room availability.

FeatureAgent: Matches required features (e.g., projector, capacity).

ConflictAgent: Handles scheduling conflicts.

BookingAgent: Finalizes and records reservations.

Managed communication and coordination using GroupChat and GroupChatManager.

Created a natural language interface to make the booking process user-friendly and autonomous.

### ⚠️ Note: 

Due to the large dataset size and the computational demands of the LLaMA-3 8B model, the full execution of the fine-tuning code could not be completed in resource-limited environments like Kaggle. Successful training and merging require a more powerful server or a cloud-based GPU instance.

Additionally, the AI agent system was implemented separately as a lightweight AutoGen-based multi-agent demo to simulate the meeting room booking process. It is not directly connected to the real estate dataset or the LLM fine-tuning task, and was designed to demonstrate intelligent multi-agent coordination in a simpler environment.

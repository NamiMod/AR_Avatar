# AR_Avatar

This repository showcases a demonstration of "Ana," a persistent, voice-interactive AI assistant built for Augmented Reality (AR).

The goal of this project is to create an "always-on" AI companion that lives in the user's environment, capable of understanding and responding to natural language requests.

## 📹 The Demonstration Video

The included video shows the system in action from the first-person perspective of a Microsoft HoloLens user.

## 💡 Core Concept

The vision for "Ana" is to be a seamless AR companion. She is designed to remain "always at the corner of your vision", available but unobtrusive.

Using a natural, voice-first interface, the user can:
* Ask complex questions.
* Get information about their surroundings.

## ✨ Features Demonstrated

* **Persistent AR Avatar:** "Ana" is always present in the user's AR space, providing a friendly and engaging interface for the AI.
* **Voice-First Interaction:** The system is built around natural language.
* **High-Accuracy Speech-to-Text:** Uses **OpenAI Whisper** to transcribe the user's spoken words into text with high precision.
* **LLM Backend:** The transcribed text is sent to a **Large Language Model (LLM)**, which understands the query's intent and generates an intelligent, human-like response.
* **Text-to-Speech Output:** The LLM's text response is converted back into speech using a TTS engine, allowing "Ana" to "talk" back to the user.

## ⚙️ Conceptual Architecture

This demo operates on the following data flow:

1.  **User Speaks:** The HoloLens microphone captures the user's voice
2.  **Speech-to-Text:** The audio is processed by **OpenAI Whisper**, which outputs a text string.
3.  **LLM Processing:** The text string is sent to an **LLM Backend**.
4.  **LLM Response:** The LLM generates a text-based answer.
5.  **Text-to-Speech:** The text response is fed into a **TTS Engine**, which generates an audio file.
6.  **AR Output:** The "Ana" avatar in the Unity/AR application plays the audio file.

## Status

**This is currently a project concept and demonstration.** The repository's primary asset is the video showing the system's successful implementation.

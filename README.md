# MVP_relationship_intelligence_app
Minimum Viable Product (MVP) prototype for the relationship intelligence app.

The relationship intelligence app MVP is a Python-based prototype running in Google Colab, designed to guide users through emotionally intelligent, voice-based reflections on personal relationships. Its key functionalities include:

>>4-Phase Conversation Flow:

Onboarding & History: Collects relationship context (e.g., “My friend Emma, friends for 5 years”).
Emotional Mapping: Explores feelings (e.g., “bittersweet, distant”) with sentiment tagging.
Dynamics & Tensions: Identifies interaction patterns (e.g., “I reach out first, it hurts”).
Dual-Lens Reflection: Encourages empathy (e.g., “Emma might feel busy”).
Voice Interaction:
Input: Supports text input or uploaded WAV audio (speech-to-text via speechrecognition).
Output: AI responses are spoken (text-to-speech via gtts) and printed, playable as MP3s in Colab.
System Features:
AI Memory Engine: Stores inputs, emotions, and themes in a pandas DataFrame for session summaries.
Sentiment & Depth Scoring: Uses Hugging Face’s sentiment model to label emotions (e.g., POSITIVE, NEGATIVE).
Safety & Guardrails: Detects sensitive keywords (e.g., “hurt”) for gentle responses and includes a “not therapy” disclaimer.
User Outcome Loop: Ends with an emotional summary (e.g., “You explored history, empathy… take a moment to appreciate your openness”).
End States & Summaries:
Each phase concludes clearly (e.g., “You’ve painted a clear picture”).
A final summary recaps emotions and themes, offering closure and insight.

>>Conclusion
This MVP prototype effectively demonstrates the core concept of a relationship intelligence app, enabling empathetic reflection through a structured, voice-based flow in Google Colab. It integrates essential features—memory, sentiment analysis, safety, and emotional summaries—while remaining lean for testing and feedback. Though limited by basic NLP and Colab’s constraints, it validates the app’s potential, providing a solid foundation for future development with enhanced voice, UI, and emotional depth.

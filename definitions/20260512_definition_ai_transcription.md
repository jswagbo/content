---
title: "AI transcription"
description: "AI transcription converts spoken audio into text with speech recognition models and can optionally use language models to clean the result."
---

# AI transcription

AI transcription is the process of converting spoken audio into written text with machine learning
models. Modern transcription workflows usually extract audio from a video or meeting recording, send
that audio to a speech recognition model such as Whisper, and save the returned transcript as a
searchable text file.

A production transcription workflow often adds extra steps around the model call: audio conversion with `ffmpeg`, provider selection, prompt hints for names or technical vocabulary, language selection, post-processing, and secure API key management.

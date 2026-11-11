# TrapGuard AI — Android MVP 0.1.0

A native Android starter project using Kotlin and Jetpack Compose.

## Current MVP
- Dark cybersecurity-themed interface
- Paste-in message analyser
- On-device heuristic checks for common warning patterns:
  - requests for money or banking details
  - secrecy pressure
  - intimate-image pressure
  - threats and blackmail language
  - OTP/password/PIN requests
  - unrealistic investment promises
  - fast emotional commitment
- Explainable findings, indicative score, and safety steps
- No network permission or remote upload in this prototype

## Important limitations
This is a rules-based prototype, not a trained AI model. Its score is an indicator, not a probability, proof, identity verification, or legal finding. It can miss scams and can flag harmless messages. Human context and independent verification matter.

## Build
1. Install Android Studio (current stable).
2. Open this folder as an existing Gradle project.
3. Allow Gradle sync and install the Android SDK platform 35 if prompted.
4. Run the `app` configuration on an Android device or emulator.

Package ID: `com.trapguard.ai`

## Suggested next development milestones
1. Add screenshot import and on-device OCR with explicit user consent.
2. Add secure local case history with user-controlled deletion.
3. Add an optional server-backed language model with clear consent, data minimisation, encryption, retention controls, and a privacy policy.
4. Add safe reporting guidance and verified regional helplines.
5. Conduct false-positive/false-negative testing before public release.

## Privacy and safety
The app currently analyses text locally in memory and does not request contacts, SMS, accessibility, microphone, camera, or location permissions. Do not use it to secretly monitor another person.

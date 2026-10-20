# Tech Stack Evaluation

## Project
[An audio-based Driver Emotion Analysis using Speech Emotion Recognition (CNN on mel-spectrograms, web dashboard, emergency alert).]

## Requirements that drive the decision
List 3 to 5 requirements from your own docs/requirements.md. Include at
least 2 non-functional requirements.
- FR-[1]: System predicts the driver's emotion from audio and shows the emotion and confidence on a dashboard.
- FR-[2]: System alerts a registered emergency contact when a high-risk emotion (fear or anger) is detected, with an "I'm okay" button to cancel.
- NFR-[1]: Prediction result appears within [X] seconds of the audio input.
- NFR-[2]: Model is evaluated by accuracy and precision.
- NFR-[3]: Emergency contact details must be stored securely.

## Options
- Option A: [Dynamic website (HTML and JavaScript) on GitHub Pages]
- Option B: [for example: Python web app (Flask) with a database on a cloud host]
- Option C: [your own idea]

## Decision matrix
Weight: how important the criterion is for YOUR project (1 = low, 5 = high).
Score: how well each option does (1 = poor, 5 = excellent).
Weighted score = weight x score. Add them up for each option.

| Criterion                          | Weight | A score | B score | C score |
|------------------------------------|--------|---------|---------|---------|
| Fits my requirements               | 5      |         |         |         |
| Skills I already have              | 3      |         |         |         |
| Time to build before my deadline   | 5      |         |         |         |
| Free hosting and tools             |        |         |         |         |
| Performance and security needs     |        |         |         |         |
| Room to grow later                 |        |         |         |         |
| **Total (weighted)**               |        |         |         |         |

## Decision record
- **Context:** [Final year project with a fixed deadline. Needs a CNN model, a dashboard and an alert feature, built by one person.]
- **Decision:** [the option you chose]
- **Reasons:** [2 to 3 reasons, linked to your requirements and the matrix]
- **Consequences:** [what becomes easy, what becomes hard]
- **Risks and next review:** [what could go wrong, and when you will check again]

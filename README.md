# AI-Music-Neuroscience

Project Overview: 
This project studies how AI-generated music affects brain activity. EEG data is recorded and analyzed in EEGLAB to extract features like Alpha, Beta, Theta, and Gamma waves. These patterns are compared with AI music from Suno to explore links between brain responses and musical characteristics.

Workflow:
┌────────────────────────────┐
│   1. AI Music Creation     │
│   (Suno Prompts)           │
│ - Generate diverse tracks  │
│ - Store metadata           │
└────────────┬──────────────┘
             ↓
┌────────────────────────────┐
│   2. EEG Recording          │
│   (Listening to Tracks)     │
│ - Record EEG per track      │
│ - Timestamp & annotate      │
└────────────┬──────────────┘
             ↓
┌────────────────────────────┐
│   3. EEGLAB Preprocessing   │
│ - Bandpass filtering        │
│ - ICA artifact removal      │
│ - Channel cleanup           │
└────────────┬──────────────┘
             ↓
┌────────────────────────────┐
│   4. Feature Extraction     │
│ - PSD & Bandpower           │
│ - Theta / Alpha / Beta /    │
│   Gamma bands               │
└────────────┬──────────────┘
             ↓
┌────────────────────────────┐
│   5. EEG → Music Mapping    │
│ - Correlate features        │
│ - ML/statistical modeling   │
│ - Cluster neural responses  │
└────────────┬──────────────┘
             ↓
┌────────────────────────────┐
│   6. Visualization & Report │
│ - Brain maps & PSD plots    │
│ - Interactive dashboards    │
└────────────────────────────┘

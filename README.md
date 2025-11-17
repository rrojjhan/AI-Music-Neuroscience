# AI-Music-Neuroscience

Project Overview: This project explores how human brainwave activity can influence generative music using an EEG-based workflow. EEG signals are recorded and analyzed using EEGLAB in MATLAB, where the data is preprocessed, cleaned with ICA, and transformed into neural features such as Theta, Alpha, Beta, and Gamma band powers. These features are then mapped to musical parameters—such as tempo, mood, dynamics, and instrument choice—using a custom Python/MATLAB workflow.

After creating a mapping table, music is generated using an AI music model (e.g., Suno). The project follows an iterative process: music is created first, and then evaluated with an EEG analyzer to observe emotional or cognitive responses. The goal is to build a system that connects neural patterns with musical expression, demonstrating how engineering, signal processing, and AI can be combined to study human–music interaction.

# Workflow

![MusicEEG](https://github.com/user-attachments/assets/4545b06f-ee10-4a00-860d-ed417c597930)

#

# Mapping table (Bandpower → Music type)

| EEG Feature | Meaning               | Used For Music        |
| ----------- | --------------------- | --------------------- |
| High Alpha  | Relaxation            | Ambient, slow BPM     |
| High Beta   | Concentration         | Focus tracks          |
| High Theta  | Meditation/Creativity | Dreamy, low-BPM       |
| High Gamma  | Excitement/Intensity  | Fast, energetic songs |



# AI-Music-Neuroscience

Project Overview: This project explores how human brainwave activity can influence generative music using an EEG-based workflow. EEG signals are recorded and analyzed using EEGLAB in MATLAB, where the data is preprocessed, cleaned with ICA, and transformed into neural features such as Theta, Alpha, Beta, and Gamma band powers. These features are then mapped to musical parameters—such as tempo, mood, dynamics, and instrument choice—using a custom Python/MATLAB workflow.

After creating a mapping table, music is generated using an AI music model (e.g., Suno). The project follows an iterative process: music is created first, and then evaluated with an EEG analyzer to observe emotional or cognitive responses. The goal is to build a system that connects neural patterns with musical expression, demonstrating how engineering, signal processing, and AI can be combined to study human–music interaction.

# Workflow

![MusicEEG](https://github.com/user-attachments/assets/4545b06f-ee10-4a00-860d-ed417c597930)

# Mapping table (Bandpower → Music type)

| EEG Feature | Meaning               | Used For Music        |
| ----------- | --------------------- | --------------------- |
| High Alpha  | Relaxation            | Ambient, slow BPM     |
| High Beta   | Concentration         | Focus tracks          |
| High Theta  | Meditation/Creativity | Dreamy, low-BPM       |
| High Gamma  | Excitement/Intensity  | Fast, energetic songs |



# Research Objectives

To systematically evaluate neurophysiological responses to AI-generated music by recording and analyzing electroencephalographic (EEG) data collected during exposure to distinct musical categories.

To quantify changes in neural frequency bands—including Theta (4–7 Hz), Alpha (8–12 Hz), Beta (13–30 Hz), and Gamma (30–45 Hz)—and assess their relationship to cognitive and affective states elicited by different AI-generated compositions.

To establish a rigorous and reproducible EEG preprocessing and analysis pipeline utilizing EEGLAB and MATLAB, incorporating standardized procedures for filtering, artifact correction, segmentation, and spectral analysis.

To compare and interpret neural signatures across music conditions, identifying consistent patterns that correspond to relaxation, focus, excitation, or meditative responses.

To develop an analytical framework capable of linking EEG-derived features to the structural characteristics of AI-generated music, thereby contributing to emerging research on the intersection of music technology, artificial intelligence, and human neurophysiology.

To produce transparent, publicly accessible documentation and computational resources, hosted on GitHub, to facilitate replication, peer evaluation, and future expansion of the methodology.


# Music Links
https://www.youtube.com/@ApolloVerse91
https://www.youtube.com/@%E0%B9%80%E0%B8%81%E0%B9%87%E0%B8%9A%E0%B9%80%E0%B8%AA%E0%B8%9A%E0%B8%B5%E0%B8%A2%E0%B8%87

# Reference
https://eeglab.org/tutorials/02_Quickstart/quickstart.html


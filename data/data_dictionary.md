# Data Dictionary: Combined Lyrics Dataset

This document outlines the schema and metric definitions for the lyrics datasets. The file **Annotated_lyrics_652_H.csv** contains the manual annotations.

## Core Metrics

*   **Arousal**: Represents the intensity or energy level of the emotion conveyed by the lyrics. Values typically range from `-1.0` (calm, lethargic, low energy) to `1.0` (excited, tense, high energy).
*   **Valence**: Represents the intrinsic attractiveness (positive) or aversiveness (negative) of the emotion conveyed by the lyrics. Values typically range from `-1.0` (sad, angry, negative) to `1.0` (happy, joyful, positive).

## Column Definitions

| Column Name | Description | Data Type |
| :--- | :--- | :--- |
| **Dataset** | The name of the source dataset from which the song/lyrics originate (e.g., MuVi, PMEmo). | String |
| **musicId** | A unique identifier for the specific music track or video. | String |
| **Start Time** | The timestamp indicating when the specific lyric segment begins in the audio. | String (MM:SS.s) |
| **End Time** | The timestamp indicating when the specific lyric segment ends in the audio. | String (MM:SS.s) |
| **Lyrics** | The transcribed text of the song lyrics for the given time segment. | String |
| **Arousal_A1** | The Arousal score provided by the first human annotator. | Float |
| **Valence_A1** | The Valence score provided by the first human annotator. | Float |
| **Arousal_A2** | The Arousal score provided by the second human annotator. | Float |
| **Valence_A2** | The Valence score provided by the second human annotator. | Float |
| **Arousal_A3** | The Arousal score provided by the third human annotator. | Float |
| **Valence_A3** | The Valence score provided by the third human annotator. | Float |

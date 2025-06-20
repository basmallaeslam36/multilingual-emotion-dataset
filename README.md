
# 🌍 Multilingual Emotion Expression Dataset

![License](https://img.shields.io/badge/License-CC%20BY%204.0-brightgreen)
![Entries](https://img.shields.io/badge/Entries-384-blue)
![Languages](https://img.shields.io/badge/Languages-5-orange)
![Status](https://img.shields.io/badge/Status-Complete-success)

A comprehensive, open-source dataset of approximately **384 emotionally expressive phrases** across **5 major languages** — curated for use in natural language processing (NLP), emotion classification, and inclusive AI development.

---

## 📁 Dataset Summary

- **Languages**: English (`en`), Arabic (`ar`), Spanish (`es`), Korean (`ko`), Chinese (`zh`)
- **Phrases**: Everyday expressions, idioms, slang, mental health self-expressions  
- **Total entries**: ~384 phrases (cleaned from an initial 440+ entries; malformed rows were skipped during processing)  
- **Formats**: CSV, JSON  

Each phrase is annotated with:

- `sentiment`: Positive / Negative / Neutral  
- `emotion`: Joy, Sadness, Anger, Fear, Gratitude, etc.  
- `emotion_intensity`: Mild / Moderate / High  
- `intent`: Self-Expression, Encouragement, Breakdown, etc.  
- `context`: Idiom, Slang, Everyday Expression  
- `audio_path`: Path to associated TTS-generated audio file  

---

## 🌟 Why This Dataset?

Most emotion datasets are:
- Limited to English  
- Too formal or synthetic  
- Lacking cultural nuance  

This dataset includes culturally rooted phrases and colloquialisms in multiple languages, ideal for:
- Emotion-aware multilingual chatbots  
- Mental health and affective computing research  
- Sentiment/emotion classification  
- Cross-cultural NLP exploration  

---

## 🔤 Example Entry

| phrase                  | language | sentiment | emotion  | intensity | intent          | context        | audio_path        |
|-------------------------|----------|-----------|----------|-----------|------------------|----------------|-------------------|
| طاير من الفرحة          | ar       | Positive  | Joy      | High      | Self-Expression | slang          | audio/ar/003.wav  |
| Estoy en el séptimo cielo | es    | Positive  | Joy      | High      | Self-Expression | idiom          | audio/es/002.wav  |
| I'm feeling trapped     | en       | Negative  | Trapped  | High      | Breakdown       | emotional vent | audio/en/071.wav  |

---

## 📚 File Structure

- `cleaned_multilingual_dataset.csv` — Main dataset  
- `cleaned_multilingual_dataset.json` — Structured version  
- `audio/` — Directory for TTS-generated audio samples  

---

## ✍️ How It Was Built

- Phrases manually curated and translated by project lead  
- Emotion labels based on affective computing literature  
- Audio generated via Google TTS (gTTS)  
- Manually validated and deduplicated  

---

## 📢 Citation & License

**Author**: Basmalla Eslam  
**License**: CC BY 4.0 (Attribution Required)  
Feel free to use, cite, and remix for any purpose (including commercial) with attribution.

```bibtex
@dataset{eslam2025multilingualemotion,
  title     = {Multilingual Emotion Expression Dataset},
  author    = {Basmalla Eslam},
  year      = {2025},
  url       = {https://github.com/basmallaeslam36/multilingual-emotion-dataset}
}
````

---

## 🤝 Contributing

Pull requests and feedback are welcome!
To suggest additional phrases or corrections, open an issue or submit a PR.

---

## 🚀 Future Directions

* Add recorded audio (non-TTS)
* Expand to more languages (e.g., French, Hindi)
* Build demo emotion classifier
* Submit to Hugging Face Datasets or Kaggle

---

## 💬 Contact

**Basmalla Mohamed**
📧 [basmallaeslam36@gmail.com](mailto:basmallaeslam36@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/basmalla-eslam)

Let me know if you'd like to collaborate or extend this work!


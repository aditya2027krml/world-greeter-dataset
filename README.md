# 🌍 World Greeter: A Multimodal Cultural Dataset

> A culturally rich dataset featuring greetings, languages, flags, regions, and landmark imagery from countries A–Z — ideal for multilingual, educational, or UI/UX applications.

---

## 📦 Dataset Title  
**World Greeter: A Multimodal Cultural Dataset**

---

## 📝 Dataset Documentation

### 📌 Dataset Name
**World Greeter: A Multimodal Cultural Dataset**

### 📄 Version
1.0

### 📅 Last Updated
April 20, 2025

### 👤 Authors
Aditya Kumar

### 📜 License
- **CSV Data**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- **Images**: Downloaded from [Unsplash](https://unsplash.com) under the [Unsplash License](https://unsplash.com/license). Attribution is recommended but not required.

---

## 📁 Folder Structure
/world-greeter/
  ├── index.html
  ├── data/
  │    └── countries.csv
  ├── images/
  │    ├── flags/
  │    │    ├── india.png
  │    │    ├── france.png
  │    │    └── ...
  │    └── landmarks/
  │         ├── india.jpg
  │         ├── france.jpg
  │         └── ...


## 🧾 Schema: countries.csv

| Column Name      | Type   | Description                                                  |
|------------------|--------|--------------------------------------------------------------|
| `code`           | String | One-letter country code (A–Z)                                |
| `name`           | String | Full country name                                            |
| `greeting`       | String | Common local greeting in the native language                |
| `language`       | String | Most widely spoken language in the country                  |
| `region`         | String | Continent or geographical region                            |
| `flag_image`     | Path   | Relative path to the country's flag image (`PNG`)           |
| `landmark_image` | Path   | Relative path to the country's landmark image (`JPG`)       |

---

## 🚀 Usage Examples

### ✅ Educational Tools
- Teach kids greetings and cultural diversity.
- Integrate into geography or language-learning platforms.

### ✅ UI/UX Development
- Design multicultural interfaces for onboarding screens.
- Enhance language learning apps with visuals and native phrases.

### ✅ Machine Learning
- Train a multimodal classifier combining text and image data.
- Use for tasks like image captioning or greeting prediction.

### ✅ Data Visualization
- Build interactive dashboards with D3.js, React, or Tableau.
- Create world maps with multilingual greetings and visuals.

---

## 🔧 How to Use

1. Load the `countries.csv` using your preferred data processing tool (e.g., `pandas`, D3.js, etc.).
2. Display each record’s `greeting`, `flag_image`, and `landmark_image`.
3. Use `index.html` as a front-end template to render interactive visualizations.

---

## 📷 Attribution for Images

All images in `/images/flags/` and `/images/landmarks/` are downloaded from [Unsplash](https://unsplash.com), a free-to-use image platform. Attribution is appreciated but not mandatory.

**Optional Sample Attribution:**

> Photos sourced from Unsplash. Flags and landmarks by various contributors. Visit [unsplash.com](https://unsplash.com) for more.

---

## 💡 Potential Improvements

- Include ISO 3166 country codes.
- Add pronunciation audio files.
- Provide geolocation data for landmarks.
- Expand to support multilingual greetings per country.

---

## 📚 Citation

If you use this dataset in your work, please cite it as:

```bibtex
@misc{worldgreeter2025,
  title={World Greeter: A Multimodal Cultural Dataset},
  author={Aditya Kumar},
  year={2025},
  url={[https://your-github-or-dataset-link.com](https://github.com/aditya2027krml)},
  note={Version 1.0}
}

## 📬 Contact

Feel free to reach out for suggestions, collaborations, or feedback!

## ⭐️ Show Your Support

If you like this project, consider giving it a ⭐ on GitHub!

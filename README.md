# 🎬 CineMatch
### Discover Movies You'll Love.

CineMatch is a movie recommendation system designed to help users discover movies based on content similarity. It uses machine learning and natural language processing techniques to identify movies with similar characteristics and recommend relevant titles.

## ✨ Project Overview

Finding a movie to watch can be difficult when there are thousands of options available. CineMatch aims to simplify movie discovery by analyzing movie information and suggesting similar movies.

The recommendation system uses content-based filtering to compare movie attributes and calculate similarity between titles.

## 🚀 Key Features

- **Movie Recommendations:** Discover movies similar to a selected movie.
- **Content-Based Filtering:** Recommendations based on movie metadata.
- **Movie Search:** Search for movies using the available search functionality.
- **Similarity Matching:** Uses cosine similarity to identify related movies.
- **Web Interface:** Django-based application for interacting with the recommendation system.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Django | Backend web framework |
| Pandas | Data processing |
| Scikit-learn | Machine learning and text processing |
| TF-IDF | Text feature extraction |
| Truncated SVD | Dimensionality reduction |
| Cosine Similarity | Movie similarity calculation |
| HTML, CSS, JavaScript | Frontend |

## ⚙️ How It Works

CineMatch follows a content-based recommendation approach:

1. **Data Processing:** Movie metadata is processed to prepare it for recommendation.
2. **Feature Extraction:** TF-IDF converts textual movie information into numerical features.
3. **Dimensionality Reduction:** Truncated SVD reduces the feature space.
4. **Similarity Calculation:** Cosine similarity measures how closely movies are related.
5. **Recommendation:** The system identifies and returns similar movies.

## 💻 Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/meenukumari8511/CineMatch.git
```

### 2. Navigate to the Project Directory

```bash
cd CineMatch
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows PowerShell:**

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Apply Database Migrations

```bash
python manage.py migrate
```

### 7. Run the Development Server

```bash
python manage.py runserver
```

Open the following URL in your browser:

```text
http://127.0.0.1:8000/
```

## 📁 Project Status

**Status:** Under Development

CineMatch is being customized and extended with additional functionality, UI improvements, and testing.

## 📌 Future Enhancements

- Improved movie discovery experience
- Genre-based movie filtering
- Rating-based filtering
- Enhanced user interface
- Additional recommendation capabilities

*These enhancements are planned and will be documented as they are implemented.*

## 📜 License and Attribution

This project is an adaptation of the open-source [Movie Recommendation System](https://github.com/inboxpraveen/Movie-Recommendation-System).

The original project is distributed under the MIT License. The original copyright notice and license terms are retained in this repository's `LICENSE` file.

Movie data and related assets may have separate attribution and usage requirements. This product uses data from TMDB but is not endorsed or certified by TMDB.

## 👩‍💻 Maintainer

**CineMatch**
GitHub: [@meenukumari8511](https://github.com/meenukumari8511)

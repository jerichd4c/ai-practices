<a id="readme-top"></a>

<br />
<div align="center">
  <img src="https://img.shields.io/badge/AI%20Practices-URU-blue?style=for-the-badge" alt="AI Practices" width="320" height="40">

<h3 align="center">AI Practices - Sebastian Cohen</h3>

  <p align="center">
    Repository for the Artificial Intelligence course at URU. It gathers the final versions of the class projects — computer vision, OCR, and RPA applications built in Python.
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-repository">About The Repository</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#repository-structure">Repository Structure</a></li>
    <li><a href="#main-projects">Main Projects</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>

## About The Repository

This repository brings together the material covered in the **Artificial Intelligence** course at URU. Its purpose is to keep the final, working version of each project in one organized place — a CNN-based image classifier, a real-time face recognition system, an OCR-driven document pipeline, and an RPA automation tool, all built in Python.

Each project folder is self-contained and has its own README with setup instructions and implementation details.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![Python][Python-badge]][Python-url]
* [![TensorFlow][TensorFlow-badge]][TensorFlow-url]
* [![OpenCV][OpenCV-badge]][OpenCV-url]
* [![Streamlit][Streamlit-badge]][Streamlit-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

Each project has its own dependencies and run instructions — see its individual README linked in [Main Projects](#main-projects).

### Prerequisites

* Python 3.10 or higher
* A webcam (for the face recognition system)
* Tesseract OCR installed on the system (for the receipt manager)
* A Twilio account with WhatsApp enabled (for the RPA project's real delivery mode)

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/jerichd4c/ai-practices.git
   ```
2. Open the folder for the project you want to run.
3. Follow that project's own README.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Repository Structure

These are the projects currently available in the repository:

* `ai-trash-sorter/`: a CNN-based waste classifier trained on the Kaggle Garbage Classification dataset, with a Streamlit UI.
* `face-recognition-sistem/`: a real-time face recognition and emotion analysis system using OpenCV and DeepFace.
* `receipt-manager/`: an OCR-driven receipt processing pipeline with an email-based approval workflow.
* `car-business-rpa/`: an RPA tool that analyzes sales data and delivers reports over WhatsApp via Twilio.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Main Projects

These are the projects developed during the course. Each one has its own internal documentation.

### [AI Trash Sorter](ai-trash-sorter/README.md)
A CNN-based waste classifier that sorts images into 12 waste categories, with a Streamlit interface for live classification.
* **Features**: CNN training pipeline, confusion matrix and training history plots, a Streamlit demo app, and a full written project report.
* **Documentation**: [Project README](ai-trash-sorter/README.md)

### [Face Recognition System](face-recognition-sistem/README.md)
A real-time facial recognition and emotion analysis system with both a Streamlit web interface and a CLI.
* **Features**: face embeddings via Facenet/ArcFace/VGG-Face, 7-class emotion detection, SQLite-backed detection history.
* **Documentation**: [Project README](face-recognition-sistem/README.md)

### [Receipt Manager](receipt-manager/README.md)
An automation pipeline that extracts data from receipt images/PDFs via OCR and routes them through an email-based approval flow.
* **Features**: Tesseract OCR extraction, SQLite state tracking, FastAPI backend, one-click approve/reject via email.
* **Documentation**: [Project README](receipt-manager/README.md)

### [Car Business RPA](car-business-rpa/README.md)
An RPA tool that loads sales data, computes key metrics, generates charts, and delivers the report over WhatsApp.
* **Features**: Excel-based data loading, automated chart generation, Twilio WhatsApp delivery with a simulation fallback.
* **Documentation**: [Project README](car-business-rpa/README.md)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

This roadmap summarizes the course progress and can keep growing as new units or assignments are added.

- [x] Computer vision: a CNN image classifier.
- [x] Computer vision: real-time face recognition and emotion analysis.
- [x] OCR and document processing pipeline with an approval workflow.
- [x] RPA: automated data analysis and WhatsApp reporting.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[Python-badge]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[Python-url]: https://www.python.org/
[TensorFlow-badge]: https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white
[TensorFlow-url]: https://www.tensorflow.org/
[OpenCV-badge]: https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white&color=5C3EE8
[OpenCV-url]: https://opencv.org/
[Streamlit-badge]: https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white
[Streamlit-url]: https://streamlit.io/

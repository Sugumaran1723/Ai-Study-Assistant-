# Lumen — AI Study Assistant 📚✨

Lumen is an advanced, client-side AI Study Assistant web application explicitly designed to turn heavy academic material into concise, structured, and exam-ready revision notes[span_0](start_span)[span_0](end_span). Built with a modern, high-fidelity glassmorphism user interface[span_1](start_span)[span_1](end_span), it focuses on educational efficiency, helping students extract clarity from dense PDFs, textbooks, or documents within minutes[span_2](start_span)[span_2](end_span).

---

## 🚀 Key Features

* **Instant Document Processing:** Seamlessly handles multiple file formats including `.pdf`, `.docx`, `.txt`, and images (`.png`, `.jpg`, `.jpeg`)[span_3](start_span)[span_3](end_span).
* **OCR (Optical Character Recognition):** Integrated with Tesseract.js to extract text directly from images of book pages or handwritten notes[span_4](start_span)[span_4](end_span).
* **Structured Summaries:** Generates clean, predictable study frameworks featuring Topics, Key Points, Easy Explanations, Definitions, and Exam High-Yield Notes[span_5](start_span)[span_5](end_span).
* **Exam & Quiz Suite:** Features automated tools to generate MCQs, True/False quizzes, Fill-in-the-Blanks, and quick Flashcards from your materials with a single tap[span_6](start_span)[span_6](end_span).
* **Advanced Multi-Modal Support:** Includes a built-in Voice Dictation tool for hands-free typing and Text-to-Speech (TTS) capabilities to read summaries aloud[span_7](start_span)[span_7](end_span).
* **Robust Client-Side Performance:** Everything from theme toggling (Light/Dark mode) to session exports as standard Markdown (`.md`) files is optimized beautifully[span_8](start_span)[span_8](end_span).

---

## 🛠️ Tech Stack & Architecture

Lumen is built to be lightweight, modular, and extremely fast, utilizing modern client-side web technologies and standard script injections for real-time document parsing[span_9](start_span)[span_9](end_span):

* **Frontend:** Responsive HTML5, Semantic CSS3 (custom CSS variables, Glassmorphism gradients, Space Grotesk typography)[span_10](start_span)[span_10](end_span).
* **Parsing Utilities:** 
  * `pdf.js` (Mozilla) — Client-side PDF extraction[span_11](start_span)[span_11](end_span).
  * `mammoth.js` — Core `.docx` file structure decoding[span_12](start_span)[span_12](end_span).
  * `Tesseract.js` — Pure JavaScript OCR processing engine[span_13](start_span)[span_13](end_span).
* **Markdown Renderer:** `marked.js` for beautiful, smooth text formatting of AI outputs[span_14](start_span)[span_14](end_span).

---

## 🎯 Target Audience

Specifically engineered for **undergraduate engineering students** and college academics who need high-yield, accurate revision materials right before exam week, bypassing the fluff and focusing strictly on core terminology and definitions[span_15](start_span)[span_15](end_span).

---

## 📝 How to Use Locally

1. Clone or download this repository.
2. Open the `lumen-ai-study-assistant.html` file in any modern mobile or desktop web browser[span_16](start_span)[span_16](end_span).
3. Paste your lecture material or upload a document to begin studying immediately[span_17](start_span)[span_17](end_span)!

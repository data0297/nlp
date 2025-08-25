# DATA0297: Introduction to Natural Language Processing (Fall 2025)

**Instructor:** Shuo Zhang, Ph.D, Professor of the Practice, Tufts University   
**Email:** [Shuo.Zhang@tufts.edu](mailto:Shuo.Zhang@tufts.edu)  
**Industry Advisor:** Jeanie Cherng, Ph.D    
**Time:** Mondays 6:00–9:00pm  
**Location:** Tisch Library 316, Medford campus, Tufts University      
**Office Hours:** Mondays 5:00–6:00pm (JCC 525) or by appointment (Zoom)

---



## Announcements



<blockquote style="
  border-left: 6px solid #118fcf; 
  background-color: #f0f0f0; 
  color: #000; 
  padding: 10px 15px; 
  ">
  
<span style="font-weight:bold;">[Note on this website]</span>: This course website provides a quick and practical guide to this course. The website will be updated throughout the term to reflect the latest information. For a comprehensive syllabus please see below.
</blockquote>


<blockquote style="
  border-left: 6px solid #118fcf; 
  background-color: #f0f0f0; 
  color: #000; 
  padding: 10px 15px; "
>

<span style="font-weight:bold;">[Notes on Slides]:</span> Slides links will be updated throughout the term.
</blockquote>
<blockquote style="
  border-left: 6px solid #118fcf; 
  background-color: #f0f0f0; 
  color: #000; 
  padding: 10px 15px; "
>
 
 <span style="font-weight:bold;">[Notes on homework]</span> Please refer to the Canvas for when the homework is assigned and due. The homework itself is available on the course github repo. 
 </blockquote>
<blockquote style="
  border-left: 6px solid #118fcf; 
  background-color: #f0f0f0; 
  color: #000; 
  padding: 10px 15px; "
>
 <span style="font-weight:bold;">Aug 18:</span> GitHub repo is at <a https://github.com/Tufts-University/NLP-Fall25>here</a>. Please send me your github username so I can give you access.
 </blockquote>
<blockquote style="
  border-left: 6px solid #118fcf; 
  background-color: #f0f0f0; 
  color: #000; 
  padding: 10px 15px; "
>
 <span style="font-weight:bold;">July 15:</span> Final project rules posted [here](final-proj.md).
 </blockquote>
<blockquote style="
  border-left: 6px solid #118fcf; 
  background-color: #f0f0f0; 
  color: #000; 
  padding: 10px 15px; "
>
 <span style="font-weight:bold;">July 14:</span> Welcome to DATA0297! Full syllabus PDF available below.
</blockquote>






---
## Course Info (click below to expand)
<details>
<summary> Course description </summary>
NLP is now at the center of AI, data science and data analytics. There is a wealth of textual data online. NLP-enabled products constitute an essential part of everyday life, both in consumer facing products (Siri, Alexa, ChatGPT, Google Translate, etc.) and B2B applications (e.g., NLP for medical and legal domains). However, understanding human languages and extracting structured information from this plethora of unstructured text data is a major challenge for computers. The recent advancement in machine learning and deep learning makes NLP one of the fastest growing fields in AI and data science. In this course, we will survey machine learning (ML) based NLP techniques from statistical ML approaches to the state-of-the-art (SOTA) deep learning models and Large Language Models (LLMs), with a focus on building a solid understanding of the history and theory of NLP that led to the current LLMs. Students will read the latest research papers, implement NLP algorithms or train/fine-tune deep learning/LLM models for a variety of NLP tasks, as well as completing a final project and research paper on a topic of their interest.

</details>


<details>
<summary> Homework, presentations and final projects</summary>

To adapt to the rapidly evolving field of NLP, this course is designed to simulate the real-world environment of a R&D NLP/AI practitioner wherever possible. Instead of being a static, lecture and exam based course, the students will have plenty of opportunities to actively conduct independent research, collaborate with teammates, present their projects, and keep up with the SOTA research on NLP and AI. Each student will be assigned to a team in the class. Each team is reponsible for delivering multiple code reviews and presenting on research papers throughout the term. Students will then have the opportunity to form their own teams to conduct a month-long research project on a topic of interest that will result in a final paper with the potential to submit to a conference for publication.
</details>

---

## Schedule

| Date                          | Topic|Slides| Readings  | Assignment| Presentation | Notes|
|------------|-----------------------------------------|------------------------------------------------------------------------------------|--------------------------------------------------------------------------|-----------------|--------------|----|
| **Sep 1** | **<span style="color:#8a0317;font-weight:600"> No Class </span> (Labor Day)**              |             
| **Sep 8** | **Introduction**           | [Slides](https://tufts.app.box.com/file/1304995840257?s=tu41828b9wi18h0vhkid727ki0ubfnqg ) | [Working with text in Python3](https://people.cs.georgetown.edu/nschneid/cosc572/s23/02_py-notes.html) <br> SLP3 2.1-2.3,3.1-3.3<br>[NLTK Book3](https://www.nltk.org/book/ch03.html) |        student background survey         |              |
| **Sep 15** | **Language Modeling**        | [Slides] | SLP3:3.1-3.6                   | HW2.1 Out;   <span style="color:#8a0317;font-weight:600"> survey due </span>|    |team assignment; homework logistics; github intro
| **Sep 22**  | **Machine Learning, Naive Bayes**        | [Slides] | SLP3:Chapter 4   |         HW4.1 out        |              |
| **Sep 29** | **Logistic Regression, Deep Neural Networks**    | [Slides] |     SLP3:Chapter 5&7       | HW5.1 out; <span style="color:#8a0317;font-weight:600"> HW2.1 Due </span>         |              | DNN software: Tensorflow Keras
| **Oct 6** | **Word Vectors and Embeddings**     | [Slides]| SLP3:Chapter 6            | HW6.1 out; <span style="color:#8a0317;font-weight:600"> HW4.1 due </span>      |              |
| **Oct 13** | **<span style="color:#8a0317;font-weight:600"> No Class </span> (Indigenous People's Day)**              |                                                                                    |                                                                          |                 |              |
| **Oct 20** | **Sequence Labeling, RNN; LSTM; Attention**;     <span style="color:#8a0317;font-weight:600"> Zoom class </span>            | [Slides] | SLP3: Chapter 8                  | HW9.1 out; <span style="color:#8a0317;font-weight:600"> HW4.1-6.1 due </span>        |              |
| **Oct 27**  | **Tufts HPC; Linguistics;**  <span style="color:#8a0317;font-weight:600"> guest lecturer </span>                   | [Slides] |              |      <span style="color:#8a0317;font-weight:600"> HW9.1 due </span>           |              |
| **Nov 3** | **Self-attention and Transformer**                    | [Slides] | SLP3:Chapter 9                | <span style="color:#8a0317;font-weight:600"> final project proposal due </span>       |              |
| **Nov 10** | **Large Language Models (LLM)** | [slides] |     SLP3: Chapter 10       |        HW11.1 out         |            |
| **Nov 17** | **BERT, GPT, T5**                      | [Slides] | SLP3:Chapter 11             |     <span style="color:#8a0317;font-weight:600"> HW11.1 due </span>  |              |
| **Nov 24**  | **SOTA LLMs and AI agents**                     | [Slides] | SLP3: Chapter 12               |                 |              |
| **Dec 1**  | **Industry Speaker**; <span style="color:#8a0317;font-weight:600"> guest lecturer </span>              | |                |    |              |                                                                                   |                                                                          |                 |              |
| **Dec 8** | **Project Presentations**                   |                                                                                    |                                                                          |       |              |
| **Dec 15** | **Final paper Due**                   |                                                                                    |                                                                          |  <span style="color:#8a0317;font-weight:600"> final paper due </span>     |              |

---

## Resources

- [Course syllabus (PDF)](DATA0297_syllabus_NLP.pdf) 
- [Final project rules](final-proj.md)
- [Textbook: <i>Speech and Language Processing 3rd edition</i> by Jurafsky & Martin (SLP3)](https://web.stanford.edu/~jurafsky/slp3/ed3book_Jan25.pdf)
- [Course Canvas](https://canvas.tufts.edu/courses/67839)
- [Course GitHub](https://github.com/Tufts-University/NLP-Fall25)
- [Tufts academic calendar](https://students.tufts.edu/registrar/courses-and-calendars/academic-calendar)




---

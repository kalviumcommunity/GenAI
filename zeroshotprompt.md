 What is Zero-Shot Prompting?
Zero-shot prompting is when an AI model is asked to perform a task **without being given any examples**.  
Instead of training data or sample outputs, the model only receives **clear instructions** and must generate the response on its own.  


## Application in Study Buddy AI
Our project *Study Buddy AI* uses zero-shot prompting to help students study smarter.  
By providing instructions, we can make the model:  
- Summarize complex topics into **simple bullet points**.  
- Generate **quiz questions**.  
- Explain terms in **simple everyday language**.  
- Convert content into **flashcards** for revision.

- Example 1:

**Prompt:**
You are a helpful study assistant. Summarize the following text in 5 simple bullet points that a college student can easily understand:

"Photosynthesis is the process by which green plants use sunlight to synthesize nutrients from carbon dioxide and water. It generally involves the green pigment chlorophyll and generates oxygen as a by-product."


**Response (Zero-Shot):**
- Plants make their own food using sunlight.  
- They take in carbon dioxide and water.  
- Chlorophyll (a green pigment) helps in the process.  
- Oxygen is released as waste.  
- This process is called photosynthesis.  

Example 2:

**Prompt:**  
You are a study buddy AI. Create 3 multiple-choice quiz questions from the following content. Provide 4 options for each and mark the correct answer clearly.

"Newton’s three laws of motion form the foundation of classical mechanics."


**Response (Zero-Shot):**

**Q1.** Who developed the three laws of motion?  
- A) Albert Einstein  
- B) Isaac Newton ✅  
- C) Galileo Galilei  
- D) Nikola Tesla  

**Q2.** Newton’s laws are the foundation of which field?  
- A) Quantum Mechanics  
- B) Classical Mechanics ✅  
- C) Astrophysics  
- D) Thermodynamics  

**Q3.** How many laws of motion did Newton create?  
- A) 2  
- B) 3 ✅  
- C) 4  
- D) 5  

---


# 🩺 OvaCare AI

An evidence-based multi-agent AI assistant designed to provide educational guidance for women experiencing symptoms related to PCOS/PCOD.

OvaCare AI combines specialized AI agents, clinical reasoning, and retrieval-augmented generation (RAG) to deliver personalized health insights while promoting awareness, early intervention, and informed discussions with healthcare professionals.

---

## 🌸 Why OvaCare AI?

Polycystic Ovary Syndrome (PCOS) affects millions of women worldwide.

Many women experience:

- Irregular menstrual cycles
- Acne
- Hair loss
- Weight gain
- Insulin resistance
- Sleep disturbances
- Stress and anxiety
- Fertility concerns

However, PCOS is not a single-condition disease.

It involves:

- Reproductive health
- Hormonal health
- Metabolic health
- Lifestyle factors
- Mental wellbeing

Traditional prediction models provide only a probability score.

OvaCare AI aims to provide multidisciplinary educational guidance similar to consulting multiple healthcare specialists.

---

# 🎯 Project Objectives

- Improve awareness of PCOS symptoms.
- Encourage early lifestyle interventions.
- Provide evidence-based educational information.
- Help women prepare better questions for healthcare providers.
- Demonstrate the use of Agentic AI in healthcare.

---

# 🏥 Why Multi-Agent AI?

A traditional machine learning model answers:

> "Do I have PCOS?"

Output:

```text
PCOS Probability: 82%
```

But healthcare requires deeper reasoning.

Questions such as:

- Why am I experiencing these symptoms?
- Could stress worsen my condition?
- Is weight gain related?
- How does sleep affect hormones?

require multiple perspectives.

OvaCare AI mimics a multidisciplinary care team.

---

# 🤖 AI Agent Architecture

```text
                User Input
                     │
                     ▼
            Supervisor Agent
                     │
        ┌────────────┼────────────┐
        │            │            │
        ▼            ▼            ▼
 Clinical     Metabolic     Lifestyle
  Agent         Agent         Agent
        │            │            │
        └────────────┼────────────┘
                     ▼
              Planner Agent
                     ▼
              Final Report
```

---

# 🧠 Agents

## 1. Supervisor Agent

Responsible for:

- Understanding patient concerns.
- Selecting relevant specialists.
- Explaining why specialists were chosen.

---

## 2. Clinical Agent

Focus:

- Menstrual health
- Hormonal symptoms
- Fertility concerns
- Gynecological observations

---

## 3. Metabolic Agent

Focus:

- Weight gain
- Insulin resistance
- Blood sugar
- Metabolic health

---

## 4. Lifestyle Agent

Focus:

- Stress
- Sleep
- Exercise
- Nutrition

---

## 5. Planner Agent

Responsible for:

- Combining specialist opinions.
- Generating the final patient report.
- Providing educational guidance.

---

# 📚 Retrieval Augmented Generation (RAG)

OvaCare AI uses RAG to ground responses in medical evidence.

Future knowledge sources include:

- International PCOS Guidelines
- Endocrine Society guidelines
- WHO women's health resources
- Peer-reviewed research papers

RAG improves:

- Accuracy
- Transparency
- Reduced hallucinations
- Evidence-based recommendations

---

# 💻 Technology Stack

| Component | Technology |
|----------|------------|
| Language | Python |
| UI | Streamlit |
| LLM | Gemini 2.5 Flash |
| Framework | Custom Agent Architecture |
| Environment | Python Dotenv |
| PDF Reports | ReportLab |
| Memory | JSON Storage |
| Vector Database | FAISS (planned) |
| Embeddings | Sentence Transformers (planned) |
| RAG | Planned |
| Deployment | Streamlit Cloud (planned) |

---

# 🖥 User Interface

The application allows users to provide:

- Age
- Menstrual cycle information
- Stress level
- Sleep quality
- Additional symptoms

The system then:

1. Routes the case.
2. Runs selected specialists.
3. Generates a final assessment.

---

# 📋 Sample Workflow

```text
Input:

Age: 28
Cycle: Irregular
Stress: High
Sleep: Poor

↓

Supervisor:
Clinical ✓
Lifestyle ✓

↓

Clinical Agent:
Hormonal considerations

Lifestyle Agent:
Stress and sleep recommendations

↓

Final Assessment
```

---

# 🩺 Example Questions

- I have irregular periods and acne.
- I have high stress and poor sleep.
- I am gaining weight and trying to conceive.
- I have hair loss and fatigue.

---

# ⚠ Disclaimer

OvaCare AI is intended for educational purposes only.

It does NOT:

- Diagnose medical conditions.
- Prescribe medications.
- Replace professional medical advice.

Users should consult qualified healthcare professionals for diagnosis and treatment.

---

# 🚀 Future Enhancements

## Retrieval-Augmented Generation (RAG)

- PCOS clinical guidelines
- Research papers
- Medical evidence retrieval

---

## Conversation Memory

Track:

- Symptom progression
- Lifestyle changes
- Previous assessments

---

## PDF Reports

Download personalized assessments.

---

## Risk Scoring

Potential risk categories:

- Low
- Moderate
- High

---

## Data Visualization

Charts for:

- Stress levels
- Sleep quality
- Symptom trends

---

## Authentication

- User accounts
- Secure history
- Long-term monitoring

---

# 🏗 Why Not Traditional Machine Learning?

Traditional models:

- Logistic Regression
- Random Forest
- XGBoost

can predict disease probability.

However, they cannot:

- Explain symptoms.
- Provide multidisciplinary insights.
- Offer personalized recommendations.
- Integrate lifestyle factors.
- Perform conversational reasoning.

OvaCare AI addresses these limitations using agentic AI.

---

# 🎓 Learning Outcomes

This project demonstrates:

- Agentic AI
- Multi-agent systems
- LLM orchestration
- Prompt engineering
- Healthcare AI
- Explainable AI
- Streamlit development
- Retrieval-Augmented Generation
- Human-centered AI design

---

# 👩‍💻 Author

Shrawani Singh

Senior Data Scientist | AI Engineer

Passionate about building AI systems that improve healthcare accessibility and women's health awareness.

---

# ⭐ If you found this project useful, consider giving it a star.
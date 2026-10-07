# English Tutor Agent 🎓

An AI-powered personal English tutor and conversational practice assistant designed for fluent language learning, constructive error correction, and vocabulary enhancement.

---

## 🌟 Key Features

- **Constructive Error Correction**: Analyzes user messages in real time for grammatical accuracy, spelling, syntax, and vocabulary/collocations.
- **Structured Feedback Format**: Automatically formats detected errors with original text, corrected versions, and concise grammatical explanations.
- **100% English Immersion**: Delivers all feedback, explanations, and conversational follow-ups entirely in English.
- **Knowledge-Grounded Learning**:
  - **Priority 1**: Prioritizes reference materials and plain text notes placed inside the `knowledge/` directory.
  - **Priority 2**: Consults authoritative English reference resources (e.g., Cambridge, Oxford, Merriam-Webster).
- **Conversational Continuity**: Engages in natural, supportive dialogues to keep everyday practice engaging.

---

## 📁 Repository Structure

```
├── .agents/
│   └── skills/
│       └── english-tutor/
│           └── SKILL.md       # English Tutor agent skill definition
├── knowledge/
│   └── README.md              # Directory for personal grammar notes and study guides
├── AGENTS.md                  # Workspace agent behavior instructions
├── GEMINI.md                  # IDE/Agent prompt configuration
└── README.md                  # Project documentation
```

---

## 🚀 How to Use

1. **Add Custom Study Material (Optional)**:
   Place plain text files (`.txt`, `.md`) with grammar rules, word lists, or exam prep notes into the `knowledge/` folder.
2. **Chat in English**:
   Start conversations with the agent on any topic. The tutor will:
   - Provide corrections if errors are detected under `[Corrections]`.
   - Omit corrections if your message is error-free.
   - Reply conversationally in English to maintain practice flow.

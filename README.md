# 🧠 AI Study Dashboard

A student command center with an intelligent AI agent that performs detailed searches and provides smart study insights.

## Features

### 📊 Dashboard
- **Today's Overview** — All key metrics at a glance
- **📚 Tasks** — Study tasks with AI-powered prioritization
- **🎯 Goals** — Short and long-term learning goals
- **🧠 Quiz** — Interactive quizzes with AI-generated questions
- **⏱️ Focus Timer** — Pomodoro-style focus sessions
- **📈 Progress** — Visual progress tracking
- **🔥 Streak** — Maintain learning consistency

### 🤖 AI Agent - Detailed Search Mode
When you ask the AI agent to do something, it:
1. **Parses Intent** — Understands what you want to learn or accomplish
2. **Searches Deeply** — Performs comprehensive searches across multiple sources
3. **Connects Concepts** — Creates mind maps showing how topics relate
4. **Provides Context** — Returns detailed explanations with sources
5. **Suggests Next Steps** — Recommends follow-up topics and resources

**Example**: "Help me understand machine learning"
- AI searches ML fundamentals, algorithms, applications
- Builds visual mind map connecting concepts
- Recommends reading materials, tutorials, and practice exercises
- Tracks your learning progress on related topics

### 🧠 Mind Map Visualization
- Visual flow of study topics and connections
- Interactive nodes showing relationships between concepts
- Click to dive deeper into specific topics
- AI generates recommendations based on mind map exploration

### 🗂️ Knowledge Management
- Study materials and notes
- Resource library with AI-indexed content
- Learning history and patterns
- Performance analytics and insights

## Tech Stack

- **Frontend**: React + TypeScript + Tailwind CSS
- **Visualization**: D3.js or Cytoscape.js for mind maps
- **Backend**: Node.js + Express (or Python + FastAPI)
- **AI/Search**: OpenAI API or Local LLM (Ollama)
- **Database**: MongoDB or PostgreSQL
- **Search Engine**: Elasticsearch for detailed searches

## Project Structure

```
ai-study-dashboard/
├── frontend/                 # React dashboard
│   ├── components/
│   │   ├── Dashboard.tsx
│   │   ├── MindMap.tsx
│   │   ├── TaskList.tsx
│   │   ├── Quiz.tsx
│   │   ├── FocusTimer.tsx
│   │   ├── ProgressTracker.tsx
│   │   └── StreakCounter.tsx
│   ├── pages/
│   └── styles/
├── backend/                  # AI Agent & API
│   ├── agents/
│   │   └── studyAgent.ts     # Main AI agent
│   ├── search/
│   │   └── deepSearch.ts     # Detailed search logic
│   ├── mindmap/
│   │   └── generator.ts      # Mind map creation
│   ├── routes/
│   └── models/
├── docs/                     # Documentation
└── README.md
```

## Getting Started

(Setup instructions coming soon)

## Contributing

Contributions welcome! Please open issues for feature requests.

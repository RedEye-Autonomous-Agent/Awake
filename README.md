# RedEye: Awake  
**Next-Generation Autonomous Multi-Agent System**  
Built by **SheikhVix AI Limited** | [RedEye Autonomous Agent](https://github.com/RedEye-Autonomous-Agent/Awake)

---

> **"When others sleep, RedEye builds."**

**RedEye: Awake** is an advanced multi-LLM orchestration framework that empowers AI agents to autonomously **plan**, **build**, **analyze**, and **deploy** —  
powered by **Groq Cloud**, **Cohere Command R**, **Together AI**, and **Hugging Face** integrations.

Designed with performance, modularity, and visualization at its core, RedEye redefines autonomous systems.

---

## Core Highlights

- **Multi-LLM Orchestration**  
  Integrate and dynamically switch between Groq, Together AI, Cohere, and Hugging Face models.

- **Specialized Autonomous Agents**  
  Individual agents execute isolated tasks like coding, testing, validating, and analyzing.

- **No-Code AI Builder**  
  Instantly generate and deploy agents without writing manual code.

- **Live Visualizations**  
  Real-time animated state visualizer showing agent flows, states, and interactions.

- **Fully Modular Architecture**  
  Separate memory, tasks, and workspace for each agent, ensuring isolation and optimization.

- **Security & Scalability**  
  Encrypted memory, token-secured APIs, and horizontally scalable design.

---

## System Architecture

```plaintext
RedEye Core
 ├── Multi-LLM Router
 │     ├── Groq (Llama 3, Mixtral, Gemini)
 │     ├── Together AI (DeepSeek, Zephyr, OpenChat)
 │     ├── Cohere (Command R+)
 │     └── Hugging Face (Custom fine-tunes)
 │
 ├── Planner Agent (task planning)
 ├── Generator Agent (code & content generation)
 ├── Validator Agent (testing & error checking)
 ├── Optimizer Agent (refinement & performance tuning)
 ├── Visualizer (real-time animation of agent state)
 └── Memory Core
       ├── Short-Term Memory
       ├── Long-Term Memory
       └── Task-Based Memory
```

## Technology Stack

| Layer | Technology |
|-------|------------|
| Core Language | TypeScript, Node.js (LTS) |
| Backend | FastAPI, WebSocket, Async Workers |
| Frontend | Next.js 14 (App Router), TailwindCSS, SVG Animation |
| Models | Groq API, Together AI API, Cohere API, Hugging Face Inference |
| Memory | Redis Graph Memory + Encrypted Vector Store |
| Hosting | Vercel, Fly.io, GPU Servers |

## Key Features

### 1. Multi-LLM Smart Router

Automatically selects the optimal LLM based on task type, cost efficiency, and token context.

### 2. Modular Specialized Agents

Each agent operates independently and communicates via secure message queues.

### 3. No-Code Builder

Drag-and-drop or JSON-based agent generation in seconds.

### 4. Visualized Execution

Every action taken by agents is streamed in real-time through animated graphs and flowcharts.

### 5. Secure by Design

Agents run in isolated environments with encrypted memory storage.

## Quick Start

### Clone the Repository

```bash
git clone https://github.com/RedEye-Autonomous-Agent/Awake.git
cd Awake
```

### Install Dependencies

```bash
npm install
```

### Environment Variables

Create your .env file:

```bash
cp .env.example .env
```

Edit .env and add your API keys:

```
GROQ_API_KEY=your_groq_key_here
COHERE_API_KEY=your_cohere_key_here
TOGETHER_API_KEY=your_together_ai_key_here
HF_API_KEY=your_huggingface_key_here
REDEYE_SECRET=your_custom_secret
```

### Run the System

```bash
npm run dev
```

You are now running RedEye locally!

## Project Structure

```
Awake/
 ├── src/
 │    ├── agents/
 │    │    ├── planner.ts
 │    │    ├── generator.ts
 │    │    ├── validator.ts
 │    │    ├── optimizer.ts
 │    ├── memory/
 │    │    ├── shortTerm.ts
 │    │    ├── longTerm.ts
 │    ├── router/
 │    │    ├── modelRouter.ts
 │    ├── visualizer/
 │    │    ├── liveGraph.ts
 │    ├── utils/
 │    │    ├── encryption.ts
 │    └── server.ts
 ├── public/
 │    ├── assets/
 │    ├── animations/
 ├── .env.example
 ├── README.md
 └── package.json
```

## Coming Soon

- **RedEye Studio:**  
  Web-based no-code platform to drag, configure, and deploy agents in real-time.
  
- **Fine-Tuned LLM Support:**  
  RedEye's own specialized lightweight models.
  
- **Agent Market:**  
  Share, buy, or sell custom autonomous agents through decentralized registries.

## Contributing

We welcome contributors!
Please see the CONTRIBUTING.md to get started.

```bash
# Fork, Clone, Create a Feature Branch
git checkout -b feature/your-feature

# Commit and Push
git commit -m "Add your feature"
git push origin feature/your-feature
```

## License

© SheikhVix AI Limited 2025.  
Licensed under the RedEye Autonomous License.

## Connect

- Twitter: [@sheikhvix](https://twitter.com/sheikhvix)
- Website: [sheikhvix.ai](https://sheikhvix.ai) (Coming Soon)
- Discussions: [GitHub Discussions](https://github.com/RedEye-Autonomous-Agent/Awake/discussions)

---

**RedEye: Awake — Always Watching. Always Building.**

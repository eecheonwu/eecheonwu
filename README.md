# Emmanuel Chinyere Echeonwu

**AI Research Engineer & Software Architect**  
Advancing Agentic Software Engineering through intelligent systems design, AI-native architectures, and comprehensive governance frameworks.

---

## 🚀 Featured Projects

### 1. EIP MCP Server — Engineering Intelligence Platform Integration

A **production-ready Model Context Protocol (MCP) server** that bridges local development environments with the **Engineering Intelligence Platform (EIP)** — a modern governance and planning workspace for AI-driven software engineering.

**Repository**: [eecheonwu/eip-mcp-server](https://github.com/eecheonwu/eip-mcp-server)

#### What It Does

The **EIP MCP Server** empowers AI Coding Agents (Claude Desktop, Cursor, Windsurf, Antigravity, and others) to natively interact with your EIP project by:

- **Synchronizing architectural intent** between local development and cloud-based governance
- **Maintaining a Single Source of Truth (SSOT)** across planning, design, and implementation
- **Automating intelligent task generation** from high-level requirements to executable steps
- **Enabling real-time code-to-specification drift detection and resolution**

#### Key Features

- ✅ **Dual-Mode Architecture**: Stdio MCP interface for IDE agents + HTTP webhook listener for cloud-EIP interactions
- ✅ **6 Core Tools**: Initialize SSOT, generate implementation/task/test/security plans, synchronize architecture
- ✅ **Zero-Setup Installation**: Run via `uvx` with no manual virtual environment management
- ✅ **IDE-Agnostic**: Works seamlessly with Claude Desktop, Antigravity, Cursor, Windsurf, and any MCP-compatible IDE
- ✅ **Framework**: Built on [FastMCP](https://github.com/jlowin/fastmcp) with Python 3.10+

#### Quick Start

```bash
# Run the MCP server directly
uvx --from git+https://github.com/eecheonwu/eip-mcp-server.git eip-mcp-server
```

#### IDE Configuration Example (Claude Desktop)

Add to your Claude Desktop config (`~/Library/Application Support/Claude/claude_desktop_config.json` on macOS):

```json
{
  "mcpServers": {
    "eip-mcp-server": {
      "command": "uvx",
      "args": [
        "-q",
        "--from",
        "git+https://github.com/eecheonwu/eip-mcp-server.git",
        "eip-mcp-server"
      ],
      "env": {
        "GEMINI_API_KEY": "your-api-key-here"
      }
    }
  }
}
```

**Full documentation**: See the [EIP MCP Server README](https://github.com/eecheonwu/eip-mcp-server) for comprehensive installation, architecture, and usage details.

---

### 2. SCSE Research Programme — Single Source of Truth–Centric Software Engineering

A comprehensive research program and framework for **SSOT-Centric Software Engineering (SCSE)** — an architectural methodology that uses a Single Source of Truth as the central coordinate system for all engineering artifacts, enabling seamless human–AI collaboration.

#### Core Projects

**SSOT Research Hub**  
[→ Repository](https://github.com/eecheonwu/scse-knowledge-base)  
Comprehensive knowledge base, theoretical foundations, and best practices for SSOT-driven development. Includes research papers, architectural patterns, and design principles.

**SSOT-Centric Framework (Reference Implementation)**  
[→ Repository](https://github.com/eecheonwu/ssot_centric_framework)  
Production-ready implementation of the SCSE methodology. Provides tooling and APIs for:
- Centralizing requirements, architecture, and design decisions
- Automated drift detection between specification and code
- Intelligent task generation from high-level features
- Integration with AI agents for autonomous code generation

**SSOT-Driven Feature Evolution**  
[→ Repository](https://github.com/eecheonwu/SSOT-driven-feature-evolution)  
Workflow framework demonstrating how to evolve features through the SSOT lifecycle — from requirement capture through implementation, testing, and validation.

#### Key Concepts

- **Single Source of Truth (SSOT)**: A unified, authoritative artifact (typically a Software Requirements Document + Architecture Design Record) that serves as the reference for all engineering work
- **Drift Detection**: Real-time identification of divergence between specification and implementation
- **Automated Task Generation**: AI-driven decomposition of high-level features into executable, well-scoped tasks
- **Human–AI Collaboration**: Frameworks enabling developers and AI agents to work seamlessly together

---

## 🎯 Research & Expertise

### Primary Focus: Agentic Software Engineering

I'm researching and building systems that advance **AI-native software engineering** through:

- **SSOT-Centric Software Engineering (SCSE)**: A research program that uses a Single Source of Truth as the central coordinate system for all engineering artifacts
- **Human–AI Collaboration Frameworks**: Workflows and tooling that enable seamless handoff between human developers and AI agents
- **Intelligent Planning & Governance**: Automated requirement parsing, task decomposition, and continuous drift detection
- **Domain-Driven Design for AI Systems**: Applying software architecture principles to AI-native systems

### Core Competencies

**AI & Machine Learning**  
Machine Learning • AI Agents • Large Language Models (LLMs) • Multi-Agent Systems • Prompt Engineering • Context Management

**Software Engineering**  
AI-Native Architecture • Requirement Engineering • Software Testing • Domain-Driven Design • Systems Design • SSOT Frameworks

**Languages & Tools**  
Python • Git • VS Code • FastMCP • FastAPI • LLM APIs (Gemini, OpenAI, Claude)

---

## 📚 Additional Projects

- **cmp**: [Repository](https://github.com/eecheonwu/cmp)
- **clinic_app**: [Repository](https://github.com/eecheonwu/clinic_app)

---

## 🔬 Mission

**Advance Agentic Software Engineering** by creating frameworks, tooling, and workflows that enable human–AI collaboration throughout the entire engineering lifecycle — from planning and design through implementation and testing — with the Single Source of Truth as the central coordinating structure.

---

## 📊 GitHub Activity

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=eecheonwu&show_icons=true&theme=dark)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=eecheonwu&layout=compact&theme=dark)

---

## 🤝 Connect

- **Email**: [ec.echeonwu@gmail.com](mailto:ec.echeonwu@gmail.com)
- **LinkedIn**: [linkedin.com/in/eecheonwu01](https://www.linkedin.com/in/eecheonwu01/)
- **Portfolio**: [about.me/eecheonwu](http://about.me/eecheonwu)

---

*Last updated: August 2026*

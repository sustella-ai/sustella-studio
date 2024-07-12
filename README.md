# Sustella Studio: Sustainable AI with Multi-Agent Systems 👋

![GitHub stars](https://img.shields.io/github/stars/sustella-ai/sustella-studio?style=social)
![GitHub forks](https://img.shields.io/github/forks/sustella-ai/sustella-studio?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/sustella-ai/sustella-studio?style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/sustella-ai/sustella-studio)
![GitHub language count](https://img.shields.io/github/languages/count/sustella-ai/sustella-studio)
![GitHub top language](https://img.shields.io/github/languages/top/sustella-ai/sustella-studio)
![GitHub last commit](https://img.shields.io/github/last-commit/sustella-ai/sustella-studio?color=red)
![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Follama-webui%2Follama-wbui&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)
[![Discord](https://img.shields.io/badge/Discord-Open_WebUI-blue?logo=discord&logoColor=white)](https://discord.gg/5rJgQTnV4s)
[![](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/tjbck)

Welcome to the multi-agent system designed to generate comprehensive reports from unstructured documents and structured SQL databases. This project integrates LLM-based agents and deterministic tools for a variety of tasks, including image classification, time series forecasting, XGBoost, OCR, document extraction, and API handling. The frontend is developed with Svelte, while the backend is powered by Python using OpenWebUI.

## Key Features

- **LLM-Based Agents**: Specialized RAG systems enhance report accuracy by focusing on specific topics.
- **Deterministic Tools**: Provides reliable performance with tools for image classification, time series forecasting, XGBoost, OCR, document extraction, and API handling.
- **Modular Design**: Easily extendable with custom tools and agents for tailored solutions.
- **Seamless Integration**: Combines unstructured documents and SQL databases for cohesive report generation.
- **Svelte Frontend**: Offers a responsive and user-friendly interface.
- **Python Backend**: Ensures robust and scalable backend services.
- **Installation**: Simplified setup with Docker or Kubernetes (kubectl, kustomize, or helm), supporting `:ollama` and `:cuda` tagged images.
- **Ollama/OpenAI Integration**: Integrates OpenAI-compatible APIs for versatile conversations alongside Ollama models. Customize the OpenAI API URL to connect with LMStudio, GroqCloud, Mistral, OpenRouter, and more.
- **Pipelines Plugin Framework**: Integrates custom logic and Python libraries into OpenWebUI. Examples include function calling, user rate limiting, usage monitoring with Langfuse, live translation with LibreTranslate, and toxic message filtering.
- **Responsive Design**: Delivers a seamless experience across Desktop PC, Laptop, and Mobile devices.
- **Progressive Web App (PWA)**: Provides a native app-like experience on mobile devices with offline access and a seamless user interface.
- **Markdown and LaTeX Support**: Full support for enriched interaction through Markdown and LaTeX.
- **Voice/Video Call**: Integrated hands-free voice and video call features for dynamic communication.
- **Model Builder**: Allows easy creation of Ollama models via the Web UI, adding custom characters/agents, and importing models through Open WebUI Community integration.
- **Python Function Calling Tool**: Native Python function support in the tools workspace, allowing seamless integration with LLMs.
- **Local RAG Integration**: Integrates document interactions into chat experiences with Retrieval Augmented Generation (RAG). Load documents directly into the chat or add files to your document library for easy access.
- **Web Search for RAG**: Performs web searches using various providers and injects results directly into your chat.
- **Web Browsing Capability**: Integrates web content directly into conversations.
- **Image Generation**: Incorporates image generation capabilities using options like AUTOMATIC1111 API, ComfyUI, and OpenAI's DALL-E for dynamic visual content.
- **Multi-Model Conversations**: Engages with multiple models simultaneously, leveraging their unique strengths for optimal responses.
- **Role-Based Access Control (RBAC)**: Ensures secure access with restricted permissions for authorized individuals only.
- **Multilingual Support**: Offers internationalization (i18n) support for user preference in various languages.
- **Regular Updates**: Committed to providing regular updates, fixes, and new features to enhance OpenWebUI.

For more information about our features, visit our [Open WebUI documentation](https://docs.openwebui.com/features) for a comprehensive overview!

## Installation

### Prerequisites

- Docker
- Python 3.8+
- Node.js
- rye

### Quick Start

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/sustella-ai/sustella-studio.git
    cd sustella-studio
    ```

2. **Build the Project**:

    ```sh
    rye sync
    ```

3. **Run for Development**:

    ```sh
    rye run sustella-studio dev
    ```

4. **Run Docker**:

    ```sh
    docker compose up -d
    ```

Access the application at `http://localhost:3000`.

## Contributing

We welcome contributions! Please read our [Contributing Guide](CONTRIBUTING.md) for details on the process for submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to the original repo [open-webui/open-webui](https://github.com/open-webui/open-webui) for providing a strong foundation.

## Support

For any questions or suggestions, please open an issue or join our [Discord community](https://discord.gg/yourdiscordinvite).

## Star History

<a href="https://star-history.com/#open-webui/open-webui&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />
  </picture>
</a>

---
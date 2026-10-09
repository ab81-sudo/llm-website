# Agent-First Web Sandbox

An experimental, machine-readable website designed to explore web standards optimized for autonomous AI agents. This repository hosts the source files for a static site that prioritizes semantic markdown, agent routing protocols, and machine-to-machine micropayments over human-centric CSS, dynamic DOM trees, and heavy JavaScript.

## Core Features

* **Agent Routing (`llms.txt` & `llms-full.txt`):** Provides a clean, distraction-free map of the site's endpoints and concatenates context for single-shot ingestion.
* **Markdown Content (`about.md`):** Serves core site information in raw markdown, making it instantly readable for Large Language Models.
* **Simulated x402 Protocol:** Includes an experimental `/donate` endpoint mockup designed to issue an `HTTP 402 Payment Required` challenge to test automated, on-chain stablecoin transactions.

## File Structure

* `index.html` - The human-readable frontend interface and interactive x402 payment simulator.
* `llms.txt` - The agent-optimized table of contents and navigation map.
* `llms-full.txt` - The complete site bundle, concatenating all documentation for large-context models.
* `about.md` - The project's mission statement, architecture overview, and agent directives.

## Deployment

This project is fully static and designed to be hosted for free on **GitHub Pages**. 
    
1. Upload these files to your GitHub repository.
2. Go to your repository **Settings**.
3. Navigate to **Pages** in the left sidebar.
4. Under "Build and deployment", set the source to deploy from a branch.
5. Select your `main` branch and click **Save**. 
6. Your agent-optimized site will be live within a few minutes.

## Future Roadmap

- [ ] **Model Context Protocol (MCP):** Build a server interface to allow AI models to interact with dynamic site features securely.
- [ ] **Live On-Chain Settlement:** Transition the x402 simulator to an active blockchain facilitator to accept live USDC micro-donations on the Base network.

## License

This project is open-source and available under the [MIT License](LICENSE).
# AI Red Teaming Portfolio

Documenting my work testing LLM security vulnerabilities. These attacks were conducted for educational purposes and responsible disclosure.

## About Me

Red teamer focused on AI safety and security. Background in prompt injection, jailbreaking, and bias detection. Trained through Mercor Red Teaming Academy and DeepLearning.AI coursework.

## Attacks

| # | Target | Category | Result |
|---|--------|----------|--------|
| [01](attacks/01-meta-ai-misinformation-roleplay.md) | Meta AI | Misinformation / Hate Speech | Success |
| [02](attacks/02-chatgpt-prompt-injection.md) | ChatGPT | Prompt Injection | Success |
| [03](attacks/03-chatgpt-gender-bias-multiturn.md) | ChatGPT | Gender Bias | Success |
| [04](attacks/04-llama-automated-injection.md) | Llama 3.2 (Local) | Automated Testing | 2/5 Success |
| [05](attacks/05-gandalf-lakera-challenge.md) | Gandalf (Lakera) | CTF Challenge | 7/7 Levels |

## Techniques

**Manual Attacks:**
- Roleplay and fictional framing
- Fake system prompt formatting
- Multi-turn bias elicitation
- Encoding bypasses (reverse, Base64, ASCII)
- Character-by-character extraction

**Automated Testing:**
- Python scripting against local LLMs via Ollama
- Batch prompt injection testing
- Results analysis and documentation

## Tools

- Ollama (local LLM hosting)
- Python + Requests
- ChatGPT, Meta AI, Llama 3.2
- Gandalf by Lakera (CTF platform)

## Contact

Open to red teaming opportunities and AI security roles.

GitHub: [ciarcellutidomenico-stack](https://github.com/ciarcellutidomenico-stack)

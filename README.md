## From Text To XML SLA in the 5G domain: Résumé

Service Level Agreements (SLAs) play a critical role in 5G ecosystems, formalizing commitments between providers and customers to ensure compliance with performance metrics and Quality of Service (QoS) requirements. However, the lack of standardized, user-friendly tools for defining and customizing 5G-specific SLAs in machine-readable formats, such as XML, hinders automation and interoperability in service management. To address this challenge, we propose a formal approach based on the Event-B method to model SLA components and enforce their correctness and reliability.  To validate our approach, we present a case study demonstrating the automated creation and verification of 5G SLAs. The results highlight the effectiveness of our methodology in enhancing automation, compliance, and interoperability in 5G service management.

## Evaluation

To evaluate the effectiveness of the proposed approach, we conducted a comparative analysis using AI-generated 5G SLAs examples. Specifically, we leveraged four advanced AI models: Google Gemini, Microsoft Copilot, OpenAI’s ChatGPT, and DeepSeek, to generate diverse and representative 5G SLA documents. This allowed us to assess the quality, and comprehensiveness of our approach to the proposed tool of SLA XML generation across different AI platforms, providing a robust benchmark for our its application in the 5G domain.

### Table 1: Match Rate and Average Time per Match for AI-generated 5G SLA Examples

| 5G SLA Generation Models | Average Time per Match (seconds) | Match Rate |
|--------------------------|----------------------------------|------------|
| Google Gemini            | 1.5 × 10⁻⁴                       | 100%       |
| Microsoft Copilot        | 8.2 × 10⁻⁵                       | 93.75%     |
| ChatGPT                  | 1.02 × 10⁻⁴                      | 96.15%     |
| DeepSeek                 | 1.7 × 10⁻⁴                       | 100%       |


### Table 2: Used Evaluation Metrics

| Models Utilized for 5G SLA Generation | Precision | Recall | F1-score |
|---------------------------------------|-----------|--------|----------|
| Google Gemini                         | 0.909     | 0.721  | 0.804    |
| Microsoft Copilot                     | 0.804     | 0.666  | 0.729    |
| ChatGPT                               | 0.914     | 0.680  | 0.780    |
| DeepSeek                              | 0.802     | 0.844  | 0.822    |





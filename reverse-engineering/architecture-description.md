Here’s a series of prompts to generate an architecture description from a GitHub repository. These prompts are designed to be used sequentially to build a comprehensive report.




# Prerequisite
Add your repo to the context of the LLM agent/chat. It's possible that all the prompts do not work on the same repo, for example deployment or infra related info might be in another repo, so make sure the prompts are relevant to the information/code that is in the repo being analyzed.

# Prompt 1: Introduction
```
Analyze the GitHub repository [REPO_URL] and generate an introduction for the architecture description. Include:
- The purpose of the architecture description.
- The scope of the architecture.
- Key stakeholders and their roles.
```

# Prompt 2: Context
```
Analyze the GitHub repository [REPO_URL] and generate the context section for the architecture description. Include:
- Business context: Explain the business goals and objectives that the architecture supports.
- Operational context: Describe the operational environment in which the software or service will operate.
- Technical context: Outline the technical environment, including dependencies on other systems and technologies.
```

# Prompt 3: Architecture Overview
```
Analyze the GitHub repository [REPO_URL] and generate the architecture overview section for the architecture description. Include:
- Architecture vision: Provide a high-level vision of the architecture.
- Architecture principles: List the guiding principles that the architecture adheres to.
- Architecture styles: Describe the architectural styles and patterns used (e.g., microservices, monolithic, event-driven).
```

# Prompt 4: Components and Structure
```
Analyze the GitHub repository [REPO_URL] and generate the components and structure section for the architecture description. Include:
- Core components: Identify and describe the main components of the architecture.
- Modules and services: Detail the modules, services, and their interactions in a table format.
- Data flow: Illustrate the data flow between components and generate a draw.io data flow diagram.
- Data models: Provide data models and entity-relationship diagrams if applicable, in draw.io format.
- Interfaces: Describe the interfaces between components and with external systems and generate a draw.io mermaid diagram.
- Sequence diagrams: Include sequence diagrams for key interactions in draw.io format.
```

# Prompt 5: Technology Stack
```
Analyze the GitHub repository [REPO_URL] and generate the technology stack section for the architecture description. Include:
- Programming languages: List the programming languages used, and versions as a table.
- Frameworks and libraries: Detail the frameworks and libraries employed and versions as a table.
- Databases: Describe the databases and data storage solutions as a table.
- Middleware: Explain any middleware used for communication and integration as a table.
```

# Prompt 6: Deployment and Infrastructure
```
Analyze the GitHub repository [REPO_URL] and generate the deployment and infrastructure section for the architecture description. Include:
- Deployment model: Describe how the software or service is deployed (e.g., cloud, on-premises).
- Infrastructure: Detail the infrastructure components (e.g., servers, network, storage).
- Containerization: If applicable, describe the use of containers (e.g., Docker) and orchestration (e.g., Kubernetes).
- Generate a CI/CI pipeline draw.io diagram.
```

# Prompt 7: Security
```
Analyze the GitHub repository [REPO_URL] and generate the security section for the architecture description. Include:
- Security requirements: List the security requirements and constraints.
- Authentication and authorization: Describe the mechanisms for authentication and authorization.
- Data protection: Explain how data is protected in transit and at rest.
- Threat modeling: Outline the threat model and mitigation strategies.
```

# Prompt 8: Performance and Scalability
```
Analyze the GitHub repository [REPO_URL] and generate the performance and scalability section for the architecture description. Include:
- Performance requirements: Define the performance requirements (e.g., response time, throughput) as a table.
- Scalability strategies: Describe how the architecture supports scaling (e.g., horizontal vs. vertical scaling), generate a draw.io diagram.
```

# Prompt 9: Reliability and Availability
```
Analyze the GitHub repository [REPO_URL] and generate the reliability and availability section for the architecture description. Include:
- Reliability requirements: List the reliability requirements (e.g., uptime, fault tolerance).
- Availability strategies: Explain the strategies for ensuring high availability (e.g., redundancy, failover mechanisms).
```

# Prompt 10: Maintainability and Extensibility
```
Analyze the GitHub repository [REPO_URL] and generate the maintainability and extensibility section for the architecture description. Include:
- Maintainability: Describe how the architecture supports maintainability (e.g., modular design, documentation).
- Extensibility: Explain how the architecture allows for future extensions and modifications.
```

# Prompt 11: Governance and Compliance
```
Analyze the GitHub repository [REPO_URL] and generate the governance and compliance section for the architecture description. Include:
- Governance model: Describe the governance model for the architecture.
- Compliance requirements: List any compliance requirements and how the architecture meets them.
```

# Prompt 12: Dependencies and Integrations
```
Analyze the GitHub repository [REPO_URL] and generate the dependencies and integrations section for the architecture description. Include:
- External dependencies: List external systems and services the architecture depends on.
- Integration points: Describe how the architecture integrates with other systems.
- Generate a draw.io mermaid diagram
```

# Prompt 12: Dependencies and Integrations
```
Analyze the GitHub repository [REPO_URL] and generate the dependencies and integrations section for the architecture description. Include:
- External dependencies: List external systems and services the architecture depends on.
- Integration points: Describe how the architecture integrates with other systems.
- Generate a draw.io mermaid diagram
```

# Optional: Prompt 13: Evolution and Roadmap
```
Analyze the GitHub repository [REPO_URL] and generate the evolution and roadmap section for the architecture description. Include:
- Future enhancements: Outline planned future enhancements and their impact on the architecture.
- Roadmap: Provide a high-level roadmap for the architecture’s evolution.
```

# Prompt 15: Conclusion
```
Analyze the GitHub repository [REPO_URL] and generate the conclusion section for the architecture description. Include:
- Summary: Summarize the key points of the architecture description.
- Next steps: Outline the next steps for implementing and maintaining the architecture.
```

There you go. Happy reverse-engineering!

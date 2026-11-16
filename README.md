### Bharat Bhushan

AI engineering leader. I build production GenAI platforms: LLM and RAG platforms, MCP, multi-agent systems and agent harnesses, on 10+ years of backend engineering in Java, Kotlin and Python.

[LinkedIn](https://www.linkedin.com/in/bharat-bhushan-ai/)

#### Projects

- **[OpenProgram](https://github.com/bharatnpti/OpenProgram)**: an agentic program-management system. It collects delivery status through short conversational check-ins in Slack, cross-checks the answers against Jira, Git and calendar signals, and rolls them up from task to program. [Demo video](https://github.com/bharatnpti/OpenProgram#demo-videos).
- **[langgraph-write-ownership](https://github.com/bharatnpti/langgraph-write-ownership)**: a minimal reproduction of checkpoint corruption caused by concurrent writers in LangGraph, plus a proposed conformance capability, filed upstream.
- **[lmos-cli](https://github.com/bharatnpti/lmos-cli)**: a prototype CLI for Eclipse LMOS in Kotlin, Quarkus and Picocli. It scaffolds Arc agent projects and keeps LLM configs in the macOS keychain behind a pluggable credential-manager interface.
- **[mattermost-spring-mcp](https://github.com/bharatnpti/mattermost-spring-mcp)**: an MCP server, built on Spring AI, that lets LLM agents read users, post, reply in threads and open DMs in Mattermost.

#### Open source

- **[Eclipse LMOS](https://github.com/eclipse-lmos)**, an open-source multi-agent platform: 22 merged PRs across `lmos-runtime`, `arc`, `lmos-router`, `lmos-demo` and `lmos-sample-agents`. They include
  the runtime's modular, multi-module architecture ([#46](https://github.com/eclipse-lmos/lmos-runtime/pull/46), [#68](https://github.com/eclipse-lmos/lmos-runtime/pull/68)),
  a file-based agent registry ([#167](https://github.com/eclipse-lmos/lmos-runtime/pull/167), [#179](https://github.com/eclipse-lmos/lmos-runtime/pull/179)),
  configurable CORS ([#71](https://github.com/eclipse-lmos/lmos-runtime/pull/71)),
  and tool calling for Ollama in Arc ([arc#91](https://github.com/eclipse-lmos/arc/pull/91)).
- **[Parlant](https://github.com/emcie-co/parlant)**: Azure AD authentication for the Azure OpenAI service ([#564](https://github.com/emcie-co/parlant/pull/564)).
- **[WireMock](https://github.com/wiremock/wiremock)** (7.4k★, the standard Java HTTP-mocking library): proposed ([#2331](https://github.com/wiremock/wiremock/issues/2331)) and built ([#2334](https://github.com/wiremock/wiremock/pull/2334)) the `MappingsLoaderExtension` extension point, shipped in [WireMock 3.2.0](https://github.com/wiremock/wiremock/releases/tag/3.2.0). Teams can now load stub mappings from Git, a database or any other source through a plugin, instead of forking WireMock. I also wrote the official guide, [Adding a mappings loader](https://wiremock.org/docs/extensibility/adding-mappings-loader/) ([wiremock.org#181](https://github.com/wiremock/wiremock.org/pull/181)).

#### Stack

- **GenAI:** LangGraph · LangChain · Spring AI · LangChain4j · Claude Agent SDK · MCP · RAG · Qdrant · Neo4j · OpenSearch · Ollama · OpenTelemetry
- **Backend:** Java · Kotlin · Python · Spring Boot · Quarkus · Kafka · Kubernetes · Temporal · PostgreSQL · Redis

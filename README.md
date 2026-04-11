# Curated MCP Servers

<p align="center">
  <img src="assets/banner.svg" alt="Curated MCP Servers" width="800">
</p>

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/awesome-ai-tools/curated-mcp-servers/pulls)
[![GitHub stars](https://img.shields.io/github/stars/awesome-ai-tools/curated-mcp-servers?style=social)](https://github.com/awesome-ai-tools/curated-mcp-servers/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/awesome-ai-tools/curated-mcp-servers)](https://github.com/awesome-ai-tools/curated-mcp-servers/commits/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A community-curated list of **Model Context Protocol (MCP) servers** — the open standard for connecting AI assistants to external tools, data sources, and APIs. Unlike other lists, **we welcome community contributions via pull requests**.

> [!TIP]
> PRs are welcome! If you'd like to add an MCP server, please read our [Contributing Guide](CONTRIBUTING.md) and open a pull request.

> [!NOTE]
> Originally based on [awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) by wong2 (MIT License).

## Contents

- [Featured](#featured)
- [Recently Added](#recently-added)
- [Reference Servers](#reference-servers)
- [Official Servers](#official-servers)
  - [Database & Data](#database--data)
  - [AI & Machine Learning](#ai--machine-learning)
  - [Developer Tools & DevOps](#developer-tools--devops)
  - [Cloud & Infrastructure](#cloud--infrastructure)
  - [Content & Media](#content--media)
  - [Finance & Payments](#finance--payments)
  - [Social Media & Communication](#social-media--communication)
  - [Search & Web](#search--web)
  - [Productivity & Business](#productivity--business)
  - [Security & Compliance](#security--compliance)
  - [Analytics & Monitoring](#analytics--monitoring)
  - [Other](#other)
- [Community Servers](#community-servers)
  - [Database & Data](#database--data-1)
  - [AI & Machine Learning](#ai--machine-learning-1)
  - [Developer Tools & DevOps](#developer-tools--devops-1)
  - [Cloud & Infrastructure](#cloud--infrastructure-1)
  - [Content & Media](#content--media-1)
  - [Finance & Payments](#finance--payments-1)
  - [Social Media & Communication](#social-media--communication-1)
  - [Search & Web](#search--web-1)
  - [Productivity & Business](#productivity--business-1)
  - [Security & Compliance](#security--compliance-1)
  - [Analytics & Monitoring](#analytics--monitoring-1)
  - [Other](#other-1)
- [Clients](#clients)
- [Frameworks](#frameworks)
- [Related Lists](#related-lists)

## Featured

<table>
  <tr>
    <td align="center" width="200">
      <a href="https://www.ssemble.com">
        <img src="https://www.ssemble.com/favicon.ico" width="60" alt="Ssemble Logo">
      </a>
    </td>
    <td>
      <a href="https://www.npmjs.com/package/@ssemble/mcp-server"><b>Ssemble AI Clipping</b></a><br>
      Create AI-powered short-form video clips from YouTube videos. 9 tools for creating shorts, browsing caption templates, background music, gameplay overlays, and meme hooks. Supports both local (npx) and hosted endpoint (mcp.ssemble.com).<br>
      <a href="https://www.ssemble.com">Website</a> · <a href="https://www.npmjs.com/package/@ssemble/mcp-server">GitHub</a>
    </td>
  </tr>
</table>

## Recently Added

> Last updated: March 2026

- **[Ssemble AI Clipping](https://www.npmjs.com/package/@ssemble/mcp-server)** - Create AI-powered short-form video clips from YouTube videos
- **[GitHub](https://github.com/github/github-mcp-server)** - GitHub's official MCP Server
- **[Playwright](https://github.com/microsoft/playwright-mcp)** - Playwright MCP server
- **[Google Cloud Run](https://github.com/GoogleCloudPlatform/cloud-run-mcp)** - Official MCP Server to deploy to Google Cloud Run
- **[Zapier](https://zapier.com/mcp)** - Connect your AI Agents to 8,000 apps instantly

## Reference Servers

These servers aim to demonstrate MCP features and the TypeScript and Python SDKs.

- **[Everything](https://github.com/modelcontextprotocol/servers/blob/main/src/everything)** - Reference / test server with prompts, resources, and tools
- **[Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch)** - Web content fetching and conversion for efficient LLM usage
- **[Filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem)** - Secure file operations with configurable access controls
- **[Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git)** - Tools to read, search, and manipulate Git repositories
- **[Memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory)** - Knowledge graph-based persistent memory system
- **[Sequential Thinking](https://github.com/modelcontextprotocol/servers/tree/main/src/sequentialthinking)** - Dynamic and reflective problem-solving through thought sequences
- **[Time](https://github.com/modelcontextprotocol/servers/blob/main/src/time)** - Time and timezone conversion capabilities

## Official Servers

Official integrations are maintained by companies building production ready MCP servers for their platforms.

### Database & Data

- **[Aiven](https://github.com/Aiven-Open/mcp-aiven)** - Navigate your [Aiven projects](https://go.aiven.io/mcp-server) and interact with the PostgreSQL®, Apache Kafka®, ClickHouse® and OpenSearch® services
- **[Apache Doris](https://github.com/apache/doris-mcp-server)** - MCP Server For [Apache Doris](https://doris.apache.org/), an MPP-based real-time data warehouse.
- **[Atlan](https://github.com/atlanhq/agent-toolkit/tree/main/modelcontextprotocol)** - Official MCP Server from [Atlan](https://atlan.com) which enables you to bring the power of metadata to your AI tools
- **[Baserow](https://baserow.io/user-docs/mcp-server)** - Read and write access to your Baserow tables.
- **[Chroma](https://github.com/chroma-core/chroma-mcp)** - Embeddings, vector search, document storage, and full-text search with the open-source AI application database
- **[ClickHouse](https://github.com/ClickHouse/mcp-clickhouse)** - Query your [ClickHouse](https://clickhouse.com/) database server.
- **[Convex](https://stack.convex.dev/convex-mcp-server)** - Introspect and query your apps deployed to Convex.
- **[Coresignal](https://github.com/Coresignal-com/coresignal-mcp/)** - Access comprehensive B2B data on companies, employees, and job postings for your LLMs and AI workflows.
- **[Couchbase](https://github.com/Couchbase-Ecosystem/mcp-server-couchbase)** - Interact with the data stored in Couchbase clusters using natural language.
- **[DataWorks](https://github.com/aliyun/alibabacloud-dataworks-mcp-server)** - A Model Context Protocol (MCP) server that provides tools for AI, allowing it to interact with the DataWorks Open API through a standardized interface. This implementation is based on the Aliyun Open API and enables AI agents to perform cloud resources operations seamlessly.
- **[dbt](https://github.com/dbt-labs/dbt-mcp)** - Official MCP server for [dbt (data build tool)](https://www.getdbt.com/product/what-is-dbt) providing integration with dbt Core/Cloud CLI, project metadata discovery, model information, and semantic layer querying capabilities.
- **[DreamFactory](https://github.com/dreamfactorysoftware/df-mcp/)** - An MCP server for securely (via RBAC) talking to on-premise and cloud MS SQL Server, MySQL, PostgreSQL databases and other data sources.
- **[Fireproof](https://github.com/fireproof-storage/mcp-database-server)** - Immutable ledger database with live synchronization
- **[GreptimeDB](https://github.com/GreptimeTeam/greptimedb-mcp-server)** - Provides AI assistants with a secure and structured way to explore and analyze data in [GreptimeDB](https://github.com/GreptimeTeam/greptimedb).
- **[Hologres](https://github.com/aliyun/alibabacloud-hologres-mcp-server)** - Connect to a [Hologres](https://www.alibabacloud.com/en/product/hologres) instance, get table metadata, query and analyze data.
- **[Hydrolix](https://github.com/hydrolix/mcp-hydrolix)** - Hydrolix time-series datalake integration providing schema exploration and query capabilities to LLM-based workflows.
- **[InstantDB](https://github.com/instantdb/instant/tree/main/client/packages/mcp)** - Create, manage, and update applications on InstantDB, the modern Firebase.
- **[Jetty.io](https://github.com/jettyio/mlcbakery/tree/main/mcp_server)** — Work on dataset metadata with MLCommons Croissant validation and creation.
- **[Keboola](https://github.com/keboola/keboola-mcp-server)** - Build robust data workflows, integrations, and analytics on a single intuitive platform.
- **[MCP Toolbox for Databases](https://github.com/googleapis/genai-toolbox)** - Open source MCP server specializing in easy, fast, and secure tools for Databases.
- **[Meilisearch](https://github.com/meilisearch/meilisearch-mcp)** - Interact & query with Meilisearch (Full-text & semantic search API)
- **[Milvus](https://github.com/zilliztech/mcp-server-milvus)** - Search, Query and interact with data in your Milvus Vector Database.
- **[MotherDuck](https://github.com/motherduckdb/mcp-server-motherduck)** - Query and analyze data with MotherDuck and local DuckDB
- **[Neo4j](https://github.com/neo4j-contrib/mcp-neo4j/)** - Neo4j graph database server (schema + read/write-cypher) and separate graph database backed memory
- **[Neon](https://github.com/neondatabase/mcp-server-neon)** - Interact with the Neon serverless Postgres platform
- **[OceanBase](https://github.com/oceanbase/mcp-oceanbase)** - MCP Server for OceanBase database and its tools
- **[Powerdrill](https://github.com/powerdrillai/powerdrill-mcp)** - An MCP server that provides tools to interact with Powerdrill datasets, enabling smart AI data analysis and insights.
- **[Prisma Postgres](https://github.com/prisma/mcp)** - Gives LLMs the ability to manage Prisma Postgres databases (e.g. spin up new databases and run migrations or queries)
- **[Qdrant](https://github.com/qdrant/mcp-server-qdrant/)** - Implement semantic memory layer on top of the Qdrant vector search engine
- **[SingleStore](https://github.com/singlestore-labs/mcp-server-singlestore)** - Interact with the SingleStore database platform
- **[StarRocks](https://github.com/StarRocks/mcp-server-starrocks)** - Interact with [StarRocks](https://www.starrocks.io/)
- **[Supabase](https://github.com/supabase-community/supabase-mcp)** - Connects to Supabase platform for database, auth, edge functions and more.
- **[Teradata](https://github.com/Teradata/teradata-mcp-server)** - A collection of tools for managing the platform, addressing data quality and reading and writing to [Teradata](https://www.teradata.com/) Database.
- **[Tinybird](https://github.com/tinybirdco/mcp-tinybird)** - Interact with Tinybird serverless ClickHouse platform
- **[Unstructured](https://github.com/Unstructured-IO/UNS-MCP)** - Set up and interact with your unstructured data processing workflows in [Unstructured Platform](https://unstructured.io)
- **[Verodat](https://github.com/Verodat/verodat-mcp-server)** - Interact with Verodat AI Ready Data platform

### AI & Machine Learning

- **[AllVoiceLab](https://www.allvoicelab.com/mcp)** - An AI voice toolkit with TTS, voice cloning, and video translation, now available as an MCP server for smarter agent integration.
- **[Atla](https://github.com/atla-ai/atla-mcp-server)** - Enable AI agents to interact with the [Atla API](https://docs.atla-ai.com/) for state-of-the-art LLMJ evaluation.
- **[AWS Bedrock KB Retrieval](https://github.com/awslabs/mcp/tree/main/src/bedrock-kb-retrieval-mcp-server)** - Query Amazon Bedrock Knowledge Bases using natural language to retrieve relevant information from your data sources.
- **[AWS Nova Canvas](https://github.com/awslabs/mcp/tree/main/src/nova-canvas-mcp-server)** - Generate images using Amazon Nova Canvas with text prompts and color guidance.
- **[Chronulus AI](https://github.com/ChronulusAI/chronulus-mcp)** - Predict anything with Chronulus AI forecasting and prediction agents.
- **[Cua](https://github.com/trycua/cua/tree/main/libs/mcp-server)** - MCP server for the Computer-Use Agent (CUA), allowing you to run CUA through Claude Desktop or other MCP clients.
- **[DAISYS](https://github.com/daisys-ai/daisys-mcp)** - Generate high-quality text-to-speech and text-to-voice outputs using the [DAISYS](https://www.daisys.ai/) platform.
- **[DeepResearch](https://github.com/OctagonAI/octagon-deep-research-mcp)** - Lightning-Fast, High-Accuracy Deep Research Agent 👉 8–10x faster 👉 Greater depth & accuracy 👉 Unlimited parallel runs
- **[DeepWiki by Devin](https://docs.devin.ai/work-with-devin/deepwiki-mcp)** - Remote, no-auth MCP server providing AI-powered codebase context and answers
- **[DINO-X](https://github.com/IDEA-Research/DINO-X-MCP)** - Advanced computer vision and object detection MCP server powered by Dino-X, enabling AI agents to analyze images, detect objects, identify keypoints, and perform visual understanding tasks.
- **[ElevenLabs](https://github.com/elevenlabs/elevenlabs-mcp)** - The official ElevenLabs MCP server
- **[Graphlit](https://github.com/graphlit/graphlit-mcp-server)** - Ingest anything from Slack to Gmail to podcast feeds, in addition to web crawling, into a searchable [Graphlit](https://www.graphlit.com) project.
- **[IBM wxflows](https://github.com/IBM/wxflows/tree/main/examples/mcp/javascript)** - Tool platform by IBM to build, test and deploy tools for any data source
- **[Inkeep](https://github.com/inkeep/mcp-server-python)** - RAG Search over your content powered by [Inkeep](https://inkeep.com)
- **[Langfuse Prompt Management](https://github.com/langfuse/mcp-server-langfuse)** - Open-source tool for collaborative editing, versioning, evaluating, and releasing prompts.
- **[Lingo.dev](https://github.com/lingodotdev/lingo.dev/blob/main/mcp.md)** - Make your AI agent speak every language on the planet, using [Lingo.dev](https://lingo.dev) Localization Engine.
- **[Needle](https://github.com/needle-ai/needle-mcp)** - Production-ready RAG out of the box to search and retrieve data from your own documents.
- **[Nebula-Block-Data/nebulablock-mcp-server](https://github.com/Nebula-Block-Data/nebulablock-mcp-server)** integrates with the fastmcp library to expose the full range of NebulaBlock API functionalities as accessible tools
- **[PaddleOCR](https://paddlepaddle.github.io/PaddleOCR/latest/en/version3.x/deployment/mcp_server.html)** - An MCP server that brings enterprise-grade OCR and document parsing capabilities to AI applications.
- **[Reexpress](https://github.com/ReexpressAI/reexpress_mcp_server)** - Enable Similarity-Distance-Magnitude statistical verification for your search, software, and data science workflows
- **[Root Signals](https://github.com/root-signals/root-signals-mcp)** - Equip AI agents with evaluation and self-improvement capabilities with [Root Signals](https://www.rootsignals.ai/)
- **[UnifAI](https://github.com/unifai-network/unifai-mcp-server)** - Dynamically search and call tools using [UnifAI Network](https://unifai.network)
- **[Vectorize](https://github.com/vectorize-io/vectorize-mcp-server/)** - [Vectorize](https://vectorize.io) MCP server for advanced retrieval, Private Deep Research, Anything-to-Markdown file extraction and text chunking.
- **[Winston AI](https://github.com/gowinston-ai/winston-ai-mcp-server)** - AI detector MCP server with industry leading accuracy rates in detecting use of AI in text and images. The [Winston AI](https://gowinston.ai) MCP server also offers a robust plagiarism checker to help maintain integrity.
- **[ZenML](https://github.com/zenml-io/mcp-zenml)** - Interact with your MLOps and LLMOps pipelines through your [ZenML](https://www.zenml.io) MCP server

### Developer Tools & DevOps

- **[AgentRPC](https://github.com/agentrpc/agentrpc)** - Connect to any function, any language, across network boundaries using [AgentRPC](https://www.agentrpc.com/).
- **[AlibabaCloud DevOps MCP](https://github.com/aliyun/alibabacloud-devops-mcp-server)** - Yunxiao MCP Server provides AI assistants with the ability to interact with the [Yunxiao platform](https://devops.aliyun.com).
- **[APIMatic MCP](https://github.com/apimatic/apimatic-validator-mcp)** - APIMatic MCP Server is used to validate OpenAPI specifications using [APIMatic](https://www.apimatic.io/). The server processes OpenAPI files and returns validation summaries by leveraging APIMatic's API.
- **[Augments](https://augments.dev/)** - Comprehensive framework documentation and code examples for popular development tools and libraries.
- **[AWS CDK](https://github.com/awslabs/mcp/tree/main/src/cdk-mcp-server)** - Get prescriptive CDK advice, explain CDK Nag rules, check suppressions, generate Bedrock Agent schemas, and discover AWS Solutions Constructs patterns.
- **[Azure DevOps](https://github.com/microsoft/azure-devops-mcp)** - The MCP server for Azure DevOps, bringing the power of Azure DevOps directly to your agents.
- **[Buildkite](https://github.com/buildkite/buildkite-mcp-server)** - Manage [Buildkite](https://buildkite.com) pipelines and builds.
- **[Chroma Package Search](https://trychroma.com/package-search)** - Add to coding agents like Claude or Cursor to give them the ability to understand and better use thousands of dependencies.
- **[CircleCI](https://github.com/CircleCI-Public/mcp-server-circleci)** - Enable AI Agents to fix build failures from CircleCI.
- **[Context 7](https://github.com/upstash/context7-mcp)** - Context7 MCP - Up-to-date Docs For Any Cursor Prompt
- **[Currents](https://github.com/currents-dev/currents-mcp)** - Enable AI Agents to fix Playwright test failures reported to [Currents](https://currents.dev).
- **[Debugg AI](https://github.com/debugg-ai/debugg-ai-mcp)** - Enable your code gen agents to create & run 0-config end-to-end tests against new code changes in remote browsers via the [Debugg AI](https://debugg.ai) testing platform.
- **[E2B](https://github.com/e2b-dev/mcp-server)** - Run code in secure sandboxes hosted by [E2B](https://e2b.dev)
- **[ForeverVM](https://github.com/jamsocket/forevervm/tree/main/javascript/mcp-server)** - Run Python in a code sandbox.
- **[Gitee](https://github.com/oschina/mcp-gitee)** - Gitee API integration, repository, issue, and pull request management, and more.
- **[GitHub](https://github.com/github/github-mcp-server)** - GitHub's official MCP Server
- **[GitKraken](https://github.com/gitkraken/gk-cli)** - A CLI for interacting with GitKraken APIs. Includes an MCP server via `gk mcp` that not only wraps GitKraken APIs, but also Jira, GitHub, GitLab, and more.
- **[GrowthBook](https://github.com/growthbook/growthbook-mcp)** — Create and read feature flags, review experiments, generate flag types, search docs, and interact with GrowthBook's feature flagging and experimentation platform.
- **[Harness](https://github.com/harness/mcp-server)** - Access and interact with Harness platform data, including pipelines, repositories, logs, and artifact registries.
- **[JetBrains](https://github.com/JetBrains/mcp-jetbrains)** – Work on your code with JetBrains IDEs
- **[Mastra/mcp](https://github.com/mastra-ai/mastra/tree/main/packages/mcp)** - Client implementation for Mastra, providing seamless integration with MCP-compatible AI models and tools.
- **[Mastra/mcp-docs-server](https://github.com/mastra-ai/mastra/tree/main/packages/mcp-docs-server)** - Provides AI assistants with direct access to Mastra.ai's complete knowledge base.
- **[ocireg](https://github.com/StacklokLabs/ocireg-mcp)** - An SSE-based MCP server that allows LLM-powered applications to interact with OCI registries. It provides tools for retrieving information about container images, listing tags, and more.
- **[PGYER](https://github.com/PGYER/pgyer-mcp-server)** - MCP Server for [PGYER](https://www.pgyer.com/) platform, supports uploading, querying apps, etc.
- **[Playwright](https://github.com/microsoft/playwright-mcp)** - Playwright MCP server
- **[Plugged.in](https://github.com/VeriTeknik/pluggedin-mcp-proxy)** - A comprehensive proxy that combines multiple MCP servers into a single MCP. It provides discovery and management of tools, prompts, resources, and templates across servers, plus a playground for debugging when building MCP servers.
- **[Postman](https://github.com/postmanlabs/postman-mcp-server)** - Postman's remote MCP server connects AI agents, assistants, and chatbots directly to your APIs on Postman.
- **[Powertool](https://github.com/aws-powertools/powertools-mcp)** - An MCP implementation that provides search functionality for the Powertools for AWS Lambda documentation across multiple runtimes.
- **[ProdEAI](https://github.com/CuriousBox-AI/ProdE-mc)** - Your 24/7 production engineer that preserves context across multiple codebases [Prode.ai](https://prode.ai).
- **[QA Sphere](https://github.com/Hypersequent/qasphere-mcp)** - Integration with [QA Sphere](https://qasphere.com/) test management system, enabling LLMs to discover, summarize, and interact with test cases directly from AI-powered IDEs
- **[Ref](https://github.com/ref-tools/ref-tools-mcp)** - Up-to-date documentation for your coding agent. Covers 1000s of public repos and sites. Built by [ref.tools](https://ref.tools/)
- **[Riza](https://github.com/riza-io/riza-mcp)** - Arbitrary code execution and tool-use platform for LLMs by [Riza](https://riza.io)
- **[SonarQube](https://github.com/SonarSource/sonarqube-mcp-server)** - Provides seamless integration with [SonarQube](https://www.sonarsource.com/) Server or Cloud, and enables analysis of code snippets directly within the agent context
- **[XRAY](https://github.com/srijanshukla18/xray)** - Progressive code-intelligence server: lets AI assistants map structure, fuzzy-find symbols, and assess change-impact across Python, JS/TS, and Go codebases (powered by `ast-grep`)
- **[YepCode](https://github.com/yepcode/mcp-server-js)** - Execute any LLM-generated code in the [YepCode](https://yepcode.io) secure and scalable sandbox environment and create your own MCP tools using JavaScript or Python, with full support for NPM and PyPI packages

### Cloud & Infrastructure

- **[1mcpserver](https://github.com/particlefuture/1mcpserver)** - MCP of MCPs. Automatic discovery and configure MCP servers on your local machine. Fully REMOTE! Just use [https://mcp.1mcpserver.com/mcp/](https://mcp.1mcpserver.com/mcp/)
- **[4everland/4everland-hosting-mcp](https://github.com/4everland/4everland-hosting-mcp)** - An MCP server implementation for 4EVERLAND Hosting enabling instant deployment of AI-generated code to decentralized storage networks like Greenfield, IPFS, and Arweave.
- **[AWS Core](https://github.com/awslabs/mcp/tree/main/src/core-mcp-server)** - Core AWS MCP server providing prompt understanding and server management capabilities.
- **[AWS Cost Analysis](https://github.com/awslabs/mcp/tree/main/src/cost-analysis-mcp-server)** - Analyze CDK projects to identify AWS services used and get pricing information from AWS pricing webpages and API.
- **[AWS Documentation](https://github.com/awslabs/mcp/tree/main/src/aws-documentation-mcp-server)** - Fetch, convert, and search AWS documentation pages, with recommendations for related content.
- **[Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare)** - Deploy, configure & interrogate your resources on the Cloudflare developer platform (e.g. Workers/KV/R2/D1)
- **[EdgeOne Pages MCP](https://github.com/TencentEdgeOne/edgeone-pages-mcp)** - An MCP service for deploying HTML content to EdgeOne Pages and obtaining a publicly accessible URL.
- **[Gcore Cloud](https://github.com/G-Core/gcore-mcp-server)** - Gcore's Cloud Official MCP Server
- **[Globalping](https://github.com/jsdelivr/globalping-mcp-server)** - Network access with the ability to run commands like ping, traceroute, mtr, http, dns resolve.
- **[Google Cloud Run](https://github.com/GoogleCloudPlatform/cloud-run-mcp)** - Official MCP Server to deploy to [Google Cloud Run](https://cloud.google.com/run).
- **[Hostinger](https://github.com/hostinger/api-mcp-server)** - Official [Hostinger API](https://developers.hostinger.com/) MCP server for services managment.
- **[Render](https://render.com/docs/mcp-server)** - The official Render MCP server: spin up new services, run queries against your databases, and debug rapidly with direct access to service metrics and logs.
- **[Tencent Cloud COS MCP](https://github.com/Tencent/cos-mcp)** - Quickly integrate with Tencent Cloud Storage (COS) and Data Processing (CI) capabilities powered

### Content & Media

- **[21st.dev Magic](https://github.com/21st-dev/magic-mcp)** - Create crafted UI components inspired by the best 21st.dev design engineers.
- **[Allyson](https://github.com/isaiahbjork/allyson-mcp)** - AI-powered SVG animation generator that transforms static files into animated SVG components using the [Allyson](https://allyson.ai) platform
- **[Audioscrape](https://www.audioscrape.com/docs/mcp)** - Search 1M+ hours of podcasts, interviews, talks and your private audio uploads with speaker identification and timestamps. Official Remote MCP server (via https://mcp.audioscrape.com) enabling AI assistants to access and analyze audio content through semantic and text-based search.
- **[Chart](https://github.com/antvis/mcp-server-chart)** - 🤖 A Model Context Protocol server for generating visual charts using [AntV](https://github.com/antvis).
- **[DevHub](https://github.com/devhub/devhub-cms-mcp)** - Manage and utilize website content within the [DevHub](https://www.devhub.com) CMS platform
- **[ECharts](https://github.com/hustcc/mcp-echarts)** - Generate visual charts using [ECharts](https://echarts.apache.org) with AI MCP dynamically, used for chart generation and data analysis.
- **[ELEMENT.FM](https://gitlab.com/elementfm/mcp)** - Create and publish unlimited podcast shows and episodes with [ELEMENT.FM](https://element.fm)
- **[FlyonUI](https://github.com/themeselection/flyonui-mcp)** - Build modern, production-ready UI blocks, components, and landing pages in minutes.
- **[Gluestack UI MCP Server](https://github.com/gauravsaini/gluestack-ui-mcp-server)** - An MCP server tailored for React Native–first development using Gluestack UI.
- **[Kontent.ai](https://github.com/kontent-ai/mcp-server)** - Create, manage, and explore your content and content model using natural language in any MCP-compatible AI tool.
- **[Mureka](https://github.com/SkyworkAI/Mureka-mcp)** - generate lyrics, song and background music(instrumental)
- **[Mux](https://github.com/muxinc/mux-node-sdk/tree/master/packages/mcp-server)** - [Mux](https://www.mux.com) is a video API for developers. With Mux's official MCP you can upload videos, create live streams, generate thumbnails, add captions, manage playback policies, dig through engagement data, monitor video performance, and more.
- **[SlideSpeak](https://github.com/SlideSpeak/slidespeak-mcp)** - Create presentations and PowerPoints using AI and SlideSpeak MCP
- **[Ssemble AI Clipping](https://www.npmjs.com/package/@ssemble/mcp-server)** - Create AI-powered short-form video clips from YouTube videos. 9 tools for creating shorts, browsing caption templates, background music, gameplay overlays, and meme hooks. Supports both local (npx) and hosted endpoint (mcp.ssemble.com). [Website](https://www.ssemble.com)
- **[Supadata](https://github.com/supadata-ai/mcp)** - Official MCP server for [Supadata](https://supadata.ai) - YouTube, TikTok, X and Web data for makers.
- **[VideoDB](https://github.com/video-db/agent-toolkit/tree/main/modelcontextprotocol)** - Server for advanced AI-driven video editing, semantic search, multilingual transcription, generative media, voice cloning, and content moderation.
- **[Webflow](https://github.com/webflow/mcp-server)** - Interact with Webflow APIs to list and edit your site and CMS data.

### Finance & Payments

- **[Adfin](https://github.com/Adfin-Engineering/mcp-server-adfin)** - The only platform you need to get paid - all payments in one place, invoicing and accounting reconciliations with [Adfin](https://www.adfin.com/).
- **[Alby Bitcoin Payments MCP](https://github.com/getAlby/mcp/)** - Connect any bitcoin lightning wallet to agents to send and receive payments instantly at low cost.
- **[Armor Crypto MCP](https://github.com/armorwallet/armor-crypto-mcp)** - MCP to interface with multiple blockchains, staking, DeFi, swap, bridging, wallet management, DCA, Limit Orders, Coin Lookup, Tracking and more.
- **[Bankless Onchain](https://github.com/bankless/onchain-mcp)** - Query Onchain data, like ERC20 tokens, transaction history, smart contract state.
- **[Chargebee](https://github.com/chargebee/agentkit/tree/main/modelcontextprotocol)** - MCP Server that connects AI agents to [Chargebee platform](https://www.chargebee.com).
- **[CoinGecko](https://docs.coingecko.com/reference/mcp-server/)** - Official [CoinGecko API](https://www.coingecko.com/en/api) MCP Server for Crypto Price & Market Data, across 200+ blokchain networks and 8M+ tokens.
- **[DealX](https://github.com/DealExpress/mcp-server)** - MCP Server for DealX platform
- **[DexPaprika](https://github.com/coinpaprika/dexpaprika-mcp)** - Access real-time DEX analytics across 20+ blockchains with [DexPaprika API](https://docs.dexpaprika.com), tracking 5M+ tokens, pools, volumes, and historical market data. Built by CoinPaprika.
- **[Fewsats](https://github.com/Fewsats/fewsats-mcp)** - Enable AI Agents to purchase anything in a secure way using [Fewsats](https://fewsats.com)
- **[Financial Datasets](https://github.com/financial-datasets/mcp-server)** - Stock market API made for AI agents
- **[Hive Intelligence](https://github.com/hive-intel/hive-crypto-mcp)** 📇 ☁️ 🏠 - Hive Intelligence: Ultimate cryptocurrency MCP for AI assistants with unified access to crypto, DeFi, and Web3 analytics. Hive's remote mcp server guide [remote server](https://hiveintelligence.xyz/crypto-mcp).
- **[Mercado Pago](https://mcp.mercadopago.com/)** - Mercado Pago's official MCP server, offering tools to interact with our API, simplifying tasks and product integration.
- **[Norman Finance](https://github.com/norman-finance/norman-mcp-server)** - MCP server for managing accounting and taxes with Norman Finance.
- **[Octagon](https://github.com/OctagonAI/octagon-mcp-server)** - Deliver real-time investment research with extensive private and public market data.
- **[Openfort](https://github.com/openfort-xyz/mcp)** - Supercharge your AI assistant with plug-and-play access to authentication, project scaffolding, and smart wallet tooling.
- **[PayPal](https://github.com/paypal/agent-toolkit)** - The PayPal Model Context Protocol server allows you to integrate with PayPal APIs through function calling. This protocol supports various tools to interact with different PayPal services.
- **[Ramp](https://github.com/ramp-public/ramp-mcp)** - Interact with [Ramp](https://ramp.com)'s Developer API to run analysis on your spend and gain insights leveraging LLMs
- **[RevenueCat](https://www.revenuecat.com/docs/tools/mcp/overview)** - Manage your In-app-purchases in [RevenueCat](https://www.revenuecat.com) without leaving your AI coding environment.
- **[Square](https://github.com/square/square-mcp-server)** - A Model Context Protocol (MCP) server for square
- **[Stripe](https://github.com/stripe/agent-toolkit)** - Interact with Stripe API
- **[Thirdweb](https://github.com/thirdweb-dev/ai/tree/main/python/thirdweb-mcp)** - Read/write to over 2k blockchains, enabling data querying, contract analysis/deployment, and transaction execution, powered by [Thirdweb](https://thirdweb.com/)
- **[Token Metrics](https://github.com/token-metrics/mcp)** - [Token Metrics](https://www.tokenmetrics.com/) integration for fetching real-time crypto market data, trading signals, price predictions, and advanced analytics.
- **[Trade Agent](https://github.com/Trade-Agent/trade-agent-mcp)** - Execute stock and crypto trades via [Trade Agent](https://thetradeagent.ai/)
- **[Twelve Data](https://github.com/twelvedata/mcp)** - Interact with [Twelve Data](https://twelvedata.com) APIs to access real-time and historical financial market data for your AI agents.
- **[Xero](https://github.com/XeroAPI/xero-mcp-server)** - Interact with the accounting data in your business using our official MCP server

### Social Media & Communication

- **[CallHub](https://github.com/callhub/callhub-mcp)** - Python-based MCP tool providing a comprehensive set of functions for managing contacts, phonebooks, agents, teams, campaigns, and other CallHub resources.
- **[Carbon Voice](https://github.com/PhononX/cv-mcp-server)** - <img height="20" width="20" src="https://carbonvoice.app/favicon.ico" align="center"/> MCP Server that connects AI Agents to [Carbon Voice](https://getcarbon.app). Create, manage, and interact with voice messages, conversations, direct messages, folders, voice memos, AI actions and more in [Carbon Voice](https://getcarbon.app).
- **[GoLogin MCP server](https://github.com/gologinapp/gologin-mcp)** - Manage your GoLogin browser profiles and automation directly through AI conversations!
- **[Inbox Zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server)** - AI personal assistant for email [Inbox Zero](https://www.getinboxzero.com)
- **[LINE Official Account](https://github.com/line/line-bot-mcp-server)** - Integrates the LINE Messaging API to connect an AI Agent to the LINE Official Account.
- **[Linked API](https://github.com/Linked-API/linkedapi-mcp.git)** - MCP server that lets AI assistants control LinkedIn accounts and retrieve real-time data with [Linked API](https://linkedapi.io).
- **[Mailgun](https://github.com/mailgun/mailgun-mcp-server)** - Interact with Mailgun API.
- **[MailSandbox](https://github.com/btafoya/mailsandbox)** - MailSandbox (a fork of Mailpit) is a fast, zero-dependency email testing tool & API with a web UI, SMTP server, Postmark API emulation, and MCP server for AI-assisted debugging.
- **[Mailtrap](https://github.com/railsware/mailtrap-mcp)** - Integrates with Mailtrap Email API.
- **[Tldv](https://gitlab.com/tldv/tldv-mcp-server)** - Connect your AI agents to Google-Meet, Zoom & Microsoft Teams through [tl;dv](https://tldv.io)
- **[Twilio](https://github.com/twilio-labs/mcp)** - Interact with [Twilio](https://www.twilio.com/en-us) APIs to send messages, manage phone numbers, configure your account, and more.

### Search & Web

- **[AgentQL](https://github.com/tinyfish-io/agentql-mcp)** - Enable AI agents to get structured data from unstructured web with [AgentQL](https://www.agentql.com/).
- **[AnyCrawl](https://github.com/any4ai/anycrawl-mcp-server)** - [AnyCrawl](https://anycrawl.dev) MCP Server, Powerful web scraping and crawling for Cursor, Claude, and other LLM clients via the Model Context Protocol (MCP).
- **[Apify](https://github.com/apify/actors-mcp-server)** - [Actors MCP Server](https://apify.com/apify/actors-mcp-server): Use 3,000+ pre-built cloud tools to extract data from websites, e-commerce, social media, search engines, maps, and more
- **[Bright Data](https://github.com/brightdata/brightdata-mcp)** - Discover, extract, and interact with the web - one interface powering automated access across the public internet.
- **[Browserbase](https://github.com/browserbase/mcp-server-browserbase)** - Automate browser interactions in the cloud (e.g. web navigation, data extraction, form filling, and more)
- **[Crawlbase MCP](https://github.com/crawlbase/crawlbase-mcp)** - Enables AI agents to access real-time web data with HTML, markdown, and screenshot support. SDKs: Node.js, Python, Java, PHP, .NET.
- **[Decodo](https://github.com/Decodo/decodo-mcp-server)** - Easy web data access. Simplified retrieval of information from websites and online sources.
- **[Exa](https://github.com/exa-labs/exa-mcp-server)** - Search Engine made for AIs by [Exa](https://exa.ai)
- **[FetchSERP](https://github.com/fetchSERP/fetchserp-mcp-server-node)** - All-in-One SEO & Web Intelligence Toolkit API [FetchSERP](https://www.fetchserp.com)
- **[Firecrawl](https://github.com/mendableai/firecrawl-mcp-server)** - Extract web data with [Firecrawl](https://firecrawl.dev)
- **[Hyperbrowser](https://github.com/hyperbrowserai/mcp)** - [Hyperbrowser](https://www.hyperbrowser.ai/) is the next-generation platform empowering AI agents and enabling effortless, scalable browser automation.
- **[Kagi Search](https://github.com/kagisearch/kagimcp)** - Search the web using Kagi's search API
- **[Notte](https://github.com/nottelabs/notte/tree/main/packages/notte-mcp)** - Leverage Notte Web AI agents & cloud browser sessions for scalable browser automation & scraping workflows
- **[Oxylabs](https://github.com/oxylabs/oxylabs-mcp)** - Scrape websites with Oxylabs Web API, supporting dynamic rendering and parsing for structured data extraction.
- **[Perplexity](https://github.com/ppl-ai/modelcontextprotocol)** - An MCP server that connects to Perplexity's Sonar API, enabling real-time web-wide research in conversational AI.
- **[Scrapeless](https://github.com/scrapeless-ai/scrapeless-mcp-server)** - Integrate real-time [Scrapeless](https://www.scrapeless.com/en) Google SERP(Google Search, Google Flight, Google Map, Google Jobs....) results into your LLM applications. This server enables dynamic context retrieval for AI workflows, chatbots, and research tools.
- **[Scrapezy](https://github.com/scrapezy/mcp)** - Turn websites into datasets with [Scrapezy](https://scrapezy.com)
- **[ScreenshotMCP](https://github.com/upnorthmedia/ScreenshotMCP/)** - Capture website screenshots including full page, elements, and device specific sizes.
- **[ScreenshotOne](https://github.com/screenshotone/mcp/)** - Render website screenshots with [ScreenshotOne](https://screenshotone.com/)
- **[Search1API](https://github.com/fatwang2/search1api-mcp)** - One API for Search, Crawling, and Sitemaps
- **[Tavily](https://github.com/tavily-ai/tavily-mcp)** - Search engine for AI agents (search + extract) powered by [Tavily](https://tavily.com/)
- **[VpunaAiSearch](https://github.com/vpuna/vpuna-ai-search)** - Connect to [Vpuna AI Search Service](https://aisearch.vpuna.com), a developer first platform for semantic search, summarization, and contextual chat. Each project dynamically exposes its own Remote HTTP MCP server, enabling real-time context injection from structured and unstructured data.
- **[WebDataSource](https://webdatasource.com/releases/latest/mcp/index.html)** - Web Crawler for AI Agents. Supercharge your AI agents with an MCP-ready web crawler that delivers real-time insights from the web and your private knowledge bases.
- **[WebScraping.AI](https://github.com/webscraping-ai/webscraping-ai-mcp-server)** - Interact with **[WebScraping.AI](https://WebScraping.AI)** for web data extraction and scraping.

### Productivity & Business

- **[Agile Luminary](https://github.com/AgileLuminary/mcp-agile-luminary)** - Simpler Project Management - send [Agile Luminary](https://agileluminary.com) stories straight to your IDE
- **[Audiense Insights](https://github.com/AudienseCo/mcp-audiense-insights)** - Marketing insights and audience analysis from [Audiense](https://www.audiense.com/products/audiense-insights) reports, covering demographic, cultural, influencer, and content engagement analysis.
- **[Box](https://github.com/box-community/mcp-server-box)** - Interact with the Intelligent Content Management platform through Box AI.
- **[Bucket](https://github.com/bucketco/bucket-javascript-sdk/tree/main/packages/cli#model-context-protocol)** - Flag features, manage company data, and control feature access using [Bucket](https://bucket.co)
- **[Buildable](https://github.com/chunkydotdev/bldbl-mcp)** - Official MCP server for Buildable AI-powered development platform. Enables AI assistants to manage tasks, track progress, get project context, and collaborate with humans on software projects.
- **[CRIC Wuye AI](https://github.com/wuye-ai/mcp-server-wuye-ai)** - Interact with capabilities of the CRIC Wuye AI platform, an intelligent assistant specifically for the property management industry.
- **[Dart](https://github.com/its-dart/dart-mcp-server)** - Interact with task, doc, and project data in [Dart](https://itsdart.com), an AI-native project management tool
- **[EduBase](https://github.com/EduBase/MCP)** - Interact with [EduBase](https://www.edubase.net), a comprehensive e-learning platform with advanced quizzing, exam management, and content organization capabilities
- **[eSignatures](https://github.com/esignaturescom/mcp-server-esignatures)** - Contract and template management for drafting, reviewing, and sending binding contracts.
- **[Fibery](https://github.com/Fibery-inc/fibery-mcp-server)** - Perform queries and entity operations in your [Fibery](https://fibery.io) workspace.
- **[gotoHuman](https://github.com/gotohuman/gotohuman-mcp-server)** - Human-in-the-loop platform - Allow AI agents and automations to send requests for approval to your [gotoHuman](https://www.gotohuman.com) inbox.
- **[Integration App](https://github.com/integration-app/mcp-server)** - Interact with any other SaaS applications on behalf of your customers.
- **[Knit MCP](https://developers.getknit.dev/docs/knit-mcp-server-getting-started)** - Connect with 10,000+ tools across HRIS, ATS, CRM, Accounting, Calendar, Meeting, Ticketing, and more categories.
- **[Make](https://github.com/integromat/make-mcp-server)** - Turn your [Make](https://www.make.com/) scenarios into callable tools for AI assistants.
- **[Mercado Libre](https://mcp.mercadolibre.com/)** - Mercado Libre's official MCP server, offering tools to interact with our marketplace, simplifying tasks and product integration.
- **[Notion](https://github.com/makenotion/notion-mcp-server)** - Notion official MCP server
- **[Pearl](https://mcp.pearl.com)** - Official MCP Server to interact with Pearl API. Connect your AI Agents with 12,000+ certified experts instantly.
- **[Pearch](https://github.com/Pearch-ai/mcp_pearch)** - Best people search engine that reduces the time spent on talent discovery.
- **[Plane](https://github.com/makeplane/plane-mcp-server)** - The official Plane MCP server provides integration with Plane APIs, enabling full AI automation of Plane projects, work items, cycles and more.
- **[Rember](https://github.com/rember/rember-mcp)** - Create spaced repetition flashcards in [Rember](https://rember.com) to remember anything you learn in your chats
- **[Routine](https://github.com/routineco/mcp-server)** - MCP server to interact with [Routine](https://routine.co/): calendars, tasks, notes, etc.
- **[Rube](https://rube.composio.dev)** - Rube is a Model Context Protocol (MCP) server that connects your AI tools to 500+ apps like Gmail, Slack, GitHub, and Notion. Simply install it in your AI client, authenticate once with your apps, and start asking your AI to perform real actions like "Send an email" or "Create a task."
- **[ShopSavvy](https://github.com/shopsavvy/shopsavvy-mcp-server)** - Complete product and pricing data solution for AI assistants. Search for products by barcode/ASIN/URL, access detailed product metadata, access comprehensive pricing data from thousands of retailers, view and track price history, and more. Published as `@shopsavvy/mcp-server`.
- **[TalentoHQ](https://hr.talentohq.com/mcp)** – Connect to the [TalentoHQ HR software](https://talentohq.com/features/mcp) via MCP. Transform your organization with the AI first HR software.
- **[Taskade](https://github.com/taskade/mcp)** – Connect to the [Taskade platform](https://www.taskade.com/) via MCP. Access tasks, projects, workflows, and AI agents in real-time through a unified workspace and API.
- **[Taskeract](https://github.com/Acqusys/taskeract-mcp)** - Official Taskeract MCP Server for integrating your [Taskeract](https://www.taskeract.com/) project tasks and load the context of your tasks into your MCP enabled app.
- **[VeyraX](https://github.com/VeyraX/veyrax-mcp)** - Single tool to control all 100+ API integrations, and UI components
- **[WayStation](https://waystation.ai/connect/mcp-server)** — A universal remote MCP server that connects to popular productivity tools such as Notion, Monday, AirTable, and many more.
- **[Zapier](https://zapier.com/mcp)** - Connect your AI Agents to 8,000 apps instantly.

### Security & Compliance

- **[BrowserStack](https://github.com/browserstack/mcp-server)** – Bring the full power of BrowserStack's [Test Platform](https://www.browserstack.com/test-platform) to your AI tools, making testing faster and easier for every developer and tester on your team.
- **[Cycode](https://github.com/cycodehq/cycode-cli#mcp-command-experiment)** - Boost security in your dev lifecycle via SAST, SCA, Secrets & IaC scanning with [Cycode](https://cycode.com/).
- **[RAD Security](https://github.com/rad-security/mcp-server)** - Interact with the RAD Security platform which provides AI-powered security insights for Kubernetes and cloud environments.
- **[Semgrep](https://github.com/semgrep/mcp)** - Enable AI agents to secure code with [Semgrep](https://semgrep.dev/).
- **[urlDNA](https://github.com/urldna/mcp)** - Dynamically scan and analyze potentially malicious URLs using the [urlDNA](https://urlDNA.io)
- **[VISO TRUST](https://github.com/visotrust/viso-mcp-server)** - Access and manage your VISO TRUST third-party risk program directly through your AI assistant.
- **[Zenable](https://docs.zenable.io/integrations/mcp/getting-started)** - Clean up sloppy AI code and prevent vulnerabilities

### Analytics & Monitoring

- **[Agent Mindshare](https://agentmindshare.com)** - Track and monitor AI agent mindshare across platforms - measure brand visibility in AI conversations with [Agent Mindshare](https://agentmindshare.com).
- **[Axiom](https://github.com/axiomhq/mcp-server-axiom)** - Query and analyze your Axiom logs, traces, and all other event data in natural language
- **[Comet Opik](https://github.com/comet-ml/opik-mcp)** - Query and analyze your [Opik](https://github.com/comet-ml/opik) logs, traces, prompts and all other telemtry data from your LLMs in natural language.
- **[Dash0](https://github.com/dash0hq/mcp-dash0)** - Navigate your OpenTelemetry resources, investigate incidents and query metrics, logs and traces on [Dash0](https://www.dash0.com/).
- **[Digma](https://github.com/digma-ai/digma-mcp-server)** - A code observability MCP enabling dynamic code analysis based on OTEL/APM data to assist in code reviews, issues identification and fix, highlighting risky code etc.
- **[Grafana](https://github.com/grafana/mcp-grafana)** - Search dashboards, investigate incidents and query datasources in your Grafana instance
- **[Last9](https://github.com/last9/last9-mcp-server)** - Seamlessly bring real-time production context—logs, metrics, and traces—into your local environment to auto-fix code faster.
- **[Logfire](https://github.com/pydantic/logfire-mcp)** - Provides access to OpenTelemetry traces and metrics through Logfire.
- **[Metoro](https://github.com/metoro-io/metoro-mcp-server)** - Query and interact with kubernetes environments monitored by Metoro
- **[PlainSignal](https://github.com/plainsignal/plainsignal-mcp)** - Official MCP server that connects to PlainSignal's API and querying realtime website analytics data in conversational AI.
- **[Raygun](https://github.com/MindscapeHQ/mcp-server-raygun)** - Interact with your crash reporting and real using monitoring data on your Raygun account
- **[Sentry](https://github.com/getsentry/sentry-mcp)** - Official MCP server for [Sentry](https://sentry.io).

### Other

- **[ALAPI](https://github.com/ALAPI-SDK/mcp-alapi-cn)** - ALAPI MCP Tools,Call hundreds of API interfaces via MCP
- **[Campertunity](https://github.com/campertunity/mcp-server)** - Search campgrounds around the world on campertunity, check availability, and provide booking links.
- **[Cloudbet](https://github.com/cloudbet/sports-mcp-server)** – Structured sports and esports data via Cloudbet API: fixtures, live odds, stake limits, and markets.
- **[Drand](https://github.com/randa-mu/drand-mcp-server)** - An MCP server for fetching verifiable random numbers from the [drand network](https://drand.love).
- **[Driflyte](https://github.com/serkan-ozal/driflyte-mcp-server)** - MCP Server for [Driflyte](https://console.driflyte.com). The Driflyte MCP Server exposes tools that allow AI assistants to query and retrieve topic-specific knowledge from recursively crawled and indexed web pages.
- **[FHIR](https://github.com/wso2/fhir-mcp-server/)** - Model Context Protocol server for Fast Healthcare Interoperability Resources (FHIR) APIs, enabling seamless integration with healthcare data through SMART-on-FHIR authentication and comprehensive FHIR operations.
- **[Find-A-Domain](https://findadomain.dev/mcp)** - Domain availability checking and WHOIS lookup tools.
- **[Fulcra Context](https://github.com/fulcradynamics/fulcra-context-mcp)** - Fulcra Context MCP server for accessing your personal health, workouts, sleep, location, and more, all privately. Built around [Context by Fulcra](https://www.fulcradynamics.com/).
- **[IP2Location.io](https://github.com/ip2location/mcp-ip2location-io)** - IP2Location.io API integration to retrieve the geolocation information for an IP address.
- **[IPLocate](https://github.com/iplocate/mcp-server-iplocate)** - Look up IP address geolocation, network information, detect proxies and VPNs, and find abuse contact details using IPLocate.io
- **[ilert](https://github.com/iLert/mcp-ilert)** - Interact with [ilert](https://ilert.com) through natural language.
- **[Kiwi.com](<[https://www.kiwi.com](https://mcp-install-instructions.alpic.cloud/servers/kiwi-com-flight-search)>)** - Official [Kiwi.com](https://www.kiwi.com) flight search MCP server. Search and book flights directly from your favorite AI assistant.
- **[Mapbox](https://github.com/mapbox/mcp-server)** - Unlock geospatial intelligence through Mapbox APIs like geocoding, POI search, directions, isochrones and more.
- **[OP.GG](https://github.com/opgginc/opgg-mcp)** - Access real-time gaming data across popular titles like League of Legends, TFT, and Valorant, offering champion analytics, esports schedules, meta compositions, and character statistics.
- **[Octocode](https://github.com/bgauryy/octocode-mcp)** - Leading AI-powered code assistant for advanced research, analysis and discovery across GitHub Repositories in large ecosystems
- **[OctoEverywhere For 3D Printing](https://octoeverywhere.com/mcp)** - A 3D Printing MCP server that allows for querying for live state, webcam snapshots, and 3D printer control.
- **[ThingsBoard](https://github.com/thingsboard/thingsboard-mcp)** - The ThingsBoard MCP Server provides a natural language interface for LLMs and AI agents to interact with your ThingsBoard IoT platform.
- **[TrackMage](https://github.com/trackmage/trackmage-mcp-server)** - Shipment tracking api and logistics management capabilities through the [TrackMage API] (https://trackmage.com/)
- **[Willi MaKo Knowledge Service](https://mcp.stromhaltig.de)** - A knowledge service for Germany's complex Energy Market Communications (MaKo) regulations.

## Community Servers

A growing set of community-developed and maintained servers demonstrates various applications of MCP across different domains.

### Database & Data

- **[Airtable](https://github.com/domdomegg/airtable-mcp-server)** - Read and write access to Airtable databases.
- **[BigQuery](https://github.com/LucasHild/mcp-server-bigquery)** (by LucasHild) - BigQuery database integration with schema inspection and query capabilities
- **[BigQuery](https://github.com/ergut/mcp-bigquery-server)** (by ergut) - Server implementation for Google BigQuery integration that enables direct BigQuery database access and querying capabilities
- **[bytebase/dbhub](https://github.com/bytebase/dbhub)** – 📇 Universal database MCP server supporting mainstream databases.\
- **[CockroachDB](https://github.com/amineelkouhen/mcp-cockroachdb)** - A Model Context Protocol server for managing, monitoring, and querying data in [CockroachDB](https://cockroachlabs.com).
- **[Data Exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration)** - MCP server for autonomous data exploration on .csv-based datasets, providing intelligent insights with minimal effort.
- **[Database](https://github.com/TheRaLabs/legion-mcp)** (by Legion AI) - Universal database MCP server supporting multiple database types including PostgreSQL, Redshift, CockroachDB, MySQL, RDS MySQL, Microsoft SQL Server, BigQuery, Oracle DB, and SQLite
- **[Dolt](https://github.com/dolthub/dolt-mcp)** - The official MCP server for version-controlled Dolt databases.
- **[Druid MCP Server](https://github.com/iunera/druid-mcp-server)** - STDIO/SEE MCP Server for Apache Druid by [iunera](https://www.iunera.com) that provides extensive tools, resources, and prompts for managing and analyzing Druid clusters.
- **[DynamoDB-Toolbox](https://www.dynamodbtoolbox.com/docs/databases/actions/mcp-toolkit)** - Leverages your Schemas and Access Patterns to interact with your [DynamoDB](https://aws.amazon.com/dynamodb) Database using natural language.
- **[gx-mcp-server](https://github.com/davidf9999/gx-mcp-server)** - Expose Great Expectations data validation and
  quality checks as MCP tools for AI agents. Load datasets, create validation suites, run data quality checks, and
  retrieve detailed results.
- **[JSON MCP](https://github.com/VadimNastoyashchy/json-mcp)** - MCP server empowers LLMs to interact with JSON files efficiently. With JSON MCP, you can split, merge, etc.
- **[libSQL by xexr](https://github.com/Xexr/mcp-libsql)** - MCP server for libSQL databases with comprehensive security and management tools. Supports file, local HTTP, and remote Turso databases with connection pooling, transaction support, and 6 specialized database tools.
- **[Mongo](https://github.com/QuantGeekDev/mongo-mcp)** - A Model Context Protocol (MCP) server that enables LLMs to interact directly with MongoDB databases
- **[MongoDB](https://github.com/kiliczsh/mcp-mongo-server)** - A Model Context Protocol Server for MongoDB
- **[MongoDB Lens](https://github.com/furey/mongodb-lens)** - Full Featured MCP Server for MongoDB Database.
- **[MySQL](https://github.com/designcomputer/mysql_mcp_server)** - MySQL database integration with configurable access controls and schema inspection
- **[Nile Postgres](https://github.com/niledatabase/nile-mcp-server)** - Manage and query databases, tenants, users, auth using LLMs
- **[NocoDB](https://github.com/edwinbernadus/nocodb-mcp-server)** - Manage NocoDB server, support read and write databases
- **[Peliqan](https://github.com/Peliqan-io/mcp-server-peliqan)** - Data platform with ETL and built-in data warehouse, access all business applications (ERP, CRM, Accounting etc.) via MCP and run queries on your business data.
- **[run-sql-connectorx](https://github.com/gigamori/mcp-run-sql-connectorx)** - Execute SQL (PostgreSQL, MariaDB, BigQuery, MS SQL Server, RedShift, etc.) via ConnectorX and stream results to CSV/Parquet. MCP tool: run_sql.
- **[SchemaCrawler](https://github.com/schemacrawler/SchemaCrawler-MCP-Server-Usage)** - Connect to any relational database, and be able to get valid SQL, and ask questions like what does a certain column prefix mean.
- **[SchemaFlow](https://github.com/CryptoRadi/schemaflow-mcp-server)** - Real-time PostgreSQL & Supabase database schema access for AI-IDEs via Model Context Protocol. Provides live database context through secure SSE connections with three powerful tools: get_schema, analyze_database, and check_schema_alignment. [SchemaFlow](https://schemaflow.dev)
- **[Snowflake](https://github.com/isaacwasserman/mcp-snowflake-server)** - Snowflake database integration with read/write capabilities and insight tracking
- **[SQLite](https://github.com/panasenco/mcp-sqlite)** - MCP server for SQLite files. Supports Datasette-compatible metadata!
- **[Text-To-GraphQL](https://github.com/Arize-ai/text-to-graphql-mcp)** - MCP server for text-to-graphql, integrates with Claude Desktop and Cursor.
- **[Trino MCP Server](https://github.com/tuannvm/mcp-trino)** - A Go implementation of a Model Context Protocol (MCP) server for Trino, enabling LLM models to query distributed SQL databases through standardized tools.

### AI & Machine Learning

- **[any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp)** - Chat with any other OpenAI SDK Compatible Chat Completions API, like Perplexity, Groq, xAI and more
- **[AutoGen documentation](https://github.com/sykuang/mcp-autogen-doc)** - A Model Context Protocol (MCP) server that provides AI assistants with the ability to search and retrieve Microsoft AutoGen documentation.
- **[consult7](https://github.com/szeider/consult7)** - Analyze large codebases and document collections using high-context models via OpenRouter, OpenAI, or Google AI -- very useful, e.g., with Claude Code
- **[DeepView MCP](https://github.com/ai-1st/deepview-mcp)** - Enables IDEs like Cursor and Windsurf to analyze large codebases using Gemini's 1M context window.
- **[Gemsuite](https://github.com/PV-Bhat/gemsuite-mcp)** - The ultimate open-source server for advanced Gemini API interaction with MCP, intelligently selects models.
- **[GXtract](https://github.com/sascharo/gxtract)** - GXtract is a MCP server designed to integrate with VS Code and other compatible editors (documentation: [sascharo.github.io/gxtract](https://sascharo.github.io/gxtract)). It provides a suite of tools for interacting with the GroundX platform, enabling you to leverage its powerful document understanding capabilities directly within your development environment.
- **[HuggingFace Spaces](https://github.com/evalstate/mcp-hfspace)** - Server for using HuggingFace Spaces, supporting Images, Audio, Text and more. Claude Desktop mode for ease-of-use.
- **[Jean Memory](https://github.com/jonathan-politzki/your-memory)** - Premium memory consistent across all AI applications.
- **[Memory-Plus](https://github.com/Yuchen20/Memory-Plus)** a lightweight, local RAG memory store to record, retrieve, update, delete, and visualize persistent "memories" across sessions—perfect for developers working with multiple AI coders (like Windsurf, Cursor, or Copilot) or anyone who wants their AI to actually remember them.
- **[Minima](https://github.com/dmayboroda/minima)** - Local RAG (on-premises) with MCP server.
- **[OpenAI](https://github.com/pierrebrunelle/mcp-server-openai)** - Query OpenAI models directly from Claude using MCP protocol
- **[PiAPI](https://github.com/apinetwork/piapi-mcp-server)** - PiAPI MCP server makes user able to generate media content with Midjourney/Flux/Kling/Hunyuan/Udio/Trellis directly from Claude or any other MCP-compatible apps.
- **[Pollinations](https://github.com/pollinations/model-context-protocol)** - Multimodal MCP server for generating images, audio, and text with no authentication required
- **[Scaffold](https://github.com/Beer-Bears/scaffold)** - Scaffold is a Retrieval-Augmented Generation (RAG) system designed to structural understanding of large codebases. It transforms your source code into a living knowledge graph, allowing for precise, context-aware interactions that go far beyond simple file retrieval.
- **[Vibe Check](https://github.com/PV-Bhat/vibe-check-mcp-server)** - The definitive Vibe Coder's sanity check MCP server: Prevents cascading errors by calling a "Vibe-check" agent to ensure alignment and prevent scope creep

### Developer Tools & DevOps

- **[APISIX-MCP](https://github.com/api7/apisix-mcp)** - APISIX Model Context Protocol (MCP) server is used to bridge large language models (LLMs) with the APISIX Admin API, supporting querying and managing all resources in [Apache APISIX](https://github.com/apache/apisix).
- **[Backup](https://github.com/hexitex/MCP-Backup-Server)** - Add smart Backup ability to coding agents like Windsurf, Cursor, Cluade Coder, etc
- **[Binary Ninja](https://github.com/fosdickio/binary_ninja_mcp)** - A Binary Ninja plugin, MCP server, and bridge that seamlessly integrates [Binary Ninja](https://binary.ninja) with your favorite MCP client.
- **[Browser MCP](https://github.com/browsermcp/mcp)** - Automate your local browser
- **[Browser MCP](https://github.com/bytedance/UI-TARS-desktop/tree/main/packages/agent-infra/mcp-servers/browser)** (by UI-TARS) - A fast, lightweight MCP server that empowers LLMs with browser automation via Puppeteer's structured accessibility data, featuring optional vision mode for complex visual understanding and flexible, cross-platform configuration.
- **[clj-kondo-MCP](https://github.com/Bigsy/clj-kondo-MCP)** - Clojure linter
- **[Clojars](https://github.com/Bigsy/Clojars-MCP-Server)** - Obtains latest dependency details for Clojure libraries.
- **[clojure-mcp](https://github.com/bhauman/clojure-mcp)** - Clojure development tools, direct access to the running program via REPL.
- **[Codesys-mcp-toolkit](https://github.com/johannesPettersson80/codesys-mcp-toolkit)** - A Model Context Protocol (MCP) server for CODESYS V3 programming environments.
- **[dbt-docs](https://github.com/mattijsdp/dbt-docs-mcp)** - MCP server for dbt-core (OSS) users as the official dbt MCP only supports dbt Cloud. Supports project metadata, model and column-level lineage and dbt documentation.
- **[Django REST Framework MCP](https://github.com/zacharypodbela/djangorestframework-mcp)** - Expose Django REST Framework APIs as MCP tools for LLMs and agentic applications
- **[Docker](https://github.com/QuantGeekDev/docker-mcp)** - Run and manage docker containers, docker compose, and logs
- **[elisp-dev-mcp](https://github.com/laurynas-biveinis/elisp-dev-mcp)** - elisp (Emacs Lisp) development support tools, running in Emacs.
- **[FileScopeMCP](https://github.com/admica/FileScopeMCP)** - Analyzes your codebase identifying important files based on dependency relationships. Generates diagrams and importance scores per file, helping AI assistants understand the codebase. Automatically parses popular programming languages, Python, Lua, C, C++, Rust, Zig.
- **[Files](https://github.com/flesler/mcp-files)** - Enables agents to quickly find and edit code in a codebase with surgical precision. Find symbols, edit them everywhere.
- **[GDB](https://github.com/pansila/mcp_server_gdb)** - A GDB/MI protocol server based on the MCP protocol, providing remote application debugging capabilities with AI assistants.
- **[Gentoro](https://github.com/gentoro-GT/mcp-nodejs-server)** - Gentoro generates MCP Servers based on OpenAPI specifications.
- **[GitHub Repos Manager MCP Server](https://github.com/kurdin/github-repos-manager-mcp)** - Token-based GitHub automation management. No Docker, Flexible configuration, 80+ tools with direct API integration.
- **[godoc-mcp-server](https://github.com/yikakia/godoc-mcp-server)** - MCP server to provide golang packages and their information from pkg.go.dev
- **[Godot MCP](https://github.com/Coding-Solo/godot-mcp)** - MCP server for interacting with the Godot game engine, providing tools for editing, running, debugging, and managing scenes in Godot projects.
- **[Gru Sandbox](https://github.com/babelcloud/gru-sandbox)** - Gru-sandbox(gbox) is an open source project that provides a self-hostable sandbox for MCP integration or other AI agent usecases.
- **[Hippocampus](https://github.com/cromwellian/hippycampus)** - Turns any Swagger/OpenAPI REST endpoint with a yaml/json definition into an MCP Server with Langchain/Langflow integration automatically.
- **[IDA Pro MCP](https://github.com/mrexodia/ida-pro-mcp)** - MCP Server for automated reverse engineering with IDA Pro.
- **[Kubernetes](https://github.com/Flux159/mcp-server-kubernetes)** - Connect to Kubernetes cluster and manage pods, deployments, services.
- **[Language Server](https://github.com/isaacphi/mcp-language-server)** 🏎️ - MCP Language Server gives MCP enabled clients access to semantic tools like get definition, references, rename, and diagnostics.
- **[Latex MCP Server](https://github.com/Yeok-c/latex-mcp-server)** - MCP Server to compile latex, download/organize/read cited papers, run visualization scripts and add figures/tables to latex.
- **[llm-context](https://github.com/cyberchitta/llm-context.py)** - Share code context with LLMs via Model Context Protocol or clipboard.
- **[Maven](https://github.com/Bigsy/maven-mcp-server)** - Tools to query latest Maven dependency information
- **[Maven Tools](https://github.com/arvindand/maven-tools-mcp)** - Enhanced Maven Central integration with intelligent caching, bulk operations, and version classification
- **[MCP Aggregator](https://github.com/nazar256/combine-mcp)** - An MCP (Model Context Protocol) aggregator that allows you to combine multiple MCP servers into a single endpoint allowing to filter specific tools.
- **[MCP-CLI Adapter](https://github.com/inercia/mcp-cli-adapter)** - Use command line tools in a secure fashion as MCP tools.
- **[MCP Expr Lang](https://github.com/ivan-saorin/mcp-expr-lang)** - MCP Expr-Lang provides a seamless integration between Claude AI and the powerful expr-lang expression evaluation engine.
- **[MCP Installer](https://github.com/anaisbetts/mcp-installer)** - Set up MCP servers in Claude Desktop
- **[mcp-k8s-go](https://github.com/strowk/mcp-k8s-go)** - Golang-based Kubernetes MCP Server. Built to be extensible.
- **[MKP](https://github.com/StacklokLabs/mkp)** - Model Kontext Protocol Server for Kubernetes that allows LLM-powered applications to interact with Kubernetes clusters through native Go implementation with direct API integration and comprehensive resource management.
- **[NPM Search](https://github.com/btwiuse/npm-search-mcp-server)** - Search for npm packages
- **[OpenAPI Schema Explorer](https://github.com/kadykov/mcp-openapi-schema-explorer)** - Token-efficient access to OpenAPI/Swagger specs via MCP Resources
- **[Package Registry Search](https://github.com/artmann/package-registry-mcp)** - Search and get up-to-date information about NPM, Cargo, PyPi, and NuGet packages.
- **[PiloTY](https://github.com/yiwenlu66/PiloTY)** - AI pilot for PTY operations that enables agents to control interactive terminals with stateful sessions, SSH connections, and background process management
- **[Playwright MCP Server](https://github.com/executeautomation/mcp-playwright)** - An MCP server using Playwright for browser automation and webscrapping
- **[Reloaderoo](https://github.com/cameroncooke/reloaderoo)** - A local MCP server for developers that mirrors your in-development MCP server, allowing seamless restarts and tool updates so you can build, test, and iterate on your MCP server within the same AI session without interruption.
- **[Renamify](https://docspring.github.io/renamify/mcp/overview/)** - Smart, case-aware search & replace for codebases. Provides atomic renaming of symbols, files, and directories with full undo/redo. The MCP server lets AI assistants plan, preview, and apply rename operations safely, handling all naming conventions (snake_case, camelCase, PascalCase, etc.) automatically.
- **[Repo Map](https://github.com.mcas.ms/pdavis68/RepoMapper)** -🐧 🪟 🍎 - An MCP server (and command-line tool) to provide a dynamic map of chat-related files from the repository with their function prototypes and related files in order of relevance. Based on the "Repo Map" functionality in Aider.chat
- **[Sourcerer](https://github.com/st3v3nmw/sourcerer-mcp)** - MCP for semantic code search & navigation that reduces token waste
- **[spm-mcp](https://github.com/simpleswift/spm-mcp)** - iOS Swift Package Manager server written in Swift
- **[Svelte Documentation](https://github.com/khromov/llmctx)** - Remote server (SSE/Streamable) for the latest Svelte and SvelteKit documentation
- **[TeamCity](https://github.com/itcaat/teamcity-mcp)** - MCP server for TeamCity, integrates with Claude Desktop and Cursor.
- **[Terragrunt-Docs](https://github.com/Excoriate/mcp-terragrunt-docs)** - Terragrunt documentation always up to date.
- **[Unity3d Game Engine](https://github.com/CoderGamester/mcp-unity)** - MCP Server to control and interact with Unity3d Game Engine for game development
- **[weibaohui/k8m](https://github.com/weibaohui/k8m)** Provides multi-cluster Kubernetes management and operations using MCP, featuring a management interface, logging, and nearly 50 built-in tools covering common DevOps and development scenarios. Supports both standard and CRD resources.
- **[weibaohui/kom](https://github.com/weibaohui/kom)** Provides multi-cluster Kubernetes management and operations using MCP, It can be integrated as an SDK into your own project and includes nearly 50 built-in tools covering common DevOps and development scenarios. Supports both standard and CRD resources.
- **[Windows CLI](https://github.com/SimonB97/win-cli-mcp-server)** - MCP server for secure command-line interactions on Windows systems, enabling controlled access to PowerShell, CMD, and Git Bash shells.
- **[xcodebuild](https://github.com/ShenghaiWang/xcodebuild)** - 🍎 Build iOS Xcode workspace/project and feed back errors to llm.
- **[XcodeBuildMCP](https://github.com/cameroncooke/xcodebuildmcp)** -  Popular MCP server that enables AI agents to scaffold, build, run and test iOS, macOS, visionOS and watchOS apps or simulators and wired and wireless devices. It has powerful UI-automation capabilities like controlling the simulator, capturing run-time logs, as well as taking screenshots and viewing the accessibility hierarchy.
- **[xcsimctl](https://github.com/nzrsky/simctl-mcp-server)** - 🍎 Manage Xcode simulators.
- **[xctools](https://github.com/nzrsky/xctools-mcp-server)** - 🍎 MCP server for Xcode's xctrace, xcrun, xcodebuild.

### Cloud & Infrastructure

- **[AWS EC2 Pricing](https://github.com/trilogy-group/aws-pricing-mcp)** - Get up-to-date EC2 pricing information with one call. Fast. Powered by a pre-parsed AWS pricing catalogue.
- **[DigitalOcean MCP Server](https://github.com/rohit-kaundal/digitalocean-mcp-server)** - A Model Context Protocol (MCP) server that provides programmatic access to DigitalOcean's API. This server exposes tools for managing droplets, Kubernetes clusters, and container registries through the MCP interface.
- **[DropBin](https://dropbin.org/mcp)** - Remote SSE MCP server for hosting HTML webpages and sharing content through temporary URLs without authentication
- **[Hetzner Cloud MCP Server](https://github.com/dkruyt/mcp-hetzner)** - A Model Context Protocol (MCP) server for interacting with the Hetzner Cloud API. This server allows language models to manage Hetzner Cloud resources through structured functions.
- **[MCPJungle](https://github.com/mcpjungle/MCPJungle)** 🌳 - Open-source, Self-hosted MCP server Gateway that connects your AI Agents to MCP Servers (for developers and enterprises)
- **[🧲 Magg 🧲](https://github.com/sitbon/magg)** - A meta-MCP server that acts as a universal hub, allowing LLMs to autonomously discover, install, and orchestrate multiple MCP servers - essentially giving AI assistants the power to extend their own capabilities on-demand.

### Content & Media

- **[Contentful](https://github.com/ivo-toby/contentful-mcp)** - Interact with your content on the Contentful platform
- **[Creatify](https://github.com/TSavo/creatify-mcp)** - MCP Server that exposes Creatify AI API capabilities for AI video generation, including avatar videos, URL-to-video conversion, text-to-speech, and AI-powered editing tools.
- **[Excel](https://github.com/haris-musa/excel-mcp-server)** - Excel manipulation including data reading/writing, worksheet management, formatting, charts, and pivot table
- **[HackMD](https://github.com/yuna0x0/hackmd-mcp)** - A Model Context Protocol server for integrating [HackMD](https://hackmd.io)'s note-taking platform with AI assistants.
- **[Imagician](https://github.com/flowy11/imagician)** - A MCP server for comprehensive image editing operations including resizing, format conversion, cropping, compression, and more based on sharp.
- **[ImageSorcery MCP](https://github.com/sunriseapps/imagesorcery-mcp)** - ComputerVision-based 🪄 sorcery of image recognition and editing tools for AI assistants.
- **[Maya MCP](https://github.com/PatrickPalmer/MayaMCP)** - MCP server for Autodesk Maya
- **[Mermaid](https://github.com/hustcc/mcp-mermaid)** - Generate [mermaid](https://mermaid.js.org/) diagram and chart with AI MCP dynamically.
- **[Pandoc](https://github.com/vivekVells/mcp-pandoc)** - MCP server for seamless document format conversion using Pandoc, supporting Markdown, HTML, and plain text, with other formats like PDF, csv and docx in development.
- **[shadcn-ui-mcp-server](https://github.com/heilgar/shadcn-ui-mcp-server)** - A powerful and flexible MCP server designed to enhance the development experience with Shadcn UI components, providing tools for component management, documentation, and installation.
- **[Shadcn Registry Manager](https://github.com/reuvenaor/shadcn-registry-manager)** - MCP server for Shadcn UI, enabling automated, remote, or containerized project management via local or remote registries.
- **[Storyblok](https://github.com/Kiran1689/storyblok-mcp-server)** - Storyblok MCP server enables your AI assistants to directly access and manage your Storyblok spaces, stories, components, assets, workflows, and more.
- **[Unified Diff MCP Server](https://github.com/gorosun/unified-diff-mcp)** - Beautiful HTML and PNG diff visualization using diff2html, designed for filesystem edit_file dry-run output with high-performance Bun runtime.
- **[Vega-Lite](https://github.com/isaacwasserman/mcp-vegalite-server)** - Generate visualizations from fetched data using the VegaLite format and renderer.
- **[YouTube](https://github.com/anaisbetts/mcp-youtube)** - Fetch YouTube subtitles

### Finance & Payments

- **[Algorand](https://github.com/GoPlausible/algorand-mcp)** - A comprehensive MCP server for tooling interactions(40+) and resource accessibility(60+) plus many useful prompts to interact with Algorand Blockchain.
- **[CoinCap](https://github.com/QuantGeekDev/coincap-mcp)** - A MCP server that provides real-time cryptocurrency market data through CoinCap's public API without requiring authentication
- **[Facebook Ads](https://github.com/gomarble-ai/facebook-ads-mcp-server)** - MCP server acting as an interface to the Facebook Ads, enabling programmatic access to Facebook Ads data and management features.
- **[FrankfurterMCP](https://github.com/anirbanbasu/frankfurtermcp)** - MCP server acting as an interface to the [Frankfurter API](https://frankfurter.dev/) for currency exchange data.
- **[Google Ads](https://github.com/gomarble-ai/google-ads-mcp-server)** - MCP server acting as an interface to the Google Ads, enabling programmatic access to Google Ads data and management features.
- **[LunchMoney](https://github.com/akutishevsky/lunchmoney-mcp)** - MCP server for LunchMoney personal finance and budgeting tool.
- **[Meta Ads Remote MCP](https://github.com/pipeboard-co/meta-ads-mcp)** - Remote MCP server to interact with Meta Ads API - access, analyze, and manage Facebook, Instagram, and other Meta platforms advertising campaigns.
- **[OpenMF-mifosx-self-service](https://github.com/openMF/mcp-mifosx-self-service)** - Access Apache Fineract self-service APIs for registration, authentication, account management, and transactions via MCP.
- **[QuantConnect](https://github.com/QuantConnect/mcp-server)** – Dockerized Python MCP server that lets LLMs like Claude or OpenAI o3 Pro autonomously create projects, backtest strategies, and deploy live-trading workflows via the QuantConnect API.
- **[Windsor](https://github.com/windsor-ai/windsor_mcp)** - Windsor MCP (Model Context Protocol) enables your LLM to query, explore, and analyze your full-stack business data integrated into Windsor.ai with zero SQL writing or custom scripting.

### Social Media & Communication

- **[Bluesky](https://github.com/keturiosakys/bluesky-context-server)** - integrates with Bluesky API to query and search feeds and posts.
- **[Email](https://github.com/Shy2593666979/mcp-server-email)** - This server enables users to send emails through various email providers, including Gmail, Outlook, Yahoo, Sina, Sohu, 126, 163, and QQ Mail. It also supports attaching files from specified directories, making it easy to upload attachments along with the email content.
- **[Email Send MCP](https://github.com/YUHAI0/email-send-mcp)** - A fixed one from above one. More user-friendly.
- **[gotoolkits/wecombot](https://github.com/gotoolkits/mcp-wecombot-server.git)** - 🏎️ ☁️ An MCP server application that sends various types of messages to the WeCom group robot.
- **[IMAP MCP](https://github.com/dominik1001/imap-mcp)** - 📧 An IMAP Model Context Protocol (MCP) server to expose IMAP operations as tools for AI assistants.
- **[Instagram DMs](https://github.com/trypeggy/instagram_dm_mcp)** - Send Instagram DMs via your LLM
- **[MintMCP](https://github.com/mintmcp/servers)** - MCP servers for Google Calendar, Gmail, Outlook Calendar, and Outlook.
- **[Multi Chat MCP Server (Google Chat)](https://github.com/siva010928/multi-chat-mcp-server)** - Connect AI assistants like Cursor to Google Chat and beyond — enabling smart, extensible collaboration across chat platforms.
- **[Ntfy](https://github.com/gitmotion/ntfy-me-mcp)** - An ntfy MCP server for sending/fetching ntfy notifications to your self-hosted ntfy server from AI Agents 📤 (supports secure token auth & more - use with npx or docker!)
- **[Reminder](https://github.com/arifszn/reminder-mcp)** - MCP server for scheduling and triggering reminders via Slack or Telegram.
- **[Slack](https://github.com/korotovsky/slack-mcp-server)** - The most powerful MCP server for Slack Workspaces. This integration supports both Stdio and SSE transports, proxy settings and does not require any permissions or bots being created or approved by Workspace admins 😏.
- **[TikTok](https://github.com/Seym0n/tiktok-mcp)** - TikTok integration for getting post details and video subtitles
- **[Wassenger](https://github.com/wassengerhq/mcp-wassenger)** - [Wassenger](https://wassenger.com) MCP server to chat, send messages and automate WhatsApp from any AI model client (free trial available).
- **[Webex](https://github.com/Kashyap-AI-ML-Solutions/webex-messaging-mcp-server)** - A Model Context Protocol (MCP) server that provides AI assistants with comprehensive access to Cisco Webex messaging capabilities.
- **[X (Twitter)](https://github.com/mbelinky/x-mcp-server)** - Enhanced MCP server for Twitter/X with OAuth 2.0 support, v2 API media uploads, smart v1.1 fallbacks, and comprehensive rate limiting. Post tweets with text/media, search, and delete tweets programmatically.

### Search & Web

- **[Agentset](https://github.com/agentset-ai/mcp-server)** - RAG MCP for your [Agentset](https://agentset.ai/) data.
- **[Bing Webmaster Tools](https://github.com/isiahw1/mcp-server-bing-webmaster)** - MCP server for Bing Webmaster Tools API integration providing access to search analytics, site management, URL submission, and SEO insights
- **[Exa](https://github.com/theishangoswami/exa-mcp-server)** - Exa AI Search API
- **[Facebook Ads Library](https://github.com/trypeggy/facebook-ads-library-mcp)** - Get any answer from the Facebook Ads Library, conduct deep research including messaging, creative testing and comparisons in seconds.
- **[Google News](https://github.com/ChanMeng666/server-google-news)** - Google News search capabilities with automatic topic categorization and multi-language support via SerpAPI integration.
- **[Google PSE/CSE](https://github.com/rendyfebry/google-pse-mcp)** - A Model Context Protocol (MCP) server providing access to Google Programmable Search Engine (PSE) and Custom Search Engine (CSE).
- **[Google Search Console](https://github.com/ahonn/mcp-server-gsc)** - A Model Context Protocol (MCP) server providing access to Google Search Console.
- **[Jina Reader](https://github.com/wong2/mcp-jina-reader)** - Fetch the content of a remote URL as Markdown with Jina Reader.
- **[just-every/mcp-read-website-fast](https://github.com/just-every/mcp-read-website-fast)** - Fast, token-efficient web content extraction that converts websites to clean Markdown. Features Mozilla Readability, smart caching, polite crawling with robots.txt support, and concurrent fetching with minimal dependencies.
- **[just-every/mcp-screenshot-website-fast](https://github.com/just-every/mcp-screenshot-website-fast)** - High-quality screenshot capture optimized for Claude Vision API. Automatically tiles full pages into 1072x1072 chunks (1.15 megapixels) with configurable viewports and wait strategies for dynamic content.
- **[Kagi](https://github.com/ac3xx/mcp-servers-kagi)** - Kagi search API integration
- **[MCP-SearXNG-Enhanced Web Search](https://github.com/OvertliDS/mcp-searxng-enhanced)** - An enhanced MCP server for SearXNG web searching, utilizing a category-aware web-search, web-scraping, and includes a date/time retrieval tool.
- **[Nexus](https://github.com/adawalli/nexus)** - Web search server that integrates Perplexity Sonar models via OpenRouter API for real-time, context-aware search with citations
- **[Perplexity](https://github.com/tanigami/mcp-server-perplexity)** - Interacting with Perplexity
- **[ScrapeGraphAI](https://github.com/ScrapeGraphAI/Scrapegraph-ai)** - AI-powered web scraping library that creates scraping pipelines using natural language.- [ScrapeGraphAI](https://scrapegraphai.com)
- **[Search1API](https://github.com/fatwang2/search1api-mcp)** - Search and crawl in one API
- **[SearXNG](https://github.com/ihor-sokoliuk/mcp-searxng)** - A Model Context Protocol Server for [SearXNG](https://docs.searxng.org)
- **[Secure Fetch](https://github.com/appsec-innovation-labs/secure-mcp-fetch)** - Secure fetch to prevent access to local resources
- **[Skyvern](https://github.com/Skyvern-AI/skyvern/tree/main/integrations/mcp)** - MCP Server to let Claude / your AI control the browser
- **[Toprank](https://github.com/nowork-studio/toprank)** - MCP-powered Claude Code workflow pack for SEO and Google Ads that auto-configures AdsAgent MCP and works with Google Search Console compatible servers for search analytics and site optimization.
- **[Web Search MCP](https://github.com/mrkrsl/web-search-mcp)** - A server that provides local, full web search, summaries and page extration for use with Local LLMs.
- **[WebSearch-MCP](https://github.com/mnhlt/WebSearch-MCP)** - Self-hosted Websearch API
- **[Website Snapshot](https://github.com/gustavo-meilus/mcp-web-snapshot)** - A MCP server that provides comprehensive website snapshot capabilities using Playwright. This server enables LLMs to capture and analyze web pages through structured accessibility snapshots, network monitoring, and console message collection.

### Productivity & Business

- **[Apple Notes](https://github.com/RafalWilinski/mcp-apple-notes)** - Talk with your Apple Notes
- **[Apple Shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts)** - An MCP Server Integration with Apple Shortcuts
- **[Basecamp](https://github.com/georgeantonopoulos/Basecamp-MCP-Server)** - Integration with Basecamp project management platform for managing projects, to-dos, card tables, documents, and team collaboration
- **[CalDAV MCP](https://github.com/dominik1001/caldav-mcp)** - A CalDAV MCP server to expose calendar operations as tools for AI assistants.
- **[Canvas LMS](https://github.com/ahnopologetic/canvas-lms-mcp)** - MCP server for easy access to education data through your Canvas LMS instance.
- **[Career Site Jobs](https://apify.com/fantastic-jobs/career-site-job-listing-api/api/mcp)** - A MCP server to retrieve up-to-date jobs from company career sites.
- **[Danielpeter-99/calcom-mcp](https://github.com/Danielpeter-99/calcom-mcp)** - MCP server for [Calcom](https://cal.com/) (Also known as [Cal.com](https://cal.com/)). Manage event types, create bookings, and access Cal.com scheduling data through LLMs.
- **[Google Admin MCP](https://github.com/securityfortech/google-admin-mcp)** – A Model Context Protocol (MCP) server enabling interaction with Google Admin APIs.
- **[Google Keep](https://github.com/feuerdev/keep-mcp)** - Read, create, update and delete Google Keep notes.
- **[HAP-MCP](https://github.com/mingdaocloud/hap-mcp.git)** - HAP (Super Application Platform) is developed by Mingdao（ https://www.mingdao.com ）The launched APaaS platform helps you build enterprise level applications quickly without coding. This is HAP's MCP (Model Context Protocol) server, used for seamless integration of AI. It enables every zero code application built through HAP to quickly become a tool for agents.
- **[Jira Context MCP](https://github.com/rahulthedevil/Jira-Context-MCP)** - MCP server to provide Jira Tickets information to AI coding agents like Cursor.
- **[Jira MCP Server](https://github.com/ahmetbarut/jira-mcp)** A modular and extensible MCP server designed to interact with Jira Cloud, providing tools to query boards, issues, and user data — ideal for integrating Jira with AI agents, bots, or automation systems
- **[Lazy Toggl MCP](https://github.com/movstox/lazy-toggl-mcp)** - Simple unofficial MCP server to track time via Toggl API
- **[Linear](https://github.com/tacticlaunch/mcp-linear)** - Integrates with Linear project management systems.
- **[Local History MCP](https://github.com/xxczaki/local-history-mcp)** – MCP server for accessing VS Code/Cursor's Local History.
- **[Make](https://github.com/integromat/make-mcp-server)** - Turn your Make scenarios into callable tools for AI assistants.
- **[Microsoft 365](https://github.com/softeria/ms-365-mcp-server)** 📇 ☁️ - MCP server that connects to the whole Microsoft 365 suite (Microsoft Office, Outlook, Excel) using Graph API (including mail, files, calendar)
- **[Miro](https://github.com/k-jarzyna/mcp-miro)** - Miro MCP server, exposing all functionalities available in official Miro SDK.
- **[Nextcloud Calendar](https://github.com/Cheffromspace/mcp-nextcloud-calendar)** - CalDAV Nectcloud calendar integration. Manage calendars, events, attendees, etc.
- **[NodeCodeStudio](https://nodecodestudio.com)** - Activate MCP services (Gmail, Calendar, WordPress, etc.) and run browser automation workflows via a Chrome extension with importable sequences
- **[Notion](https://github.com/danhilse/notion_mcp)** - Integrates with Notion's API to manage personal todo list
- **[Obsidian](https://github.com/MarkusPfundstein/mcp-obsidian)** - Interacting with Obsidian via REST API
- **[Odoo](https://github.com/ivnvxd/mcp-server-odoo)** - Connect AI assistants to Odoo ERP systems for business data access and workflow automation.
- **[Phabricator](https://github.com/baba786/phabricator-mcp-server)** - Interacting with Phabricator API
- **[Project Manager](https://github.com/croffasia/mcp-project-manager)** - Hierarchical task management (ideas → epics → tasks) with CLI dashboard
- **[slite-mcp](https://github.com/fajarmf/slite-mcp)** - Model Context Protocol server for Slite integration. Search and retrieve notes, browse note hierarchies, and access content from your Slite workspace.
- **[Squad AI](https://github.com/the-basilisk-ai/squad-mcp)** – Product‑discovery and strategy platform integration. Create, query and update opportunities, solutions, outcomes, requirements and feedback from any MCP‑aware LLM.
- **[Task Orchestrator](https://github.com/EchoingVesper/mcp-task-orchestrator)** - AI-powered task orchestration and workflow automation with specialized agent roles, intelligent task decomposition, and seamless integration across Claude Desktop, Cursor IDE, Windsurf, and VS Code.
- **[Tasks](https://github.com/flesler/mcp-tasks)** - An efficient task manager. Designed to minimize tool confusion and maximize LLM budget efficiency while providing powerful search, filtering, and organization capabilities across multiple file formats (Markdown, JSON, YAML)
- **[Todoist](https://github.com/stanislavlysenko0912/todoist-mcp-server)** - Full implementation of Todoist Rest API for MCP server
- **[Trello](https://github.com/m0xai/trello-mcp-server)** - Trello integration for working with boards, lists in boards and cards in lists.
- **[Trello MCP](https://github.com/kocakli/Trello-Desktop-MCP)** - Trello Desktop MCP server that enables Claude Desktop to interact with Trello boards, cards, lists, and team members through natural language commands.
- **[Yuga Planner](https://github.com/blackopsrepl/yuga-planner)** - AI Task schedule planning with LLamaIndex and Timefold: breaks down a task description and schedules it around an existing calendar

### Security & Compliance

- **[BloodHound-MCP](https://github.com/MorDavid/BloodHound-MCP-AI)** (by MorDavid) - integration that connects BloodHound with AI through MCP, allowing security professionals to analyze Active Directory attack paths using natural language queries instead of Cypher.
- **[irulescan MCP](https://github.com/simonkowallik/irulescan?tab=readme-ov-file#mcp-server)** - :shield: MCP enabled code security analyzer for F5 iRules
- **[Keycloak MCP Server](https://github.com/sshaaf/keycloak-mcp-server)** - designed to work with Keycloak for identity and access management, with about 40+ tools covering, Users, Realms, Clients, Roles, Groups, IDPs, Authentication. Native builds available.
- **[Microsoft Entra ID MCP Server](https://github.com/hieuttmmo/entraid-mcp-server)** - A Python MCP server for Microsoft Entra ID (Azure AD) directory, user, group, device, sign-in, and security operations via Microsoft Graph.
- **[OSV](https://github.com/StacklokLabs/osv-mcp)** - Access the [OSV (Open Source Vulnerabilities) database](https://osv.dev/) for vulnerability information. Query vulnerabilities by package version or commit, batch query multiple packages, and get detailed vulnerability information by ID.
- **[Sonatype MCP Server](https://github.com/brianveltman/sonatype-mcp)** - MCP for Sonatype Nexus Repository Manager and Sonatype Repository Firewall. Manage your DevSecOps practices through AI-assisted Workflows.

### Analytics & Monitoring

- **[Alertmanager](https://github.com/ntk148v/alertmanager-mcp-server)** - A Model Context Protocol (MCP) server that enables AI assistants to integrate with Prometheus Alertmanager
- **[Comet Opik](https://github.com/comet-ml/opik-mcp)** - MCP server to talk to your [Opik](https://github.com/comet-ml/opik) cloud or open-source instance to query and analyze LLM traces, metrics and observability.
- **[Fathom Analytics](https://github.com/mackenly/mcp-fathom-analytics)** - Access and analyze Fathom Analytics data and reports
- **[Rootly-AI-Labs/Rootly-MCP-server](https://github.com/Rootly-AI-Labs/Rootly-MCP-server)** - MCP server for the incident management platform [Rootly](https://rootly.com/).

### Other

- **[AllInOneMCP](https://github.com/particlefuture/MCPDiscovery) - MCP of MCPs. A central hub for MCP servers. Helps you discover available MCP servers and learn how to install and use them. REMOTE! Use the url [https://mcp.pfvc.io/mcp/](https://mcp.pfvc.io/mcp/) to add the server. **Remember the final backslash\*\*.
- **[Android MCP](https://github.com/minhalvp/android-mcp-server)** - 📲 An MCP server that provides control over Android devices through ADB. Offers device screenshot capture, UI layout analysis, package management, and ADB command execution capabilities.
- **[AniList](https://github.com/yuna0x0/anilist-mcp)** - AniList MCP server for accessing AniList API data
- **[AnkiConnect](https://github.com/spacholski1225/anki-connect-mcp)** - AnkiConnect MCP server for interacting with Anki via AnkiConnect.
- **[BGG MCP](https://github.com/kkjdaniel/bgg-mcp)** - BGG MCP enables AI tools to interact with the BoardGameGeek API.
- **[Box](https://github.com/hmk/box-mcp-server)** - File access and search for Box.
- **[Calculator](https://github.com/githejie/mcp-server-calculator)** - This server enables LLMs to use calculator for precise numerical calculations.
- **[Chaitin IP Intelligence](https://github.com/co0ontty/chaitin-ip-intelligence-search-tool)** - Search for IP addresses using Chaitin's IP Intelligence API.
- **[Chart](https://github.com/KamranBiglari/mcp-server-chart)** - This server offers a wide variety of chart types with comprehensive Zod schema validation for type-safe chart configuration.
- **[ChuckNorris](https://github.com/pollinations/chucknorris-mcp)** - A specialized MCP gateway for LLM enhancement prompts and jailbreaks with dynamic schema adaptation. Provides prompts for different LLMs using an enum-based approach.
- **[context-awesome](https://github.com/bh-rat/context-awesome)** - A MCP server for querying 8,500+ curated awesome lists (1M+ items) and fetching the best resources for your agent.
- **[DifyWorkflow](https://github.com/gotoolkits/mcp-difyworkflow-server)** - Tools to the query and execute of Dify workflows
- **[Everything Search](https://github.com/mamertofabian/mcp-everything-search)** - Fast Windows file search using Everything SDK
- **[fast-filesystem-mcp](https://github.com/efforthye/fast-filesystem-mcp)** - Advanced filesystem operations with large file handling capabilities and Claude-optimized features. Provides fast file reading/writing, sequential reading for large files, directory operations, file search, and streaming writes with backup & recovery.
- **[FHIR MCP](https://github.com/the-momentum/fhir-mcp-server)** - MCP Server that connects AI agents to FHIR servers
- **[HAL](https://github.com/dean/HAL)** - HTTP toolkit providing all 7 HTTP methods (GET, POST, PUT, PATCH, DELETE, HEAD, OPTIONS) with secret substitution, comprehensive error handling, and support for JSON, XML, HTML, and form data.
- **[Home Assistant](https://github.com/voska/hass-mcp)** - Interact with Home Assistant to control smart home devices, query states, manage automations, and troubleshoot your smart home setup.
- **[Homey](https://github.com/pigmej/python-homey-mcp)** - Interact with Homey to control smart home system. Supports devices, flows, and zones. Contains a few goodies for better integrations with LLMs.
- **[Homebrew MCP](https://github.com/jeannier/homebrew-mcp)** - Interact with Homebrew (the package manager for macOS and Linux) using natural language commands.
- **[Inspektor Gadget MCP server](https://github.com/inspektor-gadget/ig-mcp-server)** - Debug your Container and Kubernetes workloads with an AI interface powered by eBPF.
- **[interactive-mcp](https://github.com/ttommyth/interactive-mcp)** 📇 - Enables interactive LLM workflows by adding local user prompts and chat capabilities directly into the MCP loop.
- **[aymericzip/intlayer](https://github.com/aymericzip/intlayer)** - A MCP Server that enhance your IDE with AI-powered assistance for Intlayer i18n / CMS tool: smart CLI access, versioned docs.
- **[Israel Statistics MCP](https://github.com/reuvenaor/israel-statistics-mcp)** MCP server that provides programmatic access to the Israeli Central Bureau of Statistics (CBS) price indices and economic data.
- **[KnowAir Weather](https://github.com/shuowang-ai/Weather-MCP)** – Real-time weather **and air quality** via the Caiyun Weather API (meteorology + AQI, CN & US standards).
- **[MCP Open Library](https://github.com/8enSmith/mcp-open-library)** - A Model Context Protocol (MCP) server for the Open Library API that enables AI assistants to search for book and author information.
- **[Nanoleaf](https://github.com/srnetadmin/nanoleaf-mcp-server)** - Control Nanoleaf smart lights through MCP - turn on/off, adjust brightness, change colors, set effects, and discover devices
- **[Netbird](https://github.com/aantti/mcp-netbird)** - List and analyze Netbird network peers, groups, policies, and more.
- **[Paperless-MCP](https://github.com/baruchiro/paperless-mcp)** - An MCP server for interacting with a Paperless-NGX API server. This server provides tools for managing documents, tags, correspondents, and document types in your Paperless-NGX instance.
- **[PBS API](https://github.com/matthewdcage/pbs-mcp-server)** - 🐍 ☁️ Access Australian Pharmaceutical Benefits Scheme data for medicine information, pricing, and availability. Built with Python and FastAPI.
- **[Peekaboo](https://github.com/steipete/Peekaboo)** - a macOS-only MCP server that enables AI agents to capture screenshots of applications, or the entire system.
- **[Poland KRS](https://github.com/pkolawa/krs-poland-mcp-server)** - Access to Polish National Court Register (KRS)—the government's authoritative registry of all businesses, foundations, and other legal entities.
- **[Public APIs MCP](https://github.com/zazencodes/public-apis-mcp)** - Search for free APIs using MCP.
- **[QGIS](https://github.com/jjsantos01/qgis_mcp)** - connects QGIS Desktop to Claude AI through the MCP. This integration enables prompt-assisted project creation, layer loading, code execution, and more.
- **[Random Number](https://github.com/zazencodes/random-number-mcp)** - Provides LLMs with essential random generation abilities, built entirely on Python's standard library.
- **[Salaah MCP](https://github.com/yusufk/salaah-mcp)** - FastAPI and MCP service providing Islamic prayer times and other useful calculations.
- **[scan-mcp](https://github.com/jacksenechal/scan-mcp)** - Minimal MCP server for scanner capture (ADF/duplex/page-size); typed tools; JSON Schema–validated I/O; multipage assembly; Node 22 + SANE.
- **[Screeny](https://github.com/rohanrav/screeny)** - Privacy-first macOS MCP server that provides visual context for AI agents through window screenshots
- \*\*[Spotify Player](https://github.com/vsaez/mcp-spotify-player) – Control Spotify playback, queue, volume and playlists from Claude/Cursor via MCP. (Python)
- **[Time](https://github.com/TheoBrigitte/mcp-time)** - MCP server which provides utilities to work with time and dates, with natural language, multiple formats and timezone convertion capabilities.
- **[Tmux](https://github.com/nickgnd/tmux-mcp)** - Interact with your Tmux sessions, windows and pane, execute commands in tmux panes and retrieve result.
- **[User Feedback](https://github.com/mrexodia/user-feedback-mcp)** - Simple MCP Server to enable a human-in-the-loop workflow in tools like Cline and Cursor.
- **[User Prompt MCP](https://github.com/nazar256/user-prompt-mcp)** - An MCP server for Cursor that enables requesting user input during generation process.
- **[Vectorize](https://github.com/vectorize-io/vectorize-mcp-server/)** - [Vectorize](https://vectorize.io) MCP server for advanced retrieval, Private Deep Research, Anything-to-Markdown file extraction and text chunking.
- **[Weather](https://github.com/TimLukaHorstmann/mcp-weather)** - Accurate weather forecasts via the AccuWeather API (free tier available).
- **[Whois MCP](https://github.com/bharathvaj-ganesan/whois-mcp)** - MCP server that performs whois lookup against domain, IP, ASN and TLD.
- **[Windows Control](https://github.com/Cheffromspace/nutjs-windows-control)** - Programmatic control over Windows system operations including mouse, keyboard, window management, and screen capture using nut.js.

## Clients

- **[MBro](https://github.com/sitbon/magg/blob/main/docs/mbro.md)** - A powerful interactive terminal **M**CP **Bro**wser client with tab completion and automatic documentation that allows you to work with multiple MCP servers, manage tools, and create complex workflows using AI assistants.
- **[mcp-cli](https://github.com/wong2/mcp-cli)** a cli inspector for MCP servers
- **[mcp-client](https://github.com/rakesh-eltropy/mcp-client)** MCP REST API and CLI client for interacting with MCP servers, supports OpenAI, Claude, Gemini, Ollama etc.
- **[MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge)** 🐍 an openAI middleware proxy to use mcp in any existing openAI compatible client
- **[MCP-Chatbot](https://github.com/3choff/mcp-chatbot)** A simple yet powerful ⭐ CLI chatbot that integrates tool servers with any OpenAI-compatible LLM API.
- **[Zed](https://github.com/zed-industries/zed)** multiplayer code editor from the creators of atom
- **[genkit](https://github.com/firebase/genkit)** agent and data transformation framework
- **[Continue](https://github.com/continuedev/continue)** vscode auto complete and chat tool (full feature support)
- **[gpt-computer-assistant](https://github.com/Upsonic/gpt-computer-assistant)** dockerized mcp client with Anthropic, OpenAI and Langchain.
- **[MCP-Connect](https://github.com/EvalsOne/mcp-connect)** A client that enables cloud-based AI services to access local Stdio based MCP servers by HTTP/HTTPS requests.
- **[codemirror-mcp](https://github.com/marimo-team/codemirror-mcp)** CodeMirror extension that implements the Model Context Protocol (MCP) for resource mentions and prompt commands.
- **[LibreChat](https://www.librechat.ai/)** Open-source AI Web UI, supporting multiple providers including OpenAI, Anthropic, Google, Ollama, and local models. Includes MCP support for Agents.
- **[mcphub.nvim](https://github.com/ravitemer/mcphub.nvim)** A Neovim plugin that provides a UI and api to interact with MCP servers.
- **[Nerve](https://github.com/evilsocket/nerve)** is an open source command line tool designed to be a simple yet powerful platform for creating and executing MCP integrated LLM-based agents.
- **[Shinkai](http://github.com/dcSpark/shinkai-apps/)** is a two click install AI manager (Local and Remote) that allows you to create AI agents in 5 minutes or less using a simple UI. Agents and tools are exposed as an MCP Server.
- **[mcps-playground](https://mcpsplayground.com/chat)** a playground for Remote MCP servers

## Frameworks

- **[create-mcp-ts](https://github.com/stephencme/create-mcp-ts)** - Create a new MCP server in TypeScript, batteries included - supports user-defined templates!
- **[LiteMCP](https://github.com/wong2/litemcp)** - A TypeScript framework for building MCP servers elegantly
- **[mcp-framework](https://github.com/QuantGeekDev/mcp-framework)** - Fast and elegant Typescript framework for building MCP servers
- **[MCP Plexus](https://github.com/super-i-tech/mcp_plexus)**: A secure, **multi-tenant** Python MCP server framework built to integrate easily with external services via OAuth 2.1, offering scalable and robust solutions for managing complex AI applications.
- **[oatpp-mcp](https://github.com/oatpp/oatpp-mcp)** - Anthropic's Model Context Protocol implementation for Oat++
- **[centralmind/gateway](https://github.com/centralmind/gateway)** - CLI that generates MCP tools based on your Database schema and data using AI and host as REST, MCP or MCP-SSE server
- **[ToolHive](https://github.com/Stacklok/toolhive)** - A lightweight utility designed to simplify the deployment and management of MCP servers, ensuring ease of use, consistency, and security through containerization

## Related Lists

- **[awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers)** - The original curated list of MCP servers
- **[awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients)** - A curated list of MCP clients
- **[awesome-ai-agents](https://github.com/e2b-dev/awesome-ai-agents)** - A list of AI autonomous agents
- **[awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps)** - A curated collection of awesome LLM apps
- **[modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)** - Official MCP server implementations

## Contributing

Want to add your MCP server? Check out our [Contributing Guide](CONTRIBUTING.md) and open a pull request!

---

<p align="center">
  <sub>If you find this list useful, please give it a ⭐ to help others discover it!</sub>
</p>

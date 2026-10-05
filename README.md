<p align="center"><!-- awesome:hero --><img src=".github/assets/hero.gif" width="100%" alt="Animated isometric scene: code sheets ride a belt through build, test and deploy gates, becoming checked containers that enter a server rack, until its alert beacon flashes red and an agent arm swings over to turn it green."><!-- /awesome:hero --></p>

<!-- awesome:title --><h1 align="center">Awesome Agentic DevOps</h1><!-- /awesome:title -->

<p align="center"><!-- awesome:tagline -->AI SRE and incident agents, infrastructure agents, CI/CD agents and the tools that let agents run operations.<!-- /awesome:tagline --></p>

<!-- awesome:badges -->
<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="contributing.md"><img src="https://img.shields.io/badge/PRs-welcome-0891B2" alt="PRs welcome"></a>
  <a href="https://github.com/ianwieds/awesome-agentic-devops/commits/main"><img src="https://img.shields.io/github/last-commit/ianwieds/awesome-agentic-devops?color=0891B2" alt="Last commit"></a>
</p>
<!-- /awesome:badges -->

Agentic DevOps puts AI agents to work on operations: they investigate incidents, fix broken clusters, change infrastructure and repair failing pipelines. This list covers AI SRE and incident agents, Kubernetes, cloud and CI/CD agents, the MCP servers and skills that connect agents to ops tools, and the benchmarks that test them.

## Contents

- [AI SRE agents](#ai-sre-agents)
  - [Hosted AI SRE agents](#hosted-ai-sre-agents)
  - [Incident management agents](#incident-management-agents)
  - [Observability platform agents](#observability-platform-agents)
- [Open-source SRE agents](#open-source-sre-agents)
- [Kubernetes agents](#kubernetes-agents)
- [Infrastructure and cloud agents](#infrastructure-and-cloud-agents)
- [CI/CD agents](#cicd-agents)
- [MCP servers for operations](#mcp-servers-for-operations)
  - [Cloud and infrastructure](#cloud-and-infrastructure)
  - [Kubernetes and containers](#kubernetes-and-containers)
  - [Observability and incidents](#observability-and-incidents)
  - [CI/CD and source control](#cicd-and-source-control)
- [Skills and toolkits](#skills-and-toolkits)
- [Benchmarks and research](#benchmarks-and-research)
- [Related lists](#related-lists)
- [Contributing](#contributing)

## AI SRE agents

### Hosted AI SRE agents

- [AWS DevOps Agent](https://aws.amazon.com/devops-agent/) - AWS agent that checks deployments and investigates incidents across your apps and tools.
- [Azure SRE Agent](https://azure.microsoft.com/en-us/products/sre-agent) - Azure service that diagnoses production issues and runs mitigations on Azure resources.
- [Causely](https://www.causely.ai) - Causal reasoning engine that hands AI agents the root cause behind production symptoms.
- [Ciroos](https://ciroos.ai) - AI SRE that finds root causes and cuts toil in large enterprise environments.
- [Cleric](https://cleric.ai) - Agent that follows each change into production and investigates the failures it causes.
- [Deductive AI](https://www.deductive.ai) - AI SRE that stays on call and troubleshoots incidents through to resolution.
- [DrDroid](https://drdroid.io) - AI SRE agent that maps your stack into a knowledge graph for root cause analysis.
- [Hyground](https://hyground.ai) - Self-hosted AI SRE agent that resolves incidents and runs scheduled ops inside your network.
- [Komodor](https://komodor.com) - Kubernetes operations platform that builds, runs and governs AI agents for SRE teams.
- [Lightrun](https://lightrun.com) - Agents with live runtime context that find and fix failures in production software.
- [NeuBird](https://neubird.ai) - Governed hub for the agents that touch production, with shared telemetry and memory.
- [NOFire AI](https://www.nofire.ai) - Maps every production change, by human or agent, and points to the one that broke things.
- [Resolve AI](https://resolve.ai) - AI SRE that goes on call for your team and works incidents through to resolution.
- [RunWhen](https://www.runwhen.com) - Agents that collect data from your stack and run automation to triage tickets and issues.
- [Sherlocks.ai](https://www.sherlocks.ai) - AI SRE that investigates incidents around the clock and finds their root cause.
- [Steadwing](https://www.steadwing.com) - Autonomous on-call engineer that correlates evidence, finds root cause and proposes fixes.
- [TierZero](https://www.tierzero.ai) - Production agents that triage alerts, investigate incidents and fix problems.
- [Traversal](https://www.traversal.com) - AI SRE that cuts alert noise and traces incidents to root cause in complex systems.
- [Wild Moose](https://www.wildmoose.ai) - AI SRE that investigates incidents in real time across logs, metrics and code.

### Incident management agents

- [Better Stack AI SRE](https://betterstack.com/ai-sre) - On-call agent in Better Stack that investigates alerts using your logs and metrics.
- [Harness AI SRE](https://www.harness.io/products/ai-sre) - Harness agent that ties alerts to recent changes and helps responders run incidents.
- [incident.io Investigations](https://incident.io/solution/ai-sre) - incident.io agent that finds root causes from telemetry, code changes and past incidents.
- [PagerDuty SRE Agent](https://www.pagerduty.com/platform/ai-agents/sre/) - PagerDuty agent that triages incidents and suggests next steps for responders.
- [Rootly AI SRE](https://rootly.com/ai-sre) - Rootly agent that runs root cause analysis on incidents and suggests fixes.

### Observability platform agents

- [Dash0 Agent0](https://www.dash0.com/agent0) - Dash0 agent that talks to your telemetry and closes the loop from alert to fix.
- [Datadog Bits Investigation](https://www.datadoghq.com/product/ai/bits-investigation/) - Datadog AI SRE agent, formerly Bits AI SRE, that investigates alerts and finds root causes.
- [Dynatrace Intelligence](https://www.dynatrace.com/platform/artificial-intelligence/) - Dynatrace AI layer that pairs causal analysis with agents that remediate and optimize.
- [Elastic AI Assistant for Observability](https://www.elastic.co/docs/solutions/observability/ai/observability-ai-assistant) - Elastic assistant that explains logs and alerts and runs queries for you.
- [Grafana Assistant](https://grafana.com/docs/grafana-cloud/platform/grafana-assistant/) - Agent in Grafana Cloud that queries data, builds dashboards and investigates issues.
- [Metoro](https://metoro.io/ai-sre-agent) - AI SRE for Kubernetes that finds root causes and opens pull requests with fixes.
- [Middleware OpsAI](https://middleware.io/product/ops-ai/) - Middleware agent that runs root cause analysis across APM, logs and Kubernetes and drafts fixes.
- [New Relic AI](https://newrelic.com/platform/new-relic-ai) - New Relic assistant that answers questions about your telemetry in plain language.
- [Sentry Seer](https://sentry.io/product/seer/) - Sentry agent that finds the root cause of errors and drafts code fixes.

## Open-source SRE agents

- [AURA](https://github.com/mezmo/aura) - Mezmo platform for deploying SRE agents with guardrails, state and streaming built in.
- [Aurora](https://github.com/Arvo-AI/aurora) - LangGraph agents that investigate incidents across AWS, Azure, GCP and Kubernetes.
- [Gilfoyle](https://github.com/axiomhq/gilfoyle) - SRE agent from Axiom that queries your observability stack to find root causes.
- [HolmesGPT](https://github.com/HolmesGPT/holmesgpt) - CNCF sandbox SRE agent that investigates alerts using your observability data.
- [Keep](https://github.com/keephq/keep) - AIOps and alert management platform with AI correlation and automated workflows.
- [NudgeBee](https://github.com/nudgebee/nudgebee) - CloudOps platform with AI agents for SRE, FinOps and Kubernetes operations.
- [OpenSRE](https://github.com/Tracer-Cloud/opensre) - Toolkit from Tracer for building your own AI SRE agents.
- [Opsy](https://github.com/datolabs-io/opsy) - Command-line SRE assistant that splits ops tasks across tool agents for Kubernetes, Git and AWS.
- [Robusta](https://github.com/robusta-dev/robusta) - Kubernetes alert enrichment for Prometheus with AI investigation and automatic remediation.
- [Siclaw](https://github.com/scitix/siclaw) - Read-only investigation copilot for DevOps and SRE teams.
- [SRE Agent](https://github.com/fuzzylabs/sre-agent) - Fuzzy Labs agent that reads logs, diagnoses issues and reports what it found.
- [Stakpak](https://github.com/stakpak/agent) - DevOps agent that lives on your machines and keeps your apps running.
- [Versus Incident](https://github.com/VersusControl/versus-incident) - Self-hosted AI SRE agent that learns normal behavior and escalates only real incidents.

## Kubernetes agents

- [Aegil](https://github.com/pro-deploy/aegil) - Kubernetes SRE agent that pairs deterministic log analysis with an LLM.
- [k8m](https://github.com/weibaohui/k8m) - Lightweight Kubernetes dashboard with built-in AI agents and permission-scoped MCP tools.
- [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) - CLI that scans clusters and explains what is wrong in plain language.
- [K8sGPT Operator](https://github.com/k8sgpt-ai/k8sgpt-operator) - Runs K8sGPT inside the cluster to analyze problems on a schedule.
- [kagent](https://github.com/kagent-dev/kagent) - CNCF framework for running AI agents in Kubernetes as native resources.
- [Kube-Copilot](https://github.com/feiskyer/kube-copilot) - Kubernetes agent that diagnoses problems, audits clusters and writes manifests.
- [kubectl-ai](https://github.com/GoogleCloudPlatform/kubectl-ai) - Google terminal assistant that turns requests into kubectl commands and runs them.
- [Kubernaut](https://github.com/jordigilh/kubernaut) - Takes a Kubernetes alert through AI investigation to an automated, approved fix.
- [Lucas](https://github.com/a2wio/lucas) - In-cluster agent that inspects pods and logs, then reports or fixes issues.
- [Radar](https://github.com/skyhook-io/radar) - Kubernetes UI with a built-in MCP server that shows agents what broke and why.
- [Skyflo](https://github.com/skyflo-ai/skyflo) - Self-hosted Kubernetes and DevOps agent that asks for approval before it changes anything.

## Infrastructure and cloud agents

- [AIAC](https://github.com/gofireflyio/aiac) - CLI from Firefly that generates infrastructure as code from a prompt.
- [Anyshift](https://www.anyshift.io) - Gives AI agents a live map of your infrastructure, apps and the tools around them.
- [Azure Copilot](https://learn.microsoft.com/en-us/azure/copilot/overview) - Assistant in the Azure portal that answers questions and runs tasks on your resources.
- [Cloudgeni](https://cloudgeni.ai) - Finds unmanaged cloud resources and drift and turns fixes into pull requests.
- [CloudOps Multi-Agent System](https://github.com/aws-samples/sample-cloudops-multi-agent-system) - AWS sample of agents that cover health, cost and networking across an organization.
- [env zero](https://www.envzero.com) - Infrastructure-as-code control plane that gives agents one context for safe cloud changes.
- [Firefly](https://www.firefly.ai) - Agents that codify your cloud as infrastructure as code and restore it after outages.
- [Gemini Cloud Assist](https://cloud.google.com/products/gemini/cloud-assist) - Google Cloud assistant that designs, troubleshoots and tunes your deployments.
- [Pulumi Neo](https://www.pulumi.com/product/neo/) - Pulumi agent that provisions, governs and optimizes infrastructure from requests.
- [Red Hat Automation Coding Assistant](https://www.redhat.com/en/technologies/management/ansible/automation-coding-assistant) - Service, formerly Ansible Lightspeed, that writes Ansible YAML from prompts.
- [Sedai](https://sedai.io/) - Agentic platform that tunes Kubernetes and cloud resources to cut cost on its own.
- [Spacelift Intelligence](https://docs.spacelift.io/concepts/intelligence) - Spacelift AI features, Intent and Infra Assistant, for running infrastructure stacks.
- [Spacelift Intent](https://github.com/spacelift-io/spacelift-intent) - Provisions and manages cloud infrastructure from natural language requests.
- [StackGen](https://stackgen.com) - Platform of AI agents for infrastructure, SRE and DevOps work.

## CI/CD agents

- [Chunk](https://chunk.ai/) - CircleCI agent that checks AI-written code in a clean Linux microVM before it reaches CI.
- [Claude Code Action](https://github.com/anthropics/claude-code-action) - GitHub Action that runs Claude Code on pull requests, issues and workflow jobs.
- [Codex Action](https://github.com/openai/codex-action) - GitHub Action that runs OpenAI Codex inside a workflow.
- [Gitar](https://www.sonarsource.com/products/gitar/) - Agent that diagnoses CI failures and pushes fixes to the pull request.
- [GitHub Agentic Workflows](https://github.com/github/gh-aw) - Write GitHub Actions workflows in Markdown and have coding agents run them.
- [GitLab Duo Agent Platform](https://about.gitlab.com/gitlab-duo-agent-platform/) - GitLab platform where agents and flows act across planning, CI/CD and security.
- [Harness Software Delivery Agent](https://www.harness.io/products/software-delivery-agent) - Harness agent that builds and repairs CI/CD pipelines and infrastructure as code.
- [Nx Self-Healing CI](https://nx.dev/docs/features/ci-features/self-healing-ci) - Nx Cloud feature where an agent proposes fixes for failed CI tasks.
- [Run Gemini CLI](https://github.com/google-github-actions/run-gemini-cli) - GitHub Action that runs Gemini CLI for triage, review and other workflow tasks.

## MCP servers for operations

### Cloud and infrastructure

- [AWS MCP Servers](https://github.com/awslabs/mcp) - AWS Labs suite of MCP servers for AWS services, docs and costs.
- [Cloud Run MCP](https://github.com/GoogleCloudPlatform/cloud-run-mcp) - MCP server that deploys apps to Google Cloud Run.
- [Cloudflare MCP](https://github.com/cloudflare/mcp-server-cloudflare) - Cloudflare MCP servers for Workers, DNS, logs and other account services.
- [DigitalOcean MCP](https://github.com/digitalocean-labs/mcp-digitalocean) - MCP server for managing DigitalOcean apps, droplets and other resources.
- [gcloud MCP](https://github.com/googleapis/gcloud-mcp) - MCP server that lets agents run gcloud commands against Google Cloud.
- [Heroku MCP Server](https://github.com/heroku/heroku-mcp-server) - MCP server that manages Heroku apps through the Heroku CLI.
- [Microsoft MCP](https://github.com/microsoft/mcp) - Catalog of official Microsoft MCP servers, the Azure MCP Server among them.
- [OpenTofu MCP Server](https://github.com/opentofu/opentofu-mcp-server) - MCP server that looks up providers and modules in the OpenTofu Registry.
- [Pulumi MCP Server](https://www.pulumi.com/docs/ai/mcp-server/) - Pulumi MCP server that lets agents query the registry and run Pulumi operations.
- [Terraform MCP Server](https://github.com/hashicorp/terraform-mcp-server) - HashiCorp MCP server for the Terraform Registry and HCP Terraform workspaces.
- [Vault MCP Server](https://github.com/hashicorp/vault-mcp-server) - HashiCorp MCP server for managing Vault mounts and secrets.

### Kubernetes and containers

- [ACK MCP Server](https://github.com/aliyun/alibabacloud-ack-mcp-server) - Alibaba Cloud MCP server for operating and diagnosing ACK Kubernetes clusters.
- [AKS MCP](https://github.com/Azure/aks-mcp) - MCP server that lets agents inspect and operate Azure Kubernetes Service clusters.
- [Argo CD MCP](https://github.com/argoproj-labs/mcp-for-argocd) - MCP server for managing Argo CD applications and their sync state.
- [Docker Hub MCP Server](https://github.com/docker/hub-mcp) - Docker MCP server for searching and managing images on Docker Hub.
- [Flux Operator MCP Server](https://fluxoperator.dev/mcp-server/) - MCP server that lets agents inspect and drive Flux GitOps in your clusters.
- [kmcp](https://github.com/kagent-dev/kmcp) - CLI and controller for building, testing and deploying MCP servers on Kubernetes.
- [kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) - MCP server that gives agents kubectl and Helm operations.
- [Kubernetes MCP Server](https://github.com/containers/kubernetes-mcp-server) - Go MCP server for Kubernetes and OpenShift that talks to the API directly.
- [mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) - TypeScript MCP server for kubectl and Helm commands against a cluster.
- [Trivy MCP](https://github.com/aquasecurity/trivy-mcp) - Trivy plugin that lets agents scan images, repos and IaC for vulnerabilities.

### Observability and incidents

- [CloudWatch Logs Analyzer](https://github.com/awslabs/Log-Analyzer-with-MCP) - AWS Labs MCP server for searching and analyzing CloudWatch Logs.
- [Datadog MCP Server](https://github.com/datadog-labs/mcp-server) - Datadog MCP server for querying logs, metrics, traces and incidents.
- [Dynatrace MCP Server](https://docs.dynatrace.com/docs/dynatrace-intelligence/dynatrace-mcp) - Dynatrace MCP server for querying problems, logs and metrics from agents.
- [Grafana MCP](https://github.com/grafana/mcp-grafana) - MCP server for Grafana dashboards, data sources, alerts and incidents.
- [Honeycomb MCP](https://docs.honeycomb.io/integrations/mcp/concepts) - Honeycomb MCP server that lets agents query traces and investigate issues.
- [Loki MCP](https://github.com/grafana/loki-mcp) - MCP server for running LogQL queries against Grafana Loki.
- [New Relic MCP Server](https://docs.newrelic.com/docs/agentic-ai/mcp/overview/) - New Relic MCP server for querying telemetry and alerts from agents.
- [OpenTelemetry MCP Server](https://github.com/traceloop/opentelemetry-mcp-server) - MCP server for querying OpenTelemetry traces in Jaeger, Tempo and other backends.
- [PagerDuty MCP Server](https://docs.pagerduty.com/developer/mcp-tooling-remote-server) - PagerDuty hosted MCP server for incidents, services and on-call schedules.
- [Prometheus MCP](https://github.com/prometheus/prometheus-mcp) - Prometheus project MCP server for running PromQL queries.
- [Rootly MCP Server](https://github.com/rootlyhq/rootly-mcp-server) - Rootly MCP server that pulls incident context into your editor or agent.
- [Sentry MCP](https://github.com/getsentry/toolkit) - Sentry remote MCP server that gives coding agents error and issue context.

### CI/CD and source control

- [Azure DevOps MCP Server](https://github.com/microsoft/azure-devops-mcp) - Microsoft MCP server for Azure DevOps repos, pipelines and work items.
- [Buildkite MCP Server](https://github.com/buildkite/buildkite-mcp-server) - Buildkite MCP server for pipelines, builds and job logs.
- [CircleCI MCP Server](https://circleci.com/docs/guides/toolkit/using-the-circleci-mcp-server/) - CircleCI MCP server that lets agents read build failures and find flaky tests.
- [GitHub MCP Server](https://github.com/github/github-mcp-server) - GitHub MCP server for repos, issues, pull requests and Actions runs.
- [GitLab MCP Server](https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/) - GitLab MCP server for issues, merge requests and pipelines.
- [Harness MCP Server](https://github.com/harness/mcp-server) - Harness MCP server for pipelines, deployments and other Harness resources.
- [Jenkins MCP Server Plugin](https://github.com/jenkinsci/mcp-server-plugin) - Jenkins plugin that serves jobs and builds to agents over MCP.

## Skills and toolkits

- [Agent Toolkit for AWS](https://github.com/aws/agent-toolkit-for-aws) - AWS-supported MCP servers, skills and plugins for agents that build on AWS.
- [Alibaba Cloud Skills](https://github.com/aliyun/alibabacloud-aiops-skills) - Official agent skills for working with Alibaba Cloud products.
- [Azure DevOps Skills](https://github.com/microsoft/azure-devops-skills) - Sample skills and prompts for using the Azure DevOps MCP server with agents.
- [Azure Skills](https://github.com/microsoft/azure-skills) - Microsoft agent plugin with skills and MCP configs for Azure work.
- [DevOps Security Agent Skills](https://github.com/BagelHole/DevOps-Security-Agent-Skills) - Skills for Kubernetes, cloud, CI/CD, security and compliance work.
- [Harness Skills](https://github.com/harness/harness-skills) - Skills that let coding agents create and manage Harness pipelines and resources.
- [HashiCorp Agent Skills](https://github.com/hashicorp/agent-skills) - Agent skills and Claude Code plugins for Terraform, Vault and other HashiCorp tools.
- [Pulumi Agent Skills](https://github.com/pulumi/agent-skills) - Pulumi skills for writing, migrating and operating infrastructure with agents.
- [Terraform Skill](https://github.com/antonbabenko/terraform-skill) - Skill that teaches agents Terraform and OpenTofu testing, modules and CI/CD patterns.
- [Tools for AWS DevOps Agent](https://github.com/aws/tools-for-devops-agent) - Skills, custom agents and tools that extend AWS DevOps Agent.

## Benchmarks and research

- [AIOps in the Era of Large Language Models](https://arxiv.org/abs/2404.09837) - Survey of how LLMs are used for operations tasks such as failure analysis.
- [AIOpsLab](https://github.com/microsoft/AIOpsLab) - Microsoft framework for building and evaluating AIOps agents against injected faults.
- [Automatic Root Cause Analysis via LLMs for Cloud Incidents](https://arxiv.org/abs/2305.15778) - Microsoft paper on RCACopilot, an LLM system for root-causing cloud incidents.
- [ChaosEater](https://github.com/ntt-dkiku/chaos-eater) - LLM system that plans and runs chaos engineering experiments on Kubernetes.
- [ITBench](https://github.com/itbench-hub/ITBench) - Benchmark for agents on SRE, compliance and FinOps tasks.
- [OpenRCA](https://github.com/microsoft/OpenRCA) - Benchmark that tests whether LLMs can find the root cause of software failures.
- [RCAEval](https://github.com/phamquiluan/RCAEval) - Benchmark and datasets for root cause analysis in microservice systems.
- [SREBench](https://www.srebench.com/) - Platform for benchmarking agents that diagnose and fix infrastructure issues.
- [SREGym](https://github.com/SREGym/SREGym) - Benchmark that tests whether AI agents can resolve production incidents.
- [STRATUS](https://arxiv.org/abs/2502.00055) - Paper on a multi-agent system that detects and mitigates cloud failures on its own.

## Related lists

- [AIOps Handbook](https://github.com/chenryn/aiops-handbook) - Slides, repositories and papers about AIOps.
- [Awesome Agentic DevOps (DevOpsAIguru123)](https://github.com/DevOpsAIguru123/awesome-agentic-devops) - Scored catalog of MCP servers, skills and agents for DevOps and SRE.
- [Awesome AI SRE (agamm)](https://github.com/agamm/awesome-ai-sre) - List of AI tools, platforms and resources for site reliability engineering.
- [Awesome AI SRE (pavangudiwada)](https://github.com/pavangudiwada/awesome-ai-sre) - Directory of AI SRE companies and open-source projects.
- [Awesome DevOps MCP Servers](https://github.com/rohitg00/awesome-devops-mcp-servers) - List of MCP servers for DevOps tools.
- [Awesome LLM AIOps](https://github.com/Jun-jie-Huang/awesome-LLM-AIOps) - Papers and industry material on LLMs in IT operations.
- [Awesome MCP Servers for DevOps](https://github.com/WagnerAgent/awesome-mcp-servers-devops) - DevOps-focused list of MCP servers for source control, IaC and Kubernetes.
- [Awesome SRE Agents](https://github.com/last9/awesome-sre-agents) - List of AI agents and tools for DevOps and SRE automation.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first.

<!-- awesome:maintainer -->
Maintained by [Ian Wiedenman](https://github.com/ianwieds).
<!-- /awesome:maintainer -->

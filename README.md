# CTO.ai Delivery Metrics Agent for GitHub.

Automatically record select available LifeCycle events for viewing in the
CTO.ai Delivery Metrics Dashboard.

To use this agent, just drop the provided `ctoai-agent.yml` file into the
workflows folder of the repository you want to instrument:

### Installation

1. From your GitHub repo, click Settings -> Secrets -> New Secret
  - Create CTOAI_TEAM_ID secret using your CTO.ai-issued Team Id.
  - Create CTOAI_EVENTS_API_TOKEN secret using your CTO.ai-issued API Token.
2. Access the CTO.ai Agent workflow from:
  - https://github.com/cto-ai/agent/blob/master/.github/workflows/ctoai-agent.yml
3. Place `ctoai-agent.yml` in the workflows folder of your repo:
  - `.github/workflows/ctoai-agent.yml`
4. You're done! Delivery & LifeCycle Metrics can now be viewed on the Metrics
   Dashboard.

More information on CTO.ai Delivery Metrics can be found at the official
[CTO.ai Documentation](https://cto.ai/docs/delivery-metrics), or at the
[CTO.ai GitHub Action](https://github.com/cto-ai/action).

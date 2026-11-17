# Domain naming matrix

This is the canonical vocabulary for repository, image, service, and artifact names.

## Runtime and deployment names

| Canonical term | Name | Meaning |
| --- | --- | --- |
| Engine compute | `liki-engine` | Deterministic computation image. |
| Engine MCP service | `engine-mcp` | Streamable MCP compute service. |
| Counsel judgment | `liki-counsel` | Judgment image. |
| Counsel MCP service | `counsel-mcp` | Streamable MCP judgment service. |
| Liki product MCP | `liki-mcp` | Product-facing aggregate MCP over selected ENGINE + COUNSEL tools; MCP identity `hk.liki/liki`. |
| AgentGo platform | `agentgo` | Independent standalone agent execution platform used as the base image. |
| Expert assembly | `liki-expert` | Production single-expert aggregate image. |
| Expert service | `expert` | Compose service running `liki-expert`. |
| WorkBuddy paid expert pack | `liki-pro` | The one WorkBuddy paid expert package; domains are internal routing cards. |
| SkillHub free package | `liki-free` | The free SkillHub installable package. |
| WorkBuddy free package | `liki-free` | The free WorkBuddy installable package. |
| Canonical source / npx package | `liki` | The authoritative skill source and free skills CLI package. |
| Web BFF | `liki-web` / `web` | Commerce, identity, chat BFF, and public site. |

`agentgo` is the independent base platform. `liki-expert` is the production aggregate image.

## Artifact names

| Artifact | Name |
| --- | --- |
| AgentGo base | pinned `agentgo:v1.0.0` release image |
| AgentDeployment | `deployment.json` |

## Naming domain

The service/domain is `naming`; `qiming` is not the tool prefix. MCP tools use `naming_*`.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Superfast-Robotics/robot-skill-hub/main/web/brand/wordmark-dark.png">
  <img src="https://raw.githubusercontent.com/Superfast-Robotics/robot-skill-hub/main/web/brand/wordmark-light.png" alt="Superfast Robotics" width="420">
</picture>

<br><br>

![Our direction: Super Fast Robot Agent OS. Starting with Robot Skill Hub.](https://raw.githubusercontent.com/Superfast-Robotics/robot-skill-hub/main/web/github/superfast-robotics.svg)

We are building toward a **Super Fast Robot Agent OS**: a way for agents to find useful robot code, understand its requirements and turn it into a reproducible starting point.

Our first public project is **Robot Skill Hub**.

## Robot Skill Hub

Reusable robot skills with pinned sources, explicit compatibility and evidence you can inspect. Search the public catalog, prepare a skill in your project, and contribute useful fixes through a reviewed pull request.

[**Explore the catalog →**](https://superfastrobotics.com/) · [**View the repository →**](https://github.com/Superfast-Robotics/robot-skill-hub)

| Discover | Understand | Build on it |
| :--- | :--- | :--- |
| Find code by task, runtime and robot. | Inspect exact sources, licenses and verification evidence. | Prepare pinned code; share permitted fixes for review. |

The first preview supports discovery and source preparation for ManiSkill Panda **PickCube-v1** and **StackCube-v1** recipes. The simulation target is Linux x86_64, Python 3.10 and ManiSkill 3.0.0b22. Actual simulator task execution is **`not_run` / 미검증**.

## Start with your agent

```sh
# Codex
npx skills add Superfast-Robotics/robot-skill-hub --skill find-robot-skills -a codex

# Claude Code
npx skills add Superfast-Robotics/robot-skill-hub --skill find-robot-skills -a claude-code
```

[Agent quickstart](https://github.com/Superfast-Robotics/robot-skill-hub/blob/main/docs/agent-quickstart.md) · [Compatibility](https://github.com/Superfast-Robotics/robot-skill-hub/blob/main/docs/compatibility.md) · [Contribute a fix](https://github.com/Superfast-Robotics/robot-skill-hub/blob/main/docs/contributing.md) · [Verified and pending work](https://github.com/Superfast-Robotics/robot-skill-hub/blob/main/docs/verification.md)

---

**Superfast Robotics** · Open code. Clear evidence. Useful next steps.

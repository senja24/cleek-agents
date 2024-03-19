<div align="center"><a name="readme-top"></a>

<img height="120" src="https://registry.npmmirror.com/@lobehub/assets-emoji/1.3.0/files/assets/robot.webp">
<img height="120" src="https://gw.alipayobjects.com/zos/kitchen/qJ3l3EPsdW/split.svg">
<img height="120" src="https://registry.npmmirror.com/@lobehub/assets-emoji/1.3.0/files/assets/convenience-store.webp">

<h1>Cleek Agents Index</h1>

[**Submit Your Agent >>**][submit]

[Cleek](https://cleek.id) accesses [`index.json`][website-url] from this repo to show user the list of available agents for Cleek.
</div>


## 🚀 How to Submit your Agent

You can submit through [**Submit Your Agent**][submit], or use the following steps

### Step-by-step Instructions

If you wish to add an agent onto the index, make an entry in `agents` directory using `agent-template.json` or `agent-template-full.json`, write a short description and tag it appropriately then open as a pull request ty!

1. <kbd>Fork</kbd> of this repository.
2. Make a copy of `agent-template.json` or `agent-template-full.json`
3. Fill in the copy and rename it appropriately
4. Move it into `src` directory
5. Submit a pull request and wait for review.

> \[!IMPORTANT]\
> The `createAt` date will be automatically populated after merge. Please choose the appropriate parameter configuration from `agent-template-full.json` based on your specific needs. This file provides a more comprehensive set of parameters for customization.

> \[!NOTE]
>
> - Not all agents will be accepted, we will review the agent and make an assessment.
> - You can submit agents even if you are not the author, but it is preferred that the author do it themselves.
> - If you wish to have your agent removed, or believes the description does not properly describe your agent, please open the issue or pull request.

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## 🛳 Self Hosting

If you want to deploy this service by yourself, you can follow the steps below.

### Deploy to Vercel

Click button below to deploy your private agents index.

[![][vercel-deploy-shield]][vercel-deploy-link]

<div align="right">

[![][back-to-top]](#readme-top)

</div>

## ⌨️ Local Development

You can use GitHub Codespaces for online development:

[![][github-codespace-shield]][github-codespace-link]

Alternatively, you can use the following command for local development:

[![][bun-shield]][bun-link]

```bash
$ git clone https://github.com/senja24/cleek-agents.git
$ cd cleek-agents
$ bun install
```

If you need to run the `format` script locally, you need to configure the corresponding environment variables:

| Environment Variable | Type     | Example              |
| -------------------- | -------- | -------------------- |
| `OPENAI_API_KEY`     | Required | `sk-xxxxxx...xxxxxx` |
| `OPENAI_PROXY_URL`   | Optional | `-`                  |

<div align="right">

[![][back-to-top]](#readme-top)

</div>
---

#### 📝 License

Copyright © 2024 [Cleek][profile-url]. <br />
This project is [MIT](./LICENSE) licensed.

<!-- LINK GROUP -->

[back-to-top]: https://img.shields.io/badge/-BACK_TO_TOP-black?style=flat-square
[bun-link]: https://bun.sh
[bun-shield]: https://img.shields.io/badge/-speedup%20with%20bun-black?logo=bun&style=for-the-badge
[github-action-release-link]: https://github.com/senja24/cleek-agents/actions/workflows/release.yml
[github-action-release-shield]: https://img.shields.io/github/actions/workflow/status/senja24/cleek-agents/release.yml?label=release&labelColor=black&logo=githubactions&logoColor=white&style=flat-square
[github-action-test-link]: https://github.com/senja24/cleek-agents/actions/workflows/test.yml
[github-action-test-shield]: https://img.shields.io/github/actions/workflow/status/senja24/cleek-agents/test.yml?label=test&labelColor=black&logo=githubactions&logoColor=white&style=flat-square
[github-codespace-link]: https://codespaces.new/senja24/cleek-agents
[github-codespace-shield]: https://github.com/codespaces/badge.svg
[github-contrib-link]: https://github.com/senja24/cleek-agents/graphs/contributors
[github-contrib-shield]: https://contrib.rocks/image?repo=cleek%2Fcleek-agents
[github-contributors-link]: https://github.com/senja24/cleek-agents/graphs/contributors
[github-contributors-shield]: https://img.shields.io/github/contributors/senja24/cleek-agents?color=c4f042&labelColor=black&style=flat-square
[github-forks-link]: https://github.com/senja24/cleek-agents/network/members
[github-forks-shield]: https://img.shields.io/github/forks/senja24/cleek-agents?color=8ae8ff&labelColor=black&style=flat-square
[github-issues-link]: https://github.com/senja24/cleek-agents/issues
[github-issues-shield]: https://img.shields.io/github/issues/senja24/cleek-agents?color=ff80eb&labelColor=black&style=flat-square
[github-stars-link]: https://github.com/senja24/cleek-agents/network/stargazers
[github-stars-shield]: https://img.shields.io/github/stars/senja24/cleek-agents?color=ffcb47&labelColor=black&style=flat-square
[pr-welcome-shield]: https://img.shields.io/badge/🤖/🏪_submit_agent-%E2%86%92-c4f042?labelColor=black&style=for-the-badge
[profile-url]: https://github.com/senja24
[submit]: https://github.com/senja24/cleek-agents/issues/new/choose
[vercel-deploy-link]: https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fsenja24%2Fcleek-agents&project-name=cleek-agents&repository-name=cleek-agents
[vercel-deploy-shield]: https://vercel.com/button
[website-shield]: https://img.shields.io/website?down_message=offline&label=chat-agents.cleek.id&up_message=online&url=https%3A%2F%2Fchat-agents.cleek.id&labelColor=black&logo=vercel&style=flat-square
[website-url]: https://chat-agents.cleek.id

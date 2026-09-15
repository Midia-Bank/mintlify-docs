# ⚠️ Repositório aposentado

**A fonte oficial da documentação da Solomon é [`Midia-Bank/docs`](https://github.com/Midia-Bank/docs)** — é de lá que `docs.solomon.com.br` e `solomon.mintlify.app` são publicados, com a integração do GitHub App da Mintlify (dashboard-editor + PRs automáticas de changelog).

Este repositório (`mintlify-docs`) foi criado em 01/07/2026 como um snapshot e não recebe atividade desde então — nunca foi a fonte publicada em produção. Ele diverge de `Midia-Bank/docs` (que segue sendo atualizado; hoje tem changelog, `api-reference/costs`, `api-reference/influencers` e `management/*` que este repositório não tem).

**Se você chegou aqui procurando onde editar a documentação, é em [`Midia-Bank/docs`](https://github.com/Midia-Bank/docs).**

Nada foi apagado — o conteúdo deste repositório continua aqui como histórico.

---

<details>
<summary>README original (Mintlify Starter Kit)</summary>

# Mintlify Starter Kit

Use the starter kit to get your docs deployed and ready to customize.

Click the green **Use this template** button at the top of this repo to copy the Mintlify starter kit. The starter kit contains examples with

- Guide pages
- Navigation
- Customizations
- API reference pages
- Use of popular components

**[Follow the full quickstart guide](https://starter.mintlify.com/quickstart)**

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview your documentation changes locally. To install, use the following command:

```
npm i -g mint
```

Run the following command at the root of your documentation, where your `docs.json` is located:

```
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Install our GitHub app from your [dashboard](https://dashboard.mintlify.com/settings/organization/github-app) to propagate changes from your repo to your deployment. Changes are deployed to production automatically after pushing to the default branch.

## Need help?

### Troubleshooting

- If your dev environment isn't running: Run `mint update` to ensure you have the most recent version of the CLI.
- If a page loads as a 404: Make sure you are running in a folder with a valid `docs.json`.

### Resources
- [Mintlify documentation](https://mintlify.com/docs)

</details>

# ⚠️ Antes de editar aqui, confira com o time

Uma checagem em 15/09/2026 encontrou outro repositório de documentação, [`Midia-Bank/docs`](https://github.com/Midia-Bank/docs), que parece mais atualizado que este:

- `docs` teve commits nos últimos 30 dias; este repositório não tem mudança desde a criação (01/07/2026, um commit só).
- `docs.solomon.com.br` e `solomon.mintlify.app` parecem servir o conteúdo de `docs`, não o deste repositório.
- `docs` tem páginas que este não tem (changelog, `api-reference/costs`, `api-reference/influencers`, `management/*`).

**Isso NÃO é uma decisão oficial de que este repositório está aposentado** — é só o que uma checagem pontual encontrou, e ninguém do time confirmou ainda. Se você sabe que este repositório ainda é usado por algum motivo que essa checagem não capturou, ignore este aviso (ou apague-o).

Nada foi apagado — é só um aviso, reversível.

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

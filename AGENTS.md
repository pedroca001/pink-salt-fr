# AGENTS.md - pink-salt-fr

## Purpose

- Papel do repo: pagina/advertorial VSL Pink Salt FR, com black `/selrose/` e white `/blog`.
- Stack / operacao: HTML/CSS/JS estatico.
- Raiz de codigo: `<CODIGO_ROOT>\pink-salt-fr`.

## Ownership

- Ficha canonica no Brain: `<BRAIN_ROOT>\Paginas\pink_salt_vsl_page.md`.
- Operacao/deploy: GitHub Pages/CNAME; repo publico com cautela.

## Local Contracts

- Comandos principais: abrir `index.html` ou servir com `python -m http.server 8000`.
- Segredos proibidos: valores de `.env`, tokens, API keys, service keys, cookies, credenciais, exports privados, dados de cliente/membro e qualquer segredo de producao. Documente apenas nomes.
- Risco/cuidado local: repo publico; nao adicionar README/info sensivel, secrets, checkout privado ou estrategia de cloaking. Ler ficha antes de alterar rotas.
- Preserve trabalho do usuario: nao use reset, checkout, delete ou moves em massa sem aprovacao explicita.
- Use caminhos portateis em docs: `<BRAIN_ROOT>` e `<CODIGO_ROOT>`, nunca drive/letra/usuario fixo.

## Work Guidance

- Antes de editar, leia `<BRAIN_ROOT>\AGENTS.md`, `<CODIGO_ROOT>\AGENTS.md`, este arquivo e a ficha canonica em Ownership.
- Siga padroes, scripts e estrutura ja existentes neste repo antes de criar abstracoes novas.
- Antes de deploy, rota, checkout, Worker, DNS, banco, auth ou automacao, confirme o alvo operacional na ficha Brain.
- Mantenha outputs, midias, caches, `node_modules`, builds e stores locais de credenciais fora do Git salvo regra explicita do repo.

## Verification

- Verificacao base: Sirva localmente com `python -m http.server 8000` e confira a pagina ou rota principal no navegador.
- Rode tambem qualquer teste, lint, build, typecheck, dry-run ou checagem manual mais estreita que combine com os arquivos tocados.
- Se a verificacao nao puder rodar, registre o bloqueio e o risco residual.

## Child DOX Index

- Nenhum `AGENTS.md` filho existe hoje. Este arquivo cobre o repo inteiro ate uma subpasta virar fronteira duravel propria.

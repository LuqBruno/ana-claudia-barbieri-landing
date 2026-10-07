# Prévia — Ana Cláudia Barbieri Arquitetura

Landing de demonstração comercial para apresentar uma página de projetos residenciais com briefing de orçamento. **Não representa contratação ou aprovação da profissional.**

## Prévia local

O conteúdo e o acervo ficam isolados na configuração `clients/ana-claudia-barbieri` do produto interno `03_Empresa_Interna/05_Templates/architecture`.

```powershell
cd "C:\Users\itzlu\OneDrive\Documentos\ChatGPT\rico\03_Empresa_Interna\05_Templates\architecture"
npm.cmd run dev -- ana-claudia-barbieri
```

## Direção visual provisória

O perfil público comunica arquitetura, interiores e decoração e identifica Criciúma e Florianópolis. Como não foi localizado um manual de marca nem logo oficial em arquivos locais, a proposta usa uma linguagem editorial residencial — pedra clara, madeira, sombras naturais e tipografia elegante — sem criar símbolo ou alegar que a paleta seja oficial. O acervo visual gerado é conceitual e não mostra obras da profissional. A composição e os tokens estão em `DESIGN.md`; as regras específicas de UI estão em `clients/ana-claudia-barbieri/.impeccable/`.

## Fontes e direitos

- Perfil público: https://www.instagram.com/anaclaudiabarbieriarquitetura/ — consultado em 06/10/2026.
- Link da bio observado: https://whats.link/anaclaudiabarbieri — no momento da consulta, exibia mensagem de link inexistente/removido.
- Imagens conceituais: arquivos originais, metadados de prompts, variantes responsivas, créditos e limites de uso estão documentados em `clients/ana-claudia-barbieri/MATERIAIS.md`.

## Interações

O briefing de demonstração forma uma folha de partida local, sem envio nem persistência. O resumo só é copiado após ação explícita. `motion@14.0.0` anima a entrada curta do resumo, com suporte a movimento reduzido. Nada no conteúdo depende da animação. A dependência está adicionada ao package da base Architecture porque a prévia usa essa mesma stack.

## Pendências comerciais e de publicação

Confirmar diretamente com Ana: nome profissional preferido, logo e paleta oficiais, serviços/escopo, regiões efetivamente atendidas, canal oficial de contato e destino do briefing, autorização para publicar fotos/projetos e dados profissionais. Até lá, a demonstração é `noindex`, não envia formulários e não atribui imagens conceituais ao portfólio.

Estado técnico e verificações: [STATUS.md](STATUS.md).

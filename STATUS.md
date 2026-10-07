# STATUS — prévia Ana Cláudia Barbieri Arquitetura

Atualizado em 06/10/2026. **Demonstração comercial em andamento; contratação/aprovação não confirmadas.**

## Direção e evidências

- Pedido: página para projetos residenciais com briefing de orçamento.
- Fonte oficial consultada: perfil público [@anaclaudiabarbieriarquitetura](https://www.instagram.com/anaclaudiabarbieriarquitetura/), em 06/10/2026. O perfil identifica Arquitetura, Interiores e Decoração, com Criciúma e Florianópolis na bio. O conteúdo público observado apresenta trabalhos residenciais/interiores, mas não concede autorização para reutilizar as imagens.
- Link da bio observado (`whats.link/anaclaudiabarbieri`) estava indisponível/removido na consulta. Sem telefone, e-mail, endereço ou destino de orçamento validado.
- Direção provisória: “Caderno de morar” — leitura editorial, matéria residencial e fotografia ampla. Tons minerais e madeira são uma proposta de apresentação, não uma paleta oficial confirmada. Sem logo inventada.
- Stack: produto interno Architecture (React, TypeScript, Vite, CSS tokens; Three.js somente sob demanda). Sem migração; Motion 14.0.0 foi adicionado para a entrada curta do resumo interativo.

## Verificações desta rodada

- `npm run check`: passou (TypeScript).
- `npm test`: passou, 29/29 testes.
- `npm run validate -- ana-claudia-barbieri`: 0 erros; 25 pendências factuais intencionais (logo, fatos de cases, contatos, URL e privacidade real).
- `npm run build -- ana-claudia-barbieri --previa`: passou. O Vite emitiu o aviso já existente sobre o carregamento CommonJS/ESM de `shared/src/validate.ts`; bundle inicial 431,46 kB / 134,77 kB gzip e cena 3D compartilhada em chunk separado, não carregada nesta página.
- Prévia local inspecionada em `http://127.0.0.1:3030/` com Playwright. Sem rolagem horizontal em 360, 390, 430, 768, 1024 e 1440 px; CTA principal cabe na primeira tela nas larguras mobile verificadas. Hero e seção de projetos conferidos visualmente; painel técnico de pendências está fora do caminho da apresentação.
- Testes manuais: menu mobile abre e fecha com Escape; briefing de teste Casa nova + Criciúma gera “Resumo local · não enviado”; console sem erros/avisos relevantes (somente mensagem informativa do React DevTools); preferência `prefers-reduced-motion: reduce` mantém a página funcional.
- Capturas: `screenshots/desktop-hero.png`, `screenshots/desktop-projetos.png`, `screenshots/mobile-390.png`, `screenshots/mobile-390-reduced-motion.png`.
- 3 estudos conceituais e 24 derivados AVIF/WebP; acervo responsivo total ~5,82 MB. As variantes de imagem carregadas no navegador foram verificadas. Nenhuma imagem de Instagram usada.
- Não foi medido Lighthouse, INP/LCP de laboratório nem desempenho em dispositivos físicos; não tratar métricas como aprovadas.

## Pendências

- Aprovação da identidade provisória, logo, cores e tipografia.
- Confirmação de serviços, escopo e cidades atendidas.
- Canal oficial de contato e autorização/destino para formulário de orçamento.
- Fotos, renders e projetos com autorização de uso e respectivas legendas.
- Nome e dados profissionais a exibir.

## Próxima ação

Apresentar a prévia ao usuário e recolher validação da profissional sobre marca, escopo, regiões e canais antes de qualquer uso público. Não publicar nem contatar a profissional nesta etapa.

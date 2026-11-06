# Skills de marketing, escrita e desenvolvimento

Skills de terceiros copiadas sem alteração de conteúdo. Cada pasta mantém a licença original (`LICENSE`). Os servidores MCP ficam em `.mcp.json`, na raiz do repositório.

## Escrita e redação

| Skill | Origem | Licença | Observação |
|---|---|---|---|
| `stop-slop/` | [hardikpandya/stop-slop](https://github.com/hardikpandya/stop-slop) | MIT | Regras e exemplos em inglês. |
| `humanizer/` | [blader/humanizer](https://github.com/blader/humanizer) | MIT | Remove padrões de texto gerado por IA, baseado no guia "Signs of AI writing" da Wikipédia. |
| `copywriting/` | [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) (`skills/copywriting`) | MIT | Copy de páginas, headlines e CTAs. |
| `content-research-writer/` | [skillcreatorai/ai-agent-skills](https://github.com/skillcreatorai/ai-agent-skills) | MIT | Pesquisa, citações e outline para artigos. |

## Conteúdo e pesquisa

| Skill | Origem | Licença | Observação |
|---|---|---|---|
| `content-plan/` | [ceyddrick/skills](https://github.com/ceyddrick/skills) (`content:plan`) | MIT | Depende de outras skills desse repositório e de arquivos pessoais do autor (perfil de voz em `~/.claude/skills/writing:xpost/`). |
| `persona/` | [takechanman1228/claude-persona](https://github.com/takechanman1228/claude-persona) | MIT | Painéis de personas de clientes para pesquisa. Não é um painel de CTO ou designer. Usa `references/` e `templates/` copiados junto. |
| `book-to-skill/` | [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill) | MIT | Converte PDF ou EPUB em skill. Precisa de Python e de extratores (pdftotext, docling etc.). Leia `SECURITY-NOTICE.md`, que alerta para uma cópia maliciosa em outro repositório. |

## Desenvolvimento (Superpowers)

Origem: [obra/superpowers](https://github.com/obra/superpowers), MIT.

| Skill | Para quê |
|---|---|
| `systematic-debugging/` | Encontrar a causa raiz antes de propor correções. |
| `test-driven-development/` | Escrever testes antes do código. |
| `writing-plans/` | Criar planos de implementação antes de codificar. |
| `brainstorming/` | Sessão estruturada de ideação antes do trabalho de design. Inclui servidor local opcional para visualização (`scripts/`). |

## Servidores MCP (`.mcp.json`)

Servidores oficiais de [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers). Iniciam com `uvx` (Python) ou `npx` (Node). Não exigem conta.

- `fetch`: baixa uma página e converte para Markdown.
- `time`: conversão de fuso horário e cálculos de data.
- `filesystem`: leitura e escrita restritas a este diretório (`.`).
- `sequential-thinking`: raciocínio em etapas para problemas complexos.

## Não incluídas

- **YouTube Transcript / Article Extractor**: só encontrei agregadores de catálogo, sem repositório de origem verificável.
- **Lessie** (`people-search`, `lessie-email`): sem arquivo de licença no repositório e exige conta e CLI externos. Busca contatos de pessoas reais.
- **Persona Definer, Copy Master, Content Cluster**: aparecem só em sites de catálogo, sem o `SKILL.md` de origem.
- **Market Research, Tone Adjuster, B2B Prospector, Data Analyst, JSON/Markdown Exporter**: não encontrei skill publicada com esses nomes.
- **Claude-Persona de CTO e designer**: não encontrei skill com esse perfil. A `persona` acima é a única correspondência próxima.

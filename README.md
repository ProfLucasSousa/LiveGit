# Live Git

Projeto simples de loja usado como apoio para uma aula prática de Git e GitHub. O exemplo combina uma página estática com JavaScript e uma lista curta de convenções para commits.

## Objetivos da prática

- Organizar uma estrutura básica de projeto.
- Criar e publicar um repositório.
- Trabalhar com commits semânticos.
- Evoluir HTML, CSS e JavaScript em pequenos passos.

## Convenções de commit usadas

| Tipo | Uso |
| --- | --- |
| `chore` | Criação e configuração |
| `feat` | Nova funcionalidade |
| `fix` | Correção de erro |
| `style` | Alterações visuais |
| `docs` | Documentação |

## Como visualizar

Não há dependências. Abra `index.html` no navegador ou execute um servidor estático:

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000`.

## Estrutura

- `index.html`: página da loja.
- `src/css/estilo.css`: estilos.
- `src/js/script.js`: interação da página.
- `src/docs/Readme.md`: anotações originais da aula.

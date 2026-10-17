# Projeto 3 — Consulta e solicitação de processos

Este projeto reúne referências e modelos para localizar informações, conduzir solicitações de processos e preparar seus resultados. Use este README como ponto de entrada: identifique o tipo de necessidade, consulte os arquivos relacionados e informe os dados necessários para que a solicitação possa ser atendida.

> **Estado atual:** os arquivos listados abaixo estão vazios. Preencha-os com os procedimentos, critérios e modelos oficiais antes de tratá-los como orientação validada.

## Onde encontrar cada informação

| Necessidade | Arquivo | Conteúdo esperado |
|---|---|---|
| Consultar informações de clientes | [`apoio/clientes.md`](apoio/clientes.md) | Dados de referência, critérios de busca e cuidados com informações de clientes. |
| Entender como executar um processo | [`docs/procedimentos.md`](docs/procedimentos.md) | Etapas, responsáveis, entradas necessárias, prazos, critérios e exceções. |
| Preparar ou revisar um parecer | [`docs/modelo_parecer.md`](docs/modelo_parecer.md) | Estrutura, campos obrigatórios e padrão de redação do parecer. |
| Consolidar e comunicar o resultado | [`saída/resumo_final.md`](sa%C3%ADda/resumo_final.md) | Modelo de resumo final, decisões, pendências e próximos passos. |

## Como localizar um processo

1. Pesquise em `docs/procedimentos.md` pelo nome do processo, assunto, etapa ou área responsável.
2. Confira se o procedimento informa os critérios de entrada, documentos necessários, responsável e prazo.
3. Se a solicitação depender de dados de cliente, consulte `apoio/clientes.md` e use apenas as informações pertinentes.
4. Se precisar formalizar análise, use `docs/modelo_parecer.md`.
5. Registre a conclusão e as pendências conforme `saída/resumo_final.md`.
6. Se a informação não estiver documentada, sinalize a lacuna e peça validação à área responsável; não presuma regras ou prazos.

## Como solicitar a execução ou análise de um processo

Ao abrir uma solicitação, informe:

- **Processo ou assunto:** nome conhecido, área e termos relacionados para busca.
- **Objetivo:** o que precisa ser localizado, analisado, decidido ou produzido.
- **Contexto:** resumo do caso e motivo da solicitação.
- **Cliente ou referência:** identificador necessário para localizar o registro, evitando incluir dados pessoais desnecessários.
- **Documentos e links:** materiais já consultados e fontes relevantes.
- **Prazo:** data necessária e justificativa, se houver urgência.
- **Resultado esperado:** por exemplo, orientação, parecer, conferência documental ou resumo final.
- **Pendências e restrições:** tentativas anteriores, dependências, aprovações ou informações ainda faltantes.

### Modelo de solicitação

```text
Processo/assunto:
Objetivo:
Contexto:
Cliente ou referência:
Documentos e links:
Prazo:
Resultado esperado:
Pendências/restrições:
```

## Padrão para registrar um procedimento

Para facilitar buscas futuras, documente cada processo com os seguintes campos em `docs/procedimentos.md`:

- Nome do processo e nomes alternativos usados nas solicitações
- Área responsável e ponto de contato
- Quando se aplica e critérios de elegibilidade
- Informações e documentos de entrada
- Etapas numeradas, com responsável por etapa
- Prazo de referência e eventos que afetam o prazo
- Resultado produzido e onde registrá-lo
- Exceções, aprovações e escalonamentos
- Data da última revisão e responsável pela atualização

Use títulos claros e termos que as pessoas provavelmente pesquisarão. Registre siglas por extenso na primeira ocorrência e mantenha nomes de processos consistentes entre os arquivos.

## Organização

```text
.
├── README.md
├── apoio/
│   └── clientes.md
├── docs/
│   ├── modelo_parecer.md
│   └── procedimentos.md
└── saída/
    └── resumo_final.md
```

## Manutenção

Quando um processo ou modelo mudar, atualize o arquivo correspondente e revise este índice se os caminhos ou a finalidade dos arquivos mudarem. Registre a data e a pessoa responsável pela revisão no documento atualizado.

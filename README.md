# Soulan Docs

**Uma solução para apoiar e padronizar a elaboração de documentos de Atração e Seleção com o auxílio da tecnologia e da inteligência artificial.**

O Soulan Docs é um projeto desenvolvido com o objetivo de facilitar a rotina dos profissionais de Atração e Seleção, reduzindo o trabalho manual na organização de informações e na elaboração de documentos utilizados nos processos seletivos.

A proposta é centralizar a preparação dos documentos em um fluxo orientado, no qual as informações fornecidas pelo consultor são organizadas conforme modelos e regras previamente definidos, mantendo a necessidade de revisão e validação humana.

---

## Demonstração do projeto

Assista à demonstração do Soulan Docs e conheça a proposta, a interface e o fluxo de utilização do protótipo.

**[ASSISTIR AO VÍDEO DEMONSTRATIVO](INSERIR_LINK_DO_VIDEO)**

> A demonstração apresenta o protótipo em desenvolvimento. As funcionalidades exibidas devem ser consideradas conforme o estágio atual de implementação do projeto.

---

## O problema que o projeto busca resolver

A elaboração de documentos de Atração e Seleção pode envolver diferentes fontes de informação, como currículos, briefings, e-mails, anotações de entrevistas e informações compartilhadas em reuniões.

Organizar esses dados manualmente, identificar quais informações pertencem a cada campo e manter um padrão entre os documentos pode demandar tempo e gerar inconsistências.

O Soulan Docs foi idealizado para apoiar esse processo, utilizando uma estrutura padronizada e regras de negócio que orientam a organização, a revisão e a preparação dos documentos.

## Objetivo

Desenvolver uma ferramenta de apoio à produção documental de Atração e Seleção, com foco em:

- Reduzir o trabalho manual de organização das informações.
- Padronizar a estrutura dos documentos.
- Facilitar a identificação de informações ausentes.
- Sinalizar divergências entre diferentes fontes.
- Preservar a necessidade de validação pelo consultor.
- Apoiar a geração de documentos nos formatos Word e PDF.
- Manter regras de negócio e critérios de qualidade definidos para cada modelo.

---

## Documentos contemplados

O escopo do projeto considera quatro modelos documentais:

| Código | Documento |
|---|---|
| AV | Formulário de Abertura de Vaga |
| CV | Currículo Padrão Soulan |
| CR | Currículo + Relatório de Entrevista |
| PE | Parecer de Entrevista — Vagas Estratégicas |

Cada modelo possui uma estrutura e regras próprias de preenchimento.

## Como funciona a proposta

O fluxo planejado para utilização do Soulan Docs é composto pelas seguintes etapas:

1. **Seleção do documento:** o usuário escolhe qual documento deseja preparar.
2. **Envio das informações:** são fornecidos textos, currículos, briefings, anotações ou arquivos de apoio.
3. **Organização dos dados:** as informações são distribuídas conforme a estrutura do documento selecionado.
4. **Revisão:** o usuário visualiza o conteúdo organizado, as informações pendentes e possíveis divergências.
5. **Validação:** o consultor revisa e confirma as informações.
6. **Finalização:** o documento pode ser preparado para exportação nos formatos previstos.

O projeto estabelece como regra fundamental que informações não fornecidas não devem ser inventadas. Dados ausentes ou divergentes precisam ser identificados para validação humana.

---

## Tecnologias utilizadas

A arquitetura do projeto foi organizada em duas partes principais:

### Frontend
- React
- TypeScript

Responsável pela interface de interação, navegação e apresentação das etapas do processo.

### Backend
- Python
- FastAPI

Responsável pela estrutura do backend e pela organização das regras de negócio.

### Testes e documentação
- Testes automatizados.
- Dados fictícios para validação.
- Documentação de requisitos e decisões.
- Histórico de alterações do projeto.

---

## Arquitetura e organização

O projeto possui uma separação entre interface, backend, regras de domínio, testes e documentação.

Principais diretórios:

- `frontend/`: interface do usuário.
- `backend/`: aplicação e regras do backend.
- `backend/app/dominio/`: camada de regras de negócio.
- `tests/`: testes automatizados.
- `test_data/`: dados fictícios utilizados nos testes.
- `assets/`: recursos não corporativos utilizados no projeto.
- `docs/`: documentação funcional e técnica.
- `historico_alteracoes/`: registros de evolução e decisões.
- `scripts/`: scripts auxiliares.

---

## Documentação do projeto

A documentação acompanha a evolução do Soulan Docs e registra as decisões que orientam seu desenvolvimento.

Ela contempla:

- Análise e especificação dos requisitos.
- Definição das funcionalidades e regras de negócio.
- Arquitetura e organização técnica.
- Experiência do usuário e interface (UX/UI).
- Wireframes e referências de telas.
- Estrutura dos modelos documentais.
- Regras de preenchimento, pendências e divergências.
- Segurança e tratamento dos conteúdos corporativos.
- Orientações para execução dos testes.
- Histórico de alterações e decisões.

A documentação pode ser consultada no diretório [`docs/`](docs/), juntamente com os guias e materiais de apoio disponíveis no repositório.

---

## Status atual do projeto

**Status: protótipo em desenvolvimento.**

O projeto já possui uma estrutura de frontend e backend, regras de domínio, testes automatizados, controles de segurança e recursos de navegação, incluindo o menu "Como usar".

A geração de documentos Word e PDF a partir do conteúdo revisado também foi testada no protótipo.

Algumas funcionalidades ainda estão em desenvolvimento ou aguardam validação:

- Integração com uma inteligência artificial real.
- Interpretação automática de textos livres e arquivos.
- Integração e validação de um modelo de IA local.
- Validação completa do fluxo de ponta a ponta.
- Preparação para implantação em ambiente de produção.
- Etapas adicionais de segurança e conformidade com a LGPD antes da utilização de dados reais.

O simulador utilizado nos testes atuais não representa uma integração de IA real: ele utiliza um comando específico de simulação para executar determinados preenchimentos demonstrativos.

Portanto, o projeto ainda não deve ser considerado uma solução pronta para utilização em produção.

---

## Segurança, privacidade e dados

O desenvolvimento e os testes devem utilizar exclusivamente dados fictícios.

Por questões de confidencialidade e segurança, materiais corporativos, modelos oficiais, logomarcas, documentos internos, credenciais, arquivos de configuração sensíveis e dados pessoais não devem ser publicados indevidamente no repositório.

O projeto possui orientações específicas sobre os conteúdos corporativos que ficam fora do versionamento.

Consulte também o arquivo `CONTEUDO_CORPORATIVO.md`.

---

## Testes

O projeto possui testes automatizados voltados à validação das regras de domínio e do comportamento esperado.

As orientações para execução estão disponíveis em:

[`docs/guias/executar_testes.md`](docs/guias/executar_testes.md)

Os resultados dos testes devem ser considerados de acordo com a versão do código e o ambiente utilizado.

---

## Licenças e utilização

As informações sobre licenças e recursos utilizados estão documentadas em [`LICENCAS.md`](LICENCAS.md).

A publicação do código não concede autorização automática para reutilização de marcas, documentos, modelos ou materiais corporativos da Soulan.

---

## Considerações finais

O Soulan Docs é um projeto em desenvolvimento que busca aproximar tecnologia, padronização e inteligência artificial das atividades de Atração e Seleção.

Mais do que preparar documentos, a proposta é estruturar um processo que facilite o trabalho dos consultores, preserve a qualidade das informações e mantenha a validação humana como parte essencial da entrega.

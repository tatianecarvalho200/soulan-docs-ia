# Soulan Docs

**Uma solução digital para otimizar, organizar e padronizar a elaboração de documentos de Atração e Seleção.**

O **Soulan Docs** é uma aplicação desenvolvida para facilitar a rotina dos profissionais de Atração e Seleção, tornando a preparação de documentos mais organizada, padronizada e eficiente.

A solução reúne fluxos de preenchimento, organização de informações, revisão e preparação de documentos, utilizando regras de negócio específicas para cada modelo documental.

Seu propósito é reduzir atividades manuais, minimizar inconsistências e proporcionar mais agilidade aos consultores, mantendo a validação humana como parte essencial do processo.

---

## Demonstração do projeto

Conheça o Soulan Docs na prática e acompanhe seu funcionamento, desde a seleção do documento até a revisão e preparação do resultado final.

**[▶ ASSISTIR AO VÍDEO DEMONSTRATIVO](INSERIR_LINK_PUBLICO_DO_VIDEO)**

---

## O problema que o projeto busca resolver

A elaboração de documentos de Atração e Seleção envolve diferentes fontes de informação, como currículos, briefings, e-mails, anotações de entrevistas e informações compartilhadas em reuniões.

A organização manual desses conteúdos pode demandar tempo, gerar retrabalho e dificultar a manutenção de um padrão entre os documentos.

O Soulan Docs foi desenvolvido para apoiar esse processo, oferecendo uma experiência orientada por etapas e regras específicas para cada tipo de documento.

## Objetivos da solução

- Reduzir o trabalho manual na preparação de documentos.
- Padronizar a estrutura e a organização das informações.
- Facilitar a identificação de dados ausentes.
- Identificar possíveis divergências entre diferentes fontes.
- Orientar a revisão e a validação das informações.
- Apoiar a preparação de documentos nos formatos Word e PDF.
- Preservar os padrões documentais e as regras de negócio estabelecidas.

---

## Documentos contemplados

A solução contempla quatro categorias de documentos:

| Código | Documento |
|:---:|---|
| AV | Formulário de Abertura de Vaga |
| CV | Currículo Padrão Soulan |
| CR | Currículo + Relatório de Entrevista |
| PE | Parecer de Entrevista — Vagas Estratégicas |

Cada categoria possui estrutura, campos e critérios próprios de organização e revisão.

## Como funciona

O Soulan Docs organiza o processo em seis etapas:

1. **Seleção do documento:** escolha do modelo que será preparado.
2. **Envio das informações:** inclusão de textos, currículos, briefings, anotações e arquivos de apoio.
3. **Organização dos dados:** distribuição das informações conforme a estrutura do documento selecionado.
4. **Revisão:** visualização do conteúdo organizado, dos dados pendentes e das possíveis divergências.
5. **Validação:** conferência e confirmação das informações pelo consultor.
6. **Finalização:** preparação do documento para utilização e exportação nos formatos previstos.

### Princípios de funcionamento

- **Fidelidade às fontes:** nenhuma informação deve ser inventada para completar campos.
- **Identificação de pendências:** dados ausentes são sinalizados para validação.
- **Tratamento de divergências:** informações conflitantes devem ser apresentadas para conferência.
- **Validação humana:** o consultor mantém a responsabilidade pela revisão e confirmação do conteúdo.
- **Padronização:** cada documento segue sua estrutura e suas regras específicas.

---

## Tecnologias utilizadas

A aplicação foi estruturada com tecnologias voltadas ao desenvolvimento de interfaces web e serviços de backend.

### Frontend
- **React:** construção da interface.
- **TypeScript:** tipagem e organização do código.

### Backend
- **Python:** desenvolvimento da lógica de aplicação.
- **FastAPI:** estruturação dos serviços e endpoints.

### Engenharia e qualidade
- Testes automatizados.
- Separação de responsabilidades.
- Organização das regras de domínio.
- Dados fictícios para validação.
- Controle de versão com Git e GitHub.
- Documentação funcional e técnica.

---

## Arquitetura e desenvolvimento

O Soulan Docs foi concebido com uma arquitetura que separa a interface, os serviços de backend e as regras de negócio.

Essa organização permite manter responsabilidades bem definidas, facilitar a manutenção e apoiar a evolução das funcionalidades.

O desenvolvimento considera aspectos como:

- Organização modular da aplicação.
- Separação entre interface e lógica de negócio.
- Estruturação das regras específicas de cada documento.
- Validação das informações durante o fluxo.
- Preparação dos documentos para exportação.
- Testes e verificação dos comportamentos esperados.

---

## Documentação do projeto

A documentação foi uma parte importante do desenvolvimento do Soulan Docs, orientando as definições funcionais, técnicas e visuais da solução.

Durante o projeto, foram estruturados materiais de referência para registrar as necessidades identificadas, as decisões tomadas e os critérios que orientam o funcionamento da aplicação.

Entre os principais temas documentados estão:

**Análise e requisitos**
- Levantamento das necessidades.
- Definição do escopo.
- Requisitos funcionais e não funcionais.
- Especificações das funcionalidades.

**Regras de negócio**
- Regras específicas para cada modelo documental.
- Identificação e tratamento de informações ausentes.
- Tratamento de divergências.
- Critérios de validação e confirmação.
- Regras para revisão e finalização.

**Arquitetura técnica**
- Organização do frontend e backend.
- Separação das responsabilidades.
- Estrutura das camadas e módulos.
- Organização das regras de domínio.

**UX/UI — Experiência e interface**
- Fluxos de navegação.
- Estrutura das telas.
- Componentes visuais.
- Wireframes e referências de interface.
- Decisões de usabilidade e padronização visual.

**Modelos documentais**
- Mapeamento dos quatro documentos.
- Estrutura dos campos.
- Critérios de preenchimento.
- Regras de organização das informações.

**Segurança e privacidade**
- Orientações para proteção de dados.
- Separação de materiais corporativos.
- Cuidados com arquivos e configurações sensíveis.
- Diretrizes relacionadas à LGPD.

**Testes e validação**
- Cenários de teste.
- Dados fictícios.
- Verificação das regras de negócio.
- Critérios de qualidade.

**Histórico de alterações**
- Registro das decisões.
- Evolução dos requisitos.
- Alterações implementadas.
- Controle das versões do projeto.

A documentação serviu como referência durante o desenvolvimento, contribuindo para manter a coerência entre os requisitos, as regras de negócio, a experiência do usuário e a implementação técnica.

---

## Segurança, privacidade e proteção de dados

A organização do projeto considera a importância da confidencialidade das informações utilizadas nos processos de Atração e Seleção.

As diretrizes consideradas incluem:

- Utilização de dados fictícios nos testes e demonstrações.
- Proteção de credenciais e variáveis de ambiente.
- Não exposição indevida de documentos internos.
- Cuidados com informações pessoais de candidatos.
- Separação entre código-fonte e materiais corporativos.
- Consideração dos requisitos de segurança e LGPD.

O material disponibilizado publicamente foi limitado ao conteúdo autorizado para divulgação, preservando informações e documentos internos.

---

## Considerações finais

O Soulan Docs representa a aplicação da tecnologia à rotina de Atração e Seleção, com foco na padronização, organização das informações e melhoria dos processos documentais.

Sua proposta reúne interface, regras de negócio, documentação e mecanismos de validação, formando uma solução orientada à produtividade e à qualidade das entregas.

**Soulan Docs — Mais organização, padronização e eficiência na produção de documentos.**

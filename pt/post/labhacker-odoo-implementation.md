---
title: "LabHacker Maceió: um ERP próprio e de código aberto"
kicker: "Consultoria · outubro de 2026 – janeiro de 2027"
lede: "Implantação de um ERP próprio, de código aberto e em português, para um laboratório brasileiro de cultura digital, com consultoria em captação de recursos."
date: "2026-10-01"
categories:
  - "consulting"
coverImage: "cover-labhacker.svg"
description: "Consultoria de implantação do Odoo para o LabHacker, Laboratório Brasileiro de Cultura Digital, em Maceió: ERP de código aberto, módulos sob medida para atas, aprovações, despesas, contratos e captação."
ref: labhacker-odoo-implementation
---

<dl class="facts">
  <div><span class="k">Cliente</span><span class="v">LabHacker, Maceió (AL)</span></div>
  <div><span class="k">Serviço</span><span class="v">Implantação de ERP próprio + consultoria em captação</span></div>
  <div><span class="k">Período</span><span class="v">Out 2026 – Jan 2027</span></div>
  <div><span class="k">Tecnologia</span><span class="v">Odoo 19 Community · OCA · PostgreSQL · Docker</span></div>
</dl>

O LabHacker é o Laboratório Brasileiro de Cultura Digital, organização da sociedade civil que atua em cultura digital. A equipe toca projetos, eventos, cursos e uma loja, e precisava de um lugar único para atas, aprovações, reembolsos, contratos e captação de recursos, sem pagar licenças por usuário nem depender de um fornecedor proprietário.

Minha proposta foi um **ERP próprio da organização, em português, em software livre e no seu próprio servidor**, construído sobre o Odoo Community e os módulos da Odoo Community Association (OCA), com desenvolvimento sob medida apenas onde não havia solução pronta.

## O que a consultoria cobre

- **Oficinas de necessidades e mapa de módulos.** Cada necessidade levantada pela equipe foi associada a um aplicativo nativo do Odoo, a um módulo da OCA, a um módulo sob medida ou a uma segunda etapa, para que o escopo fosse honesto sobre o que a edição gratuita faz e não faz.
- **Servidor e segurança.** Odoo 19 em contêineres, HTTPS automático, backups diários com retenção, cadastro público fechado e perfis de acesso (diretoria, coordenação, financeiro, comunicação, equipe, externos).
- **Contabilidade para organizações sem fins lucrativos.** Plano de contas conforme a ITG 2002, com regras de retenção de impostos, conciliação bancária e depreciação de ativos imobilizados da OCA.
- **Módulos sob medida**, cada um em uma primeira versão enxuta que a equipe realmente usa:
  - *Atas*: as decisões viram tarefas com responsável e prazo, e as pessoas são avisadas por e-mail e chat
  - *Aprovações*: uma fila única para comunicação, compras e contratos
  - *Despesas em lote com OCR*: envio de comprovantes, revisão e envio para aprovação
  - *Contratos* com partes, valor, vigência e alertas de vencimento
  - *CRM de captação*: financiador, valor solicitado, contrapartida, prazos, prestação de contas
  - *Viagens* com cotações comparadas
  - *Ponto*: regras de registro de presença adaptadas a uma equipe de organização sem fins lucrativos
- **Documentação.** Um manual de uso de 41 páginas dentro da própria base de conhecimento do sistema, escrito para pessoas não técnicas.
- **Consultoria em captação de recursos**, em paralelo à implantação, para que o novo CRM e a estratégia de financiamento do laboratório sejam construídos juntos.

## Abordagem

Código aberto por padrão, pequenos incrementos e documentação como entrega. O sistema foi desenhado para que o LabHacker possa mantê-lo, hospedá-lo, auditá-lo e ampliá-lo sem mim.

[LabHacker](https://labhacker.org.br) · [Voltar para Consultoria](/pt/consultoria.html)

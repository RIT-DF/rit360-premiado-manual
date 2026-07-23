---
title: "Regulamento"
nav_order: 4
parent: "Módulos"
permalink: /modulos/regulamento/
role: admin
routes: ["#/campanhas/:id"]
screenshots: [reg-assistente-etapas]
last_verified: 2026-07-22
status: publicado
---

# Regulamento

O regulamento é o documento que define as regras da campanha — e é **obrigatório**: nenhuma campanha abre sem um regulamento publicado. O módulo monta a maior parte do texto para você, num **assistente guiado em etapas**.

![Assistente de regulamento em etapas](/assets/screenshots/reg-assistente-etapas.png)

## Semi-automático, em etapas

O assistente tem quatro etapas: **Dados da campanha** (automáticos), **Cláusulas essenciais**, **Outras cláusulas** e **Revisão**. O texto combina:

1. **Dados automáticos** da organização e da campanha (nome, CNPJ, prêmio, datas, quantidade, valor).
2. **Campos essenciais** que você preenche — com **“Inserir da biblioteca”** para trazer um texto-modelo pronto e editá-lo.
3. **Outras cláusulas** — cláusulas gerais (LGPD, foro…) e texto livre, em cartões que você adiciona, edita, reordena e remove. A biblioteca é editável em **Configurações → Banco de Cláusulas de Regulamento**, onde cada cláusula tem um **campo sugerido**.

Ao inserir uma cláusula da biblioteca, o texto é **copiado e congelado** na campanha: mudar a biblioteca depois não altera regulamentos já montados.

## Versionado e carimbado

- Ao publicar, o plugin tira um **snapshot** dos dados da organização — o documento fica fiel ao que valia naquele momento.
- A primeira publicação é a **v1**; editar depois cria **v2, v3…**, arquivando a anterior. Há **histórico** completo.
- É um **gate de publicação**: a campanha só abre com o regulamento publicado.

## Público

O regulamento publicado aparece na página da campanha, com o conteúdo sanitizado e seguro.

O passo a passo está em [Publicar o regulamento](/guias/publicar-regulamento/).

> ⚠️ **Importante**
>
> Descreva no regulamento o **método de apuração** que será usado e todas as regras relevantes **antes** de abrir a campanha. Um regulamento claro é a base da segurança jurídica e da confiança do público. Veja [Requisitos legais de um sorteio](/boas-praticas/requisitos-legais/).

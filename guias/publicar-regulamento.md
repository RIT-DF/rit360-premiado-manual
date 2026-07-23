---
title: "Publicar o regulamento"
nav_order: 4
parent: "Guias por tarefa"
permalink: /guias/publicar-regulamento/
task: publicar-regulamento
role: admin
routes: ["#/campanhas/:id"]
screenshots: [reg-assistente-etapas, reg-outras-clausulas, reg-banco-clausulas-target, bp-09-dados-legais]
source_docs: [PRD_Bussola_Premiada.md#8.10, PRD_Bussola_Premiada.md#8.11]
last_verified: 2026-07-22
status: publicado
---

# Publicar o regulamento

O regulamento é **obrigatório**: nenhuma campanha entra no ar sem um regulamento publicado. A boa notícia é que o RIT360 Premiado monta a maior parte dele para você — a partir dos dados da organização, dos dados da campanha e de uma biblioteca de cláusulas prontas.

> **A partir da versão 2.7.0**, a aba Regulamento virou um **assistente guiado em etapas**: você segue um passo a passo, e pode **puxar uma cláusula pronta da biblioteca direto para dentro do campo** para editá-la. A logo da organização (a mesma cadastrada em [Configurar a organização](/guias/configurar-organizacao/)) continua aparecendo no topo do documento.

## Onde fica

Abra a campanha e clique na aba de topo **Regulamento**. No topo há uma **barra de progresso** com as quatro etapas do assistente.

![Assistente de regulamento em etapas](/assets/screenshots/reg-assistente-etapas.png)

## As quatro etapas

1. **Dados da campanha** — dados da organização e da campanha (nome, CNPJ, prêmio, datas, quantidade, valor) entram **sozinhos**; você só confere. Ajuste-os, se preciso, na campanha e em **Organização**.
2. **Cláusulas essenciais** — as seções principais (critérios de participação, política de entrega etc.). Em cada campo há o botão **“+ Inserir da biblioteca”**: clique para trazer um **texto-modelo pronto** e então edite à vontade. Os campos com **\*** são obrigatórios.
3. **Outras cláusulas** — cláusulas gerais (LGPD, foro, destinação à causa…) e qualquer texto livre, em forma de **cartões** que você adiciona, edita, reordena e remove. Use **“+ Inserir da biblioteca”** para começar de um modelo, ou **“+ Cláusula em branco”** para escrever do zero.
4. **Revisão** — pré-visualização fiel ao que o público verá + o botão **Publicar**.

![Etapa Outras cláusulas, com cartões editáveis](/assets/screenshots/reg-outras-clausulas.png)

## Passo a passo

1. Na etapa **Cláusulas essenciais**, preencha cada seção. Para ir mais rápido, clique em **“+ Inserir da biblioteca”** no campo e escolha uma cláusula-modelo — o texto entra no campo **pronto para editar**.
2. Em **Outras cláusulas**, adicione as cláusulas gerais que se aplicam (também via “Inserir da biblioteca”) e ajuste os cartões: **reordene** com as setas, **remova** o que não usar.
3. Na etapa **Revisão**, use a **pré-visualização** para conferir o texto final. Clique em **Salvar rascunho** quando quiser continuar depois.
4. Clique em **Publicar regulamento** e confirme.

> 💡 **Como as cláusulas sabem onde entrar**
>
> Cada cláusula da biblioteca tem um **campo sugerido**. Você define isso em **Configurações → Banco de Cláusulas de Regulamento**, no seletor **“Sugerir no campo”** de cada cláusula. É por isso que, ao clicar “Inserir da biblioteca” num campo, aparecem só as cláusulas daquele tema.
>
> ![Seletor de campo sugerido no Banco de Cláusulas](/assets/screenshots/reg-banco-clausulas-target.png)
>
> Ao inserir uma cláusula, o texto é **copiado** para a campanha e fica **congelado** ali: editar a biblioteca depois **não altera** os regulamentos já montados.

## O que acontece ao publicar

- O plugin tira um **snapshot** dos dados da organização — o regulamento fica "carimbado" com o que valia naquele momento.
- A primeira publicação vira a **versão 1**. Se você editar depois de publicado, uma nova versão (v2, v3…) é criada e a anterior é arquivada. Assim há **histórico** de tudo.
- O item "regulamento publicado" do checklist da campanha é atendido, liberando a abertura.

## Dados legais

Na aba **Dados legais** você registra número de autorização, processo e observações. São **opcionais**, mas se estiverem em branco o plugin **pede confirmação explícita** antes de publicar a campanha — um lembrete para você não esquecer.

![Aba Dados legais](/assets/screenshots/bp-09-dados-legais.png)

> ✅ **Boas práticas**
>
> Leia o regulamento inteiro na pré-visualização antes de publicar, como se fosse um participante. Ele é o documento que dá segurança jurídica à campanha e transmite seriedade ao público. Veja também [Requisitos legais de um sorteio](/boas-praticas/requisitos-legais/).

> 💡 **Dica**
>
> Se você duplicar uma campanha, o regulamento é copiado junto — ótimo para campanhas recorrentes que seguem o mesmo modelo.

---
title: "Fazer o setup de Autopilot para dispositivo Windows"
categories:
  - blog
tags:
  - Intune
  - Autopilot
---

Neste primeiro artigo vamos explorar primeiro como fazer o setup para Autopilot. Tem vindo a ser mais comum chamarmos um computador de dispositivo.

<H2>Registar dispositivos</H2>

O primeiro passo para fazer o setup de Autopilot será registar os dispositivos windows no serviço do Autopilot. Normalmente o caso comum é já termos alguns dispositivos mas acontece que não estão enrolled no Intune e portanto não os conseguimos ver na consola.

Este passo server exatamente para isso.

**Permissões / Roles de Azure:** Para efetuar todas estas alterações e setup é necessário que seja feito com um utilizador que tenha no minimo a role de *Intune Administrator*
{: .notice--info}
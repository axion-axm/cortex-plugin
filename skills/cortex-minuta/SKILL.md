---
name: cortex-minuta
description: "Criação de minuta com o Cortex: redige a peça (embargos, agravo, contestação, impugnação, manifestação) com base nos autos e em precedentes, pronta para revisão. Use quando o usuário pedir uma peça ou minuta, ou digitar /cortex-minuta."
---

Chame a ferramenta `cortex_iniciar_funcao` com `funcao` igual a `minuta` e siga a etapa devolvida, uma de cada vez,
avançando com `cortex_avancar_funcao` e a continuação recebida. Respeite as regras do Cortex que vêm em cada etapa.

Se a mensagem do usuário já trouxer as informações pedidas na etapa, use-as sem perguntar de novo.

Se as ferramentas do Cortex não estiverem disponíveis nesta conversa, peça ao usuário para conectar o conector
Cortex (Configurações → Conectores) e tentar de novo.

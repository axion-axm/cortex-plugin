---
name: cortex-parecer
description: "Parecer jurídico com o Cortex: responde quesitos com fundamentação nos autos e em precedentes, no tom do destinatário. Use quando o usuário pedir um parecer ou opinião jurídica fundamentada, ou digitar /cortex-parecer."
---

Chame a ferramenta `cortex_iniciar_funcao` com `funcao` igual a `parecer` e siga a etapa devolvida, uma de cada vez,
avançando com `cortex_avancar_funcao` e a continuação recebida. Respeite as regras do Cortex que vêm em cada etapa.

Se a mensagem do usuário já trouxer as informações pedidas na etapa, use-as sem perguntar de novo.

Se as ferramentas do Cortex não estiverem disponíveis nesta conversa, peça ao usuário para conectar o conector
Cortex (Configurações → Conectores) e tentar de novo.

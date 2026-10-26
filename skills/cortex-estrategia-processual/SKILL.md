---
name: cortex-estrategia-processual
description: "Estratégia processual com o Cortex: mapeia caminhos de atuação, fundamentos, riscos e recomendação para um ou mais processos do escritório. Use quando o usuário pedir estratégia, caminhos de atuação, avaliar embargar ou negociar, ou digitar /cortex-estrategia-processual."
---

Chame a ferramenta `cortex_iniciar_funcao` com `funcao` igual a `estrategia-processual` e siga a etapa devolvida, uma de cada vez,
avançando com `cortex_avancar_funcao` e a continuação recebida. Respeite as regras do Cortex que vêm em cada etapa.

Se a mensagem do usuário já trouxer as informações pedidas na etapa, use-as sem perguntar de novo.

Se as ferramentas do Cortex não estiverem disponíveis nesta conversa, peça ao usuário para conectar o conector
Cortex (Configurações → Conectores) e tentar de novo.

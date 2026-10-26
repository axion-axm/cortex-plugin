---
name: cortex-pesquisa-jurisprudencial
description: "Pesquisa jurisprudencial com o Cortex: precedentes qualificados (súmulas, repetitivos, repercussão geral, IRDR) a favor, contra ou em panorama, com tese e identificação. Use quando o usuário pedir jurisprudência ou precedentes, ou digitar /cortex-pesquisa-jurisprudencial."
---

Chame a ferramenta `cortex_iniciar_funcao` com `funcao` igual a `pesquisa-jurisprudencial` e siga a etapa devolvida, uma de cada vez,
avançando com `cortex_avancar_funcao` e a continuação recebida. Respeite as regras do Cortex que vêm em cada etapa.

Se a mensagem do usuário já trouxer as informações pedidas na etapa, use-as sem perguntar de novo.

Se as ferramentas do Cortex não estiverem disponíveis nesta conversa, peça ao usuário para conectar o conector
Cortex (Configurações → Conectores) e tentar de novo.

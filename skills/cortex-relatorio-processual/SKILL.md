---
name: cortex-relatorio-processual
description: "Relatório processual com o Cortex: síntese de um ou mais processos para cliente, uso interno, comitê ou auditoria, com datas e páginas. Use quando o usuário pedir relatório, status ou situação de processos, ou digitar /cortex-relatorio-processual."
---

Chame a ferramenta `cortex_iniciar_funcao` com `funcao` igual a `relatorio-processual` e siga a etapa devolvida, uma de cada vez,
avançando com `cortex_avancar_funcao` e a continuação recebida. Respeite as regras do Cortex que vêm em cada etapa.

Se a mensagem do usuário já trouxer as informações pedidas na etapa, use-as sem perguntar de novo.

Se as ferramentas do Cortex não estiverem disponíveis nesta conversa, peça ao usuário para conectar o conector
Cortex (Configurações → Conectores) e tentar de novo.

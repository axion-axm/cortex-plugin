---
name: cortex-consulta-autos
description: "Consulta aos autos com o Cortex: responde perguntas sobre processos do acervo do escritório citando peça e página. Use quando o usuário perguntar algo sobre um processo (resumo, decisões, andamentos, garantias, prazos, valores) ou digitar /cortex-consulta-autos."
---

Chame a ferramenta `cortex_iniciar_funcao` com `funcao` igual a `consulta-autos` e siga a etapa devolvida, uma de cada vez,
avançando com `cortex_avancar_funcao` e a continuação recebida. Respeite as regras do Cortex que vêm em cada etapa.

Se a mensagem do usuário já trouxer as informações pedidas na etapa, use-as sem perguntar de novo.

Se as ferramentas do Cortex não estiverem disponíveis nesta conversa, peça ao usuário para conectar o conector
Cortex (Configurações → Conectores) e tentar de novo.

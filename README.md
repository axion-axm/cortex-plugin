# Cortex

Plugin do Cortex para o Claude: seis atalhos para o trabalho do advogado sobre o acervo de processos do escritório,
os relatórios de análise, as consultas públicas dos tribunais e a pesquisa de jurisprudência.

> O Cortex usa inteligência artificial. As respostas do Claude e os relatórios de análise são gerados com IA e podem
> conter erros, omissões ou citações imprecisas; todo resultado precisa ser revisado pelo advogado responsável antes
> de qualquer uso.

## Quem pode usar

O Cortex é contratado por escritórios de advocacia. O acesso é por convite: o administrador do escritório cadastra o
e-mail de cada advogado, e cada pessoa enxerga somente o acervo do próprio escritório. Para contratar, escreva para
suporte@axiomaintelligence.com.

## Instalação

No Claude (navegador, aplicativo do computador ou Cowork; conta Pro, Max, Ultra, Team ou Enterprise):

1. Em Configurações → Recursos, deixe ligada a execução de código.
2. Em Configurações → Plugins, clique em Adicionar → Adicionar marketplace, informe `axion-axm/cortex-plugin` e
   confirme.
3. Instale o plugin Cortex e ligue a sincronização automática do marketplace, para receber as novas versões.
4. Na aba Conectores do plugin, conecte o Cortex e entre com o e-mail convidado pelo escritório (chega um código por
   e-mail).

Em escritórios no plano Team ou Enterprise do Claude, o proprietário da conta do escritório no Claude adiciona o
conector Cortex para a organização (Configurações da organização → Conectores), liga as opções Skills e execução de
código da organização (Configurações da organização → Plugins e skills → Política) e decide como o plugin chega aos
advogados: cada um pelo caminho acima, se a organização permitir que os membros adicionem plugins, ou todos de uma
vez, pelo envio do pacote do plugin em Configurações da organização → Plugins e skills. O pacote e as orientações:
suporte@axiomaintelligence.com. Quem instalou antes o plugin por arquivo deve removê-lo e instalar pelo marketplace: a
versão enviada por arquivo não recebe atualizações.

No Claude Code (versão 2.1.275 ou posterior):

```
/plugin install axioma-cortex --marketplace axion-axm/cortex-plugin
```

Depois de instalar, conecte o Cortex quando o Claude pedir e faça o login com o e-mail convidado pelo escritório.

## O que vem no plugin

- O endereço do conector Cortex. Ao conectar, o Claude pede o login com o e-mail convidado pelo escritório.
- Seis atalhos (digite `/` e escolha no menu, que mostra o nome do plugin ao lado de cada um). Cada um começa com
  perguntas rápidas, a maioria com opções para clicar, e depois faz o trabalho:
  - `/axioma-cortex:cortex-consulta-autos`
  - `/axioma-cortex:cortex-relatorio-processual`
  - `/axioma-cortex:cortex-estrategia-processual`
  - `/axioma-cortex:cortex-pesquisa-jurisprudencial`
  - `/axioma-cortex:cortex-parecer`
  - `/axioma-cortex:cortex-minuta`

O plugin traz só instruções e o endereço do conector. Não traz chave, senha nem dado de processo: o acesso é
conferido no servidor do Cortex a cada consulta, pelo login de quem está usando.

## Exemplos

- "Resuma o processo [número CNJ do seu acervo]: partes, pedido, fase atual e próximas providências, com a página de
  cada fato."
- "/axioma-cortex:cortex-relatorio-processual para o processo [número CNJ do seu acervo], em versão para eu revisar antes de enviar
  ao cliente."
- "Pesquise jurisprudência do STJ sobre compensação de créditos reconhecidos em mandado de segurança tributário."

## Links

- Documentação: https://conector.cortex.axioma-app.com/documentacao
- Política de privacidade: https://conector.cortex.axioma-app.com/privacidade
- Termos de uso: https://conector.cortex.axioma-app.com/termos
- Suporte: suporte@axiomaintelligence.com

Cortex é um serviço da Axm Intelligence LTDA (Axioma Intelligence), CNPJ 68.922.576/0001-40.

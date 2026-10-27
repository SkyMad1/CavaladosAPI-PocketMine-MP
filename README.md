# Cavalados API

**Cavalados API** é uma versão modificada do **PocketMine-MP API 2.0.0**, desenvolvida em **PHP 7**, com melhorias, adaptações e recursos experimentais voltados principalmente para o ecossistema do **End Craft (antigo CraftsmanEND)**.

O projeto tem como objetivo expandir as funcionalidades originais do PocketMine-MP, possibilitando maior compatibilidade com recursos personalizados do End Craft, além de implementar sistemas experimentais que vão além das capacidades padrão da API original.

## ✨ Recursos e funcionalidades

- **Sistema experimental de proxy:** implementação de um protótipo de integração com proxy, ainda em desenvolvimento e parcialmente funcional.
- **Sistema avançado de troca de nicknames:** permite alterar os nicknames dos jogadores de maneira otimizada, buscando evitar conflitos durante o processo.
- **Detecção do End Craft:** mecanismo para identificar se um jogador está conectado ao End Craft (antigo CraftsmanEND).
- **Registro do Ender Pearl:** suporte ao registro do item Ender Pearl na API modificada.
- **Carregamento experimental de itens personalizados:** configurações que permitem forçar a exibição de itens específicos do End Craft que não estão registrados nativamente no PocketMine-MP.
- **Compatibilidade direcionada ao End Craft:** o modo de exibição forçada de itens foi projetado para funcionar exclusivamente com o End Craft, buscando evitar crashes no Minecraft PE original, nas versões 0.14.x até 0.15.10.
- **Colocação experimental de blocos não registrados:** implementação em fase de testes que permite colocar determinados blocos que não possuem registro nativo no PocketMine-MP. Atualmente, o funcionamento é limitado a alguns blocos específicos.

## 🧪 Estado do desenvolvimento

A Cavalados API contém funcionalidades experimentais que ainda estão em desenvolvimento e testes.

| Funcionalidade | Estado |
|---|---|
| Integração com proxy | Protótipo parcialmente funcional |
| Troca de nicknames | Sistema implementado |
| Detecção do End Craft | Recurso implementado |
| Registro do Ender Pearl | Implementado |
| Exibição forçada de itens personalizados | Experimental |
| Colocação de blocos não registrados | Em fase de testes |

*O funcionamento de determinados recursos pode variar conforme a versão do cliente, a configuração do servidor e o suporte oferecido pelo End Craft.*

## 🎯 Objetivo do projeto

Expandir e adaptar o PocketMine-MP API 2.0.0 para oferecer novas possibilidades de desenvolvimento, experimentação e compatibilidade com os recursos personalizados do End Craft, preservando o foco no ambiente legado do Minecraft PE 0.14.x–0.15.10.

## ⚠️ Aviso

Este projeto utiliza uma base legada do PocketMine-MP, com modificações específicas para atender às necessidades do End Craft. Algumas funcionalidades são experimentais e podem apresentar limitações ou comportamento inesperado.

**A Cavalados API não deve ser considerada totalmente compatível com todos os recursos do PocketMine-MP original ou com todas as versões do Minecraft PE.**

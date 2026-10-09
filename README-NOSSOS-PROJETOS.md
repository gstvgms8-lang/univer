# Univer: aplicações nos nossos sistemas

Documentação complementar de gstvgms8-lang, preparada em 09/10/2026 para estudo. As aplicações abaixo são propostas de avaliação, não funcionalidades já integradas aos nossos sistemas.

[Repositório original](https://github.com/dream-num/univer) · [Nosso fork](https://github.com/gstvgms8-lang/univer) · [README oficial](https://github.com/dream-num/univer/blob/dev/README.md) · [Documentação](https://docs.univer.ai) · [Biblioteca](https://github.com/gstvgms8-lang/referencias-projetos)

## Finalidade

**Área:** Editor de planilhas.

SDK para editores de planilhas, documentos e apresentações, com arquitetura de plugins, renderização em Canvas e motor de fórmulas.

## Possíveis aplicações

- Estudar seleção de células, edição, fórmulas, filtros e formatação para nosso editor de planilhas.
- Comparar o modelo de dados, os comandos de edição e undo/redo com as necessidades de persistência do nosso sistema.
- Pesquisar extensões por plugins antes de decidir entre incorporar o SDK e desenvolver componentes próprios.

## O que avaliar antes de integrar

- O repositório usa Apache-2.0; recursos e pacotes Univer Pro possuem condições próprias. Importação/exportação, colaboração e outros recursos não devem ser presumidos como parte gratuita deste fork.
- A branch padrão consultada é dev: avaliar uma versão estável apropriada antes de qualquer integração.
- Validar fórmulas e referências, separadores e datas em português, colagem, recuperação após falha e desempenho com planilhas representativas.

## Estado e próximos passos

O fork é uma referência para estudo e documentação. Nenhum pacote, skill, serviço ou integração foi instalado em nossos aplicativos nesta organização. A próxima etapa exige escolher o projeto-alvo, registrar requisitos e critérios de aceitação e avaliar uma prova de conceito isolada. Mudanças futuras devem preservar funcionalidades atuais e passar por revisão e testes de regressão.

## Preservação, créditos e manutenção

O código, os READMEs oficiais, avisos, licenças e históricos pertencem aos autores e colaboradores do [projeto original](https://github.com/dream-num/univer). Esta documentação própria não representa afiliação ou endosso. Consulte o [arquivo de licença original](https://github.com/dream-num/univer/blob/dev/LICENSE); dependências e componentes adicionais podem ter condições próprias.

Manter este guia separado como `README-NOSSOS-PROJETOS.md`, sem substituir documentação ou licença original. Para atualizar o fork, conferir mudanças do upstream e resolver conflitos sem apagar customizações ou reescrever o histórico. Atualizar o fork não atualiza automaticamente os aplicativos.

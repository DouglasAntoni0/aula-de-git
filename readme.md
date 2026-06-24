# Aula de Git

![Git](https://img.shields.io/badge/Git-controle%20de%20versao-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-repositorio-181717?style=for-the-badge&logo=github&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-base%20web-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-estilizacao-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Projeto de prática para fixar comandos essenciais de Git, organização de arquivos e publicação de uma base web simples no GitHub. O repositório contém arquivos HTML, CSS e textos de apoio usados como base para exercitar alterações controladas e rastreáveis.

Mesmo sendo uma entrega pequena, o projeto comunica uma prática importante: todo repositório público deve explicar minimamente seu propósito. Isso facilita leitura, revisão e reaproveitamento, além de demonstrar disciplina técnica.

## Objetivo do projeto

Este repositório foi criado para praticar o fluxo inicial de trabalho com Git e GitHub:

- clonar ou criar um repositório;
- alterar arquivos locais;
- conferir mudanças com `git status`;
- preparar arquivos com `git add`;
- registrar histórico com `git commit`;
- publicar no GitHub com `git push`;
- manter o README coerente com o conteúdo do projeto.

Esse fluxo é base para qualquer atuação técnica em desenvolvimento, QA, automação de testes e engenharia de qualidade.

## O que este projeto demonstra

| Frente | Aplicação prática | Por que importa |
| --- | --- | --- |
| Git básico | Criação, alteração e versionamento de arquivos | Garante histórico e rastreabilidade |
| Organização de repositório | Separação entre HTML, CSS e arquivos de apoio | Facilita leitura e manutenção |
| Evolução incremental | Mudanças pequenas e registradas | Ajuda a entender o que mudou e quando mudou |
| Comunicação técnica | README estruturado para explicar objetivo e execução | Evita repositório sem contexto |
| Base web | Arquivos `index.html` e `styles.css` | Aproxima o exercício de um projeto real simples |

## Estrutura do repositório

```text
.
├── exemplo.txt      # Arquivo de apoio para prática de alteração
├── exemplo2.txt     # Segundo arquivo de apoio
├── index.html       # Página HTML base
├── readme.md        # Documentação do repositório
└── styles.css       # Estilos da página
```

A presença de arquivos diferentes permite praticar Git de forma mais realista: nem toda mudança acontece em um único arquivo, e saber selecionar o que entra em cada commit é parte importante da rotina profissional.

## Como executar localmente

Clone o repositório:

```bash
git clone https://github.com/DouglasAntoni0/aula-de-git.git
cd aula-de-git
```

Abra o arquivo `index.html` no navegador para visualizar a página estática.

## Fluxo de trabalho recomendado

Depois de modificar algum arquivo, use:

```bash
git status
```

Adicione os arquivos alterados:

```bash
git add index.html styles.css readme.md
```

Crie um commit com mensagem objetiva:

```bash
git commit -m "Atualiza estrutura da aula de git"
```

Envie para o GitHub:

```bash
git push
```

## Resultado técnico

O repositório consolida uma etapa importante da formação: usar GitHub como ferramenta de rastreabilidade. Essa prática aparece de forma mais madura nos demais projetos, onde versionamento, documentação e execução reprodutível sustentam suítes de testes automatizados.

Em QA, rastreabilidade é um ativo. Ela ajuda a responder perguntas como:

- quando uma mudança foi feita;
- qual arquivo foi alterado;
- qual versão estava em uso durante uma falha;
- qual ajuste pode ter causado uma regressão;
- qual evidência pertence a qual entrega.

## Competências evidenciadas

- Uso inicial de Git e GitHub.
- Organização básica de projeto web.
- Separação entre estrutura HTML e estilo CSS.
- Escrita de documentação simples e objetiva.
- Compreensão de histórico e entrega incremental.

## Possíveis evoluções

Este projeto pode ser expandido com:

- uma página HTML com conteúdo semântico;
- estilos mais organizados no CSS;
- publicação via GitHub Pages;
- checklist de validação visual;
- pequenos testes manuais documentados;
- integração futura com automação de interface.

## Conclusão

Este repositório representa uma base. Ele não tenta ser complexo; ele demonstra o começo correto: versionar, organizar, documentar e publicar. Esse cuidado é o mesmo que sustenta projetos maiores de automação, API testing, mobile testing e CI/CD.

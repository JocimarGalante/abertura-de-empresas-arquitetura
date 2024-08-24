# Desafio Arquitetura Front: Abertura de Empresa

Nosso sistema pode precisar reutilizar um componente básico como um botão ou até mesmo um estrutura maior. Desta forma temos que pensar como estruturar esses componentes de uma forma escalável. Outra questão bem pertinente é ter vários clientes usando um mesmo sistema. Como exibir o mesmo conteúdo só mudando a cor, por exemplo?

Neste desafio, te convidamos a pensar como alguém que irá realizar a solicitação de abertura de uma empresa. Em que teremos três telas. Simule através das rotas a mudança de layout para um cliente A, B e C, podendo nomeá-lo como desejar. Ao entrar na primeira tela o sistema mudará a cor principal do sistema de acordo com o cliente acessado.

Não teremos protótipo, pois a intenção é avaliar também a sua criatividade e interpretação do escopo. Pode colocar itens adicionais para compor a tela, os essenciais são:

## Primeira Tela
- Coloque um cabeçalho com o logotipo fícticio do cliente
- Título da Página: Abertura de Empresa
- Listagem de opções: Abertura de Matriz e Abertura de Filial

## Segunda Tela
- Cabeçalho padrão
- Título da Página de acordo com a opção escolhida na tela anterior
- Formulário com duas seções:
  - Dados do Solicitante: Nome, CPF, Data de nascimento.
  - Dados da Empresa: Nome fantasia e Entidade de registro (Cartório, Junta Comercial, OAB ou RFB)
    - Caso seja Filial, terá que informar a UF e CNPJ da Matriz (Estruture essa condição de uma forma limpa)
- Botão de Solicitar e Voltar. Crie um componente botão que terá variações de estilo primário e secundário (Deixando escalável caso surja outros estilos).
- Ao clicar em Solicitar o sistema valida se os campos estão preenchidos, e então estando ok mostra um modal de sucesso com a mensagem "Solicitação cadastrada com sucesso" e direciona para a tela final.

## Terceira Tela
- Cabeçalho padrão
- Título da Página de acordo com o fluxo escolhido
- Confirmação dos dados: Liste os dados preenchidos na tela anterior
- Botão de Nova solicitação direcionando para a primeira tela

## Avaliação

### O mínimo que esperamos
- Esperamos que faça commits com poucas alterações, sendo bem coerente e semântico nas mensagens
- Documente os comandos de instalação e execução e rota inicial para cada cliente
- Documente a estrutura do projeto, principais funções e arquivos
- Use o framework Angular na versão LTS ou até duas versões anteriores à LTS
- Opcional: Usar um framework de UI
- HTML, CSS e Typescript
- Use o gerenciador de pacotes npm
- Crie um repositório no Gitlab

### Pontos diferenciais
## Básico
- Clean Code
- SOLID
- Parte visual bem estruturada
- Layout Responsivo

## Médio
- Clean Architecture
- ESLint e Prettier
- Validações e feedbacks visuais

## Avançado
- Testes unitários
- Utilizar uma API fake como json-server
- Desenho da arquitetura da solução
- Subir projeto em algum lugar (Heroku, Netlify, Vercel)

### Como nos enviar a resolução
- Crie um repositório, adicionando como membro (develop) o usuário `jocimargalante`;
- Desenvolva. Você terá 3 (três) dias a partir da data do envio do desafio;
- Crie um arquivo README.md com a explicação de como devemos executar o projeto e com uma descrição do que foi feito, o que não fez e/ou o que poderia melhorar; 
- Após concluir seu trabalho, publique e nos comunique com o link do repositório; 
- Pronto! Agora é so esperar o nosso feedback... Boa sorte!!

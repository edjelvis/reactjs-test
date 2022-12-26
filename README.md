# ReactJs Teste

### Tela "login":

- Ao entrar app pela primeira vez, devo inserir meu nome de usuário do Github. O meu nome aparecerá em todas as telas, no topo em uma toolbar fixa, incluindo foto de perfil. Se eu clicar no meu nome, no topo, deve ser redirecionado para a tela de dados do usuário.
---

### Tela inicial/busca:

- Na tela inicial consigo pesquisar um usuário pelo username do Github retornando os repositórios do mesmo em uma nova tela.

- Na tela inicial, vejo um botão de histórico, onde quando clicado me leva a uma tela que mostra as últimas 20 pesquisas que fiz.
----

### Tela de repositórios:

- Na tela de listagem de repositórios, deverá exibir:
  - nome do usuário `*`;
  - total repositórios encontrados;
  - listagem de repositórios:
    - nome do repositório;
    - descrição (se houver `**`);
    - linguagem daquele repositório

- Eu consigo abrir cada repositório mostrado clicando nele, indo para o GitHub respectivo.
- Tenho a possibilidade de buscar novamente através de um botão dedicado.

```
* Obs: deverá exibir através de ícone, ou com texto destacado (sublinhado, cor diferente, negrito) o nome do usuário onde é possível clicar e ser redicionado para uma tela com os dados gerais do usuário.
** Obs: se não houver descrição, deve exibir de forma destacada uma mensagem de que não há conteúdo disponível.
```
---

### Tela de histórico:

- Na tela de histórico eu vejo a data e hora de pesquisa, o username, status (se foi localizado com sucesso ou não), e a quantidade de repositórios encontrados.

- Ao clicar no nome do usuário em um item do histórico, deverá abrir a tela de visualização de detalhes do usuário.

- Ao clicar no total de repositórios deverá ser redicionado para a tela de listagem de repositórios.

- Deverá ter um botão com ícone para que eu possa excluir o item do histórico.
----

### Tela de detalhes do usuário:

- Exibir nessa tela os dados do usuário, sendo:
  - nome;
  - tag do usuário;
  - quantidade de seguidores;
  - quantidade de pessoa seguindo o mesmo;
  - quantidade de repositórios `*`;
  - biografica (se houver `**`);
  - email (se houver `**`);
  - twitter (se houver `**` `***`);
  - nome da empresa (se houver `**`);
  - site (se houver `**` `***`)

- Possuir um botão para alterar o usuário "logado" `****`;

```
* Obs: deve ser possível, ao clicar no total de repositório e ser redirecionado para a tela de listagem dos mesmos.
** Obs: se não houver descrição, deve exibir de forma destacada uma mensagem de que não há conteúdo disponível.
*** Obs: se houver twitter ou site próprio, ao clicar deve redirecionar para seus respectivos links em uma aba separada.

****: Ao clicar nesse botão, deve ser redirecionado para a tela de "login".
```


### Informações adicionais:

- Se eu fechar a página/app, ao voltar, deverá aparecer o último nome configurado, no topo, indo direto para a tela de busca (tela inicial).
---


## Requisitos:
- ReactJS `*`
- Context API ou Redux;
- Typescript `*`
- Bibliotecas de pacote de componentes como MaterialUI por exemplo.

Obs: os itens marcado com "`*`" são obrigatórios.<br />

---

## Observações:
- Pode usar algum boilerplate, a questão maior a ser validade será a organização interna.
- Fazer a documentação no Readme do repositório (deploy, dependências, etc) 
- Não há um padrão de design fixo, seja livre na escolha de cores, fontes, e qualquer item que seja da identidade visual.
- Suba para o Github.

[Link para visuaização do fluxo das telas](https://whimsical.com/Gsz118BwUD1ZqhnBDbwsWH)

BOA SORTE! 😉️

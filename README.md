![RAM_LOGO_FINAL](https://user-images.githubusercontent.com/71162750/111799267-9eccbb00-88a9-11eb-974c-b7f1bbff1d43.jpg)


## Link: http://tainah-taqtile-challenge.surge.sh/
---

### Challenge Rick n Morty desenvolvido para a Taqtile <br>

### 📝️ Challenge
<h4> A ideia foi desenvolver 2 telas consultando uma API, conforme a seção com esforço estimado de 12h~16h. </h4>

### 🚀️ Tecnologias utilizadas

- ReactJS
- API: <span>https://rickandmortyapi.com/documentation/#get-a-single-episode</span>
- Material-UI
- Styled-components
- Axios
- React-dom-router

### Desenvolvido por

<a href="https://www.linkedin.com/in/tainah-bernardo/">***Tainah Boarini Bernardo***</a>
<br/> 

![screencapture-tainah-taqtile-challenge-surge-sh-home-2021-03-19-11_54_20](https://user-images.githubusercontent.com/71162750/111799547-e3585680-88a9-11eb-9d69-100f83e7a995.png)
![screencapture-tainah-taqtile-challenge-surge-sh-characterDetails-2-2021-03-19-11_54_33](https://user-images.githubusercontent.com/71162750/111799555-e4898380-88a9-11eb-9524-0ed754ca6164.png)



---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# Descrição do desafio:


## Bem-vindo 
A Taqtile é uma empresa que contribui para o desenvolvimento de estratégias mobile para centenas de marcas relevantes no mercado brasileiro e internacional. Isto só é possível pois todos colaboradores carregavam um senso crítico e uma preocupação de aprimoramento constante. Nosso objetivo é sempre manter o senso de qualidade, contando com pessoas totalmente alinhadas com nosso dever para com os clientes internos e externos. 

## O desafio
A ideia é simples, você deverá desenvolver 2 telas consultando uma API (Graphql), conforme a seção "Instruções", com esforço estimado de 12h~16h. O prazo pode ser estendido até 1 semana a partir do fork, mas também aumentará o rigor com que o código será avaliado.

**Dica:** tente atingir os objetivos básicos para depois partir para a seção bônus.

## Instruções
1. Crie um repositório privado na sua conta do github.
2. Convide os membros da Taqtile como colaboradores: `emiyake`, `felipewaku`, `tibawatanabe`.
3. Crie uma branch `challenge/rickandmorty`. 
4. Crie um projeto [React](https://pt-br.reactjs.org/docs/create-a-new-react-app.html#create-react-app) nesta branch.
5. Consuma a API https://rickandmortyapi.com/graphql
6. Desenvolva a listagem de personagens (em forma de lista ou cards). Como exibição padrão, a listagem deve trazer todos os personagens com as seguintes informações:
   - imagem do personagem;
   - status;
   - nome do personagem.
 
7. Ao clicar em um dos personagens, uma tela contendo os detalhes deverá ser apresentada. Deve conter:
   - imagem do personagem;
   - nome do personagem;
   - todos os episódios que o mesmo apareceu (apenas o nome).
 
8. A tela de detalhes deverá possuir um botão ou link para retornar a listagem.
9. Ao concluir seu desafio, faça um pull request para a branch `master` e notifique os membros da Taqtile para realizar o code review.

## Regras
- Você pode discutir este exercícios com outras pessoas, mas não peça para ninguém escrever ou revisar seu código.
- Você pode nos contatar a qualquer momento para tirar suas dúvidas ou para qualquer outra necessidade.
- Você pode usar o Google para qualquer necessidade de consulta.
- Você pode usar qualquer biblioteca que julgar necessário.
- Não será necessário implementar nenhum mecanismo de paginação.
- Para exibição da tela de detalhes não é necessário implementar nenhum mecanismo de rotas. Mas também não há problemas de adotar um pacote para este fim. No entanto, o detalhe deve ser exibido em uma tela em branco ou sobrepondo a listagem (modal).
- Não será necessário persistir a posição do scroll da listagem ao retornar do detalhe para a listagem.
- Realizar commits a cada tarefa concluída. Não faça apenas um commit no final.

## Bônus
- Utilização do `styled-components`.
- Demonstrar algum comportamento responsivo (desktop vs. mobile) com apenas um breaking point: 768px.
- Utilização de conceitos de atomic design.
- Comportamento adequado do botão "back" do browser ao voltar do detalhe para a listagem.

**Importante:** de tentar contemplar os itens de bônus, tenha em mente que não estamos avaliando a perfeição, e sim o equilíbrio entre objetivo principal, esforço esperado (12~16h) e a compreensão de conceitos. Os itens desta seção devem ser utilizados para facilitar o desenvolvimento e não trazer mais complexidade ao desafio.

## Critérios de avaliação
- Não esperamos que você seja super familiarizado com React, Typescript, ou nada que utilizamos como stack padrão em nossa empresa.
- Fazer perguntas é positivo. Não penalizaremos por questionarem. No nosso ambiente de trabalho, preferimos que a pessoa gaste um tempo para entender o que deve ser feito, do que despender o dia inteiro implementando algo errado.
- Buscamos levantar indícios que você entende conceitos como separação de responsabilidades, reatividade, reaproveitamento de código, composição, eventos, promises.
- A API pode retornar erro. Seu código deverá tratar de forma amigável tais exceções. Exemplo: timeout, problemas de conexão, erro de rota, etc.
- Esperamos que seu código seja limpo, fácil de ser compreendido e testado. Comente seu código mas lembre-se que excesso de comentários também é fonte de poluição.
- Se você considerar este desafio muito complexo ou se sente travado, sinta-se à vontade em pedir nossa ajuda. Preferimos candidatos que atinjam seu objetivo, mesmo com auxílio, do que simplesmente desistir.
- Realizaremos o pull de seu branch. Para rodar o sistema, executaremos dois comandos em sequência:
  - `yarn install`
  - `yarn start`
  - O sistema deverá ser executado sem nenhum erro no console ou terminal.

## FAQ
### Posso usar Next, Gatsby ou outro framework?
Para este projeto, gostaríamos que utilizasse a biblioteca da forma mais limpa, ou seja, através do cli `create-react-app`.

### Posso utilizar Typescript para escrever meu código?
Sim.

### Como devo organizar as pastas e nomear meus arquivos?
Não há uma regra para isto. Apenas tenha em mente que esta separação deve seguir alguma regra consistente.

### Eu preciso fazer o deploy da resposta?
Não. A sua branch deve ser enviada através de um pull request e deverá rodar através do comando `yarn start` sem erros.

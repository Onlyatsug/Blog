+++
date = '2025-07-23T13:32:52-04:00'
draft = true
title = 'O básico de UI/UX Design'
+++

### Introdução

Inspirado por revisar conceitos de **UI**, decidi resumir o *"processo das coisas"* de uma forma simples. Apesar de ser fácil encontrar uma infinidade de conteúdos sobre o assunto, optei por filtrar e sintetizar apenas os de maior qualidade, lembrando que a ideia não é se aprofundar, mas sim possibilitar o entendimento do desenvolvimento de **interfaces gráficas** — servindo tanto para a web, aplicativos ou até mesmo sistemas robustos.

---

### User Flow

O primeiro passo, após a **análise de requisitos**, é pensar e demonstrar graficamente o comportamento do usuário ao acessar sua interface.

Podemos começar exemplificando: no seu app favorito de assistir séries ou filmes, ao acessá-lo, você passa por algumas etapas — *fazer login*, *buscar o nome de determinada série ou filme*, *escolher o episódio* e por aí vai...

**O ponto é**: precisamos ter em mente o *trajeto* que o usuário vai percorrer e pensar na melhor maneira de ele fazer isso.

E um de jeito fazer isso é usando um diagrama. Algumas regras simples se aplicam:

- **Retângulo** → Representa uma *interface completa*.
- **Losângulo** → Representa uma *condição possível*.
- **Círculo** → Representa uma *ação do usuário*.

Exemplo com o app *JOJUCO 2023*[^1]

![a](/userflow.png)

> Percebe-se que este é apenas um exemplo *inicial* e ele segue um fluxo contínuo. Ou seja, mesmo que, a partir das telas especifícas, o usuário possa voltar para a tela inicial, **não precisamos indicar isso**.

Utilize o *Figma*[^2] para prototipar, caso queira acessar o projeto da imagem acima, acesse por aqui:

[🔗 Acessar projeto no Figma](https://www.figma.com/board/QDXp9ZPyTA5zGtPL7fEz84/User-Flow-Template?node-id=0-1&t=YCvEwOWcJ0b5DQl0-1)


Após isso, eu sinceramente recomendo analisar novamente todo o *"flow"* e reduzir o que puder de telas inteiras. Acredite em mim: todas terão um propósito, sem excessos.  
> *Às vezes, o jeito mais fácil é cortar, em vez de adicionar*.

---

### Wireframes

Nessa etapa, vamos desenvolver cada uma das telas definidas anteriormente.  
Mas se acalme: **nada de cores, fontes ou estilos ainda**...

Aqui vamos ser brutos — **caixas, círculos e rascunhos**.  
O foco é inserir de forma grosseira o que deve ser visualizado. Também vale buscar inspiração funcional na web.

Quer prototipar uma tela de cadastro para um usuário comentar no seu blog? Simples, procure e use o que já funciona, não é hora de ser criativo!

Exemplo: *Blog da web servindo de inspiração para prototipar um app*

![b](/wireframe.png)

> A partir de um exemplo de um site, adaptei meu aplicativo com os elementos funcionais. Perceba que o usuário ao clicar no campo "Nome", ele expande outros campos necessários para o cadastro, isso é necessário porque ao pensarmos no usuário que não quer comentar e apenas ler os comentários, ficaria com muita informação inútil na tela.

**Extra:** vale a observação que, se o usuário já estivesse feito login, a tela seria diferente. Não seria necessariamente uma tela inteiramente nova, mas a mesma com uma condição diferente. Podemos criar outras telas com essas mudanças no futuro, mas saiba que o desenvolvedor front-end será responsável por reaproveitar a mesma tela com uma lógica por trás.

Você pode utilizar ferramentas como o *Figma* ou o *Excalidraw*[^3].

Dito isso, faça isso para todas as interfaces catalogadas no *user flow*, e finalmente estamos prontos para a próxima etapa.

[^1]: App de gerência de torneios entre atléticas acadêmicas. [JOJUCO 2023](https://play.google.com/store/apps/details?id=br.com.unic.jojuco2023&hl=pt_)
[^2]: Figma é uma ferramenta online de design e prototipagem colaborativa muito utilizada para criar interfaces de usuário.
[^3]: Ferramenta online de desenhos e rascunhos (eu particularmente a uso muito) [Excalidraw](https://excalidraw.com/).
# Brumadinho Location

## English
The aim of this project is to setup a repository of tools to support the search and rescue efforts,currently taking place at Brumadino/MG/Brazil, in response to the [**Brumadinho dam disaster**](https://en.wikipedia.org/wiki/Brumadinho_dam_disaster) occurred on 25 January 2019. As this file is being updated, 65 people have been confirmed dead and over 300 are still missing.

### How to colaborate:
* Please see the list of [Projects](https://github.com/dieegom/brumadinho_location/projects) that are being worked on and their respective issues. Project details are also listed below.
* If you can help with any issue, please add a comment to the issue to indicate that that you will work on it. 
* If you are the first to work on any given project, you can choose the language or technology that you are more familiar with.
* If other volunteers are already helping with the project then please contact them to discuss what still needs to be implemented.
* Once your change is complete please submit your Pull Request.
* If you would like to suggest other tools for development then please create an issue and tag it with the #suggestion label.

You can fork the project at will. We will continue to improve the code throughout the week.
Join us in this project! This may be useful in the future as well.
Thank you!

### - Location 
This tool calculates the probable location of missing individuals' bodies by taking into consideration their last known location coordinates (i.e. latitude and longitude) and the tailing flows.

The algorithm still needs improvement and to improve it, we will need tailings physical-chemical data, location topographic map (.csv), simulations of the tailing spreading, and, of course, the latitude and longitude coordinates from the victims' cell phones.

The production enviromment is currently live at: http://18.218.138.85

We ask that those contributing to the project submit their Pull Requests as soon as possible to help improve the algorithm and make it available to those responsible for the search and rescue operations.

#### Ideas to be implemented:
*  http://fluidityproject.github.io/
*  http://lorenabarba.com/blog/cfd-python-12-steps-to-navier-stokes/
*  https://pt.wikipedia.org/wiki/Equa%C3%A7%C3%B5es_de_Navier-Stokes
*  http://rlguy.com/gridfluidsim/
  
### - Where we had searched
This tool provides information regarding  areas that have already been inspected by the search and rescue teams. 

### - Report info
App to report missing people and missing animals.

### - Missing people list
This tool returns an updated .csv with all the names of missing people.

## Português
Pretendemos que esse projeto seja um repositório de ferramentas para ajudar no resgate e localização das vítimas atingidas pelo rompimento da barragem que ocorreu recentemente em Brumadinho/MG, onde muitas pessoas morreram e muitas outras ainda estão desaparecidas. 

>No início da tarde do dia 25 de janeiro de 2019 rompeu-se uma barragem de rejeitos de mineração controlada pela Vale S.A.,construída no ribeirão Ferro-Carvão, na localidade de Córrego do Feijão.
>
> — https://pt.wikipedia.org/wiki/Rompimento_de_barragem_em_Brumadinho

### Como colaborar

* Acesse [Projetos](https://github.com/dieegom/brumadinho_location/projects) e veja a lista de ferramentas que estamos e suas respectivas issues. Você também pode ver essa lista logo abaixo. 
* Se você puder ajudar com alguma issue, escreva um comentário dizendo que você irá trabalhar nela.
* Se você for o primeiro a trabalhar no projeto, você pode escolher a linguagem ou tecnologia que se sinta mais confortável.
* Se mais voluntários estiver ajudando, contate-os antes para saber o que ainda precisa ser implementado.
* Quando acabar, façam seu Pull Request.
* Se tiver sugestão de alguma outra ferramenta, cadastre uma issue usando o label #suggestion

"Forkem" à vontade. Continuaremos melhorando o código ao longo da semana. <br/><br/>
Vamos todos fazer a nossa parte! Isto pode ser útil no futuro também.<br/>
Obrigado.

### - Location 

Essa ferramenta requer as coordenadas de latitude e longitude dos desaparecidos para calcular a estimativa baseando-se no fluxo de rejeitos <br/>
O algoritmo precisa ser melhorado (e muito) ainda. Além disso, fizemos apenas com os poucos dados que obtivemos. Ideal seria termos dados físico-químicos do rejeito, mapa topográfico (em .csv) do local, simulações do rejeito se espalhando e, claro, latitude e longitude dos celulares.<br/>

Vamos deixar o sistema atualizado rodando em: http://18.218.138.85  <br/>
Pedimos aos Devs que façam seus Pull Requests para que possamos deixar este algoritmo mais robusto e disponível para os responsáveis pelo resgate. "Forkem" à vontade. Continuaremos melhorando o código ao longo da semana. <br/><br/>

####  Ideias a serem implementadas: <br/>
*  http://fluidityproject.github.io/ <br/>
*  http://lorenabarba.com/blog/cfd-python-12-steps-to-navier-stokes/ <br/>
*  https://pt.wikipedia.org/wiki/Equa%C3%A7%C3%B5es_de_Navier-Stokes <br/>
*  http://rlguy.com/gridfluidsim/<br/><br/>

### - Onde já foi buscado
Nesta ferramenta locais e equipes de resgatem podem fornecer informações de geolocalização sobre as áreas onde as buscas já foram realizadas.

### - Report info
App para relatar informações de pessoas e animais desaparecidos


### - Missing people list
Essa ferramenta retorna um arquivo .csv atualizado com todos os nomes das pessoas desaparecidas.

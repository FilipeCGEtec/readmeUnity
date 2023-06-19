# Projeto Unity: Skate

# Informações do projeto:
   - `Status`: Finalizado
   - `Linguagem`: C#
   - `Plataforma`: Unity (versão 2021.3.6f1)
   - `Autores`: Filipe Custódio, João Lucas
# Índice
  * [Título](#projeto-unity-skate)
  * [Badges](#informações-do-projeto)
  * [Índice](#índice)
  * [Descrição do Projeto](#descrição-do-projeto)
  * [Funcionalidades](#funcionalidades)
  * [Informações Técnicas](#informações-técnicas)
  * [Acesso ao Projeto](#onde-acessar)
  * [Tecnologias utilizadas](#tecnologias)
  * [Conclusão](#conclusão)

# Descrição do projeto:
 <P>Projeto desenvolvido para a diciplina de Linguagem de programação do curso de desesnvolvimento de jogos digitais da escola Etec Professor Basilides de Godoy.</P>
 <P>Este projeto foi desenvolvido no Unity, nele foi construida uma cena que simula uma pista de skate com diversos trajetos. A cena conta com elementos basicos como movimentação, gravidade e colisão.</P>

# Funcionalidades
  - `Movimentação`: O skate pode se mover para frente e para trás, alem de poder se mover lateralmente quando se rotaciona. Algumas plataformas tambem se movem constantemente na cena.
  - `Colisão`: O skate tem uma caixa de colisão" adicionada através do elemento "Boxcolider" do proprio Unity.
  - `Pulos`: O pulo é similar a movimentação basica, mas é limitado pelo tempo real, não por frames pos segundo (mais informações em ).
    - `Manobras`: As manobras são rotações que o skate faz quando está pulando.

# Informaçoes Técnicas:
  <h2>Skate<h2>
    <h3>Scripts<h3>
      <h4>Andar</h4>
        <P>  "Andar" é um script feito em C# para a movimentação do skate. O script manipula o objeto a se mover no eixo X usando Uma condicional e a função Input.GetKey(KeyCode) Para identificar as teclas. Com isso, é possivel determiar a direção em que o skate vai seguir. Para o skate andar para os lados, existe as condiçoes em que 2 botoes devem der precionados, fazendo o skate rotacionar levemente na direção determinada.</P>
        <P>  Pelos frequetes problemas de queda do skate, o script tambem conta com uma funcionalidade extra. Com apenas um botão, o skate vai ser posicionado intantaneamente no ponto inicial de sua geração, podendo se mover livremente após isso.</P>
      <h4>Pulo e Manobras</h4>
        <P>  "Manobras" é o script que move o skate verticalmente da mesma forma que a movimentação do script "Andar". A principal diferença é que o script de pulo é feito com base em tempo real, diferentemente do movimento tradicional, feito a cada frame por segundo.</P>
        <P>  No mesmo script estão as manobras do skate. As manobras consistem na rotação do skate em diferentes eixos quando pula.</P>

  <h2>Plataforma</h2>
    <h3>Scripts</h3>
      <h4>  Movimentação</h4>
        <P>  "Movimentação" é o script que faz com que certas plataformas se movam em determinados eixos em uma distancia fixa.</P>
        
  ## Comandos
   - `W`: Desloca no eixo X a uma velocidade (Vái para frente)
   - `S`:  Desloca no eixo X a uma velocidade negativa (vai para trás)
   - `W/S + D`:  Faz rotacionar no eixo Y a um valor a cada FPS
   - `W/S + A`: Faz rotacionar no eixo Y a um valor Negativo a cada FPS
   - `ESPAÇO`: Faz o Skate se deslocar no eixo Y.
      - `I`:  Faz a manobra "Ollie"
      - `O`:  Faz a manobra "Mortal"
      - `U`:  Faz a manobra "Flip"
   - `M`:  Volta o skate para posição inicial
   - `N`:  Volta para o angulo inicial

# Técnologias Utilizadas:
  <P>Todos os scripts do projeto foram feitos utilizando a linguagem C#</P>

# Desenvolvimento:

<P>   A primeira coisa a ser feita foram instalar assets externos através da loja de assets do próprio Unity. Logo em seguida foram baixadas diversas imagens para que sirvam de textura para materiais.</P>
<P>   A cena começou a ser montada com um grande cubo como base, o skate importado, seguido por algumas rampas, barris e containers para trajetos. Os trajetos são: Um bloco com diversos containers para subir, uma pequena ponte com duas rampas, um loop  feito com diversas rampas agrupadas e um pequeno corredor com barris, uma grande rampa em format de funil</P>
<P>   Finalmente, foram feitos os scripts para o skate e plataformas, seguido pela aplicação de materiais e a adição de alguns grafites.</P>
<img src="https://github.com/FilipeCGEtec/readmeUnity/assets/127852282/9c8a4864-41f6-4c60-af3a-f781174a4216">
<img src="https://github.com/FilipeCGEtec/readmeUnity/assets/127852282/f14b77ee-72ad-478e-b40e-f1d15364c605">
<img src="https://github.com/FilipeCGEtec/readmeUnity/assets/127852282/41674cc4-c27e-4d37-a9ae-57cda8bfc5d0">
<img src="https://github.com/FilipeCGEtec/readmeUnity/assets/127852282/b43feb3f-f3fe-4d49-89b0-20cfe5494652">
<img src="https://github.com/FilipeCGEtec/readmeUnity/assets/127852282/22949f0e-7625-4b08-b302-566aab07bdd4">
<img src="https://github.com/FilipeCGEtec/readmeUnity/assets/127852282/27fd9195-3722-4381-b354-fa377fd77a6e">
<img src="https://github.com/FilipeCGEtec/readmeUnity/assets/127852282/16edb293-9afa-45ad-8c79-082d41fa6e4a">
<img src="https://github.com/FilipeCGEtec/readmeUnity/assets/127852282/911de527-c5a1-4f12-bc81-d083644fad0">

# Onde acessar:

  <p> Você pode acessar a pasta compactada no Google drive do projeto clicando <a href="https://drive.google.com/drive/u/0/folders/1sHKxyeKL0Bc2_k_Pb2iH4mJZtojDq1YE">AQUI</a></p>

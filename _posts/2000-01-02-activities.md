---
title: Discover
bg: activities
color: white
icon: cesium.png
---

#### A city church with a community presence

# City Evangelical Church
<div class="row features">
  <div class="col s12 m4 feature">
    <i class="fa fa-compass fa-4x">
    </i>
    <h4> Services </h4>
    <p class="feature-description"> We meet every Sunday for church services at 10:45 and 18:30. </p>
  </div>
  <div class="col s12 m4 feature">
    <i class="fa fa-book fa-4x">
    </i>
    <h4> Growth groups </h4>
    <p class="feature-description"> On Tuesdays, Wednesdays and Thursdays we meet in small groups for bible studies in peoples homes. </p>
  </div>
  <div class="col s12 m4 feature">
    <i class="fa fa-terminal fa-4x">
    </i>
    <h4> Prayer </h4>
    <p class="feature-description"> On the first Wednesday of every month is our church prayer meeting. </p>
  </div>
</div>

<ul class="challenge collapsible" data-collapsible="accordion">
  <li>
    <div class="challenge-title collapsible-header"><i class="fa fa-terminal fa-4x"></i>Enunciado</div>
    <div class="challenge-body collapsible-body">
      {% highlight haskell %}
-- Descobrir o posicionamento de aspersores de água
-- Por cada posição regada, 1 ponto é atribuído
-- O objetivo é maximizar a pontuação
  -- Só se podem colocar no máximo 8 aspersores
  -- Cada aspersor só pode regar com um raio máximo de 20
  -- Não se pode regar mais do que um cato
  -- Não se pode regar fora da área de 51x51

-- Posições dos catos:
  [(1, 14),(3, 47),(18, 6),(18, 2),(22, 17),(37, 3),(9, 6),
  (23, 10),(12, 49),(21, 50),(33, 0),(30, 47),(36, 16),(20, 22),
  (2, 41),(37, 48),(18, 9),(48, 36),(28, 34),(5, 24)]

-- Syntax do output
  [(x, y, radius), (x, y, radius)]
-- Exemplo de output
  [(5, 5, 2), (35, 5, 1)]

-- A linguagem para a resolução do desafio fica à tua discrição
      {% endhighlight %}
      <a class="challenge-apply waves-effect waves-light btn bg-white" href="http://storm.cesium.di.uminho.pt/desafio/index.html" target="blank">Submeter</a>
    </div>
  </li>
</ul>

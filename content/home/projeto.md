+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 80  # Order that this section will appear.

title = "Projeto Final"
subtitle = ""

[content]
  # Page type to display. E.g. project.
  page_type = "project"
  
  # Filter toolbar (optional).
  # Add or remove as many filters (`[[content.filter_button]]` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `[[content.filter_button]]` below.
  
  # Default filter index (e.g. 0 corresponds to the first `[[filter_button]]` instance below).
  filter_default = 0
  
  # [[content.filter_button]]
  #   name = "All"
  #   tag = "*"
  
  # [[content.filter_button]]
  #   name = "Deep Learning"
  #   tag = "Deep Learning"
  
  # [[content.filter_button]]
  #   name = "Other"
  #   tag = "Demo"

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "2"

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view = 5

  # For Showcase view, flip alternate rows?
  flip_alt_rows = false

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.
  
  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  # image = "background.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.

  # Text color (true=light or false=dark).
  # text_color_light = true  
  
[advanced]
 # Custom CSS. 
 css_style = ""
 
 # CSS class.
 css_class = ""
+++

Esta é a última avaliação da turma de Introdução à Modelagem de Big Data do semestre 2020.2. É um projeto de análise de dados, com assunto e escopo definido pelo próprio aluno, que deverá vir acompanhado de um relatório deito em R Markdown e ser apresentado em sala de aula a partir de 19/04/2021.

### Instruções

* Este projeto será avaliado de duas maneiras: em sala, numa apresentação de slides, e por escrito, através de um relatório

* A apresentação de slides deverá durar de 12 a 15 minutos

* Não há limite mínimo ou máximo para o número de páginas do relatório escrito

* Uma das seções do relatório deverá conter o código utilizado pelos alunos para resolver seu problema

* Os arquivos com a apresentação de slides, relatório e banco de dados devem ser enviados para o professor logo após a apresentação oral

* A data da entrega e apresentação do projeto é 19/04/2021, durante o horário da aula

O projeto visa avaliar aquilo que os alunos aprenderam durante o curso. Serão formados grupos de até três alunos, que irão realizar a análise de um conjunto de dados à sua escolha. Esta escolha é de inteira responsabilidade dos alunos. Algumas sugestões de áreas para o projeto são

* Dados biológicos

* Webscraping

* Mineração de textos 

* Genética

* Dados de localização

* Marketing

* Finanças

* Dados de saúde

Cada grupo deverá obter um banco de dados em algum destes assuntos ou outros, de modo a responder perguntas a seu respeito. É possível usar dados de suas próprias pesquisas, caso o aluno queira propor uma nova maneira de abordar seu trabalho. As perguntas a serem respondidas serão formuladas pelos próprios alunos. A única obrigatoriedade é a aplicação de ferramentas de análise de dados vistas no curso. Os grupos que quiserem propor a utilização de uma nova ferramenta que tenha similaridade com aquelas que vimos em aula sintam-se encorajados a fazê-lo. Algumas boas fontes para procura de dados:

* [Brasil.IO](https://brasil.io/)

* [Kaggle](https://www.kaggle.com/datasets)
  
* [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/)

* Sites de governos ([dados.gov.br](https://dados.gov.br/), [data.gov](https://catalog.data.gov/dataset))



### Exigências a Respeito dos Bancos de Dados a Serem Escolhidos

Há duas restrições a respeito dos dados a serem analisados:

1. Eles não podem ter sido analisados previamente em alguma aula da disciplina

2. Não podem haver dois ou mais grupos com bancos de dados que sejam subconjuntos um do outro ou com bancos de dados que sejam parte um um conjunto maior

Para evitar que hajam problemas respeito do item 2, solicito aos grupos que enviem um email para marcus@marcusnunes.me descrevendo o banco de dados que utilizarão. Assim, os primeiros grupos a escolherem o conjunto de análise terão preferência na escolha.




### Conteúdo do Trabalho

Alguns assuntos que podem ser tratados no projeto são

* Comparação entre dois ou mais métodos de classificação ou regressão

* Construção de um aplicativo no shiny

* Demonstração de uma alguma ferramenta de machine learning não vista durante a disciplina (Deep Learning, eXtreme Gradient Boosting etc.)

* Paralelização de código utilizando GPU

* Reprodução de algoritmos vistos em aula em outras linguagens, como Python ou Julia, e como o desempenho deles se compara ao R

Portanto, os alunos não precisam se limitar aos conteúdos vistos em aula.



### Datas Importantes

* 24/02/2021: entrega do pré-projeto final. No pré-projeto vão constar as seguintes informações
  * nomes dos membros dos grupos
  * descrição do conjunto de dados a ser analisado
  * as perguntas a serem respondidas no projeto

* As apresentações ocorrerão em 19/04/2021




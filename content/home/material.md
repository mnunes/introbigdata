+++
# A Projects section created with the Portfolio widget.
widget = "portfolio"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Material"
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

O material do curso, como slides, conjuntos de dados e exemplos de códigos, está disponível no [github](https://github.com/mnunes/introbigdata_material). Lá também está a lista de pacotes do `R` a serem instalados em sua máquina para que o curso possa ser acompanhado. [Clique aqui](https://github.com/mnunes/introbigdata_material) para ver um tutorial sobre como automatizar o download de todo o conteúdo da disciplina para o seu computador.

A lista completa com as aulas assíncronas se encontra em uma [playlist no YouTube](https://www.youtube.com/playlist?list=PLr1K6DyuZsE7e36K7ljToOTpMH1bKyFtJ). Não é esperado que os alunos tenham assistido aos vídeos antes das aulas presenciais, mas essa é uma tarefa encorajada.

* Semana 01 - Introdução
  * O que é Big Data? ([vídeo](https://youtu.be/_WPwzO5nt0c)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/00_Introducao/00a_O_Que_E_Big_Data.pdf))
  * Exemplos de Aplicações com Big Data ([vídeo](https://youtu.be/4DG8Y_nxd5U)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/00_Introducao/00b_Exemplos.pdf))
* Semana 02 - Obtenção de Dados
  * Obtenção de Dados ([vídeo](https://youtu.be/NXkixK-S80E)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/01_Obtencao_de_Dados/01a_Obtencao_De_Dados.pdf))
  * Transformações nos Dados ([vídeo](https://youtu.be/0oGPYj06Ukk)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/01_Obtencao_de_Dados/01b_Transformacoes_Nos_Dados.pdf))
* Semana 03 - Análise de Componentes Principais ([vídeo](https://youtu.be/QZf0uoG97QA)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/02_Analise_de_Componentes_Principais/02_Analise_De_Componentes_Principais.pdf))
* Semana 04 - K-Means ([vídeo](https://youtu.be/eqQFAhUS_es)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/03_K-Means/03_k-means.pdf))
* Semana 05 - Clusterização Hierárquica ([vídeo](https://youtu.be/D3XwLVsLDVE)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/04_Clusterizacao_Hierarquica/04_Clusterizacao_Hierarquica.pdf))
* Semana 06 - Avaliação I
* Semana 07 - Validação Cruzada
  * Validação Cruzada ([vídeo](https://youtu.be/JgqDtu3t9So)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/06_Validacao_Cruzada/06a_Validacao_Cruzada.pdf))
  * `tidymodels` ([vídeo](https://youtu.be/nAFssJLymek)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/06_Validacao_Cruzada/06b_Tidymodels.pdf))
* Semana 08 - K Vizinhos Mais Próximos ([vídeo](https://youtu.be/4AyVUPjjQqA)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/07_K_Vizinhos_Mais_Proximos/07_k_Vizinhos_Mais_Proximos.pdf))
* Semana 09 - Máquinas de Vetor Suporte ([vídeo](https://youtu.be/aQlXsaN7MmU)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/08_Maquinas_de_Vetor_Suporte/08_Maquinas_de_Vetor_Suporte.pdf))
* Semana 10 - Árvores de Classificação e Regressão ([vídeo](https://youtu.be/Vf5GvJ562Ns)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/09_Arvores_de_Classificacao_e_Regressao/09_CART.pdf))
* Semana 11 - Random Forest ([vídeo](https://youtu.be/eXfHh_CovHY)|[slides](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/10_Random_Forest/10_Random_Forest.pdf))
* Semana 12 - Avaliação II
* Semana 13 - Projeto Final ([instruções](https://raw.githubusercontent.com/mnunes/introbigdata_material/main/aulas/12_Projeto_III/Projeto_III.pdf)|dúvidas)
* Semana 14 - Projeto Final (dúvidas)
* Semana 15 - Projeto Final (dúvidas)
* Semana 16 - Projeto Final (apresentação)
* Semana 17 - Quarta prova

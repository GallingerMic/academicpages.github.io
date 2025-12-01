---
permalink: /
title: "Grupo de Investigación en Ecología y Microbiología de Suelos"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Acá podría decir quienes somos -  Ceci capaz podemos poner algo que cuente cómo arrancaste vos..........

Líneas de investigación
======
- Ecología microbiana del suelo  
- Impacto del fuego en microbiomas edáficos
- Aplicaciones de secuenciación (16S, ITS, metagenómica)
- Bioinformática y análisis de comunidades microbianas

### **Directora: Cecilia E. Mlewski**

<div style="display: flex; align-items: flex-start; gap: 20px; margin-top: 10px;">

<img src="{{ site.baseurl }}/images/Ceci-Mlewski.jpg">

<div>


**Cecilia E. Mlewski** Mi línea de trabajo aborda el estudio de las comunidades de microorganismos en ambientes extremos desde una perspectiva ecológica, genética y funcional, utilizando técnicas de secuenciación masiva de segunda generación, clonado/Sanger, marcación por hibridación in situ fluorescente y microscopía. Dentro de los ambientes extremos encontramos lagos de la Antártida, más precisamente del archipiélago James Ross, donde estudiamos la diversidad microbiológica de matas microbianas asociadas a estos lagos, su dinámica y la importancia de ciertos grupos como posibles proxies relacionados al cambio climático. La Laguna Negra y Terma los Hornos, en la Puna Catamarqueña, desde una perspectiva geomicrobiológica, intentamos comprender la relación microorganismo-mineral y la señal que estos microorganismos pueden dejar en las rocas como una ventana hacia el pasado y con una mirada astrobiológica. Con cepas de cianobacterias aisladas de la Puna estamos avanzando en el estudio de la resistencia y la remoción del arsénico. Y por último, recientemente hemos comenzado un estudio del efecto del fuego en las comunidades edáficas del bosque Serrano, su dinámica y la detección de posibles microorganismos pirófilos. 

</div>
</div>

---
Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

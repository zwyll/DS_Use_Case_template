# Examples for running machine learning models on DesignSafe Jupyterhub

**Wenyang Zhang, Texas Advanced Computer Center (TACC), University of Texas, Austin**  

This documentation will explain how to easily perform machine learning (ML) analysis using Jupyterhub, which has been installed on DesignSafe web portal (https://www.designsafe-ci.org). Three ML examples with supplementary Python codes are provided: Random Forest (RF), XGBoosting and Artificial Neural Network (ANN).

## Background 

### Citation and Licensing

* Please cite [Durante and Rathje (2021)](https://doi.org/10.1177/87552930211004613) to acknowledge the use of any resources from this use case.

* Please cite [Rathje et al. (2017)](https://doi.org/10.1061/(ASCE)NH.1527-6996.0000246) to acknowledge the use of DesignSafe resources.  

* This software is distributed under the GNU General Public License (https://www.gnu.org/licenses/gpl-3.0.html).  

### Description 

This project uses machine learning algorithms to predict liquefaction induced lateral spreading displacement. This study is trained using data from the 2011 Christchurch earthquake in the Avon River area. The trained models can be used in the range of applicability reported in the ReadMe file. The Jupyter Notebook example files can be adapted to train any dataset. All the information are contained in the ReadMe file.

[Published project - PRJ-2998](https://www.designsafe-ci.org/data/browser/public/designsafe.storage.published/PRJ-2998v2)

## Header 2

Euismod nisi porta lorem mollis aliquam ut. Tincidunt ornare massa eget egestas purus viverra accumsan in. Varius quam quisque id diam vel. Fermentum odio eu feugiat pretium nibh ipsum consequat nisl. Placerat duis ultricies lacus sed turpis tincidunt id aliquet risus. Condimentum vitae sapien pellentesque habitant morbi tristique senectus et netus. Egestas sed sed risus pretium quam vulputate. Posuere morbi leo urna molestie at elementum. Eget magna fermentum iaculis eu non diam. Nisl tincidunt eget nullam non nisi. Sit amet risus nullam eget felis eget nunc lobortis mattis.

### Header2 Subheading

In aliquam sem fringilla ut morbi. Interdum varius sit amet mattis vulputate enim nulla aliquet. Sit amet mattis vulputate enim nulla.  In egestas erat imperdiet sed euismod nisi porta lorem. Eget nulla facilisi etiam dignissim diam.  Facilisi cras fermentum odio eu feugiat. Velit aliquet sagittis id consectetur. Vel quam elementum pulvinar etiam.  Ut diam quam nulla porttitor massa id neque aliquam. Sodales ut etiam sit amet nisl.  Scelerisque varius morbi enim nunc faucibus a. Sit amet volutpat consequat mauris nunc. Et leo duis ut diam.

*Add images to the folder img and use relative path to specify the location of the image.*   

![caption](img/mkdocs-template.png)
> Use case template design


## Header3

Morbi tristique senectus et netus et. Tristique senectus et netus et malesuada fames.  Eu mi bibendum neque egestas congue quisque. Id consectetur purus ut faucibus pulvinar elementum integer enim. Nunc consequat interdum varius sit amet mattis vulputate enim nulla.  Porta nibh venenatis cras sed felis eget. Dui id ornare arcu odio ut sem nulla pharetra diam. Pellentesque habitant morbi tristique senectus et netus et. Commodo nulla facilisi nullam vehicula ipsum a arcu. Nisi porta lorem mollis aliquam ut porttitor leo.

Numbered list 

1. [numbered linked item](https://maps.google.com)
2. second item
3. third item

### Header3 subheading

Ac feugiat sed lectus vestibulum mattis ullamcorper. Et egestas quis ipsum suspendisse ultrices gravida dictum fusce ut. Scelerisque eu ultrices vitae auctor eu augue ut lectus arcu.  Imperdiet proin fermentum leo vel orci porta non pulvinar. Dictumst quisque sagittis purus sit amet. Aliquam purus sit amet luctus. Aliquet bibendum enim facilisis gravida neque convallis a cras. Orci porta non pulvinar neque laoreet suspendisse. Urna neque viverra justo nec ultrices dui.

**Example Table**

| Column 1 | Column 2 | Column 3 |
|----------|----------|----------|
| Stampede2| CPU      | 2017     |     
| Frontera | CPU & GPU| 2019     |     

Or use markdown table generator: [https://www.tablesgenerator.com/markdown_tables](https://www.tablesgenerator.com/markdown_tables)


### Math

To generate math equations in markdown.

For inline mode formulas: $`a^2+b^2=c^2`$.

For display mode formulas which appear on a separate line
```math
f(x) = \int_{-\infty}^\infty
\hat f(\xi)\,e^{2 \pi i \xi x}
\,d\xi
```

### Code

``` python
import tensorflow as tf
```

Highlight specific lines of the code

``` python hl_lines="3 4"
""" Bubble sort """
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

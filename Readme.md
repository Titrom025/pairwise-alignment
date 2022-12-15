# Assignment 6

Sequence:  
`MVEYFGQNLNGFLFTKNAWVQSYGTRCVKPPIVWGDVSRANPITVEWSAYAQSKTDHVMKGMLTGPVTILNWSWPREDITHEEQTKQLALAIRDEVLDLE`

Prediction tools: OpenFold, OmegaFold  
Pair alignment tool: [PDBeFold](https://www.ebi.ac.uk/msd-srv/ssm/)  

Predictions:  
`openfold.pdb` - OpenFold (Notebook - `OpenFold.ipynb`)  
`omegaFold.pdb` - OmegaFold (Notebook - `Omegafold.ipynb`)  

Files for PDBeFold analysis: `pairs.txt` and `tarball.tar`

PDBeFold results:
![image](PDBeFold.png)

Visualization using VMD:
![gif](results.gif)


Выводы:
При загрузке структур в VMD предварительно было проведено их выравнивание в пространстве (изначально структуры были повернуты под разными углами). Возможно, это следствие не сильно высоких метрик. Также при сравнении двух структур заметны отличия, но, в целом, структуры похожи между собой.
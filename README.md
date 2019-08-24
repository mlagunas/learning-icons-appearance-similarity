# learning-icons-appearance-similarity
Sample code that select similar icons using the method from the paper Learning Icons Appearance Similarity.

#### Project structure

- **./small_dataset** folder containing a small subset downloaded from _the noun project_.
- **model_icons.pth** stores the weights of the model.
- **model_icons.py** contains the description of the model.
- **plot_similar.py** plots similar icons to a given reference.

#### How to run

First make sure that you have installed the following packages for python:

```
torch
torchvision
matplotlib
tqdm
```

Then, in order to find similar icons in the sample dataset run:
```
python3 plot_similar.py
```

_Note that we have tested the code using Python 3.6_
#### Useful information

If you found this code useful please cite our work:
```
@Article{Lagunas2018,
  author="Lagunas, Manuel and Garces, Elena and Gutierrez, Diego",
  title="Learning icons appearance similarity",
  journal="Multimedia Tools and Applications",
  year="2018",
  month="Sep",
  issn="1573-7721",
  doi="10.1007/s11042-018-6628-7",
}
```

For more information and related work visit [my personal website](http://giga.cps.unizar.es/~mlagunas).

If you have further questions feel free to open an issue or send an email to `mlagunas at unizar dot es`.
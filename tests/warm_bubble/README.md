This is one of the benchmark cases. Here we use DG1-P2 method introduced in the paper
[Two-Dimensional Evaluation of ATHAM-Fluidity, a Nonhydrostatic Atmospheric Model Using Mixed Continuous/Discontinuous Finite Elements and Anisotropic Grid Optimization. Savre et al. 2016](https://journals.ametsoc.org/view/journals/mwre/144/11/mwr-d-15-0398.1.xml)

### see options
```$ cd FLUIDITY_PATH```

```$ diamond -s ./schemas/fluidity_options.rng ./tests/warm_bubble/warm_bubble.flml &```

### run the case
```cd FLUIDITY_PATH/tests/warm_bubble```
```/home/baichuan/fluidity-main/bin/fluidity -v3 -l warm_bubble.flml```

-v? (where ? is either 1, 2 or 3) is a verbose option with 3 different levels (from the least to the most verbose), and -l generates log and error files (one per processor). 

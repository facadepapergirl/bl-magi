# bl-magi


### To activate this environment, use:
``` 
$ source activate bl-magi 
```
### To deactivate this environment, use:
``` 
$ source deactivate bl-magi
```

### Conda setting:
``` 
$ conda env create -f conda/environment_{machine}.yml
```

### Add Libraries to PYTHONPATH
``` 
# on the top directory
$ export PYTHONPATH=$PYTHONPATH:`pwd`:`pwd`/tensorflow/slim
``` 

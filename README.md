# dvc-import-bug
Reproducing a bug with dvc import


In DVC 1.x `dvc pull` will import `data/import/owl_sticker.png`. 

In DVC >2 it does not happen - likely due to gitignore issues.


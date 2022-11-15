Incremental progess was made by training models based off weights of the models that came before.

The folder yolo5m6 has each model that was trained, and the best model is the highest version number in the folder.

IMPORTANT: Git LFS is used to store the model.pt file. If you want to download the model, you will need to use git lfs pull.
The reason for using git lfs is because one of the failed training runs was too large to be stored on github, and I never undid the git lfs tracking.
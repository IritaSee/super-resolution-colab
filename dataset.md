It is obvious I should not upload a whole dataset here, so I need your help to download them
you can download them (and extract them) manually here
https://drive.google.com/drive/folders/1ZVQpum8PZO1abO3VCL6eJE6zHrWfqtkw?usp=drive_link

or, there is a command in the python notebook file, please be sure they are extracted here, in this folder (new_dataset)

or, you can (with colab) connect to your google drive, delete this folder, and create symlink, like this

```py
import os
os.symlink('/content/drive/MyDrive/super-resolution-master/new_dataset','./new_dataset',target_is_directory=True)
```
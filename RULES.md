Here you can find a few instructions to include a dataset of your choosing in this repository. This is to prevent any major conflicts in the future and to make the process as easy and smooth as possible.

## Instructions

1. Fork our repository into your own github account.
2. Clone your forked version into your local machine (optional). you can also work online on your own repository.
3. Add the original repository as the upstream repository by entering the following command in the terminal on your local machine:

```git
git remote add upstream https://github.com/hooshvare/parsi-hub
git fetch upstream
git rebase upstream/master
```

4. Make a branch with the name of your own dataset (e.g. my_dataset) and switch to it. **Please DO NOT use any spaces or special characters like _!@#$%^&(){}[]_ in the names you choose. To separate words please use underscore (_):**

```git
git checkout -b YOUR_DATASET_NAME
```

5. Under the *dataset* directory go to the appropriate directry based on the characteristics of your dataset (e.g. if your dataset is a text-based dataset, go to *text* directory under *dataset*).
6. Make a new directory with the exact same name as your branch and your dataset (e.g. my_dataset).
7. Based on the type of the data in your dataset (i.e. text, video, image, audio), go to the template directory in the root directory and copy the appropriate the template into your dataset directory.
8. Fill out the template, providing all the necessary information of all sections based on the characteristics of your dataset.
9. Follow the below commands to add and commit your changes.

```git
git add dataset/DATA_SECTION/YOUR_DATASET_NAME
git commit -m "message"
git fetch upstream
git rebase upstream/master
```

10. If working on a local machine, push your branch and all your changes into your online forked repository on github.

```git
git push -u origin YOUR_DATASET_NAME
```

11. Make a pull request from your github dataset branch into our master branch.
12. After careful examination of the information you have provided, we will merge your changes into our own master branch. Please make sure to watch this repository and the issues as we might request some changes before we merge the pull request.
13. If we write a review and request a change to the information you have provided, please make the necessary changes and follow the below commands to merge your changes back into the pull request. **You DO NOT need to make a new pull request in this case.**

```git
git add dataset/DATA_SECTION/YOUR_DATASET_NAME
git commit -m "message"
git fetch upstream
git merge upstream/master
git push -u origin YOUR_DATASET_NAME
```

14. Step 13 might be repeated a few times.

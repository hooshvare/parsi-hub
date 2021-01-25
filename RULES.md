Here you can find a few instructions to include a dataset of your choosing in this repository. This is to prevent any major conflicts in the future and to make the process as easy and smooth as possible.

## Instructions

1. Fork our repository into your own github account.
2. Clone your forked version into your local machine (optional). you can also work online on your own repository.
3. Make a branch with the name of your own dataset (e.g. my_dataset). **Please DO NOT use any spaces or special characters like _!@#$%^&(){}[]_ in the names you choose. To separate words please use underscore (_).**
4. Switch to the newly created branched.
5. Under the *dataset* directory go to the appropriate directry based on the characteristics of your dataset.
6. Make a new directory with the exact same name as your branch and your dataset (e.g. my_dataset).
7. Based on the type of the data in your dataset (i.e. text, video, image, audio), go to the template directory in the root directory and copy the appropriate the template into your dataset directory.
8. Fill out the template, providing all the necessary information of all sections based on the characteristics of your dataset.
9. Add and commit. To prevent git conflicts due to the works of other people while you are working on your own branch, you should use the following commands before pushing and sending a pull request:

```git
git fetch upstream
git rebase upstream/master
```
10. If working on a local machine, push your branch and all your changes into your online forked repository on github.
11. Make a pull request from your online dataset branch into our master branch.
12. After careful examination of the information you have provided, we will merge your changes into our own master branch. Please make sure to watch this repository and the issues as we might request some changes before we merge the pull request.

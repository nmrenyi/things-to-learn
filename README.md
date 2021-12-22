# things-to-learn

things I wanna learn in spare time

## Personal Website
HUAWEI cloud or other student cloud services?

## Google Developer Documentation Style
When I'm wondering is there any convention for dir and file naming, I found this https://developers.google.com/style/filenames .
I really love Google docs. They're always professional and clearly explained.

## Missing Semester
MIT missing semester https://missing.csail.mit.edu/ . There's a lot of pratical things to learn.

## Tensorflow 2
In fact I'm always willing to try out new things. TF is not so prevalent among researchers. But I still wanna give it a try, especially TensorFlow 2
https://www.tensorflow.org/

## Reorganize All Configuration Files
ssh config, gitconfig, overwall config, zsh config, anaconda config...
sync zsh config https://superuser.com/questions/152574/keeping-my-zsh-or-bash-profile-synced-up-on-all-my-machines

## Config All Servers in THUIR
config zsh, plugins, git, ssh, font, etc.

## Docker
docker is a highly useful tool for software with environment. Tensorflow 2.x already supports docker.
https://www.docker.com/

## Learn Different Recommendation Frameworks
ReChorus https://github.com/THUwangcy/ReChorus/

HappyRec

RecBole https://github.com/RUCAIBox/RecBole

Try to analyze the highlights as well as drawbacks and then construct your own framework!

## Writing on GitHUb and Typora
professional writing on GitHub and Typora

https://docs.github.com/en/github/writing-on-github

## ReChorus
### Highlights
#### About Recommendation
(shown in ReChorus `README.md` and paper)

#### About Code
1. Nice progress bar and intermediate display.

### Drawbacks
#### About Recommendation

#### About Code
1. Compatibility problems due to old Pytorch version
2. Lack of options for only running on CPU despite of GPU availability. Some GPU (like NVIDIA MX150) do not support some operations in ReChorus, leading to runtime error.
3. Confusion of object reference. Class `Dataset` contains a reference to the model, which sounds weird.
4. Rude GPU configuration. Setting `torch.device('cuda:X')` seems more subtle than setting OS environment variables, where `X` denotes the target GPU id.
5. Poor keyboard interruption support. Sometimes the training procedure cannot capture Ctrl+C signal for early stopping, causing the whole process to stop directly.

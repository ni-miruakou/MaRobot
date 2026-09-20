# 工作日志

> ```Shell
>
> git submodule add https://github.com/huggingface/lerobot thirdparty/lerobot_hugging
> git submodule sync --recursive
> git submodule update --init --recursive
>
> cd thirdparty/lerobot_hugging
> git fetch --tags origin
> git tag -l '*0.4.3*'
> git checkout v0.4.3
> cd ../..
> ```

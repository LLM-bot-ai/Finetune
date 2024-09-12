


# 安装所需库
```shell
pip install flash-attn --no-build-isolation
pip install datasets
pip install peft
```shell

# 登录Hugging Face
```shell
huggingface-cli login
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
```shell

# 运行实验
```shell
python experiments/run_prediction.py train_configs/simcse/MetaLlama3.json
```shell

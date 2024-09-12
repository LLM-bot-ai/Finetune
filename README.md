




# Install packages

```
pip install flash-attn --no-build-isolation
pip install datasets
pip install peft
```

# Loggin to Hugging Face

```
huggingface-cli login
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
```

# Train

```
python experiments/run_prediction.py train_configs/simcse/MetaLlama3.json

```

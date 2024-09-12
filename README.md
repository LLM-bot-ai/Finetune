




# Install packages

```
pip install flash-attn --no-build-isolation
pip install datasets
pip install peft
```

# Logging to Hugging Face

```
huggingface-cli login
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
```

# Train

data file is in 'experiments/tfns.parquet'

```
python experiments/run_prediction.py train_configs/simcse/MetaLlama3.json

```

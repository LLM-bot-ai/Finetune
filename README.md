




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

Data file is in 'experiments/tfns.parquet'. Dataset has two columns, 'text' and 'return', separately.

```
python experiments/run_prediction.py train_configs/simcse/MetaLlama3.json

```

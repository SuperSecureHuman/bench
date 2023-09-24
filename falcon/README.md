# Falcon 7B testing

This is the model with FP16 training, no LORA and stuff

```python
python falcon_stock.py --batch_size_per_device 16
```

Model with lora

```python
python falcon_lora.py --batch_size_per_device 16 --quantize_mode 4bit # 4bit, 8bit, 16bit
```


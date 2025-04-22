### GRPO

## 使用8卡A800内存80G并行对Qwen2.5-7B在非结构化【医学推理】数据集（50000条）上进行GRPO训练
自定义奖励函数：准确性、推理深度、语言清晰度、格式奖励

{"_runtime":28304.121412316,"loss":0.003861287608742714,"iteration":1,"step":500,"grpo_iter":1,"_timestamp":1.7425710752104497e+09,"_step":499,"average_reward":1.7871406078338623,"_wandb":{"runtime":28304}}
- average-reward
![W B Chart 2025_3_26 14_10_58](https://github.com/user-attachments/assets/bb4ad68f-b76d-4502-9363-84de841009c6)

- loss
![W B Chart 2025_3_26 14_10_26](https://github.com/user-attachments/assets/0d3829f7-988b-4135-917d-c1a1188e06ac)


## 使用8卡A800内存80G对Qwen2.5系列在gsm8k数据集上进行GRPO训练

<br>

## Qwen2-5-3B-instruct

- pre_accuracy: 66.7%
- post_grpo_accuracy: 90%
- average-reward
![W B Chart 2025_3_13 09_08_23](https://github.com/user-attachments/assets/98cc0af1-2534-4903-bfb9-d74686d15f28)
- loss
![W B Chart 2025_3_13 09_07_57](https://github.com/user-attachments/assets/e7147727-ca28-4410-9924-f7a645d50f35)


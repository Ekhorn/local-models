# Metrics

## Prompt

```text
Explain recursion.
```

## Average metrics

| Model | Reasoning effort | Runs | Prompt tokens | Generated tokens | Thinking tokens | Prefill (t/s) | Decode (t/s) | Est. inference (s) |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| deepseek-v4-flash-q2xxs-0731 | no thinking | 13 | 3075.6 | 673.9 | 0.0 | 397.16 | 19.58 | 42.172 |
| deepseek-v4-flash-q2xxs-0731 | low | 14 | 3063.3 | 707.3 | 84.0 | 410.23 | 19.59 | 43.574 |
| deepseek-v4-flash-q2xxs-0731 | high | 11 | 3186.0 | 766.6 | 239.1 | 443.30 | 19.60 | 46.321 |
| deepseek-v4-flash-q2xxs-0731 | max | 14 | 3155.3 | 687.2 | 128.3 | 441.45 | 19.56 | 42.279 |
| deepseek-v4.1-flash-1017-gsq-rco-coder-q2xxs | no thinking | 14 | 3076.3 | 572.1 | 0.0 | 1291.18 | 24.02 | 26.194 |
| deepseek-v4.1-flash-1017-gsq-rco-coder-q2xxs | low | 14 | 3101.3 | 709.4 | 133.1 | 1271.43 | 24.15 | 31.820 |
| deepseek-v4.1-flash-1017-gsq-rco-coder-q2xxs | high | 11 | 3145.0 | 767.3 | 191.8 | 1302.49 | 23.97 | 34.423 |
| deepseek-v4.1-flash-1017-gsq-rco-coder-q2xxs | max | 14 | 3101.3 | 943.4 | 359.9 | 1302.20 | 24.07 | 41.578 |
| lfm3 | not supplied | 29 | 3147.2 | 540.2 | 43.1 | 5882.84 | 105.96 | 5.634 |
| qwen3.8-27b-q4_k_xl | no thinking | 15 | 3037.4 | 358.4 | 0.0 | 544.49 | 34.29 | 16.499 |
| qwen3.8-27b-q4_k_xl | low | 15 | 3061.4 | 850.9 | 275.2 | 560.20 | 33.35 | 31.217 |
| qwen3.8-27b-q4_k_xl | medium | 10 | 3052.0 | 834.0 | 243.1 | 557.24 | 32.75 | 30.733 |
| qwen3.8-27b-q4_k_xl | xhigh | 14 | 3072.2 | 1057.4 | 510.6 | 557.74 | 32.59 | 37.720 |
| qwen3.8-flash-next-q4_k_xl | no thinking | 14 | 3034.2 | 324.1 | 0.0 | 1876.09 | 53.08 | 7.641 |
| qwen3.8-flash-next-q4_k_xl | low | 14 | 3058.2 | 517.9 | 44.3 | 1806.88 | 53.78 | 11.397 |
| qwen3.8-flash-next-q4_k_xl | medium | 10 | 3050.0 | 606.3 | 54.6 | 1829.01 | 52.58 | 13.216 |
| qwen3.8-flash-next-q4_k_xl | xhigh | 14 | 3070.2 | 599.2 | 116.1 | 1863.66 | 52.63 | 13.192 |

Values are arithmetic means across runs. `not supplied` does not necessarily mean thinking was disabled.

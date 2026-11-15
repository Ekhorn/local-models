# Metrics

## Prompt

```text
Explain recursion.
```

## Average metrics

| Model | Reasoning effort | Runs | Prompt tokens | Generated tokens | Thinking tokens | Prefill (t/s) | Decode (t/s) | Est. inference (s) |
| --- | --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| deepseek-v4-flash-q2xxs-0731 | no thinking | 2 | 2903.0 | 731.0 | 0.0 | 387.37 | 19.60 | 44.796 |
| deepseek-v4-flash-q2xxs-0731 | low | 3 | 2903.0 | 722.3 | 84.0 | 401.06 | 19.61 | 44.075 |
| deepseek-v4-flash-q2xxs-0731 | max | 3 | 2995.0 | 483.7 | 65.0 | 434.95 | 19.59 | 31.573 |
| deepseek-v4.1-flash-1017-gsq-rco-coder-q2xxs | no thinking | 3 | 2916.0 | 710.7 | 0.0 | 1285.30 | 24.05 | 31.824 |
| deepseek-v4.1-flash-1017-gsq-rco-coder-q2xxs | low | 3 | 2941.0 | 735.3 | 183.0 | 1228.14 | 24.18 | 32.812 |
| deepseek-v4.1-flash-1017-gsq-rco-coder-q2xxs | max | 3 | 2941.0 | 856.7 | 232.7 | 1299.19 | 24.12 | 37.777 |
| lfm3 | not supplied | 4 | 2976.0 | 469.5 | 0.0 | 5934.34 | 106.16 | 4.924 |
| qwen3.8-27b-q4_k_xl | no thinking | 3 | 2971.0 | 373.7 | 0.0 | 551.88 | 34.24 | 16.315 |
| qwen3.8-27b-q4_k_xl | low | 3 | 2995.0 | 848.0 | 232.3 | 547.27 | 32.52 | 31.643 |
| qwen3.8-27b-q4_k_xl | xhigh | 3 | 3007.0 | 986.3 | 532.0 | 556.22 | 31.30 | 36.408 |
| qwen3.8-flash-next-q4_k_xl | no thinking | 3 | 2969.0 | 113.3 | 0.0 | 1809.05 | 48.60 | 3.962 |
| qwen3.8-flash-next-q4_k_xl | low | 3 | 2993.0 | 660.7 | 54.7 | 1750.47 | 50.54 | 14.880 |
| qwen3.8-flash-next-q4_k_xl | xhigh | 3 | 3005.0 | 704.7 | 128.7 | 1838.07 | 48.63 | 16.121 |

Values are arithmetic means across runs. `not supplied` does not necessarily mean thinking was disabled.

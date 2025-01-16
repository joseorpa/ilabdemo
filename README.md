# ilabdemo
## Some useful commands (Intructlab v0.21 on Macbook M1)
```bash
ilab serve --model-path /Users/jortizpa/.cache/instructlab/models/instructlab-merlinite-7b-lab-trained/instructlab-merlinite-7b-lab-Q4_K_M.gguf
ilab chat -m  ilab serve --model-path /Users/jortizpa/.cache/instructlab/models/instructlab-merlinite-7b-lab-trained/instructlab-merlinite-7b-lab-Q4_K_M.gguf
ilab data generate --model /Users/jortizpa/.cache/instructlab/models/merlinite-7b-lab-Q4_K_M.gguf --taxonomy-base=empty --pipeline simple
ilab train --data-path /Users/jortizpa/.local/share/instructlab/datasets --pipeline simple --model-path instructlab/merlinite-7b-lab
ilab model convert --model-dir /Users/jortizpa/.local/share/instructlab/checkpoints/instructlab-merlinite-7b-lab-mlx-q  --model-name instructlab-merlinite-7b-lab-gathering
ilab serve --model-path /Users/jortizpa/.cache/instructlab/models/instructlab-merlinite-7b-lab-trained/instructlab-merlinite-7b-lab-Q4_K_M.gguf
ilab chat -m /Users/jortizpa/.cache/instructlab/models/instructlab-merlinite-7b-lab-trained/instructlab-merlinite-7b-lab-Q4_K_M.gguf
```


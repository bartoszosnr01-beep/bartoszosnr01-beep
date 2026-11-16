### Bartosz Bajda — AI & GPU Infrastructure Developer

Independent AI developer building reproducible inference pipelines, workflow tooling, and desktop studio integrations around multimodal diffusion and vision-language models (`Qwen-Image-2.1`, `Qwen3-VL`, `ComfyUI`).

#### Featured Repository
* **[`qwen21-gpu-infra`](https://github.com/bartoszosnr01-beep/qwen21-gpu-infra)** — Multi-cloud `ComfyUI` infrastructure and **AMD Instinct™ MI300X (ROCm BF16 vs. INT8 ConvRot)** evaluation tooling with shared model manifests and automated live-preview workflows.

#### Current Focus
* Evaluating unquantized **BF16** multimodal diffusion + VLM encoders (`~32.4 GB` weights) on **AMD ROCm / MI300X** (`192 GB HBM3`)
* Benchmarking `comfy-kitchen` / Triton kernel compatibility and end-to-end latency on PyTorch ROCm
* Building unified deployment tooling across ROCm bare-metal and serverless GPU runtimes

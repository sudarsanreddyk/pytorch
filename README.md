uv add --index https://stable.repo.amd.com/rocm/whl-next/ \
    "torch[device-gfx1151]==2.13.0+rocm10.0.0" \
    "torchvision[device-gfx1151]==0.28.0+rocm10.0.0" \
    "torchaudio==2.11.0.2+rocm10.0.0"


HSA_OVERRIDE_GFX_VERSION="11.5.1"
TORCH_BLAS_PREFER_HIPBLASLT="1"
TORCH_ROCM_AOTRITON_ENABLE_EXPERIMENTAL="1"
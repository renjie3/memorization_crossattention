# Unveiling and Mitigating Memorization in Text-to-image Diffusion Models through Cross Attention

Official code for [Unveiling and Mitigating Memorization in Text-to-image Diffusion Models through Cross Attention](https://arxiv.org/abs/2403.11052)

Recent advancements in text-to-image diffusion models have demonstrated their remarkable capability to generate high-quality images from textual prompts. However, increasing research indicates that these models memorize and replicate images from their training data, raising tremendous concerns about potential copyright infringement and privacy risks. In our study, we provide a novel perspective to understand this memorization phenomenon by examining its relationship with cross-attention mechanisms. We reveal that during memorization, the cross-attention tends to focus disproportionately on the embeddings of specific tokens. The diffusion model is overfitted to these token embeddings, memorizing corresponding training images. To elucidate this phenomenon, we further identify and discuss various intrinsic findings of cross-attention that contribute to memorization. Building on these insights, we introduce an innovative approach to detect and mitigate memorization in diffusion models. The advantage of our proposed method is that it will not compromise the speed of either the training or the inference processes in these models while preserving the quality of generated images.

## Necessary dependencies

diffusers, pytorch, transformers

## How to use

Detailed CMD of generation and detection can be found in **local_cmd.sh**

## Cite
```
@article{ren2024unveiling,
  title={Unveiling and Mitigating Memorization in Text-to-image Diffusion Models through Cross Attention},
  author={Ren, Jie and Li, Yaxin and Zen, Shenglai and Xu, Han and Lyu, Lingjuan and Xing, Yue and Tang, Jiliang},
  journal={arXiv preprint arXiv:2403.11052},
  year={2024}
}
```

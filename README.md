# MiniMax H3 多图参考视频实验（H3 Video Experiment）

> 2026-08-19 在 AutoDL（RTX 4080，¥1.77/时）+ ComfyUI 上用 **MiniMax H3（Ref2VA）** 跑"多图参考生成视频"，并与以往路线横向比对，决定以后各方法该在什么场景用。
>
> 产出：单图参考 `r2v_test_00001.mp4` + 双图参考 `r2v_multi_2img.mp4`。

## 文档

| 文档 | 内容 |
|---|---|
| [H3与之前方法比对.md](H3与之前方法比对.md) | 横评：H3 Ref2VA vs LTX-2.3 I2V vs Vidu API（平台/画质/成本/适用场景） |
| [H3多图参考生成视频-操作记录.md](H3多图参考生成视频-操作记录.md) | 实操记录：autodl-cli 租卡 + ComfyUI 原生 API 跑通流程、坑 |

## output/ 资产

参考图（角色 LoRA 素材）、抽帧预览、两段成片 mp4。素材源于本机 `comfyui/images/all_images/` 的旧角色参考图。

## 说明

私有归档实验仓（含生成素材与成片）。如需公开请先过素材版权与人物肖像确认。

# Tweeter Waveguide Designer - 车载高音波导生成器

## 项目简介 (Project Introduction)
这是一个基于声学物理模型开发的辅助设计工具，旨在为车载高音单元生成专属的声波导（Waveguide/Horn）面板。
本软件利用多模态AI大模型辅助编程，帮助用户通过 3D 打印技术，实现对高音单元指向性（Directivity）和声阻抗（Acoustic Impedance）的物理控制。

This tool generates acoustic waveguide profiles for car audio tweeters to optimize directivity and minimize room reflections.

## 开发背景与声学发现 (Background & Acoustic Insights)
在复杂的车内声学环境中，高音单元的安装位置至关重要。
我们在开发过程中对比了传统的 **“A柱8字倒模” (Figure-8 Molding)** 与 **“波导面板” (Waveguide)** 的实测数据，发现了以下显著差异：

1.  **传统倒模的物理局限**：
    *   当高音单元紧贴挡风玻璃安装（常见于8字倒模）时，3kHz-6kHz 频段极易因反射声与直达声的相位干涉，产生 **梳状滤波 (Comb Filtering)**，导致中高频听感不实。
    *   10kHz 以上频段容易受到挡风玻璃的 **号角效应 (Horn Loading)** 影响，产生非线性的能量增益。

2.  **波导技术的优势**：
    *   本软件设计的波导面板，能够主动控制高频声波的辐射角度。
    *   通过收窄指向性，减少射向玻璃的能量，从而在源头上减轻反射干扰，获得更平滑的频响和更精准的相位。

## 核心功能 (Key Features)
*   **参数化建模**：输入高音单元振膜尺寸，自动生成优化的波导曲率（Profile）。
*   **声学优化**：改善分频点附近的声阻抗匹配，提升中低端灵敏度。
*   **3D打印就绪**：生成的模型导出后可直接用于 SLA/FDM 3D 打印，适配A柱或高音杯安装。

## 适用人群
*   汽车音响发烧友 (Car Audio Enthusiasts)
*   专业改装技师 (Professional Installers)
*   声学DIY爱好者 (Acoustic DIYers)

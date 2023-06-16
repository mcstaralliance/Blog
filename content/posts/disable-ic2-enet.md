+++
date        = "2023-6-16T20:40:27+08:00"
title       = "关闭工业时代电压系统"

+++

在 `.minecraft/config/ICI2.ini` 内，在约 292 行找到 `enableEnetExplosions` ，将其设置为 false 即可关闭过载爆炸。

将 `enableEnetCableMeltdown` 设置为 false 可关闭电流过大导致的导线消失。
# STM32F446RET6-tutorial

STM32F446RET6の周辺回路のみの回路図です。

# Note

`/lbr` ::使用している外部ライブラリです。　秋月の表面実装タクトスイッチ、水晶発振子と、STM32F446RET6のライブラリを使用しています。

`stm32f446RET6-tutorial.ioc` ::Serial-wireをデバッグに、クロックソースにHSEの水晶発振子にしただけのCubeMXプロジェクトです。
このプロジェクトを使うと、STLinkで書き込んで、水晶発振子での動作、デバッグの確認をすることができます。

# Requirement

* STM32 CubeMX

* STM32 CubeIDE

# Author

* Shun Kayaki

    Kyushu institute of Technology
    
    shun@guetan.dev

# License

Copyright (c) 2020 Shun Kayaki
Released under the MIT license

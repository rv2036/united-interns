# 2026 年 05 月进展 - 实习生

实习生进展月度汇总

## smullllu

### Mentor: weilinfox

### 本月工作总结

本月主要围绕 ruyi-pytest 项目进行工作，为 RuyiSDK 的自动化测试框架新增了 config、self、device、uninstall 四个模块的测试用例，覆盖了配置管理、自检、设备管理与卸载等核心功能路径，并集成了 pytest-html 以实现测试报告的可视化输出。同时继续跟进上月提交的 5 个 Armbian RISC-V 板卡（musepipro、orangepirv2、visionfive2）packages-index manifest PR，根据 review 反馈进行了修改与迭代。

### 本月的交付产物

- [#5 tests: add config test cases](https://github.com/ruyisdk-test/ruyi-pytest/pull/5)
- [#6 tests: add self test cases](https://github.com/ruyisdk-test/ruyi-pytest/pull/6)
- [#7 tests: add device test cases](https://github.com/ruyisdk-test/ruyi-pytest/pull/7)
- [#8 tests: add uninstall test cases and pytest-html](https://github.com/ruyisdk-test/ruyi-pytest/pull/8)

### 其他交付物

修改了以下 pr

- [#190 board-image/armbian-spacemit-musepipro: add new packages](https://github.com/ruyisdk/packages-index/pull/190)
- [#184 board-image/armbian-orangepi-rv2-xfce:add new packages](https://github.com/ruyisdk/packages-index/pull/184)
- [#185 board-image/armbian-orangepi-rv2-minimal:add new packages](https://github.com/ruyisdk/packages-index/pull/185)
- [#188 board-image/armbian-starfive-visionfive2-xfce:add new packages](https://github.com/ruyisdk/packages-index/pull/188)
- [#189 board-image/armbian-starfive-visionfive2-minimal:add new packages](https://github.com/ruyisdk/packages-index/pull/189)
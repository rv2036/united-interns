# 2026 年 06 月进展 - 实习生

实习生进展月度汇总

## smullllu

### Mentor: weilinfox

### 本月工作总结

本月继续围绕 ruyi-pytest 项目推进测试覆盖，新增了 repo（软件源管理）、update（系统更新）、telemetry（遥测）三个模块的测试用例，并对 pytest-html 可视化测试报告进行了独立优化与增强。同时持续跟进上月提交的 config、self、device、uninstall 测试 PR 以及 5 个 Armbian RISC-V 板卡（musepipro、orangepirv2、visionfive2）packages-index manifest PR 的 review 迭代。在 riko-bot 方面，修复了 armbian-musepipro 的 metadata 描述问题，并将三个板卡的 image-combo 拆分为 minimal 与 xfce 两种变体，与 packages-index 的 manifest 结构保持一致。此外，向 ruyi 上游提交了 issue #480，反馈 `ruyi repo add ruyisdk` 在非 Rich 终端下报错信息缺失关键词 "repo" 的问题。

### 本月提交的PR

pr:

- [#10 tests: add repo test cases](https://github.com/ruyisdk-test/ruyi-pytest/pull/10)
- [#11 tests: add update test cases](https://github.com/ruyisdk-test/ruyi-pytest/pull/11)

### 本月合并的PR

pr:

- [#5 tests: add config test cases](https://github.com/ruyisdk-test/ruyi-pytest/pull/5)
- [#7 tests: add device test cases](https://github.com/ruyisdk-test/ruyi-pytest/pull/7)
- [#8 tests: add uninstall test cases](https://github.com/ruyisdk-test/ruyi-pytest/pull/8)
- [#9 tests: add pytest-html for visual test reports](https://github.com/ruyisdk-test/ruyi-pytest/pull/9)
- [#12 tests: add telemetry test cases](https://github.com/ruyisdk-test/ruyi-pytest/pull/12)

### 其他交付物

修改了以下 pr

- [#6 tests: add self test cases](https://github.com/ruyisdk-test/ruyi-pytest/pull/6)
- [#190 board-image/armbian-spacemit-musepipro: add new packages](https://github.com/ruyisdk/packages-index/pull/190)
- [#184 board-image/armbian-orangepi-rv2-xfce:add new packages](https://github.com/ruyisdk/packages-index/pull/184)
- [#185 board-image/armbian-orangepi-rv2-minimal:add new packages](https://github.com/ruyisdk/packages-index/pull/185)
- [#188 board-image/armbian-starfive-visionfive2-xfce:add new packages](https://github.com/ruyisdk/packages-index/pull/188)
- [#189 board-image/armbian-starfive-visionfive2-minimal:add new packages](https://github.com/ruyisdk/packages-index/pull/189)

修改了以下 commits:

- [b517ab5 ruyi_packages: update the metadata desc for armbian-musepipro](https://github.com/ruyisdk-test/riko-bot/commit/b517ab51a569f2525ac79ad04bf2ab9ec27f59fa)
- [a8ebb79 ruyi_packages: split armbian-musepipro image-combo into minimal and xfce variants](https://github.com/ruyisdk-test/riko-bot/commit/a8ebb792ce78777a5da8bf8d0b53506d863dd16e)
- [5e19925 ruyi_packages: split armbian-orangepirv2 image-combo into minimal and xfce variants](https://github.com/ruyisdk-test/riko-bot/commit/5e19925eac7d250dc15d747d31973f27224b30f7)
- [b9b4c4e ruyi_packages: split armbian-visionfive2 image-combo into minimal and xfce variants](https://github.com/ruyisdk-test/riko-bot/commit/b9b4c4e3a0f942e2002e7ed80db1eea9ac02a7c2)


修改了以下 issues:

- [#480 repo add ruyisdk 报错信息在非 Rich 终端下缺失关键词 repo](https://github.com/ruyisdk/ruyi/issues/480)
Wenchang Satellite Launch Center

A replica of the Wenchang Satellite Launch Center (Wenchang Spacecraft
Launch Site), Hainan, China, for Kerbal Space Program.

Original mod: IcecoveryStudio (KERWIS), model/textures/configs by ladeng
Original page: https://spacedock.info/mod/1091/Wenchang%20Satellite%20Launch%20Center
Community patch & bugfixes: Li Jingting

----------------------------------------
VERSION
----------------------------------------
- Fixed for KSP 1.12.x (tested on 1.12.5) + Kerbal Konstructs for KSP 1.12
  (KK 1.8.7 upstream series / 1.12.3 KSP-RO fork).

----------------------------------------
DEPENDENCIES
----------------------------------------
- Kerbal Konstructs (for KSP 1.12.x)

----------------------------------------
WHAT THIS PATCH CHANGES
----------------------------------------
1. Fixed a duplicate static name bug: both pads were named
   "wenchang_launch_2", which made Kerbal Konstructs spawn pad 102 with
   pad 101's model. They are now "wenchang_lc101" and "wenchang_lc102".

2. All preset placements (Instances) were removed. The models are no
   longer pre-placed anywhere: place them yourself with the KK editor
   (Ctrl+K). An optional real-coordinates placement is provided in the
   "Optional" folder.

3. Bundled fix plugin WenchangFix.dll (GameData/WenchangFix/):
   replaces KK's AnimateOnClick module for the animated doors/towers.
   Fixes the bug where a door animation freezes and becomes unclickable
   after an interruption (recovering a vessel, reverting to VAB/SPH,
   scene switches, KK range unloading). Keep the WenchangFix folder when
   installing or repacking this mod.

----------------------------------------
INSTALLATION
----------------------------------------
Copy the contents of "GameData" into your KSP "GameData" folder.

----------------------------------------
MANUAL PLACEMENT (KK editor, Ctrl+K)
----------------------------------------
1. Open the statics editor and select one of the models:
   - "Wenchang Satellite Launch Center 101" (wenchang_lc101, pad)
   - "Wenchang Satellite Launch Center 102" (wenchang_lc102, pad)
   - "Wenchang Satellite Launch Center"     (wenchang_launch, main complex)
2. Place them wherever you like. Real Wenchang reference:
   - LC-101 pad area: 19.6147 N / 110.9511 E
   - LC-201 pad area: 19.6190 N / 110.9490 E
3. For each pad, add a launch site (facility) on the instance:
   - spawn transform: first_spawn (pad 101) / second_spawn (pad 102)
   - launch site type: VAB, category: RocketPad
   (the spawn-transform defaults are preconfigured in the cfgs)

----------------------------------------
OPTIONAL: REAL WENCHANG PRESET (in the Optional folder)
----------------------------------------
The package ships an optional pre-made placement of the whole facility
at the real Wenchang site on Earth (for RSS / Sol / RSS Reborn):

  - Pad 101 (wenchang_lc101):  19.631579 N / 110.952606 E
  - Pad 102 (wenchang_lc102):  19.632114 N / 110.955794 E
  - Main complex:              19.631768 N / 110.952655 E

How to install the preset:
1. Make sure a Sol system mod (RSS or RSS Reborn) providing the body
   "Earth" is installed.
2. Copy the contents of "Optional/Wenchang_Real_Placement/GameData"
   into your KSP "GameData" folder, so the four .cfg files end up in
   GameData/KerbalKonstructs/NewInstances/.
3. Start KSP. The statics appear under the KK group "NewGroup_2".
4. Both launch pads default to CLOSED: open the KK map, click each pad
   to open it (opening cost: 0 funds) and it will show up in the VAB
   launch-site list.

To remove the preset later, simply delete those four files from
GameData/KerbalKonstructs/NewInstances/.

----------------------------------------
INTERACTIONS
----------------------------------------
- Click the launch tower to open/close it.
- Click the transport platform to open/close it.
- Click the ground to switch the lights on/off.

Note: It is recommended to wait for an animation to finish before triggering the next action (including reverting to the VAB after launch). If the animation freezes, click once or twice more to restore it.
----------------------------------------
LICENSE
----------------------------------------
CC BY-SA 4.0 (original mod and this patch).
See LICENSE.txt.

KERWIS Produced
Fixed by: Li Jingting

========================================
文昌卫星发射中心
========================================

坎巴拉太空计划（KSP）mod：中国海南文昌航天发射场复刻。

原 mod：IcecoveryStudio（KERWIS 工作室），模型/贴图/配置 ladeng
原发布页：https://spacedock.info/mod/1091/Wenchang%20Satellite%20Launch%20Center
社区补丁与修复：李敬亭（Li Jingting）

----------------------------------------
版本
----------------------------------------
- 适配 KSP 1.12.x（已在 1.12.5 上测试）+ KSP 1.12 版 Kerbal Konstructs
  （上游 1.8.7 系列 / KSP-RO 分支 1.12.3）。

----------------------------------------
依赖
----------------------------------------
- Kerbal Konstructs（KSP 1.12.x 对应版本）

----------------------------------------
本补丁改动
----------------------------------------
1. 修复静态模型重名 bug：两个发射台原同名 "wenchang_launch_2"，
   导致 KK 加载 102 台时错误套用 101 台的模型。
   现改为 "wenchang_lc101" 与 "wenchang_lc102"。

2. 移除全部预置摆放（Instances）：模型不再自动出现在地图上，
   需用 KK 编辑器（Ctrl+K）手动摆放。
   如需真实坐标预置，见包内 "Optional" 文件夹（可选安装）。

3. 附带修复插件 WenchangFix.dll（GameData/WenchangFix/）：
   替换 KK 自带的 AnimateOnClick 门动画模块，修复动画进行中被
   打断（回收航天器、回退 VAB/SPH、切换场景、KK 卸载加载）后
   大门卡死、无法再点击的问题。安装或重新打包时请务必保留
   WenchangFix 文件夹。

----------------------------------------
安装
----------------------------------------
把 "GameData" 内的内容复制进你的 KSP "GameData" 文件夹。

----------------------------------------
手动摆放教程（KK 编辑器，Ctrl+K）
----------------------------------------
1. 打开静态件编辑器，选择模型：
   - "Wenchang Satellite Launch Center 101"（wenchang_lc101，发射台）
   - "Wenchang Satellite Launch Center 102"（wenchang_lc102，发射台）
   - "Wenchang Satellite Launch Center"（wenchang_launch，主体建筑群）
2. 摆放到任意位置。真实文昌参考坐标：
   - LC-101 工位：北纬 19.6147 / 东经 110.9511
   - LC-201 工位：北纬 19.6190 / 东经 110.9490
3. 给两个发射台分别添加发射场设施：
   - 出生点：101 台用 first_spawn / 102 台用 second_spawn
   - 发射场类型：VAB，分类：RocketPad
   （出生点默认值已预先写在 cfg 里）

----------------------------------------
可选：真实文昌坐标预置（Optional 文件夹）
----------------------------------------
包里附带一套可选的现成摆放，把整个发射场放在地球（RSS/Sol/RSS Reborn）
的真实文昌位置：

  - 发射台 101（wenchang_lc101）：北纬 19.631579 / 东经 110.952606
  - 发射台 102（wenchang_lc102）：北纬 19.632114 / 东经 110.955794
  - 主体建筑（wenchang_launch）：北纬 19.631768 / 东经 110.952655

预置安装方法：
1. 确保已安装 Sol或RSS或RSS Reborn 星系 mod。
2. 把 "Optional/Wenchang_Real_Placement/GameData" 里的内容复制到
   你的 KSP "GameData" 文件夹，使 4 个 .cfg 文件落到
   GameData/KerbalKonstructs/NewInstances/ 目录下。
3. 启动游戏，建筑会出现在 KK 组 "NewGroup_2" 中。
4. 两个发射台默认处于关闭状态：打开 KK 地图，点击发射台将其
   开启（开启费用为 0），之后即可在 VAB 的发射点列表中选择。

以后想移除该预置，只需删除 GameData/KerbalKonstructs/NewInstances/
目录下的这 4 个文件。

----------------------------------------
交互玩法
----------------------------------------
- 点击发射塔架：开/合塔架
- 点击活动转运平台：展开/收起平台
- 点击地面灯光：开关照明

注意：建议动画完成后再执行下一个动作（包括回退发射时，回退组装大楼）。如果出现动画卡住了，再点击一两次即可恢复。
----------------------------------------
许可协议
----------------------------------------
CC BY-SA 4.0（原 mod 与本补丁）。详见 LICENSE.txt。

KERWIS 制作
修复：李敬亭

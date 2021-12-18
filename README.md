# my_ue4_demo

时间仓促，只做了一周，没有玩法，没有ui

演示视频：https://www.bilibili.com/video/BV1FL4y1n7cx

pc版打包好的游戏：https://disk.pku.edu.cn:443/link/FBA3ABCA380EA7F899BF9E5095F40205
有效期限：2023-01-01 23:59

## 已完成内容：

### 动作系统

· 移动  使用blend，混合不同速度的移动姿势

· 跳跃  状态机

· 翻滚  四向翻滚 montage的notify

· 冲刺  niagara 粒子系统 

· 多向受击

### 攻击系统

·拔刀 收刀  

·攻击判定 射线检测

·锁敌     

·打击感（camera shake）

·处决         正面处决，背后处决 球形射线检测

·敌人血条  受击显现，一段时间未受击消失

### AI 行为树

·在navigation区域内漫游

·看到player就追逐

·player在攻击距离内就攻击

### 操作按键

·移动：WASD

·跳跃：Space

·攻击：鼠标左键

·蓄力攻击：鼠标中键

·冲刺&翻滚：Shift

拔刀状态时翻滚，收刀状态时冲刺

·拔刀收刀：F

·锁定最近敌人：R

·处决：E

正面处决需要目标敌人是player最后一次攻击到的对象且血量在25%之下

背后处决需要离敌人足够近

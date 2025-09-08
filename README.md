# Crystal
一款 Garmin Connect IQ 手表表盘。

## 描述
**如果你喜欢使用 Crystal，可以通过小额捐赠支持我的工作：**
https://goo.gl/vFCE4T

**常见问题，包括如何更改表盘设置：**
https://github.com/warmsound/crystal-face/wiki/FAQ

一个晶莹剔透的手表表盘，带有类似 LCD 的目标计量段落，创作时正值英格兰异常寒冷的天气中雪花飘落。

功能（取决于手表支持情况）：
- 中间显示大号时间数字，小时加粗。可隐藏前导零和秒。小时和分钟颜色可独立设置。
- 最多 3 个可自定义的数据字段：心率（历史/实时）、电池、通知、卡路里、距离、闹钟、海拔、温度计、日出/日落、天气（OpenWeatherMap）。
- 最多 3 个可自定义指示器：蓝牙、闹钟、通知、蓝牙/通知、电池。
- 2 个可自定义计量器：步数、爬楼层数、活跃分钟数（每周）、电池、卡路里（自定义目标）。计量器具有自动缩放段和当前/目标值显示。
- 移动条。
- 12 种配色主题。

技术说明：为了节省手表电池，目标计量器和移动条使用受调色板限制的后备缓冲区绘制，以提高绘制性能，并尽量减少内存消耗。

这是我第一个 Connect IQ 表盘（请多包涵！），期待你的反馈，以便改进表盘并支持更多设备。

评测：
- Sergio 的西班牙语视频评测：https://www.youtube.com/watch?v=TZFhnm_y1MM。

## 更新内容

### 2.7.1
- 添加对 vívoactive® 6 的支持。

### 2.7.0
- 添加对最新手表的支持，包括 fēnix® 8 系列、Forerunner® 165 系列、Instinct® 3 AMOLED 和 Enduro™ 3。
- 技术升级到 CIQ 8.1.0。

### 2.6.1
- 修复圆形 454x454 手表上的“夜间散云”天气图标。

### 2.6.0
- 添加对最新手表的支持，包括 vívoactive® 5 和 Venu® 3。
- 修复 AMOLED 屏幕电池计量器间隙问题。
- 技术升级到 CIQ 6.4.1。对支持的手表使用 Properties/Storage 替代 Object Store。修复大部分编译器警告。

### 2.5.0
- 添加对 Venu® 2 和 Venu® 2S 的支持（感谢 fallingrock 的测试帮助）。感谢你的耐心！
- 技术升级到 CIQ 4.0.3。

### 2.4.7
- 改进德语翻译（感谢 2b2bff）。
- 翻译荷兰语设置（感谢 DRG-developer）。
- 允许覆盖内置 OpenWeatherMap 密钥，以防该密钥被屏蔽。
- 技术升级到 CIQ 3.2.5 SDK。

### 2.4.6
- 更换 OpenWeatherMap 密钥以规避因密钥滥用导致的账户封禁。

### 2.4.5
- 添加韩语支持（感谢 nanbean）。
- 第二次尝试修复设置相关崩溃。

### 2.4.4
- 添加对 Approach® S62、D2 Air、Descent™ Mk2、Garmin Swim™ 2、Rey™、MARQ® Golfer、Venu® Mercedes-Benz Collection、Venu® Sq、Venu® Sq – Music Edition 的支持。
- 修复多个设置相关的崩溃。
- 更新俄语翻译（感谢 ya_kazachkov）。
- 修正德语翻译（感谢 axcro7）。
- 技术升级到 CIQ 3.2.2 SDK。

### 2.4.3
- 可能修复 Venu™ 在 2.80 固件上的崩溃。

### 2.4.2
- 第二次尝试修复 fēnix® 5X 崩溃。识别到 15.10 固件中 Bug（requiresBurnInProtection 错误地设置为 true），感谢 jeriveraf 的宝贵帮助。

### 2.4.1
- 可能修复 fēnix® 5X 系列崩溃。感谢大家的耐心。

### 2.4.0
- 添加对 Venu™ 的支持，新增常显布局。
- 添加对 MARQ™ Adventurer 和 Commander 的支持。
- 技术升级到 CIQ 3.1.5 SDK。

### 2.3.7
- 为 fēnix® 6X 添加专用字体和布局。
- 提高所有手表小字体的可读性。

### 2.3.6
- 技术升级到 CIQ 3.1.4 SDK。添加对 fēnix® 6 系列（除 fēnix® 6X）、Captain Marvel、First Avenger 和 vívoactive® 4 系列的支持。

### 2.3.5
- 添加对 Forerunner® 45 的支持。

### 2.3.4
- 修复通过 Connect IQ Store 应用更改数字设置（如“卡路里目标”）时的崩溃。

### 2.3.3
- 新的计量器样式选项，以及新的计量器数字样式设置。
- 修复字段或指示器数量设置为 0 时的问题。
- 修复 Forerunner® 735XT 天气图标显示问题。
- 修复德语翻译拼写错误。
- 技术升级到 CIQ 3.0.11 SDK。添加对 Forerunner® 245/245 Music/945 和 vívolife 的支持。

### 2.3.2
- 修复天气和湿度未更新的问题。
- 技术升级到 CIQ 3.0.10 SDK。添加对 MARQ™ 系列和 vívoactive® 3 Mercedes-Benz 的支持。

### 2.3.1
- 可能修复 fēnix® 5 系列、vívoactive® 3 系列和 Approach® S60 的间歇性存储相关崩溃。
- 更新瑞典语翻译（感谢 fredrikaverpil）。
- 技术升级到 CIQ 3.0.9 SDK。添加对 vívoactive® 3 Music LTE 的支持。

### 2.3.0
- 增大时间字体并调整所有手表布局。
- vívoactive® HR 显示单行时间。

### 2.2.6
- 添加“湿度”数据字段（使用 OpenWeatherMap）。非常感谢 jrmcsoftware 的实现。
- 技术升级到 CIQ 3.0.8 SDK。

### 2.2.5
- “气压”数据字段应使用历史数据，以尊重 fēnix® 5 手表的手动气压校准（感谢 Allalin72 的帮助）。

### 2.2.4
- 修复在“显示填充段”模式下移动条不清除的问题（感谢 BrettL 提供复现步骤）。
- 添加“玉米黄（深色）”和“荧光橙（浅色）”主题。
- 添加“气压”数据字段。
- 技术升级到 CIQ 3.0.7 SDK。

### 2.2.3
- 移除输入 OpenWeatherMap 密钥的需求。
- 技术升级到 CIQ 3.0.6 SDK。

### 2.2.2
- 修复天气密钥未激活前使用导致卡住“key!”的问题。

### 2.2.1
- 修复接收天气数据后间歇性崩溃。

### 2.2.0
- 添加“天气”数据字段：仅 CIQ 2.x 设备，需要免费的 OpenWeatherMap API 密钥 (https://openweathermap.org/)。

### 2.1.0
- 添加“日出/日落”数据字段。
- 从更及时的来源读取海拔，并对所有手表启用。
- 添加克罗地亚日期翻译（感谢 Kristijan）。
- 更新俄语翻译及字符串修正（感谢 xgsa）。
- 设置界面德语翻译（感谢 dragonito）。
- 技术升级到 CIQ 3.0.4 SDK。

### 2.0.1
- 修复更改设置时的崩溃。

### 2.0.0
- 表盘和设置界面俄语翻译（感谢 xgsa）。
- 显示附加时区：在设置中指定城市（仅 CIQ 2.x 设备，测试版）。参见 FAQ。
- 重新启用对 Approach® S60 的支持。
- 技术升级到 CIQ 3.0.3 SDK。

### 1.8.1
- 添加“心率（实时 5 秒）”数据字段。
- 从更及时的来源读取心率。
- 改进电池指示器清晰度。
- “隐藏小时前导零”现在适用于 12 小时和 24 小时模式。
- 技术升级到 CIQ 2.4.9 SDK，添加对 D2™ Delta、D2™ Delta PX、D2™ Delta S 的支持。

### 1.8.0
- 添加设置以控制数据字段数量（0-3）。
- 添加设置以控制指示器数量（0-3）：蓝牙、闹钟、通知、蓝牙/通知。
- 改进内存效率。
- 布局调整。
- 技术升级到 CIQ 2.4.8 SDK。

### 1.7.4
- 设置界面波兰语翻译（感谢 Flugcojt）。
- 设置界面瑞典语翻译（感谢 hasselrot）。

### 1.7.3
- 升级到 CIQ 2.4.7 SDK，添加对 fēnix® 5 Plus、fēnix® 5S Plus、fēnix® 5X Plus、vívoactive® 3 Music 的支持。
- 修复“ft”海拔单位显示不正确的问题（感谢 Matt Reiser）。

### 1.7.2
- 海拔单位遵循英制/公制设置（感谢 Rick Gorham）。
- 添加“电池（隐藏百分比）”数据字段（感谢 Paolo Avezzano）。
- 修正移动条段数为 5（感谢 Viorel）。
- 技术升级到 CIQ 2.4.6 SDK。

### 1.7.1
- 重新启用 Forerunner® 920XT，使用 Coleman 提供的非抗锯齿自定义字体解决方法。
- 修正法语翻译（感谢 Ju Neusch）。

### 1.7.0
- 添加温度数据字段选项。
- 添加鲜艳黄色深色主题。
- 添加计量器样式设置。
- 添加移动条样式设置。
- 修正德语翻译（感谢 Christoph Heymann 的帮助）。
- 临时移除对 Approach® S60 和 Forerunner® 920XT 的支持，等待 Garmin 修复 - 非常感谢耐心等待。
- 技术升级到 CIQ 2.4.5 SDK。

### 1.6.1
- 为支持的 CIQ 2.x 设备添加气压海拔。
- 在 12 小时模式下，将午夜显示为“12”而非“00”。
- 修复 vívoactive® 默认设置错误。

### 1.6.0
- 添加蓝色、红色和绿色浅色主题。
- 允许独立覆盖小时和分钟颜色。
- 允许在 12 小时模式下隐藏小时前导零。
- 防止半圆手表上目标数字重叠（感谢 G_stijn 的报告）。

### 1.5.3
- 如果楼层或活跃分钟目标设置为 0，修复崩溃：显示禁用计量器。

### 1.5.2
- 技术升级到 CIQ 2.4.4 SDK。

### 1.5.1
- 添加闹钟数据字段选项。
- 部署到 CIQ 1.x 设备，第 2 部分：Forerunner® 230、Forerunner® 235、Forerunner® 630、Forerunner® 920XT、vívoactive®。

### 1.5.0
- 部署到 CIQ 1.x 设备，第 1 部分：D2™ Bravo、D2™ Bravo Titanium、fēnix® 3、fēnix® 3 HR。

### 1.4.3
- 计量器现在可以显示自定义卡路里目标，可在设置中指定。
- 修复在非英文语言环境下通过 Garmin Express 更改设置时出现的错误字符串或崩溃（感谢 Ezio Pillan 报告此 bug）。
- 设置页面添加应用版本。

### 1.4.2
- 允许隐藏秒数。

### 1.4.1
- 减少电池消耗，第 2 部分：优化每分钟更新（缓存可绘制引用）。
- 允许计量器显示电池电量。

### 1.4.0
- 减少电池消耗，第 1 部分：将每秒更新时间从 ~13ms 减少到 ~5ms（在 Approach® S60 模拟器上测量）。
- 添加红色（深色）和单色（深色）主题。
- 添加对 vívoactive® HR 的支持。

### 1.3.0
- 添加对 fēnix® 5S、fēnix® Chronos、Forerunner® 735XT 的支持。
- 添加荧光橙主题。

### 1.2.1 
- 修复距离值过低的问题（感谢 catana.remulus 报告并协助修复）。

### 1.2.0
- 添加对 Approach® S60、D2™ Charlie、Descent™ Mk1、Forerunner® 645、Forerunner® 645 Music、Forerunner® 935、fēnix® 5、fēnix® 5X 的支持。
- 添加矢车菊蓝和柠檬奶油主题以提高可见性。

**注意：由于 vívoactive® 3 固件 bug，该表盘将在 3.30-3.40 固件升级时保持当时的语言。希望 Garmin 在未来固件中修复此问题。**

### 1.1.0
- 国际化：添加对中文（简体/繁体）、捷克语、丹麦语、荷兰语、芬兰语、法语、德语、匈牙利语、意大利语、挪威语、波兰语、葡萄牙语、斯洛伐克语、斯洛文尼亚语、西班牙语、瑞典语的支持。
- 对不支持的地区强制使用英语，以防止乱码。
- 修复电池计量器未能及时显示低电量/临界警告颜色的问题。

### 1.0.1
- 修复中午显示为 AM 而非 PM 的问题（感谢 JACalvo 报告）。
- 修复移动条更新不正确的问题。

### 1.0.0
- 初次公开发布，仅支持 vívoactive® 3。

## 致谢
图标：
- “[距离](https://thenounproject.com/term/distance/1514833/)” 图标由 Becris 提供，来自 [The Noun Project](https://thenounproject.com)。
- “[火焰](https://thenounproject.com/term/fire/24187/)” 图标由 Jenny Amer 提供，来自 [The Noun Project](https://thenounproject.com)。
- “[步数](https://thenounproject.com/term/steps/87667/)” 图标由 Eugen Belyakoff 提供，来自 [The Noun Project](https://thenounproject.com)。
- “[楼层](https://thenounproject.com/term/upstairs/304907/)” 图标由 Arthur Shlain 提供，来自 [The Noun Project](https://thenounproject.com)。
- “[秒表](https://thenounproject.com/term/stopwatch/319102/)” 图标由 Rohith M S 提供，来自 [The Noun Project](https://thenounproject.com)。
- “[山脉](https://thenounproject.com/term/mountains/1468194/)” 图标由 Deemak Daksina 提供，来自 [The Noun Project](https://thenounproject.com)。
- “[湿度](https://thenounproject.com/term/humidity/1554816/)” 图标由 Akriti Bhusal 提供，来自 [The Noun Project](https://thenounproject.com)。

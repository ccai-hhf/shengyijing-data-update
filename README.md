# 生意经视频数据日更 Skill（WorkBuddy）

必胜客三个抖音账号（您真是披萨心肠 / 有亿点好吃😋 / 🐱林小奇想吃汉堡🐶）的生意经视频数据日更跟踪。

## 安装（1分钟）

1. 点击绿色 **Code** 按钮 → **Download ZIP**（无需登录 GitHub）
2. 解压后，把 `shengyijing-data-update` 文件夹整个放进 WorkBuddy 技能目录：
   - **Windows**: `C:\Users\你的用户名\.workbuddy\skills\shengyijing-data-update\`
   - **Mac**: `~/.workbuddy/skills/shengyijing-data-update/`
3. 重启 WorkBuddy（或新开一个对话）

## 使用前提（只做一次）

1. 在 WorkBuddy 里连接「飞书」连接器，并确保登录的飞书账号对跟踪表有编辑权限
2. 首次使用时 WorkBuddy 会请求飞书读写授权，点同意即可

## 每天怎么用

1. 生意经后台导出 xlsx（**日期范围务必选「2026-10-19～当天」**，否则当天新视频不在表里）
2. 把 xlsx 拖进 WorkBuddy 对话，说一句「**更新数据**」
3. AI 自动完成：筛选三账号 → 更新飞书主表最新值 → 往「数据明细」子表追加当日快照 → 输出变化汇总

## 数据口径

- 飞书主表 Sheet1：每个视频的**最新累计值**（每天覆盖更新）
- 「数据明细」子表：每天追加一份快照，**不覆盖**，可回看每条视频 15 天的增长轨迹

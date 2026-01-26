# 个人主页定制 - 修改日志

本文档记录了为李浩勋（Haoxun Li）定制个人主页模板所做的所有修改。

**日期：** 2026年1月21日

---

## 1. 配置文件更新 (`_config.yml`)

### 网站设置
- **标题**：从 "Zhenglin (Carlos) Wan 万政霖" 改为 "Haoxun Li"
- **描述**：从 "Ph.D. student @ NUS Computing" 改为 "Affective Speechie"
- **仓库**：从 "vanzll/vanzll.github.io" 改为 "WD-233/WD-233.github.io"

### 作者信息
- **姓名**：改为 "Haoxun Li"
- **位置**：从 "Singapore" 改为 "Hangzhou, China"
- **单位**：添加了 "HIAS, UCAS"（在侧边栏用房子图标显示）
- **邮箱**：改为 "lihaoxun23@mails.ucas.ac.cn"
- **Google Scholar**：改为用户ID "Nj4Ew20AAAAJ"
- **GitHub**：改为 "WD-233"
- **Twitter**：已移除（设置为空字符串）
- **LinkedIn**：已移除（设置为空字符串）

---

## 2. 主页内容更新 (`_pages/about.md`)

### 简历和联系方式部分
- **简历**：更新为链接到中文简历PDF (`resume_in_chinese_20260120.pdf`)
  - 更新日期："Updated on 20 Jan, 2026"
- **联系方式**：更新为：
  - 主要：lihaoxun23@mails.ucas.ac.cn
  - 次要：rickyhx@163.com

### 关于我部分
- 完全重写以反映李浩勋的背景：
  - 人工智能硕士研究生（即将毕业）
  - 所在学院：中国科学院大学杭州高等研究院智能科学与技术学院
  - 研究兴趣：情感语音生成与识别、多模态情感计算
  - 导师：李太豪教授和瞿乐源博士
  - 实验室同学：刘宇和史汉磊
  - 关于情感计算和人机交互的研究理念

### 新闻部分
- 将滚动窗口高度从9条缩减为2条
- 替换所有新闻条目为单条：
  - *2026.01*：两篇论文被 ICASSP 2026 接收（TTS和SER）

### 出版物部分
- **标题**：从 "Selected Publications" 改为 "Publications"
- **子标题**：从 "Conference papers and Preprints" 改为 "Papers and preprints"
- **署名说明**：从 "\* denotes joint-first-author and equal contribution" 改为 "\* denotes Co-first Author, † denotes Advisor"

### 发明专利部分
- 添加了说明注释："† denotes Advisor"
- 添加了4项专利（所有标题翻译为英文）：
  1. 一种细粒度强调可控的情感语音合成方法
  2. 一种基于有监督对比学习的语音情感识别方法
  3. 一种动态表情识别方法、电子设备及计算机可读存储介质
  4. 一种基于和弦情感的动机发展多声部音乐生成算法

### 白皮书部分
- **状态**：已注释掉（保留在代码中以便将来可能使用）

### 教育经历部分
- 替换所有教育条目为两条新记录：
  1. **人工智能硕士**
     - 中国科学院大学，杭州高等研究院
     - 导师：李太豪教授
     - 时间：2023.09 -
     - 图片：`images/ucas.png`
  2. **计算机科学与技术学士**
     - 北京工业大学樊恭秀荣誉学院
     - 导师：马维教授
     - 时间：2019.09 - 2023.07
     - 图片：`images/bjut-logo-2048px.png`

### 实习和工作经历部分
- **状态**：已注释掉（保留在代码中以便将来可能使用）

### 服务部分
- **状态**：已注释掉（保留在代码中以便将来可能使用）

### 荣誉、奖项和奖学金部分
- 替换所有奖项为：
  - 国家奖学金
  - 中科院一等学业奖学金
  - 中科院三好学生
  - 北工大创新创业奖
  - 北工大优秀毕业论文奖

### 媒体报道部分
- **状态**：已注释掉（保留在代码中以便将来可能使用）

### 杂项部分
- 完全重写个人兴趣内容：
  1. **音乐**：吉他历程（古典到指弹）、乐队（"半成品乐队"、"三人一猪"）、毕业典礼演出
     - 图片：`m1-1.jpg`, `m1-2.jpg`, `m2-1.png`, `m2-2.jpg`
  2. **围棋**：业余5段、国家二级运动员、比赛成就
     - 图片：`m3-1.jpg`
  3. **逻辑游戏**：狼人杀、血染钟楼、数独、IMC金奖
  4. **球类运动**：羽毛球、乒乓球、足球、网球、台球，获得五枚奖牌
     - 图片：`jiangpai.jpg`
  5. **电子游戏**：明日方舟和第五人格
     - 图片：`mingrifangzhou.png`, `diwurenge.png`

---

## 3. 出版物数据文件 (`_data/publications.yml`)

替换整个出版物列表为6篇论文：

1. **EMORL-TTS**：基于强化学习的大语言模型TTS中的细粒度情感控制
   - 会议：ICASSP 2026
   - 链接：论文、演示
   - 图片：`emorl-tts.png`

2. **MSF-SER**：用多粒度语义丰富声学建模以进行语音情感识别
   - 会议：ICASSP 2026
   - 链接：论文
   - 图片：`msf-ser.png`

3. **Centering Emotion Hotspots**：用于对话情感识别的多模态局部-全局融合和跨模态对齐
   - 状态：预印本
   - 链接：论文
   - 图片：`hotspots.png`

4. **HOPE**：面向优化和个性化感知的抑郁症评估的层次融合
   - 会议：ACM MM
   - 链接：论文、代码
   - 图片：`hope.png`

5. **EME-TTS**：解锁语音合成中的强调和情感联系
   - 会议：INTERSPEECH
   - 链接：论文、演示
   - 图片：`eme-tts.png`

6. **标签语义驱动的对比学习**用于语音情感识别
   - 会议：INTERSPEECH
   - 链接：论文
   - 图片：`la.png`

**注意**：出版物模板中所有包含"Haoxun Li"的作者名字都会自动加粗。

---

## 4. 布局和模板更改

### 语言切换功能 (`_layouts/default.html`)
- **状态**：已注释掉
- 移除了右上角的"中/英"语言切换按钮
- 注释掉了相关的JavaScript语言切换代码

### CSS样式 (`_includes/head/custom.html`)
- **语言切换样式**：注释掉了所有与 `.lang-toggle` 类相关的CSS样式

---

## 5. 图片文件验证

所有必需的图片文件都存在于 `/images/` 目录中：

### 个人照片
- `m1-1.jpg`, `m1-2.jpg`（吉他照片）
- `m2-1.png`, `m2-2.jpg`（乐队照片）
- `m3-1.jpg`（围棋照片）
- `jiangpai.jpg`（体育奖牌）
- `mingrifangzhou.png`, `diwurenge.png`（游戏截图）

### 机构标志
- `ucas.png`（中国科学院大学）
- `bjut-logo-2048px.png`（北京工业大学）

### 出版物图片
- `emorl-tts.png`
- `msf-ser.png`
- `hotspots.png`
- `hope.png`
- `eme-tts.png`
- `la.png`

---

## 6. 主要更改总结

1. **个人信息**：更新所有个人详细信息以反映李浩勋的身份
2. **学术背景**：从新加坡国立大学博士改为中科院硕士研究生
3. **研究方向**：从强化学习转向情感计算和情感语音
4. **出版物**：替换为6篇语音/情感相关论文
5. **专利**：添加4项中国发明专利（标题翻译为英文）
6. **教育**：更新显示中科院（硕士）和北工大（本科）
7. **兴趣爱好**：完全重写杂项部分，包括音乐、围棋、体育和游戏
8. **界面更改**：移除语言切换功能，调整新闻部分高度
9. **注释部分**：白皮书、实习、服务、媒体报道（保留以备将来使用）

---

## 未来修改注意事项

- 所有注释掉的部分都保留在代码中，可以通过删除注释标记轻松恢复
- 图片路径使用从根目录开始的相对路径
- 所有超链接都正确格式化且可用
- 出版物模板会自动将包含"Haoxun Li"的作者名字加粗
- 网站保持响应式设计和深色模式功能

---

## 更新日志 - 2026年1月21日（第二轮）

### 额外修改

1. **头像图片路径** (`_config.yml`)
   - 将头像路径从 `images/soochow.jpg` 改为 `/data/lihaoxun/tmp/images/soochow.jpg`（绝对路径）

2. **侧边栏显示** (`_config.yml`)
   - 从 employer 字段移除了 "HIAS, UCAS"（留空以获得更好的视觉效果）

3. **社交媒体链接移除** (`_config.yml`)
   - 完全注释掉 `twitter` 字段以确保不显示
   - 完全注释掉 `linkedin` 字段以确保不显示

4. **导航栏** (`_data/navigation.yml`)
   - 注释掉"Internships"导航项
   - 注释掉"Services"导航项
   - 注释掉"Press/Media"导航项
   - 这些部分在页面中保持注释状态，但不再从顶部导航访问

5. **杂项部分图片格式** (`_pages/about.md`)
   - 所有图片现在使用 `object-fit: contain` 和 `height: auto` 保持纵横比
   - 通过最大宽度约束减小整体图片大小：
     - 吉他照片（m1-1.jpg, m1-2.jpg）：max-width 700px 容器，各占48%宽度
     - 乐队照片（m2-1.png, m2-2.jpg）：max-width 700px 容器，各占48%宽度
     - 围棋照片（m3-1.jpg）：max-width 500px 容器（从60%视口宽度显著减小）
     - 体育奖牌（jiangpai.jpg）：max-width 500px 容器
     - 游戏截图（mingrifangzhou.png, diwurenge.png）：max-width 700px 容器，各占48%宽度
   - 在并排图片之间添加了 `gap: 10px` 以获得更好的间距
   - 使用 `margin: 15px auto` 将所有图片容器居中

### 更改摘要
- 修复头像路径使用绝对路径
- 成功从侧边栏移除 Twitter 和 LinkedIn
- 移除 HIAS, UCAS 单位显示
- 清理导航栏以隐藏注释的部分
- 优化杂项部分所有图片，在保持纵横比的同时实现更好的响应式显示

---

## 更新日志 - 2026年1月21日（第三轮）

### 额外修改

1. **添加导师链接** (`_pages/about.md`)
   - 为李太豪教授添加超链接：https://people.ucas.ac.cn/~0070909
   - 为瞿乐源博士添加超链接：https://people.ucas.edu.cn/~leyuanqu

2. **网站图标/页面图标更新** (`_includes/head/custom.html`)
   - 将所有favicon引用从默认图标更改为 `images/fei.png`
   - 更新了：
     - apple-touch-icon (180x180)
     - favicon (32x32)
     - favicon (16x16)

3. **用户手动图片大小调整** (`_pages/about.md`)
   - 用户手动调整图片大小以获得更好的视觉平衡：
     - 吉他照片：从48%/48%改为60%/40%分割
     - 乐队照片：从48%/48%改为60%/60%
     - 围棋照片：max-width从350px减小到220px
     - 体育奖牌：改为40%宽度，简化样式
     - 游戏截图：从48%/48%改为70%/55%分割
   - 文字修正："human–AI interaction"改为"human-computer interaction"

---

## 更新日志 - 2026年1月21日（第四轮）

### 禁用 GitHub Actions 工作流

1. **禁用自动 Google Scholar 爬虫** (`.github/workflows/google_scholar_crawler.yaml`)
   - 注释掉 `on:` 触发器部分以防止自动执行
   - 这样可以停止每日计划任务，从而不再收到失败邮件
   - 工作流文件保留以备将来需要时使用

**如何在将来重新启用：**
如果你以后想启用自动引用数据抓取功能，请按以下步骤操作：

1. **在 GitHub 中配置 Google Scholar ID：**
   - 访问你的仓库：`https://github.com/WD-233/WD-233.github.io`
   - 导航至：**Settings** → **Secrets and variables** → **Actions**
   - 添加新的仓库密钥：
     - Name: `GOOGLE_SCHOLAR_ID`
     - Value: `Nj4Ew20AAAAJ`（你的 Google Scholar ID）

2. **重新启用工作流：**
   - 打开 `.github/workflows/google_scholar_crawler.yaml`
   - 取消注释第6-9行（删除开头的 `#`）：
     ```yaml
     on: 
      page_build: 
      schedule:
       - cron:  '0 8 * * *'
     ```
   - 提交并推送更改

3. **可选 - 调整频率：**
   - 当前设置 `'0 8 * * *'` 每天8:00 UTC运行
   - 每周运行：`'0 8 * * 0'`（每周日）
   - 每月运行：`'0 8 1 * *'`（每月1号）

---

**修改日志结束**

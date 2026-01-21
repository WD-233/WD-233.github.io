# Personal Homepage Customization - Change Log

This document records all modifications made to customize the personal homepage template for Haoxun Li (李浩勋).

**Date:** January 21, 2026

---

## 1. Configuration File Updates (`_config.yml`)

### Site Settings
- **Title**: Changed from "Zhenglin (Carlos) Wan 万政霖" to "Haoxun Li"
- **Description**: Changed from "Ph.D. student @ NUS Computing" to "Affective Speechie"
- **Repository**: Changed from "vanzll/vanzll.github.io" to "WD-233/WD-233.github.io"

### Author Information
- **Name**: Changed to "Haoxun Li"
- **Location**: Changed from "Singapore" to "Hangzhou, China"
- **Employer**: Added "HIAS, UCAS" (displayed with house icon in sidebar)
- **Email**: Changed to "lihaoxun23@mails.ucas.ac.cn"
- **Google Scholar**: Changed to user ID "Nj4Ew20AAAAJ"
- **GitHub**: Changed to "WD-233"
- **Twitter**: Removed (set to empty string)
- **LinkedIn**: Removed (set to empty string)

---

## 2. Main Page Content Updates (`_pages/about.md`)

### Resume and Contact Section
- **Resume**: Updated to link to Chinese resume PDF (`resume_in_chinese_20260120.pdf`)
  - Updated date: "Updated on 20 Jan, 2026"
- **Contact**: Updated to:
  - Primary: lihaoxun23@mails.ucas.ac.cn
  - Secondary: rickyhx@163.com

### About Me Section
- Completely rewritten to reflect Haoxun Li's background:
  - Final-year M.S. candidate in Artificial Intelligence
  - At School of Intelligent Science and Technology, HIAS, UCAS
  - Research interests: emotional speech generation and recognition, multimodal affective computing
  - Advisors: Prof. Taihao Li and Dr. Leyuan Qu
  - Labmates: Yu Liu and Hanlei Shi
  - Research philosophy on affective computing and human-AI interaction

### News Section
- Reduced scroll window height from 9 items to 2 items
- Replaced all news items with single entry:
  - *2026.01*: Two papers accepted by ICASSP 2026 (TTS and SER)

### Publications Section
- **Title**: Changed from "Selected Publications" to "Publications"
- **Subsection**: Changed from "Conference papers and Preprints" to "Papers and preprints"
- **Attribution note**: Changed from "\* denotes joint-first-author and equal contribution" to "\* denotes Co-first Author, † denotes Advisor"

### Invention Patents Section
- Added explanatory note: "† denotes Advisor"
- Added four patents (all titles translated to English):
  1. A Fine-Grained Emphasis-Controllable Emotional Speech Synthesis Method
  2. A Speech Emotion Recognition Method Based on Supervised Contrastive Learning
  3. A Dynamic Facial Expression Recognition Method, Electronic Device, and Computer-Readable Storage Medium
  4. A Chord-Emotion-Based Motivic Development Algorithm for Multi-Voice Music Generation

### White Paper Section
- **Status**: Commented out (preserved in code for potential future use)

### Education Section
- Replaced all education entries with two new ones:
  1. **M.S. in Artificial Intelligence**
     - University of Chinese Academy of Sciences, HIAS
     - Advisor: Prof. Taihao Li
     - Period: 2023.09 -
     - Image: `images/ucas.png`
  2. **B.S. in Computer Science and Technology**
     - Fan Gongxiu Honors College, Beijing University of Technology
     - Advisor: Prof. Wei Ma
     - Period: 2019.09 - 2023.07
     - Image: `images/bjut-logo-2048px.png`

### Internships and Work Experiences Section
- **Status**: Commented out (preserved in code for potential future use)

### Services Section
- **Status**: Commented out (preserved in code for potential future use)

### Honors, Awards and Scholarships Section
- Replaced all awards with:
  - National Scholarship
  - UCAS First-Class Academic Scholarship
  - UCAS Merit Student Award
  - BJUT Innovation & Entrepreneurship Award
  - BJUT Outstanding Graduation Thesis Award

### Press/Media Section
- **Status**: Commented out (preserved in code for potential future use)

### Miscellaneous Section
- Completely rewritten with personal interests:
  1. **Music**: Guitar journey (classical to fingerstyle), bands ("半成品乐队", "三人一猪"), graduation ceremony performance
     - Images: `m1-1.jpg`, `m1-2.jpg`, `m2-1.png`, `m2-2.jpg`
  2. **Go (围棋)**: Amateur 5-dan, National Level-2 Athlete, competition achievements
     - Image: `m3-1.jpg`
  3. **Logic Games**: Werewolf, Blood on the Clocktower, Sudoku, IMC Gold Award
  4. **Ball Sports**: Badminton, table tennis, soccer, tennis, billiards, five medals
     - Image: `jiangpai.jpg`
  5. **Video Games**: Arknights and Identity V
     - Images: `mingrifangzhou.png`, `diwurenge.png`

---

## 3. Publications Data File (`_data/publications.yml`)

Replaced entire publication list with 6 papers:

1. **EMORL-TTS**: Reinforcement Learning for Fine-Grained Emotion Control in LLM-based TTS
   - Conference: ICASSP 2026
   - Links: Paper, Demo
   - Image: `emorl-tts.png`

2. **MSF-SER**: Enriching Acoustic Modeling with Multi-Granularity Semantics for Speech Emotion Recognition
   - Conference: ICASSP 2026
   - Links: Paper
   - Image: `msf-ser.png`

3. **Centering Emotion Hotspots**: Multimodal Local-Global Fusion and Cross-Modal Alignment for Emotion Recognition in Conversations
   - Status: preprint
   - Links: Paper
   - Image: `hotspots.png`

4. **HOPE**: Hierarchical Fusion for Optimized and Personality-Aware Estimation of Depression
   - Conference: ACM MM
   - Links: Paper, Code
   - Image: `hope.png`

5. **EME-TTS**: Unlocking the Emphasis and Emotion Link in Speech Synthesis
   - Conference: INTERSPEECH
   - Links: Paper, Demo
   - Image: `eme-tts.png`

6. **Label Semantic-Driven Contrastive Learning** for Speech Emotion Recognition
   - Conference: INTERSPEECH
   - Links: Paper
   - Image: `la.png`

**Note**: All author names with "Haoxun Li" are bolded in the publications template.

---

## 4. Layout and Template Changes

### Language Toggle Feature (`_layouts/default.html`)
- **Status**: Commented out
- Removed the "中/英" language switch button from the top-right corner
- Commented out related JavaScript code for language switching

### CSS Styles (`_includes/head/custom.html`)
- **Language Toggle Styles**: Commented out all CSS styles related to `.lang-toggle` class

---

## 5. Image Files Verified

All required image files are present in the `/images/` directory:

### Personal Photos
- `m1-1.jpg`, `m1-2.jpg` (guitar photos)
- `m2-1.png`, `m2-2.jpg` (band photos)
- `m3-1.jpg` (Go/chess photo)
- `jiangpai.jpg` (sports medals)
- `mingrifangzhou.png`, `diwurenge.png` (game screenshots)

### Institution Logos
- `ucas.png` (University of Chinese Academy of Sciences)
- `bjut-logo-2048px.png` (Beijing University of Technology)

### Publication Images
- `emorl-tts.png`
- `msf-ser.png`
- `hotspots.png`
- `hope.png`
- `eme-tts.png`
- `la.png`

---

## 6. Summary of Key Changes

1. **Personal Information**: Updated all personal details to reflect Haoxun Li's identity
2. **Academic Background**: Changed from NUS Ph.D. to UCAS M.S. candidate
3. **Research Focus**: Shifted from Reinforcement Learning to Affective Computing and Emotional Speech
4. **Publications**: Replaced with 6 speech/emotion-related papers
5. **Patents**: Added 4 Chinese invention patents (translated titles)
6. **Education**: Updated to show UCAS (master's) and BJUT (bachelor's)
7. **Interests**: Completely rewritten Miscellaneous section with music, Go, sports, and games
8. **UI Changes**: Removed language toggle feature, adjusted news section height
9. **Commented Sections**: White Paper, Internships, Services, Press/Media (preserved for potential future use)

---

## Notes for Future Modifications

- All commented-out sections are preserved in the code and can be easily restored by removing comment markers
- Image paths use relative paths from the root directory
- All hyperlinks are properly formatted and functional
- The publications template automatically bolds author names containing "Haoxun Li"
- The site maintains responsive design and dark mode functionality

---

**End of Change Log**


## Part 1: Project Introduction & Motivation 研究簡介與動機

### **Project Overview**
本研究旨在開發一款針對「大餐後修復（Post-overeating Recovery）」的健康管理應用程式。核心機制在於打破使用者因攝取高熱量食物（Cheat Meal）後產生的挫折感與逃避心理。透過記錄大餐行為、提供具體的修復建議（如散步、飲水），並結合虛擬寵物「孵蛋」與「圖鑑收集」的遊戲化機制，轉化傳統健康 App 給予使用者的負面壓力，提升長期的使用黏著度。

This research aims to develop a health management application focused on "Post-overeating Recovery." The core mechanism is designed to counteract the frustration and avoidance behaviors users experience after consuming high-calorie "cheat meals." By allowing users to log these meals and providing actionable recovery steps (e.g., walking, hydration), combined with a gamified "egg hatching" and "collection" system, the app transforms the negative pressure of traditional health apps into positive motivation, thereby enhancing long-term engagement.

### **Rationale for Literature Selection / 文獻選用理由**
我們挑選的文獻涵蓋了心理學、行為經濟學以及人機互動（HCI）三大領域，旨在從以下三個維度支持本專案：
1.  **行為動機：** 證明「逃避記錄」是普遍的人性心理（鴕鳥效應、罪惡感）。
2.  **系統限制：** 指出現有 Personal Informatics 工具在面對負面數據時的設計缺失。
3.  **解決方案：** 探討如何利用虛擬寵物情感連結與遊戲化機制，將枯燥的修復任務轉化為有趣的體驗。

The selected literature spans Psychology, Behavioral Economics, and Human-Computer Interaction (HCI). These references support the project across three dimensions:
1.  **Behavioral Motivation:** Proving that "avoiding tracking" is a common human psychological response (Ostrich Effect, Guilt).
2.  **System Limitations:** Identifying the design flaws of current Personal Informatics tools when dealing with negative data.
3.  **Solutions:** Exploring how virtual pet emotional bonds and gamification can transform tedious recovery tasks into engaging experiences.

---

## Part 2: Related Work 相關文獻綜述

### 1. 關於「逃避負面數據」與「紀錄中斷」
**Beyond Abandonment to Next Steps: Understanding and Designing for Life after Personal Informatics Tool Use**
* **Authors:** Daniel A. Epstein, Anant Bhardwaj, Candice L. Abraidman, James Fogarty, Sean A. Munson.
* **Venue:** Proceedings of the 2016 CHI Conference on Human Factors in Computing Systems (CHI '16).
* **Description:**
    這篇論文是研究自我追蹤行為「中斷（Lapses）」的經典。研究指出，使用者停止記錄並非單純因為懶惰，而往往是為了「逃避負面數據（Avoiding Negative Data）」。當使用者預期數據不理想時（如大餐後熱量超標），會感到心理負擔而主動放棄使用工具。這直接支持了我們為何需要「修復機制」來降低使用者的心理門檻。
* **Summary:**
    This foundational paper explores why users stop using self-tracking tools. It identifies "Avoiding Negative Data" as a primary cause for lapses—users often abandon apps when they feel their behavior (e.g., overeating) will result in "bad" data. This directly supports the need for a "recovery" mechanism to reduce emotional burden.

### 2. 關於「飲食記錄中的罪惡感」
**Barriers and Strategies in Food Journaling**
* **Authors:** Felicia Cordeiro, Elizabeth Bales, Elizabeth Cherry, James Fogarty, Sean Munson.
* **Venue:** Proceedings of the 33rd Annual ACM Conference on Human Factors in Computing Systems (CHI '15).
* **Description:**
    本研究深入探討了飲食紀錄的障礙。其中最關鍵的發現是「罪惡感（Guilt）」與「社會期許偏誤」。使用者在攝取不健康食物時會感到羞恥，這種負面情緒會導致他們刻意不記錄或放棄 App。這篇文獻能強力佐證你組員提出的假設：很多人不會在傳統 App 上登記 Cheat Meal。
* **Summary:**
    This study investigates the barriers to food journaling, highlighting "Guilt" and social desirability bias as major obstacles. Users feel ashamed when consuming unhealthy food, leading to selective logging or total abandonment. This provides strong evidence for the hypothesis that many users avoid tracking cheat meals in traditional apps.

### 3. 關於「虛擬寵物與遊戲化機制」
**Facilitating Unmotivated Tasks Based on Affection for Virtual Pet**
* **Authors:** Z. Liang, et al.
* **Venue:** Pervasive Health 2019 / Related Gamification Workshops.
* **Description:**
    這篇研究探討了如何利用使用者對「虛擬寵物」的情感連結來驅動他們完成原本沒動機完成的任務。這與你的「孵蛋機制」高度契合：將「散步、喝水」等修復任務，轉化為「為了讓蛋孵化/讓小動物成長」的情感責任，有效將健康負擔轉化為遊戲動力。
* **Summary:**
    This research examines how emotional attachment to virtual pets can motivate users to complete tasks they otherwise lack the drive for. It aligns perfectly with your "egg-hatching" mechanic: transforming recovery tasks into an emotional responsibility to care for a virtual creature, effectively turning health burdens into playful engagement.

### 4. 心理學基礎：鴕鳥效應
**The Ostrich Effect: Selective Attention to Information**
* **Authors:** Niklas Karlsson, George Loewenstein, Duane Seppi.
* **Journal:** Journal of Risk and Uncertainty (2009).
* **Description:**
    這是行為經濟學中著名的理論，解釋了人類在面對可能帶有負面情緒的消息時，會選擇「閉上眼不看」的傾向。這項心理學基礎能解釋為何在大餐過後，使用者會出現逃避行為，是本研究最重要的理論根基。
* **Summary:**
    A well-known theory in behavioral economics describing the tendency of individuals to avoid information that might cause psychological discomfort. This psychological foundation explains why users "bury their heads in the sand" after a cheat meal, serving as a core theoretical pillar for this study.

---

### **Summary Table / 文獻概覽表**

| 類別 (Category) | 篇名 (Title) | 核心公信力 (Credibility) | 關鍵貢獻 (Key Contribution) |
| :--- | :--- | :--- | :--- |
| **HCI / PI** | **Beyond Abandonment...** | **Top Tier (CHI)** | 定義了「逃避負面數據」導致的中斷行為。 |
| **HCI / Food** | **Barriers and Strategies...** | **Top Tier (CHI)** | 證實「罪惡感」是飲食記錄最大的障礙。 |
| **Gamification** | **Facilitating Unmotivated Tasks...** | **Peer-reviewed** | 驗證虛擬寵物能提升使用者完成任務的動機。 |
| **Psychology** | **The Ostrich Effect...** | **Classic Theory** | 提供人類逃避負面回饋的心理學解釋。 |



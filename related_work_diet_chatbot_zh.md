# Related Work 整理（飲食紀錄／行為改變／聊天機器人）

> 說明  
> 1. 本文件依照先前挑選的 10 篇 related work 整理。  
> 2. 為了確保每篇都能**實際查到正式來源**，我將先前較不穩定、像是「方向性標題」而非獨立可檢索論文的條目，替換為**可查證、可引用的正式 peer-reviewed 文獻**。  
> 3. 「Abstract」欄位以下以**繁體中文摘要整理**為主，避免直接大段複製原文摘要。  
> 4. 每篇皆包含：網址、摘要整理、研究方法與關注問題、和本研究的相關性、限制。  
> 5. 本研究指的是：**結合飲食記錄、If-Then 行為介入（spell cards）、小怪獸情緒回饋、以及 AI chatbot 的健康飲食互動系統**。

---

## 類別 A：解決相同／相似問題，但方法不同

### 1. The Effectiveness of a Chatbot Single-Session Intervention for People on Waitlists for Eating Disorder Treatment: Randomized Controlled Trial
- **年份 / 場域**：2025 / Journal of Medical Internet Research (JMIR)
- **網址**：https://www.jmir.org/2025/1/e70874
- **DOI**：https://doi.org/10.2196/70874

#### Abstract（中文整理）
這篇研究關注的是等待飲食失調治療的患者，在正式接受治療前能否透過單次、短時間的聊天機器人介入獲得幫助。作者使用名為 ED ESSI 的 rule-based chatbot，提供大約 30 分鐘的單次介入內容，並觀察其對飲食失調症狀、心理社會功能受損、憂鬱、焦慮、壓力，以及改變動機的影響。

#### 使用的方法 / 關注的問題
- **研究方法**：多中心、雙組、隨機對照試驗（RCT）
- **樣本**：60 位在候診名單上的飲食失調患者
- **介入方式**：聊天機器人提供單次心理教育與簡短介入；對照組則閱讀同主題的網頁資訊
- **核心問題**：如何在正式治療前，用低成本數位工具提供短期支持

#### 和我的研究的相關性
- 與我的系統同樣使用 **chatbot** 來支持與飲食相關的困擾
- 都不是單純記錄，而是希望透過對話提供行為或心理上的幫助
- 可支撐「聊天式介面可以在飲食領域中扮演支持者角色」

#### 侷限性
- 研究情境偏**臨床飲食失調**，而不是一般日常健康飲食管理
- 採用 **rule-based chatbot**，互動彈性與個人化程度有限
- 單次介入不等於長期陪伴，和我想做的日常系統差距仍大

---

### 2. Foody Talk: Exploring Opportunities for Conversational Food Journaling
- **年份 / 場域**：2025 / CHI 2025
- **網址**：https://dl.acm.org/doi/10.1145/3706598.3713875
- **開放頁面**：https://iro.uiowa.edu/esploro/outputs/conferenceProceeding/Foody-Talk-Exploring-Opportunities-for-Conversational/9984813287602771
- **DOI**：https://doi.org/10.1145/3706598.3713875

#### Abstract（中文整理）
這篇研究指出，數位飲食記錄有助於反思與改善飲食習慣，但常因負擔太高而被放棄。作者認為對話式介面（CUI）可能讓記錄行為變得更自然，因此透過 33 場共同設計 session、18 位參與者，探索人們理想中的「對話式食物記錄」應該長什麼樣。研究發現，使用者期待這種系統能夠學習個人目標與參照標準、在不同情境下調整深度與細節，並提供同理且不批判的回饋。

#### 使用的方法 / 關注的問題
- **研究方法**：共同設計（co-design）與質性分析
- **樣本**：18 位參與者，33 場共設 session
- **核心問題**：如何讓 food journaling 從繁重的手動記錄，變成較自然的對話式互動

#### 和我的研究的相關性
- 這篇和我最接近，因為我也把 **飲食記錄 + 對話式介面** 放在同一個系統裡
- 它支撐了「對話介面能降低記錄摩擦」這個方向
- 但我的系統多了 **行為介入、怪獸回饋、補償機制與聊天代理人**

#### 侷限性
- 偏設計探索，沒有驗證長期使用成效
- 著重 journaling 介面本身，沒有完整涵蓋情緒支持或行為改變機制
- 沒有像我的系統一樣把遊戲化角色、補償與提醒整合進來

---

### 3. A Refined Mobile Health Intervention (SMARTFAMILY2.0) to Promote Physical Activity and Healthy Eating in a Family Setting: Randomized Controlled Trial
- **年份 / 場域**：2025 / JMIR mHealth and uHealth
- **網址**：https://mhealth.jmir.org/2025/1/e65558
- **DOI**：https://doi.org/10.2196/65558

#### Abstract（中文整理）
這篇研究針對家庭情境中的身體活動與健康飲食，改良既有的 SMARTFAMILY app，加入更好的設計與易用性、遊戲化、健康識能，以及 just-in-time adaptive intervention（JITAI）等元素。研究以 cluster-randomized design 檢驗其效果，希望了解在家庭中共同使用 app 是否能促進健康行為。

#### 使用的方法 / 關注的問題
- **研究方法**：叢集隨機對照試驗（cluster RCT）
- **樣本**：52 個家庭
- **介入方式**：3 週 app 介入，並設 post-test 與 follow-up
- **核心問題**：如何透過家庭共同參與的 mHealth app 改善身體活動與健康飲食

#### 和我的研究的相關性
- 同樣屬於 **數位健康行為介入**
- 也涉及 **遊戲化、JITAI、健康飲食**
- 可作為「健康飲食 app 不只是記錄，也可以有介入機制」的支持文獻

#### 侷限性
- 主要放在家庭共同使用，不是個人 daily companion
- 飲食只是健康行為的一部分，沒有深挖飲食情境中的情緒、罪惡感、折衷決策
- 沒有結合聊天機器人與擬人化角色互動

---

### 4. Digital Interventions Targeting Healthy and Sustainable Eating Behavior: Systematic Review and Meta-Analysis
- **年份 / 場域**：2026 / Journal of Medical Internet Research (JMIR)
- **網址**：https://www.jmir.org/2026/1/e80821
- **DOI**：https://doi.org/10.2196/80821
- **Preprint**：https://preprints.jmir.org/preprint/80821

#### Abstract（中文整理）
這篇系統性回顧與統合分析聚焦在數位介入如何改善更健康且更永續的飲食行為。作者整合非臨床族群中的數位介入研究，關心的不只是健康飲食，也包括增加植物性飲食、降低動物性飲食等永續面向，並試圖找出哪些參與者特徵與介入特徵可能與更好的效果有關。

#### 使用的方法 / 關注的問題
- **研究方法**：systematic review + meta-analysis
- **搜尋資料庫**：Web of Science、Embase、Scopus，並補前後向文獻搜尋
- **納入條件**：準實驗或縱向設計、非臨床族群、數位介入
- **核心問題**：數位介入對健康／永續飲食是否有效，哪些設計特徵比較有效

#### 和我的研究的相關性
- 是很好的「大傘型」背景文獻，可支撐我研究放在 **digital interventions for eating behavior** 這個脈絡
- 提醒我可思考：不同數位媒介、不同行為改變技術，是否影響成效
- 幫助我把系統定位到更大的研究地景中

#### 侷限性
- 偏宏觀文獻整理，不提供具體互動設計細節
- 永續飲食與健康飲食並列，與我主題不完全相同
- 不能直接回答聊天機器人或遊戲化角色在實作上的設計問題

---

### 5. Towards a Data-Driven Approach to Intervention Design: A Predictive Path Model of Healthy Eating Determinants
- **年份 / 場域**：2012 / Persuasive Technology (Springer LNCS, PERSUASIVE 2012)
- **網址**：https://link.springer.com/chapter/10.1007/978-3-642-31037-9_18
- **DOI**：https://doi.org/10.1007/978-3-642-31037-9_18

> 註：先前我曾提到一個較像方向性標題的 Springer 條目；為了確保你放在 GitHub 的版本可以**真正查到正式來源**，我改用這篇同樣非常相關、且更適合引用的 peer-reviewed 文獻。

#### Abstract（中文整理）
這篇研究想了解健康飲食態度受到哪些因素影響，並建立一個能預測健康飲食態度的路徑模型。作者使用 fast food-related eating behavior 作為案例，分析體重關注、營養知識、疾病擔憂、社會影響、食物選擇動機等因素如何共同預測健康飲食態度。

#### 使用的方法 / 關注的問題
- **研究方法**：建立資料導向的預測路徑模型
- **核心問題**：哪些 determinants 會影響健康飲食態度，以及這些因素如何作為後續說服式技術設計的基礎
- **目的**：替未來的健康飲食技術介入提供理論與設計依據

#### 和我的研究的相關性
- 幫助我把系統中的介入策略（例如 If-Then、提醒、補償）連回 **persuasive technology / behavior determinants**
- 很適合當設計理論基礎：不是只做功能，而是回到「哪些因素真正影響健康飲食態度」

#### 侷限性
- 年代較早，不是近年的 AI / chatbot 研究
- 偏理論模型，沒有做完整 app 或互動式系統驗證
- 著重健康飲食態度，而不是日常飲食陪伴或情緒支持

---

## 類別 B：解決不同問題，但方法相似

### 6. Natural Language Processing Chatbot–Based Interventions for Improvement of Diet, Physical Activity, and Tobacco Smoking Behaviors: Systematic Review
- **年份 / 場域**：2025 / JMIR mHealth and uHealth
- **網址**：https://mhealth.jmir.org/2025/1/e66403
- **DOI**：https://doi.org/10.2196/66403

#### Abstract（中文整理）
這篇研究回顧使用自然語言處理（NLP）聊天機器人來改善飲食、身體活動與戒菸行為的隨機對照試驗。作者想知道這類較先進、能以較自由自然語言互動的 chatbot，到底對健康行為改變是否有效，並同時整理使用者與 chatbot 的互動情況與感受。

#### 使用的方法 / 關注的問題
- **研究方法**：systematic review
- **資料來源**：12 個資料庫／登錄系統
- **納入研究**：2010–2024 間使用 NLP chatbot 促進 diet / PA / smoking 的 RCT
- **分析方式**：因研究異質性高，採 narrative synthesis，並用 bubble plot 視覺化結果
- **核心問題**：NLP-chatbot 對健康行為改變是否有效、使用者實際如何使用

#### 和我的研究的相關性
- 與我最直接共享的方法是 **chatbot-based health behavior intervention**
- 可幫我支持：chatbot 不只是問答介面，也可能扮演健康促進的中介工具
- 因為它也包含 diet，所以和我系統不是完全不同問題，而是更廣義的健康行為情境

#### 侷限性
- 研究結果指出對 diet 與 PA 的效果仍不一致，證據不如戒菸穩定
- 聚焦 NLP chatbot 效果回顧，沒有深入討論多模態、情緒角色或遊戲化設計
- 無法直接告訴我什麼樣的對話設計最適合飲食陪伴

---

### 7. The Development and Use of AI Chatbots for Health Behavior Change: Scoping Review
- **年份 / 場域**：2026 / Journal of Medical Internet Research (JMIR)
- **網址**：https://www.jmir.org/2026/1/e79677
- **DOI**：https://doi.org/10.2196/79677

#### Abstract（中文整理）
這篇範疇回顧想提供一個最新、可操作的總覽，說明文字型 AI chatbot 如何被設計、開發與評估，用於 8 類健康行為改變。研究整理了 chatbot 角色（例如 routine coach、on-demand assistant）、理論基礎（例如 CBT）、行為改變技術（BCTs）、技術流程，以及常用的評估面向。

#### 使用的方法 / 關注的問題
- **研究方法**：scoping review（PRISMA-ScR）
- **搜尋資料庫**：9 個資料庫，包括 PubMed、Embase、Scopus、IEEE Xplore、ACM DL 等
- **品質評估**：Mixed Methods Appraisal Tool (MMAT)
- **核心問題**：AI chatbot 如何設計、扮演什麼角色、用哪些理論／技術、如何評估

#### 和我的研究的相關性
- 這篇很適合當我的**方法論支撐**
- 可幫我定義：我的 chatbot 是 routine companion、on-demand assistant，還是混合型
- 也能幫我補強 evaluation framework：技術、行為、可用性、參與度、成本

#### 侷限性
- 是範疇回顧，不是針對飲食場景的具體設計研究
- 涵蓋範圍廣，因此無法深入單一領域（例如 emotional eating）
- 比較像 roadmap，不能直接取代系統設計細節

---

### 8. Effectiveness of AI-Driven Conversational Agents in Improving Mental Health Among Young People: Systematic Review and Meta-Analysis
- **年份 / 場域**：2025 / Journal of Medical Internet Research (JMIR)
- **網址**：https://www.jmir.org/2025/1/e69639
- **DOI**：https://doi.org/10.2196/69639
- **Preprint**：https://preprints.jmir.org/preprint/69639

#### Abstract（中文整理）
這篇研究聚焦在 AI-driven conversational agents（CA）是否能改善 12–25 歲年輕人的心理健康，特別是憂鬱與焦慮。作者透過系統性回顧與統合分析，評估 AI 對話代理人在不同族群、不同平台、不同互動模式下的效果，並探索影響成效的可能調節因素。

#### 使用的方法 / 關注的問題
- **研究方法**：systematic review + meta-analysis
- **搜尋資料庫**：PubMed、PsycINFO、EMBASE、Cochrane Library、Web of Science
- **納入研究**：14 篇文章、15 個 RCT
- **核心問題**：AI-driven CAs 對青少年與年輕族群的憂鬱、焦慮等心理健康症狀是否有效

#### 和我的研究的相關性
- 雖然它主要處理的是心理健康，而不是飲食，但方法上很像我的 **對話式 AI 支持系統**
- 我可以借這篇支撐「AI 對話代理人在年輕族群中有潛力扮演日常支持角色」
- 對我的 monster + chatbot 陪伴設計也有理論參照價值

#### 侷限性
- 問題域是心理健康，不是飲食決策
- 成效主要出現在憂鬱症狀，其他指標較不穩定
- 沒有處理飲食記錄、營養反饋或日常飲食選擇等問題

---

### 9. Generative AI Mental Health Chatbots as Therapeutic Tools: Systematic Review and Meta-Analysis of Their Role in Reducing Mental Health Issues
- **年份 / 場域**：2025 / Journal of Medical Internet Research (JMIR)
- **網址**：https://www.jmir.org/2025/1/e78238
- **DOI**：https://doi.org/10.2196/78238
- **Preprint**：https://preprints.jmir.org/preprint/78238

#### Abstract（中文整理）
這篇研究是針對生成式 AI（GenAI）心理健康聊天機器人的系統性回顧與統合分析。作者想整理現有 GenAI chatbots 的技術特徵、治療設計、研究方法與樣本情況，並透過 RCT 的統合分析量化其對心理健康問題的影響，同時檢查設計、族群、情境與 outcome 類型等調節變項。

#### 使用的方法 / 關注的問題
- **研究方法**：systematic review + meta-analysis
- **納入研究**：26 篇敘述性整合，14 個 RCT 進入 meta-analysis
- **核心問題**：GenAI chatbot 作為治療工具在心理健康上的效果如何，哪些設計條件可能影響成效

#### 和我的研究的相關性
- 這篇和我一樣觸及 **生成式 AI chatbot** 的設計與效果
- 對我來說很有價值的是：它整理了設計層面的 moderator，例如聊天機器人的任務定位、社交性、研究情境
- 可幫助我思考：飲食 chatbot 應該更像 coach、companion，還是 hybrid agent

#### 侷限性
- 專注於心理健康治療，不是日常飲食或健康行為選擇
- 比較少觸及與實體行為記錄（如 food logging）整合的系統
- 不能直接回答「聊天機器人如何與飲食 app 的其他模組互補」

---

### 10. The Effectiveness of AI Chatbots in Alleviating Mental Distress and Promoting Health Behaviors Among Adolescents and Young Adults: Systematic Review and Meta-Analysis
- **年份 / 場域**：2025 / Journal of Medical Internet Research (JMIR)
- **網址**：https://www.jmir.org/2025/1/e79850
- **DOI**：https://doi.org/10.2196/79850
- **Preprint**：https://preprints.jmir.org/preprint/79850

#### Abstract（中文整理）
這篇研究想統整 AI chatbot 對青少年與年輕成年人在兩方面的效果：一是降低心理困擾，二是促進健康行為。作者納入 RCT，分析 AI chatbot 對 mental distress 與 health behavior outcomes 的整體影響，並觀察不同研究設計與族群條件下的差異。

#### 使用的方法 / 關注的問題
- **研究方法**：systematic review + meta-analysis
- **納入研究**：31 個 RCT、近三萬名參與者
- **核心問題**：AI chatbot 是否能同時對情緒困擾與健康行為改變產生效果

#### 和我的研究的相關性
- 這篇與我的系統有很強的方法相似性，因為我的設計也想處理**情緒支持 + 健康行為改變**
- 可以支撐我主張：聊天機器人不一定只能做資訊查詢，也可能介入情緒與行為層面
- 很適合放在「不同問題但方法相似」的 related work 中

#### 侷限性
- 健康行為是廣義概念，並不聚焦飲食這個特定情境
- 研究對象是 adolescents and young adults，和我的目標族群若不同，外推需小心
- 仍然無法直接說明多模態記錄、monster 角色或 If-Then 卡牌是否能提升效果

---

## 可直接寫進 related work 的總結

### 類別 A：相似問題、不同方法
這一組文獻多半聚焦在**健康飲食、飲食相關介入、food journaling**，但方法與我的系統不同。  
有些研究採用 **臨床聊天機器人單次介入**（e70874），有些聚焦於 **對話式飲食記錄設計探索**（Foody Talk），也有 **家庭情境中的 mHealth app**（SMARTFAMILY2.0），或更宏觀的 **數位飲食介入綜述**（e80821）。這些研究有助於說明：飲食科技不再只是 calorie logging，而是逐漸朝互動支持、情境介入、與更廣泛行為改變設計前進。然而，它們通常只涵蓋其中一部分，較少像我的系統一樣，把**飲食記錄、情緒陪伴、If-Then 行為介入、遊戲化角色與聊天代理人**整合在同一個體驗中。

### 類別 B：不同問題、相似方法
這一組文獻主要聚焦在 **AI chatbot / conversational agent / health behavior change / mental health support**。  
它們不一定處理飲食，但在方法上和我的系統相近，例如使用 **聊天機器人作為健康促進工具**（e66403、e79677），或分析 **AI 對話代理人對心理困擾與健康行為的效果**（e69639、e78238、e79850）。這些文獻能支撐我在方法上的合理性：對話代理人不只是資訊傳遞介面，也可以是陪伴、提醒、動機維持與行為引導的媒介。不過，這些研究多半缺少與**具體飲食紀錄、遊戲化回饋角色、或即時折衷飲食建議**的深度整合。

---

## 建議你接下來怎麼用這份整理
1. **寫報告時**：每類挑 2–3 篇代表性文獻詳細寫，其餘放表格。  
2. **做簡報時**：用「同問題／不同方法」與「不同問題／同方法」兩欄呈現。  
3. **接你的系統貢獻時**：強調你的獨特點是  
   - 非卡路里中心  
   - If-Then 行為介入  
   - monster 的情緒回饋  
   - chatbot 與記錄系統整合  
4. **若老師追問影響力**：可以優先點 CHI、JMIR、systematic review / meta-analysis、RCT 這些高可信來源。

# 目標工作流程 3／3：文件、比價與 ERP

[← 上一頁：郵件承接與 RFQ](02_郵件承接與RFQ.md) ｜ [返回規格書 →](../承析國際_AI_Agent規格書.md)

```mermaid
%%{init: {"theme":"base", "flowchart":{"nodeSpacing":50,"rankSpacing":70}, "themeVariables":{"fontSize":"20px"}}}%%
flowchart LR
  A["A4<br/>文件擷取、引用與缺漏"] --> B["A6<br/>供應商報價比較"]
  B --> C["A5<br/>貿易文件核對與 ERP 草稿"]
  C --> D{"貿易人員核准"}
  D -->|核准後執行| E["ERP／報關正式流程"]

  classDef agent fill:#E8F3FF,stroke:#1677FF,stroke-width:3px,color:#102A43,font-size:20px;
  classDef human fill:#FFF4D6,stroke:#D48806,stroke-width:3px,color:#5C3B00,font-size:20px;
  classDef result fill:#EAF7EA,stroke:#389E0D,stroke-width:3px,color:#193D0D,font-size:20px;
  class A,B,C agent;
  class D human;
  class E result;
```

本頁結果：AI 只整理、比對並建立 ERP 草稿；正式 ERP 寫入與報關仍由有權限的人員核准執行。

[← 上一頁：郵件承接與 RFQ](02_郵件承接與RFQ.md) ｜ [返回規格書 →](../承析國際_AI_Agent規格書.md)

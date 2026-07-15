# 目標工作流程 2／3：郵件承接與 RFQ

[← 上一頁：前段業務開發](01_前段業務開發.md) ｜ [下一頁：文件與 ERP →](03_文件與ERP.md)

```mermaid
%%{init: {"theme":"base", "flowchart":{"nodeSpacing":55,"rankSpacing":70}, "themeVariables":{"fontSize":"20px"}}}%%
flowchart LR
  A["核准後寄出<br/>公司郵箱"] --> B["客戶來信事件"]
  B --> C["A3<br/>分類、翻譯、回覆草稿"]
  C --> D{"業務接手"}
  D --> E["建立商機／RFQ 案件"]

  classDef event fill:#F5F5F5,stroke:#666,stroke-width:2px,color:#222,font-size:20px;
  classDef agent fill:#E8F3FF,stroke:#1677FF,stroke-width:3px,color:#102A43,font-size:20px;
  classDef human fill:#FFF4D6,stroke:#D48806,stroke-width:3px,color:#5C3B00,font-size:20px;
  classDef result fill:#EAF7EA,stroke:#389E0D,stroke-width:3px,color:#193D0D,font-size:20px;
  class A,B event;
  class C agent;
  class D human;
  class E result;
```

本頁結果：Agent 將回覆分流並準備雙語草稿；業務確認有商機後才建立 RFQ 案件並進入文件流程。

[← 上一頁：前段業務開發](01_前段業務開發.md) ｜ [下一頁：文件與 ERP →](03_文件與ERP.md)

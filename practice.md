---
title: practice
author: Scotty
date: 2024-11-11
category: stats
layout: post
---
> ##### TIP
>
> This guide is last tested with @napi-rs/canvas^0.1.20, so make sure you have
> this or a similar version after installation.
{: .block-tip }

> ##### TIP
>
> This guide is last tested with @napi-rs/canvas^0.1.20, so make sure you have
> this or a similar version after installation.
{: .block-tip }
>
> 
```markdown
---
title: Diagrams with mermaid.js
date: 2023-08-31
layout: post
mermaid: true
---
```

Then you can use mermaid syntax in your markdown:

```mermaid
graph LR
  X[독립변수 X] --> M[매개변수 M] --> Y[종속변수 Y]
  X --> Y

```

```mermaid
graph TD
  X[독립변수 X] --> Y[종속변수 Y]
  Z[조절변수 Z] -.-> Y
  Z -.-> X
```

```mermaid
flowchart LR
    A-->|의존|B
```

```mermaid
graph LR
  %% 측정 모델 (Measurement Model)
  x[Latent Variable: x] --> x1[x1]
  x --> x2[x2]
  x --> x3[x3]

  z[Latent Variable: z] --> z1[z1]
  z --> z2[z2]
  z --> z3[z3]
  z --> z4[z4]

  y[Latent Variable: y] --> y1[y1]
  y --> y2[y2]

  mo[Latent Variable: mo] --> mo1[mo1]
  mo --> mo2[mo2]
  mo --> mo3[mo3]
  mo --> mo4[mo4]

  me[Latent Variable: me] --> me1[me1]
  me --> me2[me2]
  me --> me3[me3]

  %% 조절 효과 (Interaction Effect)
  x_mo[Interaction: x_mo] --> x1.mo1[x1.mo1]
  x_mo --> x1.mo2[x1.mo2]
  x_mo --> x1.mo3[x1.mo3]
  x_mo --> x1.mo4[x1.mo4]
  
  x_mo --> x2.mo1[x2.mo1]
  x_mo --> x2.mo2[x2.mo2]
  x_mo --> x2.mo3[x2.mo3]
  x_mo --> x2.mo4[x2.mo4]
  
  x_mo --> x3.mo1[x3.mo1]
  x_mo --> x3.mo2[x3.mo2]
  x_mo --> x3.mo3[x3.mo3]
  x_mo --> x3.mo4[x3.mo4]

  %% 경로 모형 (Path Model)
  y -->|Regression| x
  y -->|Regression| z
  y -->|Regression| me
  y -->|Regression| mo
  y -->|Regression| x_mo
  me -->|Regression| x
  ```


```mermaid
graph TD
  A[변수 유형] --> B[단일 변수 분석]
  A --> C[두 변수 간 분석]
  A --> D[다중 변수 분석]

  B --> B1[연속형]
  B1 --> B1a[평균]
  B1 --> B1b[표준편차]
  B1 --> B1c[정규성 검정]

  B --> B2[범주형]
  B2 --> B2a[빈도분석]
  B2 --> B2b[카이제곱 검정]

  C --> C1[연속형 vs. 연속형]
  C1 --> C1a[상관분석]
  C1 --> C1b[회귀분석]

  C --> C2[연속형 vs. 범주형]
  C2 --> C2a[t-검정]
  C2 --> C2b[ANOVA]

  C --> C3[범주형 vs. 범주형]
  C3 --> C3a[카이제곱 검정]
  C3 --> C3b[피셔의 정확 검정]

  D --> D1[회귀 분석]
  D1 --> D1a[다중선형 회귀]
  D1 --> D1b[로지스틱 회귀]

  D --> D2[요인 분석]
  D2 --> D2a[EFA]
  D2 --> D2b[CFA]

  D --> D3[군집 분석]
  D3 --> D3a[K-means]
  D3 --> D3b[계층적 군집]

  D --> D4[분산분석]
  D4 --> D4a[ANOVA]
  D4 --> D4b[MANOVA]

  D --> D5[기타 다변량 기법]
  D5 --> D5a[PCA]
  D5 --> D5b[SEM]
```

```mermaid
graph LR
  A[변수 유형] --> B[단일 변수 분석]
  A --> C[두 변수 간 분석]
  A --> D[다중 변수 분석]

  B --> B1[연속형]
  B1 --> B1a[평균]
  B1 --> B1b[표준편차]
  B1 --> B1c[정규성 검정]

  B --> B2[범주형]
  B2 --> B2a[빈도분석]
  B2 --> B2b[카이제곱 검정]

  C --> C1[연속형 vs. 연속형]
  C1 --> C1a[상관분석]
  C1 --> C1b[회귀분석]

  C --> C2[연속형 vs. 범주형]
  C2 --> C2a[t-검정]
  C2 --> C2b[ANOVA]

  C --> C3[범주형 vs. 범주형]
  C3 --> C3a[카이제곱 검정]
  C3 --> C3b[피셔의 정확 검정]

  D --> D1[회귀 분석]
  D1 --> D1a[다중선형 회귀]
  D1 --> D1b[로지스틱 회귀]

  D --> D2[요인 분석]
  D2 --> D2a[EFA]
  D2 --> D2b[CFA]

  D --> D3[군집 분석]
  D3 --> D3a[K-means]
  D3 --> D3b[계층적 군집]

  D --> D4[분산분석]
  D4 --> D4a[ANOVA]
  D4 --> D4b[MANOVA]

  D --> D5[기타 다변량 기법]
  D5 --> D5a[PCA]
  D5 --> D5b[SEM]
```
```mermaid
graph LR
  A[독립 변수 X] -->|가설| B[종속 변수 Y]
  B -->|영향| C[매개 변수 M]
  A -->|간접 효과| C

  subgraph SEM 모델
    direction TB
    A
    B
    C
  end

  style A fill:#f9f,stroke:#333,stroke-width:2px
  style B fill:#f9f,stroke:#333,stroke-width:2px
  style C fill:#f9f,stroke:#333,stroke-width:2px
```

```mermaid
graph LR
  A[독립 변수 X] -->|가설| B[종속 변수 Y]
  B -->|영향| C[매개 변수 M]
  A -->|간접 효과| C

  subgraph SEM 모델
    direction LR
    A
    B
    C
  end

  style A fill:#f9f,stroke:#333,stroke-width:2px
  style B fill:#f9f,stroke:#333,stroke-width:2px
  style C fill:#f9f,stroke:#333,stroke-width:2px
```
```mermaid
graph LR
  A[독립 변수 X] -->|가설| B[매개 변수 M]
  B -->|영향| C[종속 변수 Y]
  A -->|간접 효과| C

  subgraph SEM 모델
    direction LR
    A
    B
    C
  end

  style A fill:#f9f,stroke:#333,stroke-width:2px
  style B fill:#f9f,stroke:#333,stroke-width:2px
  style C fill:#f9f,stroke:#333,stroke-width:2px
```

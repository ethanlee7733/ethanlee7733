flowchart TD
    A[재활용품 수집] --> B[계량]
    B --> C[분류/처리]
    C --> D[재활용품 판매]
    A --> E[수집량 기록]
    B --> F[중량 측정]
    C --> G[에너지 사용량 측정]
    D --> H[판매량 기록]
    E & F & G & H --> I[데이터 취합 및 분석]
    I --> J[온실가스 감축량 산정]
    
    style A fill:#f9f,stroke:#333,stroke-width:2px
    style B fill:#fcf,stroke:#333,stroke-width:2px
    style C fill:#cff,stroke:#333,stroke-width:2px
    style D fill:#ffc,stroke:#333,stroke-width:2px
    style I fill:#dfd,stroke:#333,stroke-width:4px
    style J fill:#f96,stroke:#333,stroke-width:4px

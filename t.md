```mermaid
graph TD
    A[メインフォーム<br/>勤怠システム] --> B[上部エリア<br/>━━━━━━━━━━━━━━━━━<br/>📅 2024/08/26 15:30:45<br/>━━━━━━━━━━━━━━━━━<br/> 出勤 |  退勤<br/>━━━━━━━━━━━━━━━━━]
    
    B --> C[メインパネル<br/>UserControl表示エリア]
    
    C --> D[初期画面<br/>AttendanceUserControl]
    C --> E[勤務者画面<br/>EmployeeUserControl]
    C --> F[管理者画面<br/>AdminUserControl]
    
    A --> G[下部エリア<br/>━━━━━━━━━━━━━━━━━<br/> 勤務者 |  管理者<br/>━━━━━━━━━━━━━━━━━]
    
    G --> H[勤務者ボタン押下]
    G --> I[管理者ボタン押下]
    
    H --> E
    I --> F
    
    D --> J[初期画面内容<br/>・今日の出退勤状況<br/>・お知らせ<br/>・勤務時間表示]
    
    E --> K[勤務者画面内容<br/>・出退勤履歴<br/>・月間勤務時間<br/>・有給残日数<br/>・シフト確認]
    
    F --> L[管理者画面内容<br/>・全員出退勤状況<br/>・勤務時間集計<br/>・シフト管理<br/>・設定]
    
    style A fill:#e1f5fe
    style B fill:#fff3e0
    style C fill:#f3e5f5
    style D fill:#e8f5e8
    style E fill:#fff9c4
    style F fill:#ffebee
    style G fill:#fff3e0
```
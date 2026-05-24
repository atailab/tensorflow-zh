graph TB
    subgraph 数据层
        A1[多源异构科研数据]
        A2[论文<br>专利<br>技术方案<br>产品说明书<br>科研项目]
    end

    subgraph 研究内容三：科研时空关联网络构建与多粒度演化分析
        B1[3.1 多源异构科研实体对齐<br>与关联图谱构建]
        B2[3.2 多层时序网络动态构建<br>与演化轨迹建模]
        B3[3.3 多粒度网络自适应聚合<br>与跨层级联动分析]
    end

    subgraph 核心技术
        C1[大语言模型实体抽取<br>图神经网络拓扑约束<br>科研关联图谱]
        C2[自适应时间窗<br>时序图神经网络<br>跨层演化模式挖掘]
        C3[层级隶属映射<br>注意力聚合算子<br>反事实因果推断]
    end

    subgraph 输出层
        D1[科研态势全景感知]
        D2[隐含关联时序发现]
        D3[创新演化趋势推演]
        D4[多粒度价值评估]
    end

    A1 --> A2
    A2 --> B1
    B1 -->|“数据融合”| B2
    B2 -->|“时序建模”| B3
    B3 -->|“多粒度聚合”| D1
    B3 --> D2
    B3 --> D3
    B3 --> D4

    B1 -.-> C1
    B2 -.-> C2
    B3 -.-> C3

    style B1 fill:#e6f3ff,stroke:#0066cc,stroke-width:2px
    style B2 fill:#e6f3ff,stroke:#0066cc,stroke-width:2px
    style B3 fill:#e6f3ff,stroke:#0066cc,stroke-width:2px
    style D1 fill:#d4edda,stroke:#28a745,stroke-width:2px
    style D2 fill:#d4edda,stroke:#28a745,stroke-width:2px
    style D3 fill:#d4edda,stroke:#28a745,stroke-width:2px
    style D4 fill:#d4edda,stroke:#28a745,stroke-width:2px

# K-FDO Technical Specification v1.0
# K-FDO 技术规范 v1.0 (草案)

### Abstract / 摘要
**EN:** Traditional robotics data lacks "Agency." K-FDO treats robot actions as living digital entities with a "Metabolic Rate" and "Logic Purity."
**中：** 传统的机器人数据缺乏“代理权”。K-FDO 将机器人动作视为具有“代谢率”和“逻辑纯度”的活性数字实体。

### Key Metadata Fields / 关键元数据字段
| Field / 字段 | Type / 类型 | Description / 描述 |
| :--- | :--- | :--- |
| `sovereignty_id` | PID/Handle | The unique identity of the action creator. / 动作创建者的唯一身份标识。 |
| `logic_purity` | Float | Percentage of logic decoupled from raw data. / 逻辑从原始数据中解耦的比例。 |
| `metabolic_rate` | Frequency | How often the object updates its internal logic. / 对象更新其内部逻辑的频率。 |

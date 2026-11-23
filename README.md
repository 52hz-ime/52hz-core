# 52Hz Core

52Hz 的平台无关输入运行时和核心引擎。

## 负责内容

- 输入会话和组合态
- 上下文快照
- `DeviceProfile` 和设备错误模型接口
- 推理请求调度和取消
- Model Provider 抽象
- 候选、置信度、提交和撤销
- 模型输出校验

## 不负责内容

- Fcitx5、Windows TSF 或 macOS InputMethodKit 集成
- 具体 LLM 训练
- 平台相关候选窗口绘制
- 云端账号和模型分发

## 状态

项目处于接口和运行时设计阶段。

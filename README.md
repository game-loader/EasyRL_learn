# EasyRL 强化学习算法实现

本项目是对 EasyRL 教程中强化学习算法的代码重新实现，使用了更新的 Gymnasium 库替代旧版的 gym。

## 快速开始

### 安装依赖
```bash
uv sync
```

### 运行项目
```bash
# 使用 Jupyter Notebook（推荐）
jupyter lab DQN.ipynb

# 或者直接运行 Python 脚本
python main.py
```

## 项目说明

- 基于 PyTorch 的强化学习算法实现
- 使用 Gymnasium API（适配新版环境接口）
- 目前包含 DQN 算法实现
- 包含完整的训练、测试和可视化功能
- 支持训练过程的视频录制

## 已实现算法

- [x] **DQN (Deep Q-Network)** - 深度 Q 网络
- [ ] 更多算法持续更新中...

## References

- EasyRL 教程：https://datawhalechina.github.io/easy-rl/
- DeepMind DQN 论文：https://www.nature.com/articles/nature14236

## License

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件。
# Calicath.github.io
个人项目作品集
### 项目1：基于区块链的数字病历存证系统
- 仓库地址：[跳转项目](https://github.com/Calicath/blockchain_medical.git)
- 技术栈：
- 前端：React + TypeScript + Tailwind CSS
- 区块链：Hardhat + Solidity
- Web3：ethers.js
- 项目简介：
  基于区块链智能合约的医疗病历存证和医保发票验证系统。
- ✅ 实现功能：3种身份注册、病历上链、权限控制、授权查看病历
- ✅ 合约编译部署：Hardhat编译Solidity合约，通过脚本部署到本地测试网络
- ✅ 前端页面：Web前端连接MetaMask钱包，调用智能合约读写链上病历数据
- 运行方式：README内包含环境配置、合约编译部署、前端启动完整步骤


### 项目2：Java Web房屋租赁管理系统
- 仓库地址：[跳转项目](https://github.com/Calicath/house_rent.git)
- 技术栈：Java Servlet + Tomcat + MySQL + JSP + Maven
- 项目简介：
  基于MySQL的房屋租赁管理系统。
- ✅ 实现功能：支持管理员、房东、租客三类角色，覆盖房源发布、搜索看房、租赁交易、支付记录和交流论坛。
- ✅ 数据库：MySQL，提供完整数据库初始化SQL脚本
- ✅ 配套启动脚本，一键初始化数据库与Tomcat服务

### 项目3：基于深度学习的番茄病害识别系统
- 仓库地址：[跳转项目](https://github.com/Calicath/Tomato_Disease_Diagnosis.git)
- 技术栈：
  - 深度学习：TensorFlow + Keras + ResNet50
  - 图像处理：Pillow + OpenCV
  - Web交互：Gradio
  - 开发环境：Python + Virtual Environment
- 项目简介：
  基于深度学习图像分类模型的番茄叶片病害智能识别系统，实现对番茄叶片图像的自动分类与病害辅助诊断。
- ✅ 数据集处理：使用番茄叶片病害图像数据集，包含10类叶片状态，通过数据预处理、图像标准化等方式构建训练数据。
- ✅ 模型训练：基于ResNet50卷积神经网络进行迁移学习，完成模型训练、验证与保存，支持10类别病害识别。
- ✅ 模型部署：将训练完成的TensorFlow SavedModel模型部署到Web应用中，通过TFSMLayer调用深度学习模型进行实时预测。
- ✅ Web前端：基于Gradio搭建交互界面，支持用户上传叶片图片，并返回Top-3预测类别及对应置信度。
- ✅ 预测展示：实现图片预览、病害类别识别、概率可视化展示，提高模型使用的交互体验。
- 运行方式：README内包含环境配置、模型加载、依赖安装及Gradio服务启动完整步骤。

## 🛠 技能栈
编程语言：Java、Python、Solidity、TypeScript、SQL
数据分析与人工智能：
- TensorFlow、Keras、ResNet50
- NumPy、Pillow
- 数据清洗、数据分析、模型评估
数据可视化：
- Matplotlib、Seaborn
- 混淆矩阵可视化
- 分类结果分析
- 训练过程曲线绘制
- Grad-CAM模型解释可视化
框架工具：
- Gradio、Hardhat、Maven、Git
数据库与开发环境：
- MySQL、Tomcat、Vite

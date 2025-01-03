# CipherBridge - 可验证多方密文计算平台

- [查看PPT](https://gamma.app/docs/CipherBridge-dniu5htoqmm9qsb)
- [查看Demo视频(youtube)](https://youtu.be/8dlMbBVCjTc)
- [查看Demo视频(bilibili)](https://www.bilibili.com/video/BV13ZqnYLEMy/)
- [运行项目](#相关代码仓库)

## 项目概述

CipherBridge是一个基于零知识证明和全同态加密(zkFHE)技术的可验证多方密文计算平台。平台采用TFHE-rs实现高效的全同态加密计算，使用RISC Zero提供计算可验证性，并基于FISCO BCOS区块链构建信任基础设施，致力于解决数据安全共享和隐私保护下进行可信复杂计算的难题。

## 项目背景与愿景

随着数字经济的蓬勃发展，数据已成为关键生产要素。然而，数据确权、隐私保护等问题日益凸显，成为数据要素市场培育和数据流通共享的主要障碍。CipherBridge应运而生，致力于通过技术创新破解数据共享难题，推动数据要素市场化发展和多方数据共同计算。

作为国内**首个**基于zkFHE的多方密文计算平台，CipherBridge巧妙融合了全同态加密、零知识证明和区块链技术，构建了一套完整的隐私计算解决方案。平台采用TFHE-rs实现高效的全同态加密运算，通过RISC Zero提供可信的计算验证机制，并基于FISCO BCOS区块链打造可靠的信任基础设施。

## 技术创新与架构设计

CipherBridge的技术创新主要体现在三个方面。首先，在全同态加密领域，平台基于TFHE-rs实现了高效的密文计算能力，支持在不泄露原始数据的情况下进行复杂的数据分析和处理。这使得数据在保持加密状态的同时仍然可以发挥其价值。

其次，在可验证计算方面，平台创新性地采用RISC Zero零知识证明技术，为密文计算提供了可信保障。通过生成零知识证明，可以验证计算过程或结果的正确性和合规性，同时不泄露任何额外信息。这一机制有效防范了在多方计算和数据共享中的恶意行为，提升了多方协作的可信度。

在系统架构上，CipherBridge采用前后端分离的微服务设计，将核心功能模块化封装。前端提供直观的用户交互界面，后端负责复杂的密文计算和证明生成，而区块链层则提供底层的信任支撑。这种架构既保证了系统的可扩展性，也便于持续优化和升级。

## 应用场景

在金融领域，CipherBridge为普惠金融服务提供了创新解决方案。传统金融服务中，机构间的数据壁垒导致信用评估维度不足，风控效果受限。通过CipherBridge平台，各金融机构可以在保护客户隐私的前提下，实现数据的安全协同，提供更精准的信用评估和风险控制。

医疗健康领域是另一个重要应用方向。医疗数据的敏感性和机构间协作的必要性一直是个两难问题。CipherBridge通过全同态加密技术，让医疗机构能够在确保患者隐私的同时开展跨机构的医疗研究和协作诊疗，推动医疗资源的优化配置和服务水平的提升。

在政务服务创新方面，平台帮助突破了部门间数据共享的障碍。通过可验证的密文计算，各政务部门可以在确保数据安全的前提下开展深度协作，提升政务服务效率，实现更智能的社会治理。

## 核心特性

### 1. 隐私数据保护
- 采用全同态加密技术加密敏感数据
- 数据全程保持密文状态
- 确保原始数据不出本地

### 2. 可验证计算
- 通过RISC Zero生成零知识证明
- 验证密文间计算过程
- 确保密文结果解密过程可信

### 3. 区块链支持
- 基于FISCO BCOS提供信任基础设施
- 实现链上密文数据和身份管理
- 支持全流程可追溯审计

## 技术架构

### 关键组件
1. **前端交互界面**
   - 用户客户端
   - 机构客户端

2. **隐私计算后端**
   - TFHE-rs全同态加密组件
   - RISC Zero零知识证明系统

3. **区块链基础设施**
   - 数据管理模块
   - 权限控制系统
   - 任务管理系统
  
## 相关代码仓库
### CipherBridge智能合约：
https://github.com/JupiterXiaoxiaoYu/FHE-Protocol

### CipherBridge全同态加密服务端：
https://github.com/JupiterXiaoxiaoYu/FHE-API

### CipherBridge全同态加密服务端（ZK Branch）
https://github.com/JupiterXiaoxiaoYu/FHE-API/tree/zkpok

### CipherBridge前端：
https://github.com/JupiterXiaoxiaoYu/FHE-Frontend

### CipherBridge具体FISCO BCOS配置：
https://github.com/JupiterXiaoxiaoYu/FHE-FiscoBcos

### CipherBridge零知识解密证明 (ZK for Decryption):
https://github.com/JupiterXiaoxiaoYu/zkFHE-Decryption-Proof

### CipherBridge零知识全同态加密计算过程证明:
https://github.com/JupiterXiaoxiaoYu/ZK-Compuation-Proof

## 项目团队
- 香港科技大学（广州）数据科学与分析学域：余晓霄 硕士研究生 —— 导师 唐靖 助理教授 
- 香港科技大学（广州）金融科技学域：曹懿月 博士研究生 —— 导师 王雪超 助理教授 


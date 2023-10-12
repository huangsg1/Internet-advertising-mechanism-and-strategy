# Internet Advertising Strategy(计算广告机制策略)
This is a collection of research and application papers about Mechanism and Strategy in Advertising. These works are summarized from the public website. If any authors do not want their paper to be listed here, please feel free to contact me（hsg01993@gmail.com; wechat: coder_hh）.

## 1. 客户策略
### 1.1 出价策略
#### （1）Target-x系列（含ocpx）
- [中文：公众号文章](https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzU2MDE5MzA2Ng==&action=getalbum&album_id=1362906257140858882&scene=173&from_msgid=2247485036&from_itemidx=1&count=3&nolastread=1#wechat_redirect)

#### （2）Nobid系列（或auto-bidding）
- [论文：BCB](https://arxiv.org/abs/1802.08365)
- [中文：USCB](https://zhuanlan.zhihu.com/p/415040447)
- [A Cooperative-Competitive Multi-Agent Framework for Auto-bidding in Online Advertising.](https://arxiv.org/abs/2106.06224) by Chao Wen et al. WSDM 2022. (Alibaba Group)
- [Bid Optimization by Multivariable Control in Display Advertising.](https://arxiv.org/abs/1905.10928) by XunYang et al. KDD 2019. (Alibaba Group) [中文参考1](https://wulc.me/2020/07/19/%E3%80%8ABid%20Optimization%20by%20Multivariable%20Control%20in%20Display%20Advertising%E3%80%8B%E9%98%85%E8%AF%BB%E7%AC%94%E8%AE%B0/), [中文参考2](https://www.arvinzyy.cn/2022/06/06/Bid-Optimization-by-Multivariable-Control-in-Display-Advertising/)
- [Budget Constrained Bidding by Model-free Reinforcement Learning in Display Advertising.](https://arxiv.org/abs/1802.08365) by DiWu et al. CIKM 2018. (Alibaba Group)
- [小红书智能出价](https://mp.weixin.qq.com/s/zRTEQ-1PB2epnZsLE5_qMg)

#### (3) Lift-based Bidding系列
- [中文：lift-based bidding](https://zhuanlan.zhihu.com/p/24801130)
- [Unbiased Lift-based Bidding System](https://arxiv.org/pdf/2007.04002.pdf)
- [A Real-World Implementation of Unbiased Lift-based Bidding System](https://arxiv.org/abs/2202.13868)


### 1.2 广告主工具
#### （1）成效预估
- [A Unified Framework for Campaign Performance Forecasting in
Online Display Advertising](https://arxiv.org/pdf/2202.11877v1.pdf) by 安之

### 1.3 广告主建模及客户增长
- [Leaving No One Behind: A Multi-Scenario Multi-Task Meta Learning Approach for Advertiser Modeling.]() by Xiaocong Chen et al. WSDM 2022.  (Alibaba Group) 

### 1.4 优惠券设计（Coupon Design）
- [Coupon Design in Advertising Systems](https://www.weiran-shen.info/swr_page_files/coupon_design_in_advertising_systems.pdf). by Weiran Shen et al. AAAI 2021.
- [Learning to Design Coupons in Online Advertising Markets](http://ifaamas.org/Proceedings/aamas2020/pdfs/p1242.pdf). by Weiran Shen et al. AAMAS 2020.

### 1.5 预算平滑/控制（Pacing）


## 2. 平台策略
### 2.1 竞价机制
#### （1）经典竞价机制
- GFP/GSP/VCG
- uGSP
#### （2）多目标优化平台机制
- DeepGSP:[Optimizing Multiple Performance Metrics with Deep GSP Auctions for E-commerce Advertising](https://arxiv.org/abs/2012.02930). by Zhilin Zhang et al. (Alibaba Group) [中文版链接](https://zhuanlan.zhihu.com/p/483201989)
- Neural Auction: [End-to-End Learning of Auction Mechanisms for E-Commerce Advertising](https://arxiv.org/abs/2106.03593?spm=ata.21736010.0.0.4e9c7536qSQxJQ&file=2106.03593). by Xiangyu Liu et al. KDD 2021. (Alibaba Group) [中文版链接](https://zhuanlan.zhihu.com/p/412872425)  
- Two-stage Auction: [On Designing a Two-stage Auction for Online Advertising](https://arxiv.org/abs/2111.05555). by Yiqing Wang et al. WWW 2022. (Alibaba Group) [中文版链接](https://zhuanlan.zhihu.com/p/502537787) 

### 2.2 序列化投放（Sequential Advertising）
- [Dynamic Knapsack Optimization Towards Efficient Multi-Channel Sequential Advertising](https://arxiv.org/abs/2006.16312) by Xiaotian Hao et al. ICML 2020. (Alibaba Group)
- [Learning to Infer User Hidden States for Online Sequential Advertising](https://arxiv.org/abs/2009.01453) by Zhaoqing Peng et al. CIKM 2020. (Alibaba Group)

### 2.3 合约广告（Guaranteed Advertising ）
- [An Adaptive Unified Allocation Framework for Guaranteed Display Advertising](). by ** et al. WSDM 2022. (Alibaba Group)

## 3. 流量策略


---
以下汇总衍生技术点：
## 4. 调控和优化算法
### 4.1 PID调控
### 4.2 MPC调控
### 4.3 CEM/RL调控
### 4.4 贝叶斯优化
### 4.5 衍生问题
#### 问题1. 稀疏延迟统计
#### 问题2. 调控与优化之间的关系
#### 问题3. 校准策略
- [link](https://github.com/huangsg1/uncertainty-calibration)

## 5. 平台&客户&流量策略策略协同优化

## 6. 策略引擎/架构（Strategy Server）
- [阿里巴巴展示广告智能拍卖机制的演进之路](https://mp.weixin.qq.com/s/bHiEt1RLUDN9Zt2MSjCxaQ)
### 6.1 概览
### 6.2 离线策略服务
### 6.3 在线策略引擎
### 6.4 监控&报警&维护

## 7. 动态算力（智能算力）
- [美团：美团外卖广告智能算力的探索与实践(1~2)](https://tech.meituan.com/2022/04/28/evolutionary-strategies-based-multi-action-computation-allocation.html)
- [阿里妈妈：展示广告动态算力](https://zhuanlan.zhihu.com/p/573230085)


## 其他参考
- Researcher [Pingzhong Tang](http://people.iiis.tsinghua.edu.cn/~kenshin/)
- Researcher [Weinan Zhang](https://github.com/wnzhang/rtb-papers)
- Researcher [Zhe Wang](https://github.com/wzhe06/Ad-papers)
- https://github.com/Doragd/Algorithm-Practice-in-Industry

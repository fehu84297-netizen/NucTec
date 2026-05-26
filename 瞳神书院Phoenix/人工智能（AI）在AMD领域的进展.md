     人工智能（AI）在AMD领域的进展 \* { margin: 0; padding: 0; outline: 0; } body { font-family: "PingFang SC", system-ui, -apple-system, BlinkMacSystemFont, "Helvetica Neue", "Hiragino Sans GB", "Microsoft YaHei UI", "Microsoft YaHei", Arial, sans-serif; line-height: 1.6; } .\_\_page\_content\_\_ { max-width: 667px; margin: 0 auto; padding: 20px; text-size-adjust: 100%; color: rgba(0, 0, 0, 0.9); padding-bottom: 64px; } .title { user-select: text; font-size: 22px; line-height: 1.4; margin-bottom: 14px; font-weight: 500; } .\_\_meta\_\_ { color: rgba(0, 0, 0, 0.3); font-size: 15px; line-height: 20px; hyphens: auto; word-break: break-word; margin-bottom: 50px; } .\_\_meta\_\_ .nick\_name { color: #576B95; } .\_\_meta\_\_ .copyright { color: rgba(0, 0, 0, 0.3); background-color: rgba(0, 0, 0, 0.05); padding: 0 4px; margin: 0 10px 10px 0; } blockquote.source { padding: 10px; margin: 30px 0; border-left: 5px solid #ccc; color: #333; font-style: italic; word-wrap: break-word; } blockquote.source a { cursor: pointer; text-decoration: underline; } .item\_show\_type\_0 > section { margin-top: 0; margin-bottom: 24px; } a { color: #576B95; text-decoration: none; cursor: default; } .text\_content { margin-bottom: 50px; user-select: text; font-size: 17px; white-space: pre-wrap; word-wrap: break-word; line-height: 28px; hyphens: auto; } .picture\_content .picture\_item { margin-bottom: 30px; } .picture\_content .picture\_item .picture\_item\_label { text-align: center; } img { max-width: 100%; } .pay\_subscribe\_notice { margin: 30px 0; padding: 20px; background: #fffbe6; border: 1px solid #ffe58f; border-radius: 8px; } .pay\_subscribe\_badge { display: inline-block; padding: 4px 12px; background: #faad14; color: #fff; border-radius: 4px; font-size: 14px; font-weight: 500; margin-bottom: 12px; } .pay\_subscribe\_desc { font-size: 15px; line-height: 1.8; color: rgba(0, 0, 0, 0.7); margin-bottom: 12px; } .pay\_subscribe\_hint { font-size: 13px; color: rgba(0, 0, 0, 0.4); } .\_\_bottom-bar\_\_ { display: flex; justify-content: space-between; align-items: center; position: fixed; bottom: 0; left: 0; right: 0; height: 64px; padding: 8px 20px; background: white; box-sizing: border-box; border-top: 1px solid rgba(0, 0, 0, 0.2); } .\_\_bottom-bar\_\_ .left { display: flex; align-items: center; font-size: 15px; white-space: nowrap; } .\_\_bottom-bar\_\_ .right { display: flex; } .\_\_bottom-bar\_\_ .sns\_opr\_btn { display: flex; align-items: center; user-select: none; background: transparent; border: 0; color: rgba(0, 0, 0, 0.9); font-size: 14px; } .\_\_bottom-bar\_\_ .sns\_opr\_btn:not(:last-child) { margin-right: 16px; } .\_\_bottom-bar\_\_ .sns\_opr\_btn > img { margin-right: 4px; }

人工智能（AI）在AMD领域的进展
=================

原创 ✨🪐👀 瞳神书院Phoenix 2025-12-15 07:23 北京

> 原文地址: [https://mp.weixin.qq.com/s/z8PA0cmATLavl4SVOBnBjQ](https://mp.weixin.qq.com/s/z8PA0cmATLavl4SVOBnBjQ)

年龄相关性黄斑变性（AMD）是全球老年人不可逆性视力损伤的主要原因。人工智能（AI），特别是深度学习技术，已在AMD的各个管理环节——从早期筛查、精准分期到疾病进展预测和个体化治疗优化——展现出革命性的潜力。2023年至2025年间是AI在AMD领域的关键进展期。研究表明，基于卷积神经网络（CNN）和Transformer等先进架构的AI模型，在处理眼底彩照和光学相干断层扫描（OCT）图像方面已达到甚至某些方面超越人类专家的水平。

![](https://mmbiz.qpic.cn/sz_mmbiz_png/yuticickzvyCnJ7iak5n8miaggPXVnY8agGtf6wpHCRDZI42QXJLzpDQCWDzUZpXWyzcgj1fo4oaKRqjEKLpyV5NJg/640?wx_fmt=png)

图示：检测AMD发生发展过程

更重要的是，AI的应用已从静态诊断延伸至动态预测，能够有效预测AMD向晚期发展的风险，并对主流的抗血管内皮生长因子（anti-VEGF）治疗的疗效进行预判，为实现个体化治疗提供了数据驱动的决策支持。多模态AI模型的兴起，通过融合影像组学、基因组学和临床数据，进一步提升了预测的精准度和疾病理解的深度。与此同时，联邦学习等隐私保护技术为解决“数据孤岛”问题提供了新路径。尽管AI在AMD领域的应用前景广阔，但模型的可解释性、临床整合的无缝性、算法的公平性以及大规模前瞻性临床验证仍是未来需要攻克的挑战。

01

引言

年龄相关性黄斑变性（AMD）是一种进行性视网膜退行性疾病，主要影响黄斑区，导致中心视力严重受损，是造成全球50岁以上人群视力障碍和失明的主要元凶。传统的AMD管理依赖于眼科医生的专业经验和定期随访，但在大规模筛查、早期干预和治疗方案的精细化调整方面面临巨大挑战。近年来，人工智能技术的飞速发展为攻克这些挑战带来了曙光。AI，特别是以深度学习为代表的算法，能够从海量医学影像数据中自动学习复杂的病理特征，其强大的图像识别和模式分析能力在眼科学领域得到了广泛应用。

02

AI赋能AMD精准诊断与自动化分期

将AI应用于AMD的筛查与诊断是该领域最早且最为成熟的方向。AI模型能够快速、准确地从眼底图像中识别出AMD的关键生物标志物，如玻璃膜疣（drusen）、地图样萎缩（GA）和脉络膜新生血管（CNV），从而实现高效的自动化诊断与分期。

![](https://mmbiz.qpic.cn/mmbiz_png/JvDZU8nOMJFnWqAxpQJ0NzUAD1cqVMVicCw8bz5WYrWlQJCSbARYe19cKFAh4fF4oFAqzTiaqUEQRWFNMons3y2A/640?wx_fmt=png)

2.1 核心技术与模型架构

  

![](https://mmbiz.qpic.cn/mmbiz_png/1cmU83sIEAzHUvu5sklicibMefmSe7JHK8JcdXxkIKBUlVviafbTNB5J7q3dEzhTFpp9h3ib8icw3ba5eRdlEvViaNZg/640?wx_fmt=png)

研究人员广泛采用深度学习模型，尤其是 卷积神经网络（CNN）及其各种先进变体 ，作为处理眼科图像的基础架构。这些模型包括经典的AlexNet、VGG，以及更深、更复杂的ResNet、Inception、DenseNet等。通过模拟人类视觉皮层的分层结构，这些网络能有效提取从低级纹理到高级病灶形态的复杂特征。进入2024-2025年，随着 视觉转换器（ViT）及其衍生模型的兴起，研究者们也开始将其应用于AMD图像分析。与CNN关注局部感受野不同，Transformer通过其自注意力机制能够更好地捕捉图像中的长距离依赖关系，这对于识别散在分布的玻璃膜疣或评估整体病变范围具有潜在优势。例如，名为 DeepDrAMD 的分层视觉转换器模型在AMD检测任务中表现出色。此外，研究者还开发了一系列针对AMD任务的特化模型，如LSVT-Net、AMDNet23、DeepAlienNet和DeepSeeNet等。

![](https://mmbiz.qpic.cn/mmbiz_png/JvDZU8nOMJFnWqAxpQJ0NzUAD1cqVMVicCw8bz5WYrWlQJCSbARYe19cKFAh4fF4oFAqzTiaqUEQRWFNMons3y2A/640?wx_fmt=png)

2.2 海量数据集与卓越性能

  

![](https://mmbiz.qpic.cn/mmbiz_png/1cmU83sIEAzHUvu5sklicibMefmSe7JHK8JcdXxkIKBUlVviafbTNB5J7q3dEzhTFpp9h3ib8icw3ba5eRdlEvViaNZg/640?wx_fmt=png)

AI模型的卓越性能离不开大规模、高质量的训练数据。研究中广泛使用了多个大型公开或私有数据集，包括眼底彩照（CFP）和OCT图像。著名的数据集来源包括 AREDS 等。这些数据集动辄包含数万至数十万张图像，覆盖了不同疾病阶段、多种族人群和多样化的成像设备，为训练稳健且泛化能力强的模型奠定了基础。部分研究还利用超大规模数据集进行预训练，再在特定的AMD数据集上进行微调，以提升模型性能。

得益于此，AI模型在AMD诊断任务中取得了令人瞩目的表现。多项研究报告的 准确率和曲线下面积（AUC）值普遍高于90% 。在区分干性与湿性AMD方面亦是。

03

AI驱动的AMD疾病进展风险预测

AMD是一种进行性疾病，从早期/中期进展到晚期（地图样萎缩或新生血管形成）是导致视力丧失的关键节点。因此，准确预测疾病进展风险对于指导预防性干预和制定个性化随访计划至关重要。

![](https://mmbiz.qpic.cn/mmbiz_png/JvDZU8nOMJFnWqAxpQJ0NzUAD1cqVMVicCw8bz5WYrWlQJCSbARYe19cKFAh4fF4oFAqzTiaqUEQRWFNMons3y2A/640?wx_fmt=png)

3.1 预测模型的演进与应用

  

![](https://mmbiz.qpic.cn/mmbiz_png/1cmU83sIEAzHUvu5sklicibMefmSe7JHK8JcdXxkIKBUlVviafbTNB5J7q3dEzhTFpp9h3ib8icw3ba5eRdlEvViaNZg/640?wx_fmt=png)

AI预测模型通常利用基线时的眼底图像或OCT扫描，结合患者的临床信息，来预测其在未来特定时间窗（如2年、5年）内进展到晚期AMD的概率。早期的研究已证明CNN模型能够有效预测AMD进展，到了2023年，新的模型架构不断涌现以提升预测精度。这些模型不仅分析玻璃膜疣的大小、数量和融合状态等静态特征，还能捕捉到一些与进展相关的更细微的图像纹理或结构变化。

![](https://mmbiz.qpic.cn/mmbiz_png/JvDZU8nOMJFnWqAxpQJ0NzUAD1cqVMVicCw8bz5WYrWlQJCSbARYe19cKFAh4fF4oFAqzTiaqUEQRWFNMons3y2A/640?wx_fmt=png)

3.2 性能指标与临床价值

  

![](https://mmbiz.qpic.cn/mmbiz_png/1cmU83sIEAzHUvu5sklicibMefmSe7JHK8JcdXxkIKBUlVviafbTNB5J7q3dEzhTFpp9h3ib8icw3ba5eRdlEvViaNZg/640?wx_fmt=png)

不同研究报告的AMD进展预测模型性能存在一定差异，这与预测的时间跨度、数据集的异质性以及模型架构有关。尽管性能指标尚未达到诊断任务那样接近完美，但这些成果已具有显著的临床价值。

04

AI优化AMD治疗方案：迈向个体化医疗

对于湿性AMD（nAMD），抗VEGF药物玻璃体腔内注射是标准疗法。然而，患者对治疗的反应差异巨大，治疗方案（如注射频率）的确定往往依赖于医生的经验和耗时的“试错”过程。AI为解决这一难题，实现个体化、精准化的治疗方案优化提供了新思路。

![](https://mmbiz.qpic.cn/mmbiz_png/JvDZU8nOMJFnWqAxpQJ0NzUAD1cqVMVicCw8bz5WYrWlQJCSbARYe19cKFAh4fF4oFAqzTiaqUEQRWFNMons3y2A/640?wx_fmt=png)

4.1 预测抗VEGF治疗反应

  

![](https://mmbiz.qpic.cn/mmbiz_png/1cmU83sIEAzHUvu5sklicibMefmSe7JHK8JcdXxkIKBUlVviafbTNB5J7q3dEzhTFpp9h3ib8icw3ba5eRdlEvViaNZg/640?wx_fmt=png)

截至2025年，利用AI预测抗VEGF治疗反应已成为研究热点。这类模型的核心任务是，基于治疗前的OCT图像、眼底图像以及患者的临床数据（如基线视力、黄斑中心厚度CST、治疗史等），预测患者在接受一系列抗VEGF注射后的解剖学（如视网膜下液/内液的消退）和功能学（如视力改善）反应。模型架构多样，包括 CNN、循环神经网络/长短时记忆网络、时间卷积网络（TCN）以及各类集成学习算法 。研究人员利用这些模型，在包含数百名患者的临床数据集上进行训练和验证 。

![](https://mmbiz.qpic.cn/mmbiz_png/JvDZU8nOMJFnWqAxpQJ0NzUAD1cqVMVicCw8bz5WYrWlQJCSbARYe19cKFAh4fF4oFAqzTiaqUEQRWFNMons3y2A/640?wx_fmt=png)

4.2 赋能个体化治疗决策

  

![](https://mmbiz.qpic.cn/mmbiz_png/1cmU83sIEAzHUvu5sklicibMefmSe7JHK8JcdXxkIKBUlVviafbTNB5J7q3dEzhTFpp9h3ib8icw3ba5eRdlEvViaNZg/640?wx_fmt=png)

基于上述预测能力，AI能够为临床医生提供强大的决策支持，优化“治疗并扩展”（ T&E）等个体化给药方案。尽管绝大多数研究仍为回顾性分析，但其展现的巨大潜力正推动着研究者们设计和开展前瞻性临床试验，以验证这些AI工具在真实世界临床环境中的有效性和安全性。

05

多模态AI模型：整合多维度信息的综合洞察

AMD是一种复杂的、由遗传和环境因素共同驱动的疾病。单一模态的数据（如仅眼底图像）往往难以全面捕捉其病理生理全貌。因此，整合影像、基因和临床数据的多模态AI模型，成为2025年前后的一个重要发展趋势，被认为是推动精准医疗的关键力量。

![](https://mmbiz.qpic.cn/mmbiz_png/JvDZU8nOMJFnWqAxpQJ0NzUAD1cqVMVicCw8bz5WYrWlQJCSbARYe19cKFAh4fF4oFAqzTiaqUEQRWFNMons3y2A/640?wx_fmt=png)

5.1 融合策略与前沿架构

  

![](https://mmbiz.qpic.cn/mmbiz_png/1cmU83sIEAzHUvu5sklicibMefmSe7JHK8JcdXxkIKBUlVviafbTNB5J7q3dEzhTFpp9h3ib8icw3ba5eRdlEvViaNZg/640?wx_fmt=png)

多模态模型的核心在于其 融合策略 。早期的融合在输入层即拼接多源数据特征，而晚期融合则在各单模态模型输出预测结果后再进行整合。近年来，更为复杂的中间融合策略，特别是基于 跨模态注意力机制和Transformer的架构 ，显示出巨大优势。这类架构能够动态地学习不同模态特征之间的相互关联和权重。

![](https://mmbiz.qpic.cn/mmbiz_png/JvDZU8nOMJFnWqAxpQJ0NzUAD1cqVMVicCw8bz5WYrWlQJCSbARYe19cKFAh4fF4oFAqzTiaqUEQRWFNMons3y2A/640?wx_fmt=png)

5.2 性能提升与验证

  

![](https://mmbiz.qpic.cn/mmbiz_png/1cmU83sIEAzHUvu5sklicibMefmSe7JHK8JcdXxkIKBUlVviafbTNB5J7q3dEzhTFpp9h3ib8icw3ba5eRdlEvViaNZg/640?wx_fmt=png)

多模态融合的优势已在多项研究中得到证实。一项基于AREDS数据集的研究表明， 将基因型数据与眼底图像结合，预测晚期AMD的进展。另一项研究也证实，在眼底图像模型的基础上增加临床和遗传数据，可以显著提高预测的准确性。这些结果有力地证明了协同效应。在验证方面，研究人员普遍采用严格的交叉验证和独立的外部测试集（如AREDS2或NAT-2数据集）来评估模型的泛化能力。

06

新兴技术方向与核心挑战

尽管AI在AMD领域取得了长足进步，但要实现广泛的临床应用，仍需克服若干技术和实践层面的挑战。

![](https://mmbiz.qpic.cn/mmbiz_png/JvDZU8nOMJFnWqAxpQJ0NzUAD1cqVMVicCw8bz5WYrWlQJCSbARYe19cKFAh4fF4oFAqzTiaqUEQRWFNMons3y2A/640?wx_fmt=png)

6.1 联邦学习与数据隐私保护

  

![](https://mmbiz.qpic.cn/mmbiz_png/1cmU83sIEAzHUvu5sklicibMefmSe7JHK8JcdXxkIKBUlVviafbTNB5J7q3dEzhTFpp9h3ib8icw3ba5eRdlEvViaNZg/640?wx_fmt=png)

深度学习模型的性能高度依赖于大规模、多样化的数据。然而，由于患者隐私和数据安全法规的限制，跨机构共享医疗数据极为困难，形成了所谓的“数据孤岛”。 联邦学习 为解决这一难题提供了创新的解决方案。它允许各个医疗机构在本地用自己的数据训练模型，仅将加密后的模型参数（而非原始数据）上传至中央服务器进行聚合，再将更新后的全局模型下发至各机构。

截至2025年，联邦学习已在多个医学影像领域（如脑肿瘤分割）的大型多中心研究中得到成功应用，涉及多达71个研究中心，其性能被证实可与甚至超越传统的集中式训练模型。在眼科影像领域，也已有研究开始探索利用联邦学习对OCT或OCTA图像进行多病种分类，并取得了与中心化训练相当的性能。但针对AMD的大规模联邦学习研究及其通信开销、收敛速度等具体性能指标的详细报告尚在涌现中。

![](https://mmbiz.qpic.cn/mmbiz_png/JvDZU8nOMJFnWqAxpQJ0NzUAD1cqVMVicCw8bz5WYrWlQJCSbARYe19cKFAh4fF4oFAqzTiaqUEQRWFNMons3y2A/640?wx_fmt=png)

6.2 模型可解释性与临床无缝整合

  

![](https://mmbiz.qpic.cn/mmbiz_png/1cmU83sIEAzHUvu5sklicibMefmSe7JHK8JcdXxkIKBUlVviafbTNB5J7q3dEzhTFpp9h3ib8icw3ba5eRdlEvViaNZg/640?wx_fmt=png)

深度学习模型常被诟病为“黑箱”，其决策过程不透明，这阻碍了临床医生对其的完全信任。发展 可解释性AI ，如通过生成热力图或显著性图来高亮显示模型做出判断时所依据的图像区域，对于模型的调试、验证和临床采纳至关重要。

此外，将AI工具无缝整合到现有的临床工作流程中也是一个巨大的挑战。这不仅涉及技术层面的软件开发和系统集成，还涉及建立适应性监管框架、处理算法可能存在的偏见（如对特定人群表现不佳）以及对临床医生进行相应的培训。

07

结论与展望

截至2025，人工智能技术已经深刻地改变了我们对年龄相关性黄斑变性的认知和管理范式。未来预测该领域将呈现以下几个主要趋势：

*   多模态模型的成熟与普及
    
*   隐私保护技术的深化应用
    
*   从回顾性研究到前瞻性验证
    
*   关注可解释性与人机协同
    

免责声明：文中内容仅供学习和交流，不能替代专业的医疗建议、诊断或治疗。如有关于健康状况的任何疑问，请务必咨询专业的医生和医疗机构。

文中图片来自网络，版权归原作者所有，如有疑问请联系删除。

![](http://mmbiz.qpic.cn/sz_mmbiz_png/yuticickzvyCk03lQundzadUFzYUZaJEEicorxlwvonDLC3ysibC5cSUtcs82qzqnMp3ThTia8HAFhCCp9BAhjYXOQg/0?wx_fmt=png) 瞳神书院Phoenix

 ![](data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24'%3E%3C!-- Icon from Lucide by Lucide Contributors - https://github.com/lucide-icons/lucide/blob/main/LICENSE --%3E%3Cg fill='none' stroke='%23888888' stroke-linecap='round' stroke-linejoin='round' stroke-width='2'%3E%3Cpath d='M2.062 12.348a1 1 0 0 1 0-.696a10.75 10.75 0 0 1 19.876 0a1 1 0 0 1 0 .696a10.75 10.75 0 0 1-19.876 0'/%3E%3Ccircle cx='12' cy='12' r='3'/%3E%3C/g%3E%3C/svg%3E) 阅读![](data:image/svg+xml,%3Csvg width='25' height='24' viewBox='0 0 25 24' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath fill-rule='evenodd' clip-rule='evenodd' d='M16.154 6.797l-.177 2.758h4.009c1.346 0 2.359 1.385 2.155 2.763l-.026.148-1.429 6.743c-.212.993-1.02 1.713-1.977 1.783l-.152.006-13.707-.006c-.553 0-1-.448-1-1v-8.58a1 1 0 0 1 1-1h2.44l1.263-.03.417-.018.168-.015.028-.005c1.355-.315 2.39-2.406 2.58-4.276l.01-.16.022-.572.022-.276c.074-.707.3-1.54 1.08-1.883 2.054-.9 3.387 1.835 3.274 3.62zm-2.791-2.52c-.16.07-.282.294-.345.713l-.022.167-.019.224-.023.604-.014.204c-.253 2.486-1.615 4.885-3.502 5.324l-.097.018-.204.023-.181.012-.256.01v8.218l9.813.004.11-.003c.381-.028.72-.304.855-.709l.034-.125 1.422-6.708.02-.11c.099-.668-.354-1.308-.87-1.381l-.098-.007h-5.289l.26-4.033c.09-1.449-.864-2.766-1.594-2.446zM7.5 11.606l-.21.005-2.241-.001v8.181l2.45.001v-8.186z' fill='%23000'/%3E%3C/svg%3E) 赞 ![](data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24'%3E  %3Cg fill='none' fill-rule='evenodd'%3E    %3Cpath d='M0 0h24v24H0z'/%3E    %3Cpath fill='%23576B95' d='M13.707 3.288l7.171 7.103a1 1 0 0 1 .09 1.32l-.09.1-7.17 7.104a1 1 0 0 1-1.705-.71v-3.283c-2.338.188-5.752 1.57-7.527 5.9-.295.72-1.02.713-1.177-.22-1.246-7.38 2.952-12.387 8.704-13.294v-3.31a1 1 0 0 1 1.704-.71zm-.504 5.046l-1.013.16c-4.825.76-7.976 4.52-7.907 9.759l.007.287c1.594-2.613 4.268-4.45 7.332-4.787l1.581-.132v4.103l6.688-6.623-6.688-6.623v3.856z'/%3E  %3C/g%3E%3C/svg%3E) 分享 ![](data:image/svg+xml;charset=utf8,%3Csvg xmlns='http://www.w3.org/2000/svg' xmlns:xlink='http://www.w3.org/1999/xlink' width='24' height='24' viewBox='0 0 24 24'%3E  %3Cdefs%3E    %3Cpath id='a62bde5b-af55-42c8-87f2-e10e8a48baa0-a' d='M0 0h24v24H0z'/%3E  %3C/defs%3E  %3Cg fill='none' fill-rule='evenodd'%3E    %3Cmask id='a62bde5b-af55-42c8-87f2-e10e8a48baa0-b' fill='%23fff'%3E      %3Cuse xlink:href='%23a62bde5b-af55-42c8-87f2-e10e8a48baa0-a'/%3E    %3C/mask%3E    %3Cg mask='url(%23a62bde5b-af55-42c8-87f2-e10e8a48baa0-b)'%3E      %3Cg transform='translate(0 -2.349)'%3E        %3Cpath d='M0 2.349h24v24H0z'/%3E        %3Cpath fill='%23576B95' d='M16.45 7.68c-.954 0-1.94.362-2.77 1.113l-1.676 1.676-1.853-1.838a3.787 3.787 0 0 0-2.63-.971 3.785 3.785 0 0 0-2.596 1.112 3.786 3.786 0 0 0-1.113 2.687c0 .97.368 1.938 1.105 2.679l7.082 6.527 7.226-6.678a3.787 3.787 0 0 0 .962-2.618 3.785 3.785 0 0 0-1.112-2.597A3.687 3.687 0 0 0 16.45 7.68zm3.473.243a4.985 4.985 0 0 1 1.464 3.418 4.98 4.98 0 0 1-1.29 3.47l-.017.02-7.47 6.903a.9.9 0 0 1-1.22 0l-7.305-6.73-.008-.01a4.986 4.986 0 0 1-1.465-3.535c0-1.279.488-2.56 1.465-3.536A4.985 4.985 0 0 1 7.494 6.46c1.24-.029 2.49.4 3.472 1.29l.01.01L12 8.774l.851-.85.01-.01c1.046-.951 2.322-1.434 3.59-1.434 1.273 0 2.52.49 3.472 1.442z'/%3E      %3C/g%3E    %3C/g%3E  %3C/g%3E%3C/svg%3E) 推荐 ![](data:image/svg+xml,%3Csvg width='25' height='24' viewBox='0 0 25 24' fill='none' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M22.242 7a2.5 2.5 0 0 0-2.5-2.5h-14a2.5 2.5 0 0 0-2.5 2.5v8.5a2.5 2.5 0 0 0 2.5 2.5h2.5v1.59a1 1 0 0 0 1.707.7l1-1a.569.569 0 0 0 .034-.03l1.273-1.273a.6.6 0 0 0-.8-.892v-.006L9.441 19.1l.001-2.3h-3.7l-.133-.007A1.3 1.3 0 0 1 4.442 15.5V7l.007-.133A1.3 1.3 0 0 1 5.742 5.7h14l.133.007A1.3 1.3 0 0 1 21.042 7v4.887a.6.6 0 1 0 1.2 0V7z' fill='%23000' fill-opacity='.9'/%3E%3Crect x='14.625' y='16.686' width='7' height='1.2' rx='.6' fill='%23000' fill-opacity='.9'/%3E%3Crect x='18.725' y='13.786' width='7' height='1.2' rx='.6' transform='rotate(90 18.725 13.786)' fill='%23000' fill-opacity='.9'/%3E%3C/svg%3E) 留言
# 基于患者E-Health诊治数据的安全存储与管理

## 摘要

着眼于传统医疗信息系统中存在的医疗信息的安全存储和授权共享的问题，结合以太坊平台，设计了一个基于电子病历安全存储与授权共享系统。该设计通过以太坊平台来存储患者的电子病历信息和访问权限。患者可以安全有效地管理自己的诊治数据，还可以授权给医疗机构等第三方进行读取。该设计有效的实现了患者对于自身医疗数据的访问控制权限和对数据的安全存储。

关键词：安全存储、授权共享、以太坊、电子病历、访问控制权限

## Abstract

Focusing on the problem of secure storage and authorization sharing of medical information in traditional medical information systems, combined with the Ethereum platform, a secure storage and authorization sharing system based on electronic medical records was designed. The design stores the patient's electronic medical record information and access rights through the Ethereum platform. Patients can manage their diagnosis and treatment data safely and effectively, and can also be authorized to read by third parties such as medical institutions. The design effectively realizes the patient's access control authority for his own medical data and secure storage of data.

## 绪论

### 研究背景、目的与意义

医疗健康问题与每一个人都息息相关，患者的医疗记录（包括病历、化验单、CT图等）都是患者个人健康状况的有效证明，对于患者了解自身健康状态和调养十分重要。然而我国的医疗发展起步晚，医疗设施落后，医疗信息化和数字化进程缓慢，对于病人的医疗隐私数据也缺乏安全有效的管理。医疗信息数字化是未来的发展趋势，利用现代先进的计算机技术，可以减少传统医疗系统中重复的人力操作，使得诊治过程规范化。其中医疗数据（处方、病历记录、身份信息、文档信息）的安全存储和管理更是重中之重，在传统的解决方案中，需要提高电子医疗数据的权限、隐私、安全等，以维护数据的完整性、正确性、可靠性、安全性和隐私性。

另一方面，当前时代是大数据时代，数据的作用被极大的释放，医疗数据更是数据分析的宝贵来源。在传统的医疗信息系统中，由于信息缺乏安全存储，信息容易被不法分子利用，进行贩卖。同时，由于各种医疗机构之间的不信任，医疗数据的共享更是困难，逐渐的形成了"数据孤岛"。数据的不流通导致了协同诊治平台的推进困难，患者往返于各种医院和医疗机构，无法综合各个机构的诊治结果形成完善的就诊报告。

综上所述，设计一套可以独立于第三方医疗机构，对患者个人的医疗数据进行安全存储，同时可以由患者授权给第三方读取，方便不同的医院和医疗机构进行协同诊治的系统十分必要。


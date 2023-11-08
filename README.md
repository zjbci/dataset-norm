# 数据集提交规范说明



* 课题任务提交的脑机数据集拟采用 *[BIDS 规范](https://bids-specification.readthedocs.io/en/stable/)* 进行管理。

* 为降低各课题组数据规范化处理的学习门槛，特将 BIDS 规范中要求的数据集属性整理为数个 `.xlsx` 属性表格，各课题组数据集提交时，按 `.xlsx` 中的说明填写即可。
* 如数据集已符合 *[BIDS 规范](https://bids-specification.readthedocs.io/en/stable/)* 并可通过 [bids-validator](https://github.com/bids-standard/bids-validator) 验证，则可以直接提交，不需按本规范整理。
* 对于多种模态并存的数据集，在同一个数据集中按规范创建不同模态目录即可。
  * 如实验中同时记录了 EEG 与 NIRS 模态数据，则只需在  `XXXDataset/sub-01/ses-01/` 下建立 `eeg` 和 `nirs` 两个子目录即可。

* 目前支持的提交规范：
  * EEG： 已完成，EEG数据提交规范-v1.0
  * iEEG： 已完成 ，iEEG数据提交规范-v1.0
  * NIRS： 已完成，NIRS数据提交规范-v1.0
  * MRI： <未完成，暂未定稿>



**如对本数据集提交规范有疑问或建议，请联系课题负责人。**
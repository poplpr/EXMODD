<h4 align="center">
    <p>
        <a href="https://github.com/poplpr/EXMODD/blob/main/README.md">English</a> |
        <b>简体中文</b>
    </p>
</h4>

# EXMODD: An EXplanatory Multimodal Open-Domain Dialogue dataset（EXMODD：一个可解释的多模态开放域对话数据集）

**摘要**：对高质量数据的需求一直是阻碍对话任务研究的关键问题。最近的研究尝试通过手动、网络爬虫和大型预训练模型来构建数据集。然而，人类手造的数据成本高昂，从互联网收集的数据通常包括通用回复、无意义陈述和有毒性的对话。通过大模型自动生成数据是一种经济有效的方法，但对于开放域多模态对话任务，仍然存在三个缺点：1）目前没有可以接受多模态输入的开源大模型；2）模型生成的内容缺乏可解释性；3）生成的数据通常难以进行质量控制，并且需要大量资源来收集。为了减轻数据收集方面的大量人力和资源支出，我们提出了多模式数据构建框架（MDCF）。MDCF设计适当的 prompt 来激发大规模预训练语言模型生成格式良好且令人满意的内容。 此外，MDCF 还自动为给定的图像及其对应的对话提供解释，可以提供一定程度的可解释性，并方便人工后续质量检查。基于此，我们发布了可解释多模态开放域对话数据集（EXMODD）。实验表明模型生成准确理解的能力与高质量响应之间呈正相关。

目前论文已经在 ArXiv 提交，地址为 [https://arxiv.org/abs/2310.10967](https://arxiv.org/abs/2310.10967)。暂时不知道代码仓库应该放些什么内容，且数据集暂时没有整理成精简版本（image chat 的全部图片，然而我们的数据集其实仅需要一部分）。如果您有需要的话，可以尝试邮箱联系 poplpr@bit.edu.cn，我会将数据集文本部分的 json 文件发给您。

# 引用

```tex
@misc{yin2023exmodd,
      title={EXMODD: An EXplanatory Multimodal Open-Domain Dialogue dataset}, 
      author={Hang Yin and Pinren Lu and Ziang Li and Bin Sun and Kan Li},
      year={2023},
      eprint={2310.10967},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```


<h4 align="center">
    <p>
        <b>English</b> |
        <a href="https://github.com/poplpr/EXMODD/blob/main/README_zh.md">简体中文</a>
    </p>
</h4>

# EXMODD: An EXplanatory Multimodal Open-Domain Dialogue dataset 

**Abstract**: The need for high-quality data has been a key issue hindering the research of dialogue tasks. Recent studies try to build datasets through manual, web crawling, and large pre-trained models. However, man-made data is expensive and data collected from the internet often includes generic responses, meaningless statements, and toxic dialogues. Automatic data generation through large models is a cost-effective method, but for open-domain multimodal dialogue tasks, there are still three drawbacks: 1) There is currently no open-source large model that can accept multimodal input; 2) The content generated by the model lacks interpretability; 3) The generated data is usually difficult to quality control and require extensive resource to collect. To alleviate the significant human and resource expenditure in data collection, we propose a Multimodal Data Construction Framework (MDCF). MDCF designs proper prompts to spur the large-scale pre-trained language model to generate well-formed and satisfactory content. Additionally, MDCF also automatically provides explanation for a given image and its corresponding dialogue, which can provide a certain degree of interpretability and facilitate manual follow-up quality inspection. Based on this, we release an Explanatory Multimodal Open-Domain dialogue dataset (EXMODD). Experiments indicate a positive correlation between the model's ability to generate accurate understandings and high-quality responses.

Our paper is at the state of submitted on ArXiv, URL is [https://arxiv.org/abs/2310.10967](https://arxiv.org/abs/2310.10967).  Authors is constructing code in the code repo, and dataset has not been simplified. If there is something need, you can communicate poplpr@bit.edu.cn , I will send json file of our dataset in text format to you.

# Citation

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


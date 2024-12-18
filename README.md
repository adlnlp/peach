# PEACH: Pretrained-embedding Explanation Across Contextual and Hierarchical Structure

The paper is accepted at IJCAI 2024. The detailed documentation with examples for applying the code will be shared later.

### <div align="center">Feiqi Cao*, Soyeon Caren Han*, Hyunsuk Chung. (2024, August).<br>[PEACH: Pretrained-embedding Explanation Across Contextual and Hierarchical Structure](https://www.ijcai.org/proceedings/2024/0686.pdf)<br>*co-first authors<br><br>The 33rd International Joint Conference on Artificial  Intelligence <br> (IJCAI 2024). <br> \[[paper](https://www.ijcai.org/proceedings/2024/0686.pdf)\]|\[[appendix](https://github.com/adlnlp/peach/blob/main/IJCAI2024_PEACH_Appendix.pdf)\]\[[presentation](https://drive.google.com/file/d/1fHPN0KMWv6dGZ7vOrCgTUiTevO8_w7KI/view?usp=sharing)\]</div>


## Citation
```
@inproceedings{ijcai2024p686,
  title     = {PEACH: Pretrained-Embedding Explanation across Contextual and Hierarchical Structure},
  author    = {Cao, Feiqi and Han, Soyeon Caren and Chung, Hyunsuk},
  booktitle = {Proceedings of the Thirty-Third International Joint Conference on
               Artificial Intelligence, {IJCAI-24}},
  publisher = {International Joint Conferences on Artificial Intelligence Organization},
  editor    = {Kate Larson},
  pages     = {6207--6215},
  year      = {2024},
  month     = {8},
  note      = {Main Track},
  doi       = {10.24963/ijcai.2024/686},
  url       = {https://doi.org/10.24963/ijcai.2024/686},
}
```

## Instruction
Run the given ipynb files with the following order:
1. Datasets
2. Models
3. Finetune_pretrained_models
4. Cluster_feature
5. CNN_Grouping
6. DT_generation
7. Tree_Information_Extraction

## Qualitative Examples

We visualised the global and local explanation tree for the text classification tasks. Here are some examples. For more details please refer to our paper.

- Global example: 
  <p align="center"><img src="figure/peach_global.png" width="1000" /></p>
- Local examples: 
  <p align="center"><img src="figure/peach_local_business.png" width="1000" /></p>
  <p align="center"><img src="figure/peach_local_politics.png" width="1000" /></p>
  <p align="center"><img src="figure/peach_local_entertainment.png" width="1000" /></p>

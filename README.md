<h1 align="center">[Manuscript] On Imbalance in Case Types: Evaluating and Enhancing PLMs for Criminal Court View Generation</h1>

* 🎈 Manuscript is under review since August 21, 2024.
* 💻 [Github Link](https://github.com/yuquanle/Case-type-oriented-metrics)
* 📖 [Paper Link](...)
* 📁 [Datasets Link](https://github.com/bigdata-ustc/C3VG)

**Abstract**: Criminal Court View Generation (CCVG) task aims to produce succinct and coherent summaries of fact descriptions, providing interpretable opinions for verdicts. Traditional text generation evaluation metrics, such as ROUGE, BLEU, and BERTSCORE, are extensively employed for this task and measure performance by averaging the assessment scores of all samples within the test set. However, these sample-averaged metrics encounter two primarily dilemmas: 1) they fail to fairly assess overall evaluation scores across different case types, and 2) they overlook the measurement of the degree of performance imbalance between case types. To fill this research gap, we propose two novel case-type-oriented evaluation metrics: Case-type-oriented Text Generation (CTG) and Case-type-oriented Imbalance Performance (CIP). First, CTG mitigates the unfair assessment among different case types by assigning equal weight to each type. Second, CIP evaluates performance imbalance by measuring the distance between the performance of each case type and the overall performance. We provide three theorems to elucidate the properties of CIP, demonstrating that CIP can effectively identify the extent to which a CCVG model achieves balanced generation performance across different case types. Furthermore, we propose an embarrassingly simple and effective charge-guided encoder-decoder framework to enhance performance fairly across different case types in encoder-decoder pre-trained language models. Our code will be open-sourced at https://github.com/yuquanle/Case-type-oriented-metrics.


## Case-type-oriented Evaluation Metrics

### Case-type-oriented Text Generation Metrics
CTG mitigate the unfair assessment among different case types by assigning equal weight to each type.


### Case-type-oriented Imbalance Performance Metrics
CIP evaluates performance imbalance by measuring the distance between the performance of each case type and the overall performance.


Our code will be open-sourced here upon the acceptance of the manuscript.

## Citation
If you find our work inspiring or use our codebase in your research, please consider giving a star ⭐ and a citation.

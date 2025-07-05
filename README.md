<p align="center">
     <a href="https://arxiv.org/abs/2402.07518">
<img width="765" alt="image" src="assets/title.png">
     </a>
   <p align="center">
    <a href="https://scholar.google.com.hk/citations?user=1yhGS5sAAAAJ&hl=zh-CN"><strong>Boquan Li<sup>1</sup></strong></a>
    .
    <a href="https://zhangzjn.github.io/"><strong>Zirui Fu<sup>2</sup></strong></a>
    .
    <a href="https://scholar.google.com.hk/citations?user=8-Vo9cUAAAAJ&hl=zh-CN"><strong>Menghan Hu<sup>1</sup></strong></a>
    .
    <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=4daxK2AAAAAJ"><strong>Zhenyu Zhang<sup>3</sup></strong></a>
    .
    <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=fqte5H4AAAAJ"><strong>Chengjie Wang<sup>2</sup></strong></a>
    .
    <a href="https://github.com/flyingby/Awesome-Deepfake-Generation-and-Detection"><strong>Yunsheng Wu<sup>2</sup></strong></a>.
    <p align="center">
    <a href="https://scholar.google.com.hk/citations?user=E6zbSYgAAAAJ&hl=zh-CN"><strong>Guangtao Zhai<sup>4</sup></strong></a>
    .
    <a href="https://scholar.google.com.hk/citations?hl=zh-CN&user=6CIDtZQAAAAJ"><strong>Jian Yang<sup>3</sup></strong></a>
    .
    <a href="https://scholar.google.com.hk/citations?user=Ljk2BvIAAAAJ&hl=zh-CN&oi=ao"><strong>Chunhua Shen<sup>5</sup></strong></a> 
    .
    <a href="https://scholar.google.com.hk/citations?user=RwlJNLcAAAAJ&hl=zh-CN&oi=ao"><strong>Dacheng Tao<sup>6</sup></strong></a>
</p>
<p align="center">
    <strong><sup>1</sup>East China Normal University</strong> &nbsp;&nbsp;&nbsp; <strong><sup>2</sup>Tencent Youtu Lab</strong> &nbsp;&nbsp;&nbsp; <strong><sup>3</sup>Nanjing University</strong> &nbsp;&nbsp;&nbsp; <strong><sup>4</sup>Shanghai Jiao Tong University</strong>
    <br>
    <strong><sup>5</sup>Zhejiang University</strong>  &nbsp;&nbsp;&nbsp; <strong><sup>6</sup>Nanyang Technological University</strong>
    
<p align="center">
    <a href='https://arxiv.org/abs/2402.07518'>
      <img src='https://img.shields.io/badge/arXiv-PDF-green?style=flat&logo=arXiv&logoColor=green' alt='arXiv PDF'>
         </a>
  

# ACW : AI-Generated Code Watermarking  <a id="acw"></a>

This work focuses on the aspect of AI-Generated Code Watermarking. To address the challenges of inefficiency, ineffectiveness, and non-portability in prior methods, we propose a novel watermarking framework based on semantic-equivalent code transformations from the software engineering domain. Our method is designed to be a plug-and-play, high-efficiency, and low-resource-usage solution for watermarking LLM-generated code.

If you discover any defect or have any suggestions for this work, please feel free to submit a [pull request](https://github.com/flyingby/Awesome-Deepfake-Generation-and-Detection/issues) or [contact us](#contact).

### Overview for ACW

<img src="assets/Overview.png">

###  Contribution

[1]  We propose ACW, a novel code watermarking approach
for AI-generated code detection. ACW is plug-and-play
and universal across different LLMs. Moreover, ACW is
efficient and works in a training-free manner, without the
need to access or modify LLMs

[2]  The semantic-preserving transformations in ACW preserve
the utility of code after watermarking. Moreover, ACW
is resilient against common code optimizations. 

[3]  ACW is a highly effective and efficient solution for detecting AI-generated code, 
significantly outperforming existing approaches. 
Moreover, ACW successfully preserves the original code's utility, 
shows resilience against common code optimizations, 
and proves to be universally applicable across different LLMs.

</p>


## Summary of Contents
- [ACW : AI-Generated Code Watermarking](#acw)
  - [Overview for ACW](#overview-for-acw)
  - [Contribution](#contribution)
- [Summary of Contents](#summary-of-contents)
- [Comparison of Intact and Corrupted Watermarked Code](#comparison-of-intact-and-corrupted-watermarked-code)
- [Evaluation Results of Multi-bit Watermarking](#evaluation-results-of-multi-bit-watermarking)
- [Transformation Rules of ACW](#transformation-rules-of-acw)
- [Cite The Work](#Cite-The-Work)
- [Contact](#contact)


## Comparison of Intact and Corrupted Watermarked Code

## Evaluation Results of Multi-bit Watermarking
<div align="center">
     <figure>
         <img src="assets/result.png" alt="Evaluation Results of Multi-bit Watermarking">
         <figcaption>                   Table 1. Evaluation Results of Multi-bit Watermark Extraction</figcaption>
     </figure>
</div>     


## Transformation Rules for ACW
The table below shows the complete set of transformation rules for ACW, 
and provides the detailed rule description, an applicable code snippet, 
and the transformed code snippet for each rule.
<img src="assets/rules.png">

## Cite The Work
If you find our repository useful for your research project, please consider citing our paper:

```bibtex
@article{li2024acwenhancingtraceabilityaigenerated,
      title={ACW: Enhancing Traceability of AI-Generated Codes Based on Watermarking}, 
      author={Boquan Li and Mengdi Zhang and Peixin Zhang and Jun Sun and Xingmei Wang and Zirui Fu},
      year={2024},
      eprint={2402.07518},
      archivePrefix={arXiv},
      primaryClass={cs.CR},
      url={https://arxiv.org/abs/2402.07518}, 
}
```
## Contact


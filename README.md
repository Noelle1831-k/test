<p align="center">
     <a href="https://arxiv.org/abs/2402.07518">
<img width="765" alt="image" src="assets/title.png">
     </a>
   <p align="center">
    <a><strong>Boquan Li<sup>1</sup></strong></a>
    .
    <a><strong>Zirui Fu<sup>2</sup></strong></a>
    .
    <a><strong>Mengdi Zhang<sup>3</sup></strong></a>
    .
    <a><strong>Zhenyu Zhang<sup>3</sup></strong></a>
    .
    <a><strong>Peixin Zhang<sup>4</sup></strong></a>
    .
    <a><strong>Xingmei Wang<sup>4</sup></strong></a>
    .
    <a><strong>Jun Sun<sup>5</sup></strong></a>
    
<p align="center">
    <strong><sup>1</sup>Harbin Engineering University</strong> &nbsp;
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
- [Quick Start](#quick-start)
- [Comparison of Intact and Corrupted Watermarked Code](#comparison-of-intact-and-corrupted-watermarked-code)
- [Evaluation Results of Multi-bit Watermarking](#evaluation-results-of-multi-bit-watermarking)
- [Transformation Rules of ACW](#transformation-rules-of-acw)
- [Cite The Work](#Cite-The-Work)
- [Contact](#contact)

## Quick Start
### Step 1: Install Dependencies

Install the required Python libraries by running:

```bash
pip install -r requirements.txt
```

### Step 2: Prepare the Sourcery API
Login Sourcery API by running:
```bash
sourcery login --token $SOURCERY_TOKEN
```
Please apply for a token on the [official Sourcery website](https://docs.sourcery.ai/Coding-Assistant/Guides/Getting-Started/CI/).
## Comparison of Intact and Corrupted Watermarked Code

## Evaluation Results of Multi-bit Watermarking
<div align="center">
    <figure>
        <img src="assets/result.png" alt="Evaluation Results of Multi-bit Watermarking">
        <figcaption>Table 1. Evaluation Results of Multi-bit Watermark Extraction</figcaption>
    </figure>
</div>>
Table 1 presents our evaluation results. In this experiment,
we collect the watermarked code with four applicable transformations, i.e., each code snippet is embedded with 4-bit
watermarks, where the first two bits are original watermarks and the next two bits are generated based on BCH. We
present the BitACC results before and after error corrections, where the former uncorrected ones are intermediate
results for comparisons.

As shown by the result in Table 1, ACW achieves promising performance on watermark extraction, and furthermore,
the results are significantly increased based on error correction. For example, on the APPS-GPT-4 dataset, the
uncorrected BitACC is 81.92% while it increases to 100% based on our error-correction strategy. Especially, as the bold
values in the table, all the BitACC results are over 98% after correction, indicating the outstanding ability of ACW in
extracting the embedded watermarks.

## Transformation Rules for ACW
The table below shows the complete set of transformation rules for ACW, 
and provides the detailed rule desription, an applicable code snippet, 
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
If you have any questions, or would like to get in touch, please feel free to reach out to us via email at
```noelle@hrbeu.edu.cn```
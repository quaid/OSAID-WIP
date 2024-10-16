---
created: 2024-10-08T19:49:40 (UTC -07:00)
tags: []
source: https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1
author: 
---

# The Open Source AI Definition v.1.0-RC1 - HackMD

> ## Excerpt
> Open Source has demonstrated that massive benefits accrue to everyone after removing the barriers to learning, using, sharing and improving software systems. These benefits are the result of using licenses that adhere to the Open Source Definition. For AI, society needs at least the same essential freedoms of Open Source to enable AI developers, deployers and end users to enjoy those same benefits: autonomy, transparency, frictionless reuse and collaborative improvement.

---
# The Open Source AI Definition

Comment

### [](https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#version-10-RC1 "version-10-RC1")version 1.0-RC1

# [](https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#Preamble "Preamble")Preamble

## [](https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#Why-we-need-Open-Source-Artificial-Intelligence-AI "Why-we-need-Open-Source-Artificial-Intelligence-AI")Why we need Open Source Artificial Intelligence (AI)

Open Source has demonstrated that massive benefits accrue to everyone after removing the barriers to learning, using, sharing and improving software systems. These benefits are the result of using licenses that adhere to the Open Source Definition. For AI, society needs at least the same essential freedoms of Open Source to enable AI developers, deployers and end users to enjoy those same benefits: autonomy, transparency, frictionless reuse and collaborative improvement.

# [](https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#What-is-Open-Source-AI "What-is-Open-Source-AI")What is Open Source AI

When we refer to a "system," we are speaking both broadly about a fully functional structure and its discrete structural elements. To be considered Open Source, the requirements are the same, whether applied to a **system**, a **model**, **weights and parameters**, or other structural elements.

An _Open Source AI_ is an AI system made available under terms and in a way that grant the freedoms<sup class="footnote-ref"><a href="https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#fn1" id="fnref1" smoothhashscroll="">[1]</a></sup> to:

-   **Use** the system for any purpose and without having to ask for permission.
-   **Study** how the system works and inspect its components.
-   **Modify** the system for any purpose, including to change its output.
-   **Share** the system for others to use with or without modifications, for any purpose.

These freedoms apply both to a fully functional system and to discrete elements of a system. A precondition to exercising these freedoms is to have access to the preferred form to make modifications to the system.

## [](https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#Preferred-form-to-make-modifications-to-machine-learning-systems "Preferred-form-to-make-modifications-to-machine-learning-systems")Preferred form to make modifications to machine-learning systems

The preferred form of making modifications to a machine-learning system must include all the elements below:

-   **Data Information**: Sufficiently detailed information about the data used to train the system so that a skilled person can build a substantially equivalent system. Data Information shall be made available under OSI-approved terms.
    -   In particular, this must include: (1) a detailed description of all data used for training, including (if used) of unshareable data, disclosing the provenance of the data, its scope and characteristics, how the data was obtained and selected, the labeling procedures and data cleaning methodologies; (2) a listing of all publicly available training data and where to obtain it; and (3) a listing of all training data obtainable from third parties and where to obtain it, including for fee.
-   **Code**: The complete source code used to train and run the system. The Code shall represent the full specification of how the Data Information was processed and how the training was done. Code shall be made available under OSI-approved licenses.
    -   For example, if used, this must include code used for pre-processing data, code used for training including arguments and settings used, validation and testing, supporting libraries like tokenizers and hyperparameters search code, inference code, and model architecture.
-   **Parameters**: The model parameters, such as weights or other configuration settings. Parameters shall be made available under OSI-approved terms<sup class="footnote-ref"><a href="https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#fn2" id="fnref2" smoothhashscroll="">[2]</a></sup>.
    -   For example, this might include checkpoints from key intermediate stages of training as well as the final optimizer state.

The licensing or other terms applied to these elements and to any combination thereof may contain conditions that require any modified version to be released under the same terms as the original.

## [](https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#Open-Source-models-and-Open-Source-weights "Open-Source-models-and-Open-Source-weights")Open Source models and Open Source weights

For machine learning systems,

-   An **AI model** consists of the model architecture, model parameters (including weights) and inference code for running the model.
-   **AI weights** are the set of learned parameters that overlay the model architecture to produce an output from a given input.

The preferred form to make modifications to machine learning systems also applies to these individual components. “Open Source models” and “Open Source weights” must include the data information and code used to derive those parameters.

# [](https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#Definitions "Definitions")Definitions

-   AI system<sup class="footnote-ref"><a href="https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#fn3" id="fnref3" smoothhashscroll="">[3]</a></sup>: An AI system is a machine-based system that, for explicit or implicit objectives, infers, from the input it receives, how to generate outputs such as predictions, content, recommendations, or decisions that can influence physical or virtual environments. Different AI systems vary in their levels of autonomy and adaptiveness after deployment.
-   Machine learning<sup class="footnote-ref"><a href="https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#fn4" id="fnref4" smoothhashscroll="">[4]</a></sup>: is a set of techniques that allows machines to improve their performance and usually generate models in an automated manner through exposure to training data, which can help identify patterns and regularities rather than through explicit instructions from a human. The process of improving a system’s performance using machine learning techniques is known as "training".

___

1.  These freedoms are derived from the [Free Software Definition](https://www.gnu.org/philosophy/free-sw.en.html). [↩︎](https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#fnref1)
    
2.  The Open Source AI Definition does not take any stance as to whether model parameters require a license, or any other legal instruments, and whether they can be legally controlled by any such instruments once disclosed and shared. [↩︎](https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#fnref2)
    
3.  [Recommendation of the Council on Artificial Intelligence OECD/LEGAL/0449, Organization for Economic and Co-operation Development (OECD), 2024](https://legalinstruments.oecd.org/en/instruments/OECD-LEGAL-0449) [↩︎](https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#fnref3)
    
4.  [Explanatory memorandum on the updated OECD definition of an AI system, OECD Artificial Intelligence Papers, No. 8, OECD Publishing, Paris](https://doi.org/10.1787/623da898-en) [↩︎](https://hackmd.io/@opensourceinitiative/osaid-1-0-RC1#fnref4)

# Assessing Capabilities of Large Language Models for Multi-Level Modeling


This repository contains the material used in the paper "Assessing Capabilities of Large Language Models for Multi-Level Modeling"
It includes the case studies used in the project, the corresponding XMI files, a prompt template, and a set of generated diagrams derived from the models.

The goal of this repository is to provide a clear and reusable reference package for inspecting the modeling inputs, understanding the case studies, and comparing the generated outputs.

---

## Repository Content

The repository is organized as follows:

```text
.
├── XMI project used as example/
│   └── Example XMI project used as reference for LLMs
│
├── case studies used/
│   └── Case studies considered in the project
│
├── generated_diagrams/
│   └── Diagrams generated from the XMI/modeling material
│
├── prompt_template.txt
│   └── Prompt template used to guide the generation process
│
└── README.md
```

---

## Purpose of the Repository

This repository is intended to support the inspection and reuse of the modeling material used in the project.

In particular, it provides:

* The XMI project used as an example input;
* The case studies used during the analysis;
* The XMI file used as test material;
* The prompt template adopted for the generation process;
* The generated diagrams were obtained from the modeling inputs.

The material can be used to reproduce the reasoning process, examine the structure of the prompts, and compare the generated diagrams with the original case study descriptions.

---

## How to Use This Repository

### 1. Inspect the case studies

Open the `case studies used/` folder to review the case study material considered in the project.

These files provide the domain descriptions and modeling scenarios used as input for the analysis.

### 2. Review the XMI example project

Open the `XMI project used as example/` folder to inspect the reference XMI project.

This material can be used to understand the structure of the input model and how the examples were organized.

### 3. Check the prompt template

The file `prompt_template.txt` contains the prompt structure used to guide the generation process.

This template can be reused or adapted for similar experiments involving XMI files, model interpretation, or diagram generation.

### 4. Inspect the generated diagrams

The folder `generated_diagrams/` contains the diagrams generated from the available modeling material.

These outputs can be compared with the original case studies and XMI files to evaluate whether the generated diagrams correctly represent the intended models.

## Notes

This repository is not intended to provide a complete software toolchain.
Instead, it serves as a structured artifact that contains the input material, the prompt template, and the generated outputs used in the project.

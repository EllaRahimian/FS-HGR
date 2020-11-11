## Elahe Rahimian, Soheil Zabihi, Amir Asif, Dario Farina, Seyed Farokh Atashzar, and Arash Mohammadi

$\mathrm{5}$-way $\mathrm{1}$-shot classification. Each task $\mathcal{T}$, represented in a purple box, is associated with a training set $\mathcal{D}^{train}$ and a prediction set $\mathcal{D}^{test}$. Here, for constructing $\mathcal{D}^{train}$, first, $\mathrm{5}$ classes are sampled from the $\mathscr{D}_{meta-train}$, and then one example from each of these 5 classes (each corresponding with a label $1$-$5$) are sampled. $\mathcal{D}^{test}$ consists of $1$ example sampled from one of those $\mathrm{5}$ classes. The $\mathscr{D}_{meta-test}$ is represented in the same approach, covering a different set of datasets which do not include any classes presented in any of the datasets in $\mathscr{D}_{meta-train}$. Moreover, $\mathscr{D}_{meta-val}$ is defined in the same way to determine the hyper-parameters of the model
![Figure1](https://user-images.githubusercontent.com/50590345/98750785-cf956480-238c-11eb-8449-6b83eabbb26e.jpg)

>This work is motivated by the recent advances in Deep Neural Networks (DNNs) and their widespread applications in human-machine interfaces. 
DNNs have been recently used for detecting the intended hand gesture through processing of surface electromyogram (sEMG) signals. 
The ultimate goal of these approaches is to realize high-performance controllers for prosthetic. However, although DNNs have shown superior accuracy than conventional methods when large amounts of data are available for training, their performance substantially decreases when data are limited. Collecting large datasets for training maybe feasible in research laboratories, but it is not a practical approach for real-life applications.

>Therefore, there is an unmet need for the design of a modern gesture detection technique that relies on minimal training data while providing high accuracy.
Here we propose an innovative and novel “Few-Shot Learning” framework based on the formulation of meta-learning, referred to as the FS-HGR, to address this need. Few-shot learning is a variant of domain adaptation with the goal of inferring the required output based on just one or a few training examples. More specifically, the proposed FS-HGR quickly generalizes after seeing very few examples from each class.


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)

```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes
![1](https://user-images.githubusercontent.com/50590345/98749392-94456680-2389-11eb-8f71-fbdd01e6d363.jpg)
Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/EllaRahimian/Test-one/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

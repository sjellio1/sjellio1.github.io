## MAE 598 Project

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"></script>

You can use the [editor on GitHub](https://github.com/sjellio1/sjellio1.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

sdfsdfsfdsfs

<div>
$$f(x) = \sum_{k=1}^{K}\alpha_{k}$$
</div>

aaa

### Introduction

This project started with the idea for a rocket landing game in which the user would user three controls (thrust, torque left, torque right) to steer a rocket from a random initial position and random initial angle (±30°).  From the initial idea for the game, came the thought of applying machine learning to optimize a neural network to land the rocket.  The input consists of a 0-5 integer corresponding to 3 booleans (thrust, torque left, torque right).  The input is enumerated as follows:


<div>
$$x_1 = x$$

$$x_2 = y$$

$$x_3 = \theta$$

$$x_4 = \dot{x}$$

$$x_5 = \dot{y}$$

$$x_6 = \dot{\theta}$$
</div>

The neural network output consists of a 0-5 integer corresponding to 3 booleans (thrust, torque left, torque right).  The output is enumerated as follows:

1. Input=0: No Thrust; No Torque
2. Input=1: No Thrust; Torque Left
3. Input=2: No Thrust; Torque Right
4. Input=3: Thrust; No Torque
5. Input=4: Thrust; Torque Left
6. Input=5: Thrust; Torque Right
	

And so, the optimization problem became the following: optimize a neural network that can input the current rocket state and output a discrete frame control to most efficiently land the rocket at a designated landing position and state.  This objective would be achieved using a tensorflow1 Python API as well as a framework developed by Open AI Gym2.  The neural network, model, reward function, and analysis was left to be developed.  The framework for the neural network implementation and model feedback can be visualized in Figure 1.

### The Model

<img src="https://github.com/sjellio1/sjellio1.github.io/blob/master/_assets/model.png" class="img-responsive" alt="">

### Analysis

### Conclusion
































### END HERE

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

<iframe width="560" height="420" src="http://www.youtube.com/embed/oHg5SJYRHA0?color=white&theme=light"></iframe>

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

Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/sjellio1/sjellio1.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

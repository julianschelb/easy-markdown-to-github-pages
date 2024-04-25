
# Document Analysis: Project Report Template

_Group members: Name 1, Name 2, Name 3_

> This repository serves as a template for your project reports as part of the Document Analysis lecture. To set up your project report as a webpage using GitHub Pages, simply follow the steps outlined in the next chapter.
>
>**Some Organizational Details:** Get creative with your project ideas! Just make sure they relate to Natural Language Processing and incorporate this specified dataset: [Link to data](https://huggingface.co/datasets/webis/tldr-17), [Link to paper](https://aclanthology.org/W17-4508.pdf). Submissions should be made in teams of 2-3 students. Each team is expected to create a blog-style project website, using GitHub Pages, to present their findings. Additionally, teams will deliver a lightning talk during the final lecture to discuss their project. Add all your code, such as Python scripts and Jupyter notebooks, to the `code` folder. Use markdown files for your project report. [Here](https://docs.gitlab.com/ee/user/markdown.html) you can read about how to format Markdown documents. 
>
>Have fun working on your project! 🥳

## Setup The Report Template

1. **Fork the Repository:** Begin by creating a copy of this repository for your own use. Click the "Fork" button at the top right corner of this page to do this.

2. **Configure GitHub Pages:** Navigate to "Settings" -> "Pages" in your newly forked repository. Under the "Branch" section, change from "None" to "main" or "master", depending on your default branch, and then click "Save".

3. **Customize Configuration:** Modify the `_config.yml` file within your repository to personalize your site. Update the `title:` to reflect the name of your site and adjust the `description:` to provide a brief summary.

4. **Content Creation:** Start building your site by modifying the `README.md` (which serves as the home page) and by adding new Markdown files for additional pages. Use the standard [GitHub Markdown syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) for formatting. Refer to `example.md` in the repository for an example. **Important:** Ensure to prepend your new `.md` files with the header `--- layout: default ---`, as shown at the beginning of `example.md`.

5. **Update Site Navigation:** Incorporate your new Markdown files into the website’s navigation by editing the `_config.yml` file. Under `navigation:`, add each new page with `- title:` for the page name and `url:` linked to the corresponding `.md` file. Be sure to remove or update the navigation entries related to any example or template content you replace or remove.

6. **Access Your Site:** Return to "Settings" -> "Pages" in your repository to find the URL to your live site. It typically takes a few minutes for GitHub Pages to build and publish your site after updates.


## Introduction

Begin by providing context for the project and provide a summary of related work or studies that have addressed similar problems. 

### Research Question

Clearly describe the primary question or problem the project aims to address.

### Related Work

Review existing literature or previous studies that are relevant to the project's focus.

## Dataset

Provide a description of the dataset used, including its sources, size, features, and why it is specifically suited for addressing the research question.

## Experiments

### Setup 

Outline the tools, software, and hardware environment, and configurations used for conducting the experiments. Include instructions on how to install the necessary dependencies.

Ensure the Python version and dependencies are is clearly documented. Provide instructions on how to re-create your environemnt, for example: 

```bash
conda create --name myenv python=<version>
conda activate myenv
```

Include a `requirements.txt` file in your project repository. This file should list all the Python libraries and their versions needed to run the project. Provide instructions on how to install these dependencies using pip, for example:

```bash
pip install -r requirements.txt
```

### Run Experiments

Describe the experimental procedure in a way that allows for reproduction of the results, including specific steps, processes involved, and any variables controlled during the experiments. Include detailed instructions on how to execute the experiments. Specify the exact file or script that should be run, along with the command to execute it. For example:

```bash
python run_experiments.py
```

### Preprocessing Steps

Detail any data cleaning, normalization, or transformation processes applied to prepare the dataset, including rationale for the chosen methods.

### Model Training

Explain the methodologies and algorithms used for training the models. Include parameter settings, training protocols, and any steps taken to ensure the validity of the models.

## Results and Discussion

Present the findings of the experiments, including visual or statistical evidence. Discuss how these results address the research question and relate to the hypotheses and literature cited.

## Conclusion

Summarize the key outcomes of the project, reflect on the research findings, and state the final conclusions drawn from the study.

## References

List all academic and professional sources cited in the report in an appropriate citation format.

## Appendix

If needed, include supplementary material such additional graphs that support the report’s content but are too extensive to include in the main text.

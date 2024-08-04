# Hello!! These are the projects I would like to showcase!

I learn based on experience and experiments. So instead of taking notes in google docs or notion, I tend to just do these projects with some annotations for myself to come back to later. Here are some of said proejcts 

Deep learning stuff!
- **Visualizing neuralnets as crumpled paper.ipynb** People suck at explainning neuralnets. They make it seem like this mystic thing, when all its doing is taking a hyperplane and applying a series of non-linear transformations to it until it fits the shape of whatever point cloud you have...Like crumpling and folding a piece of paper until it fits the data! I try to get that point across with this notebook. 

- **Visualizing how normalizing affects gradients.ipynb** I never properly understood why model convergence improves with better normalized data. So I made a notebook showing how the shapes of the gradient surface varies with different normaization methods!

- **Implementing pytorch sequential from scratc.ipynb** Implementing neural networks from scratch without any reference tutorials using just numpy + I wanted it to be a pytorch-sequential-api-like package as well. Very proud of this one because I did not look up any reference code aside from numpy docs.

- **NLP political sentiment analysis tool.pdf** Did you know the word "billionaire" when used in reference to Elon Musk on Twitter is most commonly connotated with the words "narcssist", "fascist", and "nazi"? I used Twitter API to scrape tweets containning a certain keyword or user mention to build a corpuse dataset. Then I trained a word2vec model to learn word embeddings withint his corpus. By doing that, I can then analyze which words share similar embeddings aka connotations with each other. Which allows me to make unsupervised, real-time sentiment analysis. This one is in a different repository. Here's the link to the summary slides: https://github.com/macmacmacmac/Twitter-sentiment-analysis/

- **Identifying depression from brain region sizes.ipynb** An anonymized and cleaned version of a school project where I analyzed a dataset of depression vs. control patients and their differences in brain region sizes. In total, there were 253 different brain regions which had a statistically significant size difference between healthy and depressed subjects. Surprisingly, in certain regions depressed subjects had a higher average region size than control subjects. All the cleaning and preprocessing was done beforehand, so the notebook just shows the statistical testing (t-test for difference of means with alpha value = 0.05). 

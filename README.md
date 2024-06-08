[# The Sovereign University Content Repo

Welcome to the Sovereign University Content Repo! There's a chance that if you are here, it is to contribute to this larger-than-us project, which aims at consolidating the first multilingual and open-source e-learning platform focused on Bitcoin. (If you're just lost on GitHub, visit our [website](https://planb.network/) to learn more about Bitcoin).

Assuming you're here to contribute, I will detail the inner workings of the content management and how you can assist us -- either by producing new content or translating/reviewing content in your language.

Thank you for your time, involvement, and effort in this project. Here we believe in a [value-for-value model](https://dergigi.com/2021/12/30/the-freedom-of-value/) and we'll do our best to reciprocate for your contribution based on your Proof-of-Work. Moreover, by participating in creating valuable Bitcoin resources for your local community, tips from them could also come your way.

## Repo Structure and Content Management

This repo is organized around three main directories, which are:

- `courses`: comprising all the courses about Bitcoin, Lightning, Cryptography, Mining, and so on.
- `resources`: consisting of various types of resources about Bitcoin, such as books, company info, or podcasts.
- `tutorials`: consisting of how-to articles, categorized into themes like exchange, merchant, node, privacy, and so on.
  
Each individual content piece, which is a markdown file, is defined by its location in this tree structure and by its language in the name. For instance, the Italian tutorial about Nerd-Miner would have the following path: `sovereign-university-data/tutorials/mining/nerd-miner/it.md`.

The different images referred to in the content are saved in the `assets` folder, which is at the same level as the corresponding content.

## How to Become a PlanB Network Content Builder?

### Become a Translator/Reviewer

To scale the translation process, we are testing a combined AI x Human approach. We believe that with the use of Large Language Models (LLMs), like the infamous ChatGPT, we can translate a vast number of resources in a relatively short amount of time. We therefore created a [simple program](https://github.com/Asi0Flammeus/LLM-Translator) that leverages the ChatGPT API to translate technical contents and can add support for an additional language with ease.

While this kind of automated translation is more effective and efficient than traditional methods, such as Google Translate or DeepL, it is far from perfect -- that's when the human factor comes in. Indeed, once new content is produced (pushed into the `main` branch), it is automatically translated into the supported languages. Then, those translations MUST be reviewed by a fluent language speaker to ensure high-quality content in all languages. Most of the time, these reviews will correct wrongly translated expressions or grammatical sentence structures.
Once content is reviewed, it will be reviewed by other peers before being merged into the dedicated branch for the corresponding language, which will periodically be merged into the main branch.

Now that you understand the high-level procedure of the translation, you want to review a content you have to complete its associated issue via a PR from your local branch to the corresponding language branch (e.g. `italian-translation-and-review`).

**If you are not familiar with Git, don't worry, we have made a [step-by-step tutorial](https://notes.decouvrebitcoin.com/s/K9ijdGj9X) with comprehensive explanations.** 
Moreover, we are working on a [local interface](https://github.com/pythcoiner/planb_contributor_client) to ease the workflow by hiding all Github mechanics to contributors. 

# On Meta-Prompting

Repository for the paper ["On Meta-Prompting"](https://arxiv.org/abs/2312.06562), by De Wynter et al.

## What?

This paper introduces a formal mathematical framework to understand prompting in LLMs, along with its user interaction. A brief introduction to category theory and LLMs is provided. 

We show that meta-prompt generated prompts produce vastly better results than simple prompts, to a $p< 0.01$, in terms of user preference. We also use our framework to prove _why_ these meta-prompt generated prompts are so effective.

## Why?

Having a theoretical background to understand LLMs is valuable because _we don't know how these things work_. In fact, we don't even have probability bounds on their correctness for _any_ algorithm!
Better understanding of these models from a mathematical point of view is paramount for their safe and effective deployment. 

## Category Theory, Really?

Category theory may seem daunting (our AAAI reviewers thought so) with all them crazy arrows and diagrams! But it is a beautiful and--more importantly--_effective_ language that allows us to circumvent issues like stochasticity (see the probability bounds above!).

With that we can model effectively user interaction, understand LLMs, and describe higher-order interactions like human-machine dialogue (because a meta-prompt is a prompt is a meta-prompt :)). So don't let these arrows get to you!
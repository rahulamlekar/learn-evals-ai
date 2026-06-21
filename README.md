# A Browser Game on AI Evals

I've wanted to make evals more accessible for a while, so I built a [browser game](https://learnevals.ai/) on the topic.

<img width="1000" height="563" alt="this-robot-needs-evals" src="https://github.com/user-attachments/assets/54d139b7-cc79-4b7e-affb-7d5cf7455708" />

_Disclaimer: This post does not represent the views of my employer. Opinions are my own._

### The Idea
Introduce evals to a non-technical audience in a fun way. You fix your dessert shop's new robot, Bolt, who's been botching every order.

## The Methodology
You fix Bolt by annotating his behavior, prioritizing the worst failure mode, and writing an eval. Real evals get complex, so I distilled it to a simple annotate → prioritize → evaluate loop — short enough for a 10-minute game, but enough to give you a feel for a real workflow.

* **Annotate** — note 5 of Bolt's failures
* **Prioritize** — pick the highest-impact one to fix
* **Evaluate** — write your first eval

## Future Explorations
If you want to dig deeper into evals, I'm a big fan of [Hamel Husain](https://github.com/hamelsmu) and [Shreya Shankar](https://github.com/shreyashankar)'s work on evals. It's a great primer to get started.

I hope you like it. Let me know what you think!

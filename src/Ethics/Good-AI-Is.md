# AI Should Be...

## Easy to Steal
It is critical to avoid AI being used to concentrate power. If the nature of AI is such that it is easy to copy, then the power created by AI is likely to be distributed across more people. In many ways, AI already fits well in this regard. For most digital products the balance shifts in favor of making copying easy. There are certainly programs which haven't been cracked, data that hasn't leaked, etc. but once the box is open it can't easily be closed. That said, it's quite possible that the very open environment of today will be thrown out the window when models become more powerful making copying harder. I'm imagining if state of the art models ran in the proprietary Big Corp programming language, and any single Big Corp engineer couldn't access the full model, and Big Corp's powerful models will only run on a gargantuan Big Corp Computerator 3. This isn't too far off from the current state of affairs, but I think there is a lot of hope for copying to get easier, not harder. First, the internet is founded on open principles. If Big Corp can copy data from the internet so can anyone. Second, the ML field has a strong tradition of open source. Big Corp could certainly build their own proprietary framework, hardware, etc. but it would mean re-building much of the infrastructure they rely on and would slow forward progress in the short term. That means that at least in the short term, it should be possible to replicate Big Corp's models and results even if weights aren't leaked.

### Steps in this direction
* Open source frameworks for inference and training
* Runs on commodity hardware
* Open weights for foundation models
* Open data initiatives - internet archive, libgen, Wikipedia, etc.

## Capable at Defensive Tasks
Bad actors will use AI for harm. It is essential that AI lends itself to defensive use at least as well as offensive use. For example, if AI can be used to generate spam emails, it is essential that it can also be used to detect spam emails equally well. This applies to militant use cases, but also just to general safety and comfort. When using online platforms, people should be able to select what kind of content they'd like to see and have an agent filter content.

### Steps in this direction
* Efforts targeting detecting whether content meets/breaks an arbitrary policy (i.e. is this PG13? or Would Dave enjoy this?)
* Work to integrate personalized filters/policies into platforms
* Work using AI to stop harm IRL. Many of these fall into "unethical" territory for me, but there are definitely approaches I could support. I think my limit here is that these technologies be opt-in, and stay as close to the real harm as possible. For example, let's say truck driver Jim has a vendetta against cyclists. The right moment to intervene is not when Jim tells Bob on the phone how he's counts each pedestrian he hits as 10 points, it is when Jim is closing in on a cyclist in his truck and isn't hitting the brakes.

## Scalable - large and small, wide and narrow
For current AI models there is a direct trade-off between the compute requirements and quality of a model. Large models need incredible amounts of compute, but produce convincing results. Small models can be run on consumer hardware, but offer very limited results. Ideally, users would have full control over this trade-off, running one version of a single foundation model on whatever platform they choose and getting results consistent with the amount of compute/memory available. There is also a trade-off between memory usage/model size and the breadth of tasks a model is capable of. Cloud-based transcription models, for example, can transcribe any word in almost any language, whereas a mobile phone assistant can only recognize a few words without internet access, but has similar accuracy on those words to a large transcription model. Ideally users would also control this trade-off, using only the portions of a model required for a specific use case. Given control of these two trade-offs, useful AI wouldn't necessarily require petaflops of compute.

### Steps in this direction
* Quantization research - less memory, less performance, same basic model
* Distillation research - mega-models train small models on one particular topic
* mixture-of-experts research - possible to separate out certain abilities?

## Efficient
The laws of physics and information theory describe an upper bound on how much computation can be done with a fixed amount of energy. Every year chips get closer to this bound. T
here is also a more open-ended question governing AI efficiency - how much compute is required per unit of intelligence? Together, the answers to these two questions form the bound for how efficient an AI could be. Multiply the minimum amount of energy required per flop by the minimum number of flops needed to reach a given intelligence level, and that is the ideal performance. The best example we have of this is ourselves, and based on all estimates the human brain is incredibly efficient at producing intelligence.


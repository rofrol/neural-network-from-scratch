## Inspiration

>I wanted to write some from-scratch-in-C++ neural network implementations, and I wanted to do it with a strictly base OpenBSD system. Someone remarked that is a pretty random pairing, but it worked out ok.
>
>I have a decent overview understanding of most machine learning algorithms, and I have done some linear classifier and decision tree work, but for some reason I have avoided neural networks. On some level, I suspect that Deep Learning being so trendy tweaked a little bit of contrarian in me, and I still have a little bit of a reflexive bias against “throw everything at the NN and let it sort it out!”
>
>In the spirit of my retro theme, I had printed out several of Yann LeCun’s old papers and was considering doing everything completely off line, as if I was actually in a mountain cabin somewhere, but I wound up watching a lot of the Stanford CS231N lectures on YouTube, and found them really valuable. Watching lecture videos is something that I very rarely do — it is normally hard for me to feel the time is justified, but on retreat it was great!
>
>I don’t think I have anything particularly insightful to add about neural networks, but it was a very productive week for me, solidifying “book knowledge” into real experience.
>
>I used a common pattern for me: get first results with hacky code, then write a brand new and clean implementation with the lessons learned, so they both exist and can be cross checked.
>
>I initially got backprop wrong both times, comparison with numerical differentiation was critical! It is interesting that things still train even when various parts are pretty wrong — as long as the sign is right most of the time, progress is often made.
>I got a much better gut-level understanding of overtraining / generalization / regularization by exploring a bunch of training parameters.

- https://www.facebook.com/permalink.php?story_fbid=2110408722526967&id=100006735798590
- https://news.ycombinator.com/item?id=16518726
- http://cs231n.stanford.edu/
  - teaches python basics also

So I'm using this tutorial http://karpathy.github.io/neuralnets/ from Andrej Karpathy who is also involved in cs231n and works in Tesla.


## Tutorials

- A Neural Network in 11 lines of Python https://iamtrask.github.io/2015/07/12/basic-python-network/
  - more explanations http://www.snee.com/bobdc.blog/2016/12/a-modern-neural-network-in-11.html
  - https://aboveintelligent.com/a-neural-network-in-11-lines-of-javascript-d58b38330178
    - https://github.com/lucamug/simple-neural-network-in-javascript
- https://medium.freecodecamp.org/how-to-create-a-neural-network-in-javascript-in-only-30-lines-of-code-343dafc50d49
- https://coderoncode.com/machine/learning/2016/06/06/machine-learning-a-simple-neural-network.html
- https://medium.freecodecamp.org/building-a-3-layer-neural-network-from-scratch-99239c4af5d3
- http://www.wildml.com/2015/09/implementing-a-neural-network-from-scratch/
- https://thecodacus.com/neural-network-scratch-python-no-libraries/
- https://github.com/sar-gupta/neural-network-from-scratch
- In Processing language https://medium.com/typeme/lets-code-a-neural-network-from-scratch-part-1-24f0a30d7d62
- https://chatbotslife.com/deep-learning-in-7-lines-of-code-7879a8ef8cfb
- https://medium.com/technology-invention-and-more/how-to-build-a-simple-neural-network-in-9-lines-of-python-code-cc8f23647ca1
    - https://github.com/miloharper/simple-neural-network
    - https://news.ycombinator.com/item?id=14661904
- http://neuralnetworksanddeeplearning.com/chap1.html
  - http://neuralnetworksanddeeplearning.com/chap2.html
- https://www.kaggle.com/ancientaxe/simple-neural-network-from-scratch-in-python

## Basics

- https://www.springboard.com/blog/beginners-guide-neural-network-in-python-scikit-learn-0-18/
- http://natureofcode.com/book/chapter-10-neural-networks/
- Neural Networks Demystified https://www.youtube.com/watch?v=bxe2T-V8XRs&list=PLiaHhY2iBX9hdHaRr6b7XevZtgZRa1PoU

## Theory

- https://en.wikipedia.org/wiki/Real-valued_function
- https://pl.khanacademy.org/math/ap-calculus-ab/ab-derivative-intro/ab-derivative-intuition/v/derivative-as-a-concept
- https://www.khanacademy.org/math/multivariable-calculus/multivariable-derivatives/gradient-and-directional-derivatives/v/gradient
- derivative.js https://gist.github.com/andersonfreitas/11055882
- https://en.wikipedia.org/wiki/Derivative
- https://en.wikipedia.org/wiki/Sigmoid_function

## Neural networks

- Clean implementation of feed forward neural networks https://github.com/danijar/layered
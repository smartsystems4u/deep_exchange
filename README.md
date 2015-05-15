# deep_exchange
Investigation of re-use of learned representations to generalize learning or bootstrap new learning tasks

This project is inspired by the Deepmind paper [1]. In the paper a CNN is trained to play atari games. I'd like to investigate a) tasks that are slightly more complex, and b) ways to bootstrap learning. Learning with a deep learning algorithm takes a long time due to the complexity that needs to be experienced in order to encode it into the CNN. I wonder if we can discover emergent CNN organization that is amenable to transport to new tasks. This potentially drasticly reduce training time. Inspiration for this comes from the "deep structures" argument put forward by Noam Chomsky [2].

In this project I'll setup a q-learning agent for a continuous control task (steering behavior) and define a perception model that is general across multiple tasks. After training the agent we'll investigate candidates for CNN modules that can be transferred.

[1] Mnih, Volodymyr, et al. "Playing atari with deep reinforcement learning." arXiv preprint arXiv:1312.5602 (2013).

[2] Searle, John R. Chomsky's revolution in linguistics. Vol. 18. New York Review of Books, 1974.

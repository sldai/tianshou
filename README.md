This is a pytorch based reinforcement learning library forked from [tianshou](https://github.com/thu-ml/tianshou).

These reinforcement learning methods requires neural networks as function approximators which are customized by users. For my convenience, I modify the interface of the original methods. Now user customized neural network should output an abstract vector with the same length of the agent actions. Then the logits will be transformed into actual actions by the reinforcement learning policies. 
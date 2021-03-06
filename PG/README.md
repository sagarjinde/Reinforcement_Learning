# Policy Gradient

## CartPole
<img src="./figs/cartpole.gif" width="70%">

### Environment
Used OpenAI Gym Environment. Refer to [wiki](https://github.com/openai/gym/wiki/CartPole-v0) for details.

### Observation
Comparing all possible combinations of reward-to-go and advantage-normalization

| reward-to-go / </br>advantage-normalization | False | True |
| --- | --- | --- |
| <b>False</b> | ![cp_FF](https://github.com/sagarjinde/Reinforcement-Learning-Project/blob/master/PG/figs/cp_FF.png) | ![cp_TF](https://github.com/sagarjinde/Reinforcement-Learning-Project/blob/master/PG/figs/cp_TF.png) |
| <b>True</b> | ![cp_FT](https://github.com/sagarjinde/Reinforcement-Learning-Project/blob/master/PG/figs/cp_FT.png) | ![cp_TT](https://github.com/sagarjinde/Reinforcement-Learning-Project/blob/master/PG/figs/cp_TT.png) |

**Result:** Best results were obtained using both reward-to-go and advantage-normalization 

## LunarLander
![lunarlander](https://github.com/sagarjinde/Reinforcement-Learning-Project/blob/master/PG/figs/lunarlander.gif)

### Observation
Comparing all possible combinations of reward-to-go and advantage-normalization

| reward-to-go / </br>advantage-normalization | False | True |
| --- | --- | --- |
| <b>False</b> | ![ll_FF](https://github.com/sagarjinde/Reinforcement-Learning-Project/blob/master/PG/figs/ll_FF.png) | ![ll_TF](https://github.com/sagarjinde/Reinforcement-Learning-Project/blob/master/PG/figs/ll_TF.png) |
| <b>True</b> | ![ll_FT](https://github.com/sagarjinde/Reinforcement-Learning-Project/blob/master/PG/figs/ll_FT.png) | ![ll_TT](https://github.com/sagarjinde/Reinforcement-Learning-Project/blob/master/PG/figs/ll_TT.png) |

#### Result: 
- When both reward-to-go and advantage-normalization are True, the score curve is smooth with less variance
- When reward-to-go is False, it takes more time to solve the problem
- Best results were obtained using both reward-to-go and advantage-normalization
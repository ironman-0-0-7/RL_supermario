# RL_supermario
Reinforcement learning based bot for playing super mario game using Advantage actor critic 
<p>
  <img src=https://github.com/ironman-0-0-7/RL_supermario/blob/master/mario.jpg width="350" title="hover text">
</p>


## Advantage actor Critic (AC2)

There is a actor and critic .Actor is a neural netwrok which tells us what to do ,means it provide us 
the probality of actions .Critic is also a neural network which tells us how good our actions were,it
outputs state value .In practise policy and value networks partially overlap ,mostly due to the efficiency
and convergence consideration.
<p>
  <img src=https://github.com/ironman-0-0-7/RL_supermario/blob/master/photo_2020-09-25_12-44-02.jpg width="650" title="hover text">
</p>

The network is trained by reducing actor_loss+critic_loss.
<p>
  <img src=https://github.com/ironman-0-0-7/RL_supermario/blob/master/photo_2020-09-25_12-32-04.jpg width="650" title="hover text">
</p>

A(s,a) is advantage of action
<p>
  <img src=https://github.com/ironman-0-0-7/RL_supermario/blob/master/1%20SvSFYWx5-u5zf38baqBgyQ.png width="350" title="hover text">
</p>

why entropy term 

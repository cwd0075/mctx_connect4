# mctx_connect4  
The strongest Connect 4   
How to use the MCTX library to implement the classic Monte Carlo Tree Search (MCTS) algorithm to play Connect 4.  
At 10000 simulations, the agent was able to beat all online Connect 4 bots   

Origin from:  
https://github.com/Carbon225/mctx-classic  
https://github.com/google-deepmind/mctx  

MCTX-az, continue new search leaf node by re-using previous populated search tree. It run faster, but it lose to the above original. It use alphazero_policy and get_subtree function of mctx  
https://github.com/lowrollr/mctx-az/blob/main/connect4.ipynb   

MCTX to play the pgx Connect 4 environment  
https://github.com/sotetsuk/pgx/blob/main/colab/mcts_connect_four.ipynb  

Other details, please find my UpNote title MCTX  

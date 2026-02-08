# LinearTensorParallel
Linear tensor row/column-wise tensor parallelism


Реализованы row-wise / column-wise tensor parallelism с использованием torch.  
В качестве gt используются градиенты и веа полученные из torch.nn.Linear.  

основыне используемые в процессе источники:  
https://huggingface.co/spaces/nanotron/ultrascale-playbook?section=tensor_parallelism_in_a_transformer_block  
https://arxiv.org/html/2506.09501v1  
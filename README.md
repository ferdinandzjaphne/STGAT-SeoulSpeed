# STGAT: Spatial-Temporal Graph Attention Networks for Traffic Flow Forecasting
<p align="center">
  <img width="600" height="450" src=./figure/process.jpeg>
</p>

This is the implementation of Spatial-Temporal Graph Attention Networks for Traffic Flow Forecasting(for IJCAI 2020)
More details will be added ...

train.py
util.py
run_demo.py
model_stgat.py
draw.py
experiment

data # file

baselines
    train_base.py
    run_demo_base.py
    gwnet.py
    rnn.py
    stgcn.py
    experiment_base #file


## urban-core training command 
python train.py --adj_path= --num_nodes=304 --in_dim=1 --out_dim=1 --data_path=data/urban-core --adj_path='data/urban-core/distance.csv'
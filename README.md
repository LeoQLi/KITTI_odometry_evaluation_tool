# KITTI odometry evaluation tool

## Usage

To evaluate one or more given trajectories, such as `09_pred.txt` and `10_pred.txt`  in the `data` folder:

        python evaluation.py -result_dir=./data/ -eva_seqs=09_pred.txt,10_pred.txt 

To evaluate all trajectories in the `data` folder:

        python evaluation.py -result_dir=./data/ -eva_seqs=09_pred.txt,10_pred.txt 

The evaluation results will be generated in folder `./data/xx_eval/`. 

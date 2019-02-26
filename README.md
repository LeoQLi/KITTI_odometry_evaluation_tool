# KITTI odometry evaluation tool

## Usage

To evaluate one or more given trajectories, such as `09_pred.txt` and `10_pred.txt`  in the `data` folder:

        python evaluation.py --result_dir=./data/ --eva_seqs=09_pred,10_pred 

To evaluate all trajectories in the `data` folder:

        python evaluation.py --result_dir=./data/ --eva_seqs=* 

The evaluation results will be generated in folder `./data/xx_eval/`. 
![evaluation example](https://github.com/LearnerLee/KITTI-odometry-evaluation-tool/blob/master/doc/09_error_seg.png)
![evaluation example](https://github.com/LearnerLee/KITTI-odometry-evaluation-tool/blob/master/doc/09_path.png)
![evaluation example](https://github.com/LearnerLee/KITTI-odometry-evaluation-tool/blob/master/doc/09_rpy.png)

## Reference
<a href="http://www.cvlibs.net/datasets/kitti/eval_odometry.php" target="_blank">KITTI odometry development kit</a>

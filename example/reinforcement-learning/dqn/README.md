Deep Q-Network Example in MXNet
===============================

### Prerequisites:
  - Install the development version of [MXNet](https://github.com/dmlc/mxnet) first.
  - Install the [Arcade Learning Environment (ALE)](https://github.com/mgbellemare/Arcade-Learning-Environment)
    - You might need to copy the `ale.cfg` into the dqn folder
  - Install SciPy: `python -m pip install --user scipy`
  - Make sure the Roms are available for example download as: `git clone https://github.com/npow/atari/tree/master/roms` 

### Training
  - Run `python dqn_demo.py` to train AI for Breakout.
  - In case `breakout.bin` is not found run as: `python dqn_demo.py -r <Path_To_Roms>`


### Testing
Run `python dqn_run_test.py -d YOUR_SAVE_DIR -m QNet -e EPOCH_RANGE -v 1`

### Sample Play Video
https://www.dropbox.com/s/cglqxaipyap1pe7/dqn-breakout-197.avi?dl=0
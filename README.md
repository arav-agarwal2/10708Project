# 10708 EGNN Improvement Project

This main branch contains the egnn code simplified for our purposes, and the other branches contain the code necessary to run the experiments we provide in the report.

If you are planning on running it, the easiest way to do so is to use colab, which has all requirements minus wandb.

To run the code:
1. Checkout the appropriate branch [`git checkout ganloss` or  `git checkout idm`].
2. Install the requirements using `pip install -r requirements.txt && pip install wandb`.
3. Run the full-scale training experiments using `python3  main_qm9.py`, where the hyperparameters can be specified via the arguments.


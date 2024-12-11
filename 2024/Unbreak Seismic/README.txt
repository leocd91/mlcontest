Caution:
This notebook will run for 9 hours (on a Core(TM) i7-12700H 2.30 GHz with 32 GB RAM), with 90% of the computation time spent on transforming the 100 keys of the seismic slice test dataset. 

How to use this notebook:
1. Place the training data file "train.json" in the same directory as the "Final_Submission_Leo_v4.ipynb" file.
2. Open the "Final_Submission_Leo_v4.ipynb" file.
3. Place the holdout test data file in the same directory as the final submission notebook. 
Change the "test_file" parameter in line 3 (Part 0 Getting Ready) to the holdout test data file (by default, it is 'test_patches.json').
4. Run all the cells in the notebook.
5. The final submission file "submission.json" will be generated.

Optional:
To generate solution pictures, create a folder named "constructed_image", uncomment line 38 (Part 4 Prediction & Reconstruction) before running this notebook.
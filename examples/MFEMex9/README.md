Procedure:
- Create the following folders:
    - "data": to store the data
    - "fig": to store model parameters and figures
    - "temp": to store temporary files created during training, for evaluation of the error indicator
- run `generate_data.ipynb` in the "generate_data" folder to generate dataset
- run `train_model_sec4-4_case1.ipynb` to train a gLaSDI model by submitting a job using `batch_job.bsub`
- run `test_model.ipynb` to evalute the trained model
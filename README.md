<div align="center">

  <h1>Amazon Star Review Prediction</h1>
  
  <p>
    The Winning solution to the Danish Championship in AI 2022
  </p>
</div>

<br />

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [About the Project](#star2-about-the-project)
  * [Tech Stack](#space_invader-tech-stack)
  

<!-- About the Project -->
## :star2: About the Project
The task was to predict the amount of stars for a given review. The catch is that there was a time constraint which meant the model had to be fast. We tried we a more simple model using XGBoost and regression however we were not satisfied with the results. We therefore turned to transformers and tried to use DistilBERT where we modelled the task as a regression task. This model was however too slow, so we hard to compile and quantisize it to allow it to run fast enough on the server. Our final model achieved a RMSE of 0.6061 on the validation data. This could have been better but we didn't have time to finetune our hyperparameters and train the model for a long enough period.


<!-- TechStack -->
### :space_invader: Tech Stack
* Python
* DistilBERT


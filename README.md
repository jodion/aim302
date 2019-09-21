#### Notebook for the AIM302 workshop at the AWS Toronto Summit 2019: "Build, train, and deploy ML models with Amazon SageMaker"

### Companion slides
https://www.slideshare.net/JonathanDion/aws-toronto-summit-2019-aim302-build-train-and-deploy-ml-models-with-amazon-sagemaker

### Setup instructions

* Login to the AWS Console: https://console.aws.amazon.com.
* Select the US West (Oregon) region in the top right corner.
* Move to the SageMaker console: https://us-west-2.console.aws.amazon.com/sagemaker/home?region=us-west-2#/dashboard
* Go to "Notebook / Notebook instances".
* Click on "Create notebook instance".
    * "Notebook instance name": type a name for your instance, e.g "aim302".
    * "Notebook instance type": select _ml.t3.medium_. No need for anything bigger :)
    * "IAM role": select "Create a new role"
         * Select "Any S3 bucket".
         * Click on "Create role".
* In the "Git repositories" section:
    * Select "Clone a public Git repository" from the dropdown list.
    * In the "Git repository" box, enter: https://github.com/jodion/aim302.git
* Leave all other boxes as is and click on "Create notebook instance". A few minutes later, the instance is listed as "In Service".
* Click on "Open Jupyter".
* Click on the "aim302.ipynb" notebook and get to work :)

# versioning_data_factory_pipeline
Understanding version control for data factory pipelines for data engineers
This repository shows how can we version control a azure data factory pipeline that copies data from a csv file to parquet based format file. Following is the structure usesd for the version control.

main             
|--- develop
|--- adf_publish

We will first develop our pipeline in the development branch and then make pull request to main branch. After that we will publish changes to adf_publish and then run the pipeline. adf_publish is an automatically created branch by Azure Data Factory to create the necessary templates to run our pipeline smoothly. 

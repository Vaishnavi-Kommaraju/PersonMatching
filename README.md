# PersonMatching
Person matching in photo collections. 

## Objective 
The objective of this project is to retrieve the photos that belong to a certain individual given a query image. <br>
* Person matching is a problem of matching feature descriptor that describes a person across images consisting of multiple objects(people). <br>
* This problem typically arises in face detection and matching computer vision tasks. It’s applications include security surveillance, Google Photos,  apps where they find similar faces etc.<br>
* We pose the problem of person matching as an image retrieval task with predefined probe and gallery set.<br>


## Download the Dataset
Since the PIPA dataset is large in size, we haven't added it to this repo. Please download the tar files from [here](https://people.eecs.berkeley.edu/~nzhang/piper.html) into a data folder. <br>

## Unzipping tar files for the data
tar -xvf pipa_test.tar <br>
tar -xvf pipa_val.tar <br>
unzip annotations.zip <br>
tar -xvf pipa_leftover.tar <br>

or run the shell script as: sh unzip_script.sh <br>


# -FER-RMN-FER2013
## Usage
**Step 1. Install libraries**
```
conda env create -f environment.yml
```
**Step 2. Download processed fer2013 CSV files from this link**
```
https://1drv.ms/u/s!AmeTT2EpSz40hRbRieQ2kiQGLQ20?e=I27fR1
```
**The original dataset can be found from this link**
```
https://www.kaggle.com/competitions/challenges-in-representation-learning-facial-expression-recognition-challenge/data
```
**Step 3. Put the processed fer2013 CSV files in the following folder**
```
data
```
**Step 4. Download pre-trained models from this link**
```
https://1drv.ms/u/s!AmeTT2EpSz40hFYvpEYq3gvIUTE5?e=XgTXwb
```
**Step 5. Put the pre-trained models in the following folder**
```
checkpoint
```
**To train the model from scratch, run the following**
```
python main_fer2013.py
```
**After training the new model will be saved at the checkpoint folder**

**For evaluation, edit the cm_resmasking file to use the model you want and run the following**
```
python cm_resmasking.py
```
**After running the above file,the Confusion matrice will be saved at the cm folder**

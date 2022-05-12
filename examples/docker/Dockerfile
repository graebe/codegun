FROM tensorflow/tensorflow:latest

#RUN mkdir my-model
#ENV MODEL_DIR=/home/jovyan/my-model
#ENV MODEL_FILE_LDA=clf_lda.joblib
#ENV MODEL_FILE_NN=clf_nn.joblib

#RUN pip install joblib

#COPY train.csv ./train.csv
#COPY test.csv ./test.csv

COPY main.py ./main.py
#COPY inference.py ./inference.py

RUN python3 main.py

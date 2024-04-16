BERSt Vocal Emotion Recognition - Cmpt 419 final project
===============
Authors of this project: Andrew Ha, Lachlan Ellis, Justin Baek

## File Structure
└── 📁BERSt_Vocal_Emotion_Recognition<br>
&emsp;    └── 📁models<br>
&emsp;&emsp;        └── CNN.ipynb<br>
&emsp;&emsp;        └── combined_model.ipynb<br>
&emsp;&emsp;        └── DataProcessing.ipynb<br>
&emsp;&emsp;        └── LSTM_and_Merger.ipynb<br>
&emsp;&emsp;        └── RNN.ipynb<br>
&emsp;    └── README.md<br>
&emsp;    └── test_set.csv<br>
&emsp;    └── test_set_annotated.csv<br>
&emsp;    └── test_set_annotated2.csv<br>
&emsp;    └── training_set.csv<br>
&emsp;    └── valid_data.csv<br>

## Project Evaluation
The initial goal of this project was to apply various models onto the BERSt dataset in an attempt to determine the best model to use for speech emotion recognition with the added noise due to distance. We were successful in creating all of the models we had wanted to and we were able to obtain results from the models. The only change made to the initial proposal was the shifting of tasks, Andrew was to do the combination of 2 models together, this task was given to Justin and Andrew's task was updated to also working on the report.

## Special Dependencies
CNN uses a graphic accelerator due to the huge size of input. The jupyter notebook is set to use the graphic accelerator so if the graphic accelerator environment is not set, there might be an issue on running the code. 

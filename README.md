What is speech recognition?

  Speech recognition, or speech-to-text, is the ability of a machine or program to identify words spoken aloud and convert them into readable text. 
  Rudimentary speech recognition software has a limited vocabulary and may only identify words and phrases when spoken clearly.
  More sophisticated software can handle natural speech, different accents and various languages.
  Many speech recognition applications and devices are available, but the more advanced solutions use AI and machine learning. 
  They integrate grammar, syntax, structure, and composition of audio and voice signals to understand and process human speech.
  Various algorithms and computation techniques are used to recognize speech into text and improve the accuracy of transcription:-
    Natural language processing (NLP),
    Hidden markov models (HMM),
    Neural networks, etc.
  
How to use?
 
  Install DeepSpeech 0.6.1
  Download the pre-trained model (.pbmm), language model and trie file.
  Download instructions are given in pre-trained-models folder. 
  After download give them as arguments.
  
Contents:
  
  vui_notebook.ipynb: DNN Custom Models and Comparative Analysis to make a custom Speech Recognition model.
  DeepSpeech_Training.ipynb: Retraining of DeepSpeech Model with Indian Accent Voice Data.
  Training_Instructions.docx: Instructions to train DeepSpeech model.
  
Conclusion
   'Cepstral Analysis' separate out the accent components in speech signals, while doing Feature Extraction (MFCC) in Traditional ASR. In state-of-the-art Deep Neural Networks,      features are intrinsically learnt. Hence, we can transfer learn a pre-trained model with mutiple accents, to let the model learn the accent peculiarities on its own.

   We have proved the case, by doing transfer learning Baidu's DeepSpeech pre-trained model on Indian-English Speech data from multiple states. You can easily extend the              approach for any root language or locale accent as well.

  
  

1. rasa init.
2. Go to data
3. Change nlu.md
4. Train NLU using --> python -m rasa train nlu  or python -W ignore -m rasa train nlu
   train NLU + CORE using -->python -m rasa train
5. Run the re trained model using --> python -W ignore -m rasa shell nlu --quiet --enable-api --log-file out.log --cors *
    and for running both core+nlu write --> python -W ignore -m rasa shell 
    
6. ZMT:
   python -W ignore -m rasa run actions


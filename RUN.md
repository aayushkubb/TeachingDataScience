1. rasa init.
2. Go to data
3. Change nlu.md
4. Retrain uising --> python -m rasa train nlu  or python -W ignore -m rasa train nlu
5. Run the re trained model using --> python -W ignore -m rasa shell nlu --quiet

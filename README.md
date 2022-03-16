# text-gen

This is notebook defines a set of functions that create a bot to read a corpus of lyrics from a given musical artist, and then recreate lyrics in the style of that artist. First we tokenize the text of an artists letters at the character level, then use a recurrent neural network model based on character-level prediction. Then we can feed a trained model a few starter words and ask it to complete the line. We also play around a bit with temperature scaling our character predictions.

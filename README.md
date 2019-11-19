# Speech-emotion-recognition
Speech emotion recognition is nothing but the pattern recognition system,the emotions from the speech of male or female speakers are found out.A typical set of emotions contains 300 emotional states.

According to 'Palette theory' any emotions can be decomposed into primary emotions similar to the way that any color is a combination of some basic colors.Primary emotions are anger,disgust,fear,joy,sadness and surprise.

# Emotion recognotion model contains below modules :
# 1. Speech input:
       As speech input, i took Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS).
       https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio
# 2. Feature extraction & selection :
       Research on emotions of speech indicates that the different emotional state, corresponding
       changes occurs in the speak rate, pitch, energy and spectrum. so, as a feature selection process,
       choosed MFCC feature for pitch , Chroma feature for energy and spectrogram feature for spectrum.
# 3. Classification :
       To classification used Multi-Layer perceptron classifier.
# 4. Result :
       For triaining keep 90% of data and for test kept 10% of data.
       on 10% of test data got accuracy of approx 73%.
       
# Ref :
1.Ingale, Ashish B., and D. S. Chaudhari. "Speech emotion recognition." International Journal of Soft Computing and Engineering (IJSCE) 2.1 (2012): 235-238.

2.https://librosa.github.io/librosa/index.html

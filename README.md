# GenAI
## Prerequisites:
### Python installed on your computer (preferably Python 3.7 or later). You can use 'Jupyter notebook' as an alternative option.
An OpenAI account to access the OpenAI API Key: (https://platform.openai.com/signup/).
 OpenAI Python library (openai) installed. You can install it using pip:
#### set the path and run pip install OpenAI
#### pip install playsound
#### pip install SpeechRecognition
#### pip install gtts
#### pip install streamlit
#### python -m pip install ctransformers
#### To launch the local host run as "streamlit run main.py"
<p>A localhost:8501 will be opened automatically as chatbot named "PhysicsWhiz Assistant".
  
click on the button "Ask Questions...", it gives the running prompt as Listening for "Hey Robot".
  
Say: Hey Robot wait until it recognized it gives the prompt "I did not understand that" when it failed to recognize "Hey Robot".
when it is recognized it prompts "Wake word detected! Listening for your command..."
  
Say: a kangaroo is capable of jumping to a height of 2.62m, determine the takeoff speed of the kangaroo

ChatGPT: To determine the takeoff speed of the kangaroo, we can use the equation for the maximum height reached by an object in projectile motion: h_max = (v_i^2 sin^2(theta)) / (2 g)where: h_max = maximum height reached (2.62 m in this case)v_i = initial velocity (takeoff speed)theta = launch angle (we assume it to be 90 degrees for maximum height)g = acceleration due to gravity (approximately 9.8 m/s^2)Plugging in the known values: 2.62 = (v_i^2 sin^2(90)) / (2 9.8)Since sin(90) = 1, the equation simplifies to: 2.62 = (v_i^2) / (2 * 9.8)Rearranging the equation to solve for v_i:v_i^2 = 2.62 2 9.8v_i^2 = 51.352Taking the square root of both sides: v_i ≈ √(51.352)v_i ≈ 7.16 m/s. Therefore, the takeoff speed of the kangaroo is approximately 7.16 m/s.
  
Quit the program. The program can be terminated by using the voice command 'Quit' or 'Exit'.</p>

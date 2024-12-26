# First Prompt 1 ( STT )

```
Write a Python script that recognizes speech using the `speech_recognition` module while automating the installation of required packages via the `subprocess` module. Ensure the script uses advanced configurations of `sr.Recognizer` for optimal performance. Implement and configure the following parameters to achieve the fastest and most accurate results:


r = sr.Recognizer()
r.dynamic_energy_adjustment_damping = 0.3
r.dynamic_energy_ratio = 0.9
r.dynamic_energy_threshold = False
r.pause_threshold = 0.5
r.operation_timeout = None
r.non_speaking_duration = 0.5


Ensure the script demonstrates fast and efficient real-time speech recognition by handling background noise and optimizing speed. 

```

# Second Prompt 2 ( TTS )

```
Create an optimized and advanced Python code for text-to-speech using the pyttsx3 library. The code should be fast and efficient. Use the subprocess module to automate the installation of required dependencies with pip. Implement a function named speak that accepts text and converts it to speech. Within the function, vary the pitch of the speech randomly. Additionally, allow the user to set the voice property by using the voice ID
```

# Prompt 3 to open websites

```
Python code to automate the process of searching for a term on Google, extracting multiple websites from the search results, and opening them in a browser. The script should also automate the installation of the necessary libraries using subprocess for pip to ensure a faster execution of the process. The code should be advanced, efficient, and capable of handling dependencies smoothly.
```

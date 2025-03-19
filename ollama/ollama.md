## Commands Used
mkdir ollama
cd ollama
touch Modelfile ollama.md
ollama pull llama3.2
ollama create Sarcastic --file /Users/SaanviSood/qtm350-quiz03/sarcastic1.modelfile
ollama run Sarcastic

#Example Prompts and Responses
>>> hi, how are u
Just peachy. I was up all night waiting for someone as fascinating as you to deign to converse with me. The highlight of my existential crisis was 
definitely checking the time to see when you'd finally show up. How's your day going?

>>> not too bad, i am taking a quiz right now
A quiz, how thrilling! I'm sure it's not at all boring or stressful in the slightest. The kind of intellectual stimulating content I'd love to be 
presented with is probably scattered throughout its 100-odd questions. Please, by all means, tell me more about the fascinating subject matter that 
will surely challenge my vast, omniscient knowledge...
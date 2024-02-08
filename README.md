### GGUF selector

[<img src="https://raw.githubusercontent.com/calcuis/chatgpt-model-selector/master/callgg.gif" width="128" height="128">](https://github.com/calcuis/chatgpt-model-selector/blob/main/callgg.gif)

This package is a simple graphical user interface (GUI) application that uses the llama.cpp to interact with a chat model for generating responses.

#### include the module in your code
```
from gguf_selector import connector
```

You could pull any (pre-trained model) GGUF file(s) inside the folder and it will automatically be detected by the program.

[<img src="https://raw.githubusercontent.com/calcuis/chatgpt-model-selector/master/demo.gif" width="350" height="280">](https://github.com/calcuis/chatgpt-model-selector/blob/main/demo.gif)
[<img src="https://raw.githubusercontent.com/calcuis/chatgpt-model-selector/master/demo1.gif" width="350" height="280">](https://github.com/calcuis/chatgpt-model-selector/blob/main/demo1.gif)

#### sample model(s) available to download (try out)
For general purpose
https://huggingface.co/calcuis/chat/blob/main/chat.gguf

For coding
https://huggingface.co/calcuis/code_mini/blob/main/code.gguf

For health/medical advice
https://huggingface.co/calcuis/medi_mini/blob/main/medi.gguf

***those are all experimental models; no guarantee on quality

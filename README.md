## Install Ollama.
![image](https://github.com/cusrul/obsidian-smart-connect/assets/62647552/ab567b06-8968-4463-a7fd-4f249a191bac)

## Use the command "ollama pull nomic-embed-text" to fetch the large model.
``` ollama pull nomic-embed-text ```
## Run "ollama serve".
You should be aware that if Ollama is running on a different host than Obsidian, you need to open the corresponding firewall to ensure a successful connection.
![image](https://github.com/cusrul/obsidian-smart-connect/assets/62647552/c75cdc27-4f6d-4306-9ba9-fdaa68514af3)


# Now you can set up Smart Connect.


1.Please provide the Ollama server address in the format http://<your ollama address>/api/embeddings, for example: http://192.168.2.113:11434/api/embeddings IP: 192.168.2.113 ，Once you have filled in the Ollama server address and selected the model indicated by the arrow, you should be able to run it successfully.
2.If you want to customize the GPT's URL to run Smart Connect, you can fill in the "Set OpenAI Address" section with the format: https://aihubmix.com/v1/embeddings
![image](https://github.com/cusrul/obsidian-smart-connect/assets/62647552/ae022ad0-ff97-4e75-8ee3-c97b4726b38c)

1. make a simple chatbot 


- code :
    
        from langchain_ollama import OllamaLLM
        model = OllamaLLM(model="llama3.2:1b") 
        result = model.invoke(input="hello llama")
        print(result)

- steps :

    -    import OllamaLLM
    -    slect Ollama model
    -    give input to the model
    -    print results



2. make a chatbot that continously chat , remembers the context and works with a specified template.
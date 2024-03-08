# OpenAI cli application with golang
A powerful CLI based assistant usign Open AI, Built with GO
![alt text](image.png)

## Installation

To install the project, you need to have Go installed on your machine. Once you have Go installed, you can clone the repository and install the dependencies.
```
git clone https://github.com/AkhilSharma90/go-openai-terminal-assistant.git
cd repository
```

To run the project, you can use the go run command:
```
go run main.go
```
How to get started?
Create a .config folder -
```
mkdir ~/.config
cd ~/.config
```
create a config file here - terminal-assistant.json and mention the following details -
```
{
    "openai_key": "REPLACE WITH YOUR OPEN AI KEY",      
    "openai_model": "gpt-3.5-turbo",   
    "openai_proxy": "",               
    "openai_temperature": 0.0,        
    "openai_max_tokens": 2000,         
    "user_default_prompt_mode": "exec",
    "user_preferences": ""             
  }
  ```
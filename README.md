# Evangelion Magi Decision AIs

OK. I vibe code this for lol.  

It utilizes openrouter API to make its YES / NO decisions.  Once all models have responded, it then decides the final "Accept" or "Reject".

### License
MIT

### Free AI Models
```
    {name:"z-ai/glm-4.5-air:free",title: "GLM 4.5 · Air"},
    {name:"openrouter/hunter-alpha",title: "Hunter · Alpha"},
    {name:"nvidia/nemotron-3-super-120b-a12b:free",title: "Nemotron 3 · 120B"},
    {name:"nvidia/nemotron-3-nano-30b-a3b:free",title: "Nemotron 3 · Nano"},
    {name:"stepfun/step-3.5-flash:free",title: "StepFun 3.5 · Flash"},
    {name:"arcee-ai/trinity-large-preview:free",title: "Trinity · Large"},
    {name:"arcee-ai/trinity-mini:free",title: "Trinity · Mini"},
```

### Requirement:
[Get an OpenRouter API Key](https://openrouter.ai/settings/keys)

### Usage:
1. Enter the API key
2. Enter your question
3. Review the role and goals of each AI.
4. Change the AI model if you want.
5. Submit
6. Wait for the responses.
7. Click report for full content and reasoning.

### Customization:
#### Persistent API Key:
If you don't want to enter you API key every time, swap the API key field with a hidden field with same ID "openrouter_api_key" and value as your key.

#### Customize model list:
You can customize the AI models list by changing the support_models variable in the javascript section.

#### Customize default role for each AI.
You can change the default value from input with id, bottom-right-system-prompt, bottom-left-system-prompt and top-system-prompt

### Screenshot
![main.png](main.png)

#### Select new AI model, set role and goals
![model_selection.png](model_selection.png)

#### Report on full content and reasoning for each model.
![report.png](report.png)
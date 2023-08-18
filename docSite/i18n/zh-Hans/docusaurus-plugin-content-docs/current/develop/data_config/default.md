---
sidebar_position: 1
---

# 默认配置文件

```json
{
  "FeConfig": {
    "show_emptyChat": true,
    "show_register": false,
    "show_appStore": false,
    "show_userDetail": false,
    "show_git": true,
    "systemTitle": "FastGPT",
    "authorText": "Made by FastGPT Team.",
    "gitLoginKey": "",
    "scripts": []
  },
  "SystemParams": {
    "gitLoginSecret": "",
    "vectorMaxProcess": 15,
    "qaMaxProcess": 15,
    "pgIvfflatProbe": 20
  },
  "plugins": {},
  "ChatModels": [
    {
      "model": "gpt-3.5-turbo",
      "name": "GPT35-4k",
      "contextMaxToken": 4000,
      "quoteMaxToken": 2000,
      "maxTemperature": 1.2,
      "price": 0,
      "defaultSystem": ""
    },
    {
      "model": "gpt-3.5-turbo-16k",
      "name": "GPT35-16k",
      "contextMaxToken": 16000,
      "quoteMaxToken": 8000,
      "maxTemperature": 1.2,
      "price": 0,
      "defaultSystem": ""
    },
    {
      "model": "gpt-4",
      "name": "GPT4-8k",
      "contextMaxToken": 8000,
      "quoteMaxToken": 4000,
      "maxTemperature": 1.2,
      "price": 0,
      "defaultSystem": ""
    }
  ],
  "QAModels": [
    {
      "model": "gpt-3.5-turbo-16k",
      "name": "GPT35-16k",
      "maxToken": 16000,
      "price": 0
    }
  ],
  "VectorModels": [
    {
      "model": "text-embedding-ada-002",
      "name": "Embedding-2",
      "price": 0
    }
  ]
}
```
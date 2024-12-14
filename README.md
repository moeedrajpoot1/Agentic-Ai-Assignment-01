## Messages
The `messages` parameter is used to provide input to the API. It is a list of messages, where each message has a `role` (like system, user, or assistant) and the `content` of the message.

## Model
The `model` parameter specifies the OpenAI model being used, such as `gpt-3.5-turbo` or `gpt-4`. Each model has different features and limits.

## Max Completion Tokens
The `max_tokens` parameter sets the maximum number of tokens the model can use in its response. It helps control how long the response will be.

## n
The `n` parameter defines how many different responses the model should generate. It is useful when multiple options are needed.

## Stream
The `stream` parameter decides if the response should be sent in parts as it is generated. It is mostly used for chat applications.

## Temperature
The `temperature` parameter controls how random or creative the response will be. A higher value makes the response more random, and a lower value makes it more focused.

## Top_p
The `top_p` parameter is another way to control randomness. It limits the response to the most likely words by using a probability threshold. Lower values make the response more predictable.

## Tools
The `tools` parameter allows the API to use extra features, like connecting to the internet or running specific tasks, to make it more useful.

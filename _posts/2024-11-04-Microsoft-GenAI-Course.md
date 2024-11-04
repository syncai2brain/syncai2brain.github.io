---
layout: post
title:  Gen AI from Microsoft Perspective
categories: [Generative AI,LLM,Microsoft]
---

This post provides the snippets taken from the Generative AI course designed by Microsoft.
The course is available for free in [GitHub](https://microsoft.github.io/generative-ai-for-beginners/#/).

#### Knowledge Check

1. What's true about large language models?

- [ ] a. You get the exact same response every time.
- [ ] b. It does things perfectly, great at adding numbers, produce working code etc.
- [ ] c. The response may vary despite using the same prompt. It's also great at giving you a first draft of something, be it text or code. But you need to improve on the results.

<details>
  <summary>Click here to check your Answer</summary>
  Correct Answer is Option 'c'
</details>

## Understand different types of LLMs

LLMs can have multiple categorizations based on their architecture, training data, and use case.

- **Audio and speech recognition.** For this purpose, Whisper-type models are a great choice as they're general-purpose and aimed at speech recognition. It's trained on diverse audio and can perform multilingual speech recognition. Learn more about [Whisper type models here.](https://platform.openai.com/docs/models/whisper?WT.mc_id=academic-105485-koreyst)

- **Image generation.** For image generation, DALL-E and Midjourney are two very known choices. DALL-E is offered by Azure OpenAI. Read more about [DALL-E here.](https://platform.openai.com/docs/models/dall-e?WT.mc_id=academic-105485-koreyst)
  
- **Text generation.** Most models are trained on text generation and you have a large variety of choices from GPT-3.5 to GPT-4. They come at different costs with GPT-4 being the most expensive. It's worth looking into the [Azure OpenAI playground](https://oai.azure.com/portal/playground?WT.mc_id=academic-105485-koreyst) to evaluate which models best fit your needs in terms of capability and cost.

- **Multi-modality.** If you're looking to handle multiple types of data in input and output, you might want to look into models like [gpt-4 turbo with vision or gpt-4o](https://learn.microsoft.com/azure/ai-services/openai/concepts/models#gpt-4-and-gpt-4-turbo-models?WT.mc_id=academic-105485-koreyst) - the latest releases of OpenAI models - which are capable to combine natural language processing to visual understanding, enabling interactions through multi-modal interfaces.


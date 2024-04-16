
## top themes

- - [became the #6 model on lmsys](https://twitter.com/lmsysorg/status/1777630133798772766?t=90xQ8sGy63D2OtiaoGJuww)and top open model, beating mistral large and qwen, but behind claude sonnet, gemini pro, and gpt4t


## openai

- harvey case study https://x.com/gabepereyra/status/1775207692841488542?s=20
	- - 93% preferred vs. ChatGPT by BigLaw attorneys - 87% more accurate case citations
- more improvements to OpenAI's Fine-Tuning API & additional info on its Custom Models program [https://openai.com/blog/introducing-improvements-to-the-fine-tuning-api-and-expanding-our-custom-models-program](https://openai.com/blog/introducing-improvements-to-the-fine-tuning-api-and-expanding-our-custom-models-program "https://openai.com/blog/introducing-improvements-to-the-fine-tuning-api-and-expanding-our-custom-models-program")
	- Epoch-based Checkpoint Creation: Automatically produce one full fine-tuned model checkpoint during each training epoch, which reduces the need for subsequent retraining, especially in the cases of overfitting
	- Comparative Playground: A new side-by-side Playground UI for comparing model quality and performance, allowing human evaluation of the outputs of multiple models or fine-tune snapshots against a single prompt
	- Third-party Integration: Support for integrations with third-party platforms (starting with Weights and Biases this week) to let developers share detailed fine-tuning data to the rest of their stack
	- Comprehensive Validation Metrics: The ability to compute metrics like loss and accuracy over the entire validation dataset instead of a sampled batch, providing better insight on model quality
	- Hyperparameter Configuration: The ability to configure available hyperparameters from the Dashboard (rather than only through the API or SDK) 
	- Fine-Tuning Dashboard Improvements: Including the ability to configure hyperparameters, view more detailed training metrics, and rerun jobs from previous configurations
- minor technical stuff
	- [batch endpoint](https://twitter.com/OpenAIDevs/status/1779922566091522492) - Just upload a file of bulk requests, receive results within 24 hours, and get 50% off API prices
	- [GPT4V GA](https://twitter.com/OpenAIDevs/status/1777769463258988634) now also uses JSON mode and function calling - useases devin, healthify snap, tldraw makereal. openai account calls it "[majorly improved](https://x.com/OpenAI/status/1777772582680301665)"
		- specifically [reasoning has been further improved](https://x.com/polynoamial/status/1777809000345505801?utm_source=ainews&utm_medium=email&utm_campaign=ainews-gemini-pro-and-gpt4t-vision-go-ga-on-the). and [math](https://twitter.com/owencm/status/1777770827985150022) 
		- [cursor has better comparison](https://twitter.com/cursor_ai/status/1777886886884986944?t=6FDPaNxZcbSsELal6Sv7Ug)
		- GPT4T upgrade - [less verbose, better at codegen](https://twitter.com/gdb/status/1778126026532372486?t=6FDPaNxZcbSsELal6Sv7Ug)
- rumors
	- [NYT says openai scraped 1m hrs of youtube data](https://www.theverge.com/2024/4/6/24122915/openai-youtube-transcripts-gpt-4-training-data-google)

## frontier models

- Anthropic
	- [Claude - tool use now in beta](https://twitter.com/AnthropicAI/status/1775979802627084713)
- Google
	- gemini unerstand audio, uses unlimited files, offers json mode, no more waitlist https://x.com/liambolling/status/1777758743637483562?s=46&t=90xQ8sGy63D2OtiaoGJuww
		- https://x.com/OfficialLoganK/status/1777733743303696554
	- [codegemma](https://x.com/_philschmid/status/1777673558874829090) - 2b (27% humaneval) & 7b (52% humaneval) with 8k context - 500b extra tokens

## open models

- Cohere Command R+: [@cohere](https://twitter.com/cohere/status/1775878850699808928) released Command R+, a 104B parameter model with 128k context length, open weights for non-commercial use, and strong multilingual and RAG capabilities. It's available on the [Cohere playground](https://twitter.com/cohere/status/1775878883268509801) and [Hugging Face](https://twitter.com/osanseviero/status/1775882744792273209). [Aidan tweet](https://twitter.com/aidangomez/status/1775878606108979495)
	-   **Optimized for RAG workflows**: Command R+ is [optimized for RAG](https://twitter.com/aidangomez/status/1775878606108979495), with multi-hop capabilities to break down complex questions and strong tool use. It's integrated with [@LangChainAI](https://twitter.com/cohere/status/1775931339361149230) for building RAG applications.
	-   **Multilingual support**: Command R+ has [strong performance](https://twitter.com/seb_ruder/status/1775882934542533021) across 10 languages including English, French, Spanish, Italian, German, Portuguese, Japanese, Korean, Arabic, and Chinese. The SonnetTokenizer is [efficient for non-English text](https://twitter.com/JayAlammar/status/1775928159784915229).
	- [became the #6 model on lmsys ](https://twitter.com/lmsysorg/status/1777630133798772766?t=90xQ8sGy63D2OtiaoGJuww)and top open model, beating mistral large and qwen, but behind claude sonnet, gemini pro, and gpt4t
- Mistral 8x22B
	- 
- [Stable Audio 2.0](https://x.com/StabilityAI/status/1775501906321793266?s=20) - a new model capable of producing high-quality, full tracks with coherent musical structure up to three minutes long at 44.1 kHz stereo from a single prompt.
- Qwen 1.5-32B-Chat ([HF](https://huggingface.co/Qwen/Qwen1.5-32B-Chat)) - the beta version of Qwen2, a transformer-based decoder-only language model pretrained on a large amount of data. In comparison with the previous released Qwen, the improvements include:
	- 8 model sizes, including 0.5B, 1.8B, 4B, 7B, 14B, 32B and 72B dense models, and an MoE model of 14B with 2.7B activated;
	- Significant performance improvement in human preference for chat models;
	- Multilingual support of both base and chat models;
	- Stable support of 32K context length for models of all sizes
- IDEFICS 2 https://x.com/ClementDelangue/status/1779925711991492760

## open source tooling

- https://github.com/GregorD1A1/TinderGPT
- https://github.com/princeton-nlp/SWE-agent
- https://github.com/Dhravya/supermemory t's a ChatGPT for your bookmarks. Import tweets or save websites and content using the chrome extension.

## other launches

- udio music https://twitter.com/udiomusic/status/1778045322654003448?t=6FDPaNxZcbSsELal6Sv7Ug
	- [comedy dialogue, sports analysis, commercials, radio broadcasts, asmr, nature sounds](https://x.com/mckaywrigley/status/1778867824217542766?s=46&t=6FDPaNxZcbSsELal6Sv7Ug)
	- sonauto as well
- [Reka Core/Flash/Edge](https://publications.reka.ai/reka-core-tech-report.pdf)
	-   

## fundraising

- [XAI seeking 4b](https://www.bloomberg.com/news/articles/2024-04-11/elon-musk-s-xai-seeks-up-to-4-billion-to-compete-with-openai)

## Learning

- Thom Wolf - [how to train LLMs in 2024](https://youtu.be/2-SPH9hIKT8?si=wqYrDbhvgJUT2zHP)
## discussion

- soumith v fchollet https://x.com/fchollet/status/1776319511807115589
- delve is from nigeria https://twitter.com/moultano/status/1777727219097342287

## memes

- suno memes
	- https://x.com/goodside/status/1775713487529922702

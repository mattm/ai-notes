## Synthetic data

- Synthetic data ['is the future'](https://huggingface.co/datasets/andersonbcdefg/synthetic_retrieval_tasks) from Nous Research founder
- Microsoft trained a text embedding model from Mistral-7B that topped the MTEB  leaderboard [using synthetic data](https://twitter.com/andersonbcdefg/status/1742613575217156547)


## openai

- gpt store launch [pending](https://news.ycombinator.com/item?id=38870249) 
	- [launched on Jan 10](https://twitter.com/sama/status/1745135061731803571)
- launched and rolled back [GPT personalization and Temporary Chat](https://x.com/AndrewCurran_/status/1744923452572852608?s=20)
- [GPT builder is itself a GPT](https://help.openai.com/en/articles/8770868-gpt-builder)
- [API key based usage tracking](https://twitter.com/OfficialLoganK/status/1743401083920097432) - just tracking, no limits yet


## fundraising

- [perplexity series b](https://twitter.com/perplexity_ai/status/1742915781690798290) - 74m at 520m valuation
	- 10m MAU, 500m queries in 2023
	- https://blog.perplexity.ai/blog/perplexity-raises-series-b-funding-round
	- https://www.wsj.com/tech/ai/jeff-bezos-bets-on-a-google-challenger-using-ai-to-try-to-upend-internet-search-0859bda6?mod=hp_lead_pos4


## open source tooling

- langchain
	- [v0.1](https://twitter.com/LangChainAI/status/1744411643482951829) 
	- graph agents
- open interpreter 0.2 - vision models, and an api
	- https://twitter.com/hellokillian/status/1743418943120040109
	- https://api.openinterpreter.com/ The Open Interpreter Project has developed (and here freely hosts) an API which is capable of locating visual controls with single-pixel precision.


## models

- deepseekmoe 2b-145b MOE
	- https://x.com/deepseek_ai/status/1745304852211839163?s=46&t=90xQ8sGy63D2OtiaoGJuww


## other launches

- [Rabbit R-1 $200 LLM smartphone launched at CES](https://news.ycombinator.com/item?id=38930126)
	- highly produced 30min video, product seems polished, but people mostly unconvinced this needs to be a separate device from phone.

## misc reads 

- interesting/interpretability
	- [Chess-GPT's Internal World Model](https://adamkarvonen.github.io/machine_learning/2024/01/03/chess-world-models.html)
		- A 50 million parameter GPT trained on 5 million games of chess learns to play at ~1300 ELO in one day on 4 RTX 3090 GPUs. This model is only trained to predict the next character in PGN strings (1.e4 e5 2.Nf3 …) and is never explicitly given the state of the board or the rules of chess. Despite this, in order to better predict the next character, it learns to compute the state of the board at any point of the game, and learns a diverse set of rules, including check, checkmate, castling, en passant, promotion, pinned pieces, etc. In addition, to better predict the next character it also learns to estimate latent variables such as the ELO rating of the players in the game.
		- [Tweet thread](https://twitter.com/a_karvonen/status/1743666230127411389): "I trained Chess-GPT, a 50M parameter LLM, to play at 1500 ELO. We can visualize its internal state of the board. In addition, to better predict the next character it estimates the ELO of the players involved"
- Discussions:
	- Simonw vs Karpathy - [AI vs IA](https://x.com/karpathy/status/1744062845426532473?s=20)
		- followup https://twitter.com/karpathy/status/1744179910347039080
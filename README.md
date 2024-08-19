#Examples of use of LLMs in astronomy
The repo is basically some sandbox to play with LLMs and share results with students for inspiration.
Nothing particularly useful here, probably will update over time. The files included so far:

* proposal_parser.ipynb - an example illustrating my attempt to simplify life of reviewer of scientific proposals (i.e. mine). Result was better than what [elicit](https://elicit.com) could do for me. Still, had to read them all though. 
* expand\_outline\_with_style.ipynb - an attempt to make LLM write a full draft about observations of an X-ray pulsar in pre-defined style based on an outline (again RAG, and again, for fun/experiments only)
* citation\_sentiment.ipynb - an notebook illustrating use of RAG and local LLMs (via Ollama and langchain) to get context and conduct sentiment analysis of citations in a paper. 
* translate_gpt.ipynb - a notebook illustrating use of OpenAI APIs for vision and tool calling to translate an online lecture script by [KA Postnov](http://www.astronet.ru/db/msg/1170612/node1.html) to English. It's therefore a mix of web-scarping and LLM use. Note that more straigforward, cheap and quality, solution to that would be just to convert the scarped html to pdf via pandoc and then use something like [nougat](https://github.com/facebookresearch/nougat) to convert to tex and something like Deepl for translation. The point is, however, to illustrate OpenAI capabilities, hence the more complex route.

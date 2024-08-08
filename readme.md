# AI

## All in one
[Harbor](https://github.com/av/harbor)
Containerized LLM toolkit. Run LLM backends, APIs, frontends, and additional services via a concise CLI.

## prompt libraries
[AI LLM System Prompts Gsheet](https://docs.google.com/spreadsheets/d/1lk6JNKtl3D4bx9b5z_kJ5J8UqMYj0WKFdQ2yE7R87kg/edit?gid=0#gid=0)
[msty prompt library](https://msty.app/prompts-library)
[aiforedu](https://www.aiforeducation.io/prompt-library)
[hammerai](https://www.hammerai.com/)

## leaderboard

[AI Leaderboard](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard)

###### My PC Setup

i5 6600K 4-cores
GTX 1070 8gbvram
16gb RAM

all more than 6.8gb pushes to CPU if higher settings

## LLMs

* mistral-nemo:12b-instruct-2407-q4_0 8.1gb - bad
* mistral-nemo:12b-instruct-2407-q3_K_M 7.6gb - good, slight throttle with non-default
- earlier knowledge cutoff and conversational

###### llama3.1
* llama3.1:8b-instruct-q3_K_S - good; low quality
* llama3.1:8b-instruct-q5_1 - best so far
* llama3.1:8b-instruct-q6_K - good: nothing running, throttle with non-default
- recommended: 8 cores, 16gm ram, 3000 series GPU
- up to date knowledge cutoff and conversational

###### gemma2
* gemma2:9b-instruct-q4_1 - ok: nothing running, throttle on non-default
* gemma2:9b-instruct-q5_1 - a little slow
* gemma2:9b-instruct-q6_K - slow, default settings ok throttling
- recommended: none, modelfile below GPU VRAM
- reasoning and coding tasks

###### deepseekcoderv2
- recommended: modelfile solo run
- reasoning and coding tasks

###### phi3:latest - fast
- recommended: lowest

=================================================

## TTS
[AlwaysReddy](https://github.com/ILikeAI/AlwaysReddy)
[Piper](https://github.com/rhasspy/piper)
[High-performance inference of OpenAI's Whisper automatic speech recognition (ASR) model](https://github.com/ggerganov/whisper.cpp)
[XTTS-2-UI](https://github.com/BoltzmannEntropy/xtts2-ui)

## repos:

https://github.com/danwiseman/epimetheus
https://github.com/hybridx/ai-slack-companion
https://github.com/Fortyseven/ircawp
[fabric](https://github.com/danielmiessler/fabric) is an open-source framework for augmenting humans using AI.

[slack bot](https://github.com/village0/slack_bot)

[Dify](https://github.com/langgenius/dify) is an open-source LLM app development platform. Its intuitive interface combines AI workflow, RAG pipeline, agent capabilities, model management, observability features and more, letting you quickly go from prototype to production. Here's a list of the core features:


[Jina](https://github.com/jina-ai/jina) lets you build multimodal AI services and pipelines that communicate via gRPC, HTTP and WebSockets, then scale them up and deploy to production. You can focus on your logic and algorithms, without worrying about the infrastructure complexity.


[MemFree](https://github.com/memfreeme/memfree) is a hybrid AI search engine that simultaneously performs searches on your personal knowledge base (such as bookmarks, notes, documents, etc.) and the Internet.

[MindsDB](https://github.com/mindsdb/mindsdb)
MindsDB is the platform for customizing AI from enterprise data. You can create, serve, and fine-tune models in real-time from your database, vector store, and application data.


https://medium.com/@chinmayd49/self-host-llm-with-ec2-vllm-langchain-fastapi-llm-cache-and-huggingface-model-7a2efa2dcdab#:~:text=I%20would%20recommend%20go%20through,for%20ML%20and%20LLM%20specifically.&text=For%20application%20and%20OS%20images,softwares%20and%20are%20command%20friendly.

https://topai.tools/t/automatic-1111

=================================================

LLM Chat Web UI Platforms
https://msty.app/ ⭐️⭐️⭐️⭐️⭐️
https://github.com/ivanfioravanti/chatbot-ollama ?

mobile
https://github.com/AugustDev/enchanted ⭐️⭐️⭐️⭐️⭐️

=================================================

https://zrok.io/pricing/
https://localhost.run/
https://playit.gg/
https://theboroer.github.io/localtunnel-www/

lt --port 8000

npm install -g localtunnel

for the password
https://loca.lt/mytunnelpassword


curl http://localhost:11434/api/generate -d '{"model": "gemma2","prompt": "Why is the sky blue?"}'

=================================================

http://localhost:11434/api/generate
http://localhost:11434/api/chat
{
	"model": "qwen2",
	"prompt": "what did you previously say? please explain.",
	"stream": false,
	"format": "json"
}


# AwesomeRealtimeAI

collections of realtime ai resources focusing audio and video, including: api, client, projects, models, etc.

# API

| provider   | api reference                                                                                                                                                       | modality         | main feature                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| openai     | [Realtime API](https://platform.openai.com/docs/guides/realtime)                                                                                                       | text/audio/video | gpt-4o.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| minimax    | [Realtime API](https://platform.minimaxi.com/document/Realtime)                                                                                                        | text/audio       | compatible with openai api.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| Vapi       | [API Reference](https://docs.vapi.ai/api-reference/calls/list)                                                                                                         | text/audio       | Vapi lets developers build, test, & deploy voice AI agents in minutes rather than months — solving for the foundational challenges voice AI applications face:<br />1. Simulating the Flow of Natural Human Conversation.<br />2. Realtime/Low Latency Demands.<br />3. Taking Actions (Function Calling).<br />4. Extracting Conversation Data (Review conversation audio, transcripts, & metadata.).<br /><br />SDK: [https://docs.vapi.ai/introduction#explore-our-sdks](https://docs.vapi.ai/introduction#explore-our-sdks) |
| hume.ai    | [API Reference](https://dev.hume.ai/reference/empathic-voice-interface-evi/tools/list-tools)                                                                           | text/audio       | Real-time, customizable voice intelligence powered by empathic AI.                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Google     | [API Reference](https://googleapis.github.io/python-genai/genai.html#module-genai.live)                                                                                | text/audio/video | [gemini multimodal live api](https://ai.google.dev/gemini-api/docs/models/gemini-v2#live-api)                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| retell.ai  | [API Reference](https://docs.retellai.com/api-references/create-phone-call)                                                                                            | text/audio       | **Retell** is a comprehensive platform for building, testing, deploying, and monitoring reliable  **AI phone agents** .                                                                                                                                                                                                                                                                                                                                                                                                |
| doubao     | [volcengine](https://www.volcengine.com/docs/6348/1315561)                                                                                                             | text/audio       | ASR + LLM + TTS, WebRTC.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| elevenlabs | [conversational ai](https://elevenlabs.io/docs/conversational-ai/api-reference/conversational-ai/websocket)                                                            | text/audio       | ASR + LLM + TTS, WebSocket.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| aliyun     | [realtime ai](https://www.aliyun.com/solution/tech-solution/real-time-interaction?spm=5176.29677750.J_7uZrZlgl1hzBH9MLq1qLS.d_2_action_0.e939154aLeYPTn#83cef521efsw3) | text/audio       | aliyun realtime ai.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |

# Projects

| maintainer     | link                                                         | main feature                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| -------------- | ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| @jhakulin      | [realtime-ai](https://github.com/jhakulin/realtime-ai)          | Experimental Python SDK for OpenAI's Realtime API, Well Structured.                                                                                                                                                                                                                                                                                                                                                                                                     |
| @Pipecat       | [Pipecat](https://github.com/pipecat-ai/pipecat)                | Pipecat is an open source Python framework for building voice and multimodal conversational agents. It handles the complex orchestration of AI services, network transport, audio processing, and multimodal interactions, letting you focus on creating engaging experiences.                                                                                                                                                                                          |
| @TEN-framework | [TEN Framework](https://github.com/TEN-framework/ten_framework) | **TEN** stands for  **Transformative Extensions Network** , is a voice agent framework to create conversational AI. The TEN framework offers the following advantages:<br />1. Native Support for High-Performance, Real-Time Multimodal Interactions.<br />2. Supports Multiple Languages and Platforms.<br />3. Edge-Cloud Integration.<br />4. Flexibility Beyond Model Limitations.<br />5. Real-Time Agent State Management.<br />6. And more... |

# Models(Open Source)

| contributor | model                                                                                                    | main feature                                                                                                                                                                                                                                                                                 |
| ----------- | -------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| FDU         | [SpeechGPT2](https://0nutation.github.io/SpeechGPT2.github.io/)                                             | SpeechGPT2 is an end-to-end speech dialogue language model, similar to GPT-4o. It can perceive and express emotions, and provide appropriate voice responses in various styles such as rap, drama, robot, funny, and whisper, based on context and human instructions.                       |
| ZhipuAI     | [GLM-4-Voice](https://github.com/THUDM/GLM-4-Voice)                                                         | GLM-4-Voice is an end-to-end voice model launched by Zhipu AI. GLM-4-Voice can directly understand and generate Chinese and English speech, engage in real-time voice conversations, and change attributes such as emotion, intonation, speech rate, and dialect based on user instructions. |
| kyutai-labs | [Moshi](https://github.com/kyutai-labs/moshi)                                                               | [Moshi](https://arxiv.org/abs/2410.00037) is a speech-text foundation model and **full-duplex** spoken dialogue framework. It uses [Mimi](https://arxiv.org/abs/2410.00037), a state-of-the-art streaming neural audio codec.                                                                |
| tencent     | [Freeze-Omni](https://github.com/VITA-MLLM/Freeze-Omni)                                                     | A Smart and Low Latency Speech-to-speech Dialogue Model with Frozen LLM.                                                                                                                                                                                                                     |
| tencent     | [VITA](https://github.com/VITA-MLLM/VITA)                                                                   | open-source interactive omni-multimodal LLM.                                                                                                                                                                                                                                                 |
| InternLM    | [Intern-OmniLive](https://github.com/InternLM/InternLM-XComposer/tree/main/InternLM-XComposer-2.5-OmniLive) | a comprehensive multimodal system for long-term streaming video and audio interactions.                                                                                                                                                                                                      |
| THU         | [mini-omni](https://github.com/gpt-omni/mini-omni) / [mini-omni2](https://github.com/gpt-omni/mini-omni2)    | only English; language model: Qwen2-0.5B.                                                                                                                                                                                                                                                  |
| ICT/CAS     | [LLaMA-Omni](https://github.com/ictnlp/LLaMA-Omni)                                                          | LLaMA-Omni is a low-latency and high-quality end-to-end speech interaction model built upon Llama-3.1-8B-Instruct, aiming to achieve speech capabilities at the GPT-4o level.                                                                                                                |
| OpenBMB     | [MiniCPM-o](https://github.com/OpenBMB/MiniCPM-o)                                                           | MiniCPM-o 2.6: A GPT-4o Level MLLM for Vision, Speech and Multimodal Live Streaming on Your Phone                                                                                                                                                                                            |

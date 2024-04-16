# Real-Time Web Chat App 

## Introduction

This is a code repository for a full Realtime Chat Application with Social Auth and dedicated chat APIs/sockets.

Utilizes - [Chat Engine](https://chatengine.io) and [Firebase](https://firebase.google.com/)

## ChatGPT Bot
This app leverages [OpenAI](https://openai.com/)'s recently released ChatGPT API with `gpt-3.5-turbo` model to respond to a chain of chat messages. Users submit messages to a [SvelteKit](https://kit.svelte.dev/) API Endpoint/Request Handler, which relays the messages to the ChatGPT API. The responses are then proxied back to the client via SSE to stream the response in realtime.

# loungebot-demo
The demonstration of a Zalando Lounge bot I've been developing as a fun side project. 

This is a composerized (multi-container), robust Electron / TypeScript and Python application that asynchronously automates certain tasks. 

It utilizes a range of libraries to:
manage scheduling, 
execute HTTP requests, 
leverage in-built rotating forward proxies,
handle background job processing,
cache the drop data shared between jobs, 
perform cryptographic operations, 
establish secure communications, 
and manipulate dates and times.

Notably, the app is designed to run continuously identifying the most favorable deals through an efficient articles filtering algorithm.

Some of the technologies being used: Docker Compose for containerization, Vite for build tooling, Electron for creating cross-platform desktop app, FastAPI for Python <-> Node communication, Playwright for browser automation, Xvfb for virtual framebuffer display server, Redis for in-memory data structure store, Bull for job queues, and Fomantic-UI and React for frontend development.

How it works:
<video src="https://github.com/mrzdev/loungebot-demo/assets/106373816/e539c66d-8a58-4716-997b-52f7ae9302db"></video>

Current changes:
![demo1](https://github.com/mrzdev/loungebot-demo/assets/106373816/dd5ac463-2a4d-4d62-9ced-9f5553fc4ecb)
![demo2](https://github.com/mrzdev/loungebot-demo/assets/106373816/8c1c22b9-590f-4d3d-bfe2-9beced5f3c73)
![demo3](https://github.com/mrzdev/loungebot-demo/assets/106373816/0ac07a8e-719d-4d88-9a88-9ea1ebe4b004)
![demo4](https://github.com/mrzdev/loungebot-demo/assets/106373816/22cc001e-e3ee-4758-81da-e4450ccc2426)
![demo5](https://github.com/mrzdev/loungebot-demo/assets/106373816/40a49e1b-37bf-419a-8f1b-7910f13e6770)

Disclaimer: I am in no way affiliated with Zalando and there's no ETA on this.

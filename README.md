# [AshAI](https://ashai.netlify.app/)

## Features of this App 🤖

Generate website, product copy, and brianstorm ideas with OpenAI's Generative Pre-trained Transformer 3 (GPT-3) an autoregressive language model that uses deep learning to produce human-like text.

![theme croped](https://user-images.githubusercontent.com/29527450/229385033-67441a4b-77e5-48a5-a570-f27620d62892.jpg)


## Getting Started 🛠️: 

### Tools Used: 

- [Node.js](https://nodejs.org/)
- [npm](https://npmjs.com)
- [React](https://reactjs.org)
- [React Bootstrap](https://react-bootstrap.github.io)
- [Font Awesome](https://fontawesome.com/docs/web/use-with/react/)
- [OpenAI's GPT-3 autoregressive language model](https://openai.com/)

### Development:

This repository is set up to run on a VPS with an express backend, to run it locally do the following: 

1.  Fork and clone this repo
2.  In Terminal open the directory `AshAi`
3.  Check that Node.js is installed via Terminal by typing `node -v` if you don’t see a version [Install Node.js](https://nodejs.org/en/)
4. In the `AshAi` directory type `npm install` to install any missing dependences.
5. cd into the `AshAi/api` directory and type `npm install` to install any missing dependences.
6.  Obtain your [OpenAI API key](https://openai.com/api/) via Log In > Personal > API keys > Create and Copy your Secret Key.
7.  In the `AshAi/api` directory add a `.env` file with an API key variable and the port for the backend: 
```
   API_KEY=abc123yourapikey
   PORT=6001
```
8. In Terminal cd into the `AshAi/api` directory and `npm start`
9. finally, in Terminal cd in the ai-content directory and `npm start`

## Current app features ✨

- Navigation
- Theme toggle for dark and light modes
- Blog Post Ideas Generator
- Product Description Generator
- Company Bio Generator
- SEO Blog Intro Paragraph Generator
- LinkedIn Job Description Generator
- TL;DR Text SummarizerGenerator

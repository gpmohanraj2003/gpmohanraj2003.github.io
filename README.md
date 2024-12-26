## Welcome to gpmohanraj2003.github

I'm an Ethical Hacker.

<iframe width="560" height="315" src="https://www.youtube.com/embed/IhyzIwZ7xxk?si=dVOj6vPV0CHu_F1p" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

LangChain [agents](https://python.langchain.com/v0.1/docs/modules/agents/) to dynamically answer and render UI.

In addition, we use the financial datasets [stock market API](https://www.financialdatasets.ai/) to get real-time stock data and in-depth financials.

Finally, for general web search, we use the Tavily [search API](https://tavily.com/).

[![Twitter Follow](https://img.shields.io/twitter/follow/virattt?style=social)](https://twitter.com/virattt)

## Getting Started 🚀

<img width="1219" alt="profile.jpg" src="https://github.com/gpmohanraj2003/gpmohanraj2003.github.io/blob/main/profile.jpg">

1. Download the repo locally:
    ```
    git clone https://github.com/virattt/financial-agent-ui.git
    ```

2. Create a `.env` file in the root project directory (next to `.env.example`) and add the following:

   ```
   OPENAI_API_KEY=               # Get one at https://platform.openai.com
   FINANCIAL_DATASETS_API_KEY=   # Get one at https://financialdatasets.ai
   TAVILY_API_KEY=               # Get one at https://tavily.com
   ```

## Run the agent

We strongly recommend using Docker to run the application. This will ensure that all dependencies are installed and the application runs smoothly.

You can find Docker installation instructions [here](https://docs.docker.com/get-docker/).

Once installed, run the following command in the root project directory to start the application: 

```
 docker-compose up
```

If you don't want to use Docker, then you can manually install the application.

- To run the `backend` server, instructions are [here](https://github.com/virattt/financial-agent-ui/blob/main/backend/README.md).
- To run the `frontend` app, instructions are [here](https://github.com/virattt/financial-agent-ui/blob/main/frontend/README.md).

## Disclaimer 🛑

The goal of this application is **only** to explore generative AI and UI.

This financial agent is **not intended as financial advice**. It is designed to provide users with tools and information
to explore technical concepts with respect to generative AI only. Users should conduct their own research or consult
with a financial advisor before making any financial decisions.

## Contributing 👷‍♂️

Contributions are welcome! If you find any issues or have suggestions for improvements,
please open an issue or submit a pull request.

## License 📜

This project is licensed under the [MIT License](link-to-license-file).

## Contributors ❤️

<a href="https://github.com/virattt/financial-agent-ui/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=virattt/financial-agent-ui" />
</a>

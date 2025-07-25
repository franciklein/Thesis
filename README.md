# Thesis

## INTRODUCTION

The topic for my master’s thesis was born from an idea from my workplace. Currently I work as a technical writer for a multinational software company, SAP.

The company overall has more than a thousand technical writers, creating content every day. SAP has various products, each product storing their technical documentations in their preferred place and in preferred format, meeting their business needs.
This makes the company colourful and the products customizable, but at the same time it is hard to find the exact document if needed. So, a very relevant question popped up within the local technical writer team:

“Would it be possible to use a bot, to research through all of our technical documentation, and find the desired content in seconds?”

Motivated by this question, my master’s thesis will be researching the current possible solutions, the AI assistants dedicated to this application area.

After the release of ChatGPT by OpenAI, hundreds of ML (machine learning) projects appeared for different applications powered by LLMs (large language models). One such application is information extraction: analyzing vast amounts of text-based documentation to act as a virtual expert in the subject matter and answer the questions of human users. I will be exploring these solutions, paying special attention to the pricing
options, supported features of these tools, and comparing their performance and capabilities. I will select the most suitable tools, and test them for different document resources, formats. Then I will analyze the results of the testing.

With the conclusion of my impressions of the existing tools, I will build my own model and test it with various inputs and criteria. With the results of the testing, I will make my conclusion and provide suggestions for solving the original problem of information extraction.

In summary, my tasks will look as follows:
- Creating document datasets of different sizes, topics, and structure for testing.
- Finding and getting to know several ML tools for information extraction.
- Determining the advantages and disadvantages of each tool.
- Building own model with the gathered information.
- Configuring and feeding the model with the datasets.
- Testing the information extraction accuracy of the tools.
- Writing recommendations for choosing the right tool for a given application.

The given application of the tested tools will be, to search and analyse Technical Documentations.


## SUMMARY

When planning this thesis, I was expecting to discover significant differences between the online models, and with careful examination and selection of the best functions, I will build my local model. Contrary to my expectations, the online tools were not that diverse with no significant differences. Most of them reacted the same way to my tests, and the main difference were the supported file formats and the access of searching the web during the chat session.

This discovery was a surprising experience and yet a logical explanation as every LLM chatbot have the same operating mechanism. With this conclusion I started to build my local model in the way of fulfilling my requirements. The main difference between my model and the online tools was the supported file formats. As my aim was to provide a solution to my fellow technical writer colleagues. the required file format was Markdown, which is the most used format for writing technical documents.

I built my chatbot in Jupyter Notebook environment with using RAG method. I created one file for the retrieval part, which loads and prepares the text for the LLM model, then I created a separate notebook for the generator part, which includes feeding the documents to the model, then generating an answer as a reply to the given query. With my local model ready, I was able to run the same tests I did on the online tools and
compare the results. Drawing the conclusions, the online tools and the local model can provide the same functions. on the same level.

My suggestion for selecting the suitable tool was to consider confidentiality and cost saving over each other. Since the performance of the online and local tools are similar, my viewpoints were the following:

- Should the uploaded documents be handled as confidential?
- Does the person/company have the resources for the building and operational costs of the local model?
- 
In this thesis, my simulated environment was a big corporation, therefore I suggest building a local LLM model over using a third-party software.

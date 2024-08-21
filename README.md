# GenAihubdemos
The generative AI hub SDK is available for installation via PyPI.

To install this SDK, use the following pip command, which includes support for all models in GenAI Hub incl. langchain support:

pip install "generative-ai-hub-sdk[all]"
It is important to note that the generative-ai-hub-sdk package does not include langchain by default.
By using the [all] option as in pip install generative-ai-hub-sdk[all], pip installs all extra libraries which includes support for google, amazon, etc. models as well as langchain support. You can install a subset of these extra libraries by specifying them in square brackets.

pip install "generative-ai-hub-sdk[google, amazon]"
or only google models including langchain support:

pip install "generative-ai-hub-sdk[google_langchain]"
Note that the openai SDK (without langchain) is installed by default.
Use this to add only langchain support for models that support the openai API:

pip install "generative-ai-hub-sdk[openai_langchain]"

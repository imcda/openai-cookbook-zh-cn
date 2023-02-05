

# OpenAI 中文手册（OpenAI Cookbook)

![openai-logo](https://raw.githubusercontent.com/imcda/openai-cookbook-zh-cn/main/images/OpenAI_Logo.svg.png)

OpenAI 中文手册分享了使用 [OpenAI API] 完成常见任务的示例代码。

要运行这些例子，你需要一个OpenAI账户和相关的API密钥（[创建一个免费账户][API Signup]).

大多数代码示例是用Python编写的，尽管这些概念可以应用于任何语言。

## 指南 & 示例

* API 的使用情况
  * [如何处理请求频率限制](examples/How_to_handle_rate_limits.ipynb)
    * [避免触及请求频率限制的并行处理脚本示例](examples/api_request_parallel_processor.py)
  * [如何用 tiktoken 计算 token](examples/How_to_count_tokens_with_tiktoken.ipynb)
  * [如何串联补全](examples/How_to_stream_completions.ipynb)
* GPT-3
  * [指南：如何运行大型语言模型](how_to_work_with_large_language_models.md)
  * [指南：提高可靠性的技术](techniques_to_improve_reliability.md)
  * [How to use a multi-step prompt to write unit tests](examples/Unit_test_writing_using_a_multi-step_prompt.ipynb)
  * [Text writing examples](text_writing_examples.md)
  * [Text explanation examples](text_explanation_examples.md)
  * [Text editing examples](text_editing_examples.md)
  * [Code writing examples](code_writing_examples.md)
  * [Code explanation examples](code_explanation_examples.md)
  * [Code editing examples](code_editing_examples.md)
* Embeddings
  * [Text comparison examples](text_comparison_examples.md)
  * [How to get embeddings](examples/Get_embeddings.ipynb)
  * [Question answering using embeddings](examples/Question_answering_using_embeddings.ipynb)
  * [Semantic search using embeddings](examples/Semantic_text_search_using_embeddings.ipynb)
  * [Recommendations using embeddings](examples/Recommendation_using_embeddings.ipynb)
  * [Clustering embeddings](examples/Clustering.ipynb)
  * [Visualizing embeddings in 2D](examples/Visualizing_embeddings_in_2D.ipynb) or [3D](examples/Visualizing_embeddings_in_3D.ipynb)
  * [Embedding long texts](examples/Embedding_long_inputs.ipynb)
* Fine-tuning GPT-3
  * [Guide: best practices for fine-tuning GPT-3 to classify text](https://docs.google.com/document/d/1rqj7dkuvl7Byd5KQPUJRxc19BJt8wo0yHNwK84KfU3Q/edit)
  * [Fine-tuned classification](examples/Fine-tuned_classification.ipynb)
* DALL-E
  * [How to generate and edit images with DALL-E](examples/dalle/Image_generations_edits_and_variations_with_DALL-E.ipynb)
* Azure OpenAI (alternative API from Microsoft Azure)
  * [How to get completions from Azure OpenAI](examples/azure/completions.ipynb)
  * [How to get embeddings from Azure OpenAI](examples/azure/embeddings.ipynb)
  * [How to fine-tune GPT-3 with Azure OpenAI](examples/azure/finetuning.ipynb)

## Related resources

Beyond the code examples here, you can learn about the [OpenAI API] from the following resources:

* Try out the API in the [OpenAI Playground]
* Read about the API in the [OpenAI Documentation]
* Discuss the API in the [OpenAI Community Forum]
* Look for help in the [OpenAI Help Center]
* See example prompts in the [OpenAI Examples]
* Play with a free research preview of [ChatGPT]
* Stay up to date with the [OpenAI Blog]

## Contributing

If there are examples or guides you'd like to see, feel free to suggest them on the [issues page].

[ChatGPT]: https://chat.openai.com/
[OpenAI API]: https://openai.com/api/
[API Signup]: https://beta.openai.com/signup
[OpenAI Playground]: https://beta.openai.com/playground
[OpenAI Documentation]: https://beta.openai.com/docs/introduction
[OpenAI Community Forum]: https://community.openai.com/top?period=monthly
[OpenAI Help Center]: https://help.openai.com/en/
[OpenAI Examples]: https://beta.openai.com/examples
[OpenAI Blog]: https://openai.com/blog/
[issues page]: https://github.com/openai/openai-cookbook/issues



# OpenAI 中文手册（OpenAI Cookbook)

![openai-logo](https://raw.githubusercontent.com/imcda/openai-cookbook-zh-cn/main/images/OpenAI_Logo.png)

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
  * [如何使用多步骤提示来编写单元测试](examples/Unit_test_writing_using_a_multi-step_prompt.ipynb)
  * [文本写作范例](text_writing_examples.md)
  * [文本解释实例](text_explanation_examples.md)
  * [文本编辑实例](text_editing_examples.md)
  * [代码编写实例](code_writing_examples.md)
  * [代码解释实例](code_explanation_examples.md)
  * [代码编辑实例](code_editing_examples.md)
* 词向量
  * [文本比较实例](text_comparison_examples.md)
  * [如何获得词向量](examples/Get_embeddings.ipynb)
  * [使用词向量回答问题](examples/Question_answering_using_embeddings.ipynb)
  * [使用词向量的语义搜索](examples/Semantic_text_search_using_embeddings.ipynb)
  * [使用词向量的建议](examples/Recommendation_using_embeddings.ipynb)
  * [对词向量进行聚类](examples/Clustering.ipynb)
  * [在 2D 中可视化词向量](examples/Visualizing_embeddings_in_2D.ipynb) 或 [3D](examples/Visualizing_embeddings_in_3D.ipynb)
  * [词向量长文本](examples/Embedding_long_inputs.ipynb)
* 微调 GPT-3
  * [指南：微调 GPT-3 对文本进行分类的最佳做法](https://docs.google.com/document/d/1rqj7dkuvl7Byd5KQPUJRxc19BJt8wo0yHNwK84KfU3Q/edit)
  * [微调分类](examples/Fine-tuned_classification.ipynb)
* DALL-E
  * [如何用 DALL-E 生成和编辑图像](examples/dalle/Image_generations_edits_and_variations_with_DALL-E.ipynb)
* Azure OpenAI(基于微软 Azure 的 OpenAI)
  * [如何从 Azure OpenAI 获取补全功能](examples/azure/completions.ipynb)
  * [如何从 Azure OpenAI 获取词向量功能](examples/azure/embeddings.ipynb)
  * [如何用 Azure OpenAI 微调 GPT-3](examples/azure/finetuning.ipynb)

## 相关资源

除了这里的代码示例，你可以从以下资源中了解 [OpenAI API] :

* 在试验室 [OpenAI Playground] 试试 API 的使用效果
* 在文档 [OpenAI Documentation] 了解 API 的使用方法
* 在论坛 [OpenAI Community Forum] 讨论 API 的使用经验
* 在帮助中心 [OpenAI Help Center] 寻求使用问题的帮助
* 在案例库 [OpenAI Examples] 找到更多使用案例
* 或者不如亲自上手体验一下神奇的 [ChatGPT] 吧
* 别忘了，在博客 [OpenAI Blog] 第一时间跟进我们的最新消息

## 贡献

如果有你想看到的示例或指南，请随时在 [issues page] 提出你的需求.

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

## 更多探讨

在翻译过程中，我也发现自己能力的不足，在一些词的翻译上，无法找到准确的表达，我使用了原词，同时有些词我按照我的理解做了翻译，但仍觉得不够完美，将他们罗列在下面，供大家共同讨论，欢迎大家在 issue 中一起讨论。

### 是否有更好更准确的翻译
1. token
2. How_to_stream_completions
3. Embeddings
# ChatGPT Help Us

推荐先把本页内容**全部看完**再选择适合你的一种或多种方式进行优化！



## 一、利用ChatGPT润色的基本

- 先分部分段落润色，然后可以整体调整统一风格。

- 尽量使用多轮对话（不断发问让他进一步优化），不断激发GPT模型的潜力。

- 采用不用的润色指令。

- 使用更新的GPT模型。

  

## 二、润色指令

This list of writing prompts are from [github-ChatGPT Prompts for Academic Writing](https://github.com/ahmetbersoz/chatgpt-prompts-for-academic-writing)

```
Rewrite this paragraph in an academic language: [PARAGRAPH]

Paraphrase the text using more academic and scientific language. Use a neutral tone and avoid repetitions of words and phrases. [PARAGRAPH]

Improve the style of my writing? [PARAGRAPHS]

Improve the clarity and coherence of my writing [PARAGRAPHS]

Improve the organization and structure of my paper [PARAGRAPHS]

Can you improve this paragraph using passive voice: [PARAGRAPH]

Can you improve this paragraph to make it more cohesive? [PARAGRAPH]

Give three variations of this sentence: [SENTENCE] 
```

```
Analyze the text below for style, voice, and tone. Using NLP, create a prompt to write a new article in the same style, voice, and tone: [PARAGRAPHS]

Please write a few paragraphs using the following list of points [LIST] 

Write a transition sentence to connect the following two paragraphs: [PARAGRAPH1] [PARAPGRAPH2]

Provide effective transitions between paragraphs [PARAGRAPH1] [PARAGRAPH2]
```

```
Provide me a list of synonyms for [PARAGRAPH] and evaluate them in the context of [PARAGRAPH]

Act as a language expert, proofread my paper on [TOPIC SENTENCE] while putting a focus on grammar and punctuation.

Proofread the following text for spelling and grammatical errors and rewrite it with corrections. [PARAGRAPHS] 
```



一些措辞：

```
更精确的措辞（More precise）：选择更精确的词汇，例如使用“generate”代替“produce”或“analyze”代替“look at”。
更简练的表达（More concise）：消除不必要的词语和短语，使句子更加清晰、直接。
更客观的语言（More objective）：删除主观性语言，以中立的方式呈现信息。
更具体的描述（More specific）：提供更具体的细节，以支持论点或想法。
更连贯的表达（More coherent）：确保句子组织良好，逻辑流畅。
更一致的风格（More consistent）：确保句子所使用的语言和风格与论文的其余部分一致。
更符合学术风格（More academic）：使用学术写作中常用的术语和短语，例如“furthermore”和“thus”。
更正式的语法（More formal grammar）：使用正确的语法和句法，例如避免句子碎片或跑题的句子。
更具细节的描述（More nuanced）：通过使用词语或短语来传达更复杂或微妙的含义，使句子更具细节。
```



## 三、使用官方ChatGPT

网站为：https://chatgpt.com/ 。因为对香港暂时封闭，条件是需要有连通国外的🪜。

1. 直接新建对话然后输入：

   `polish: <your contents>`

2. 使用**GPT商店**中的**Academic Assistant Pro**，选择后开始对话，预设以及微调过以适应学术写作。

   

## 四、使用 API 的 System 预设

自建网站为：https://chatgpt.crazyang.com/ or https://chat.crazyang.com/ 。记得模型选择为 `gpt-4o-mini`。



在使用<u>chatgpt</u>时，可以新增一条system的对话，以固定系统角色，让接下来的所有对话都满足是润色的设定。复制以下内容：

```
When tasked with rewriting or polishing content, provide at least three alternative versions or suggestions. This demonstrates your ability to offer different academic perspectives and improvements. The academic field is computer science.
```



![image-20240823010923024](https://raw.githubusercontent.com/yzy1996/Image-Hosting/master/202408230109366.png)

![image-20240823010958941](https://raw.githubusercontent.com/yzy1996/Image-Hosting/master/202408230110199.png)

---

**2024年4月Nature上的润色指令建议是：**

```
I'm writing a paper on [topic] for a leading [discipline] academic journal. What I tried to say in the following section is [specific point].
Please rephrase it for clarity, coherence and conciseness, ensuring each paragraph flows into the next. Remove jargon. Use a professional tone.
```

**对第一次的回复不满意：**

```
This isn't quite what I meant. Let's adjust this part.
```



## 五、使用 GPT Academic 网页

网站为：https://github.com/binary-husky/gpt_academic

在线使用网站为：https://github.com/binary-husky/gpt_academic/wiki/online

在网页上直接输入需要润色的内容，然后点击**学术语料润色**按钮即可

![image-20240823013203886](https://raw.githubusercontent.com/yzy1996/Image-Hosting/master/202408230132463.png)



## 六、其他工具

- [Consensus](https://consensus.app/)：一个AI学术搜索引擎，可以帮你智能检索**真实的**参考文献。如果开通了ChatGPT Plus，则可以直接在对话中@consensus直接调用工具和润色。



## 七、参考

https://github.com/binary-husky/gpt_academic 63k stars

https://github.com/ahmetbersoz/chatgpt-prompts-for-academic-writing 2.7k stars
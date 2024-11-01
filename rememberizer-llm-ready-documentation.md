# Rememberizer LLM Ready Documentation

*Generated at 2024-10-31 20:41:45 PDT. Available as raw content at [rememberizer-llm-ready-documentation.md](https://raw.githubusercontent.com/skydeckai/rememberizer-webflow/refs/heads/docs/rememberizer-llm-ready-documentation.md).*

This document provides a comprehensive, consolidated reference of Rememberizer's documentation, optimized for large language model (LLM) consumption. It combines various documentation sources into a single, easily accessible format, facilitating efficient information retrieval and processing by AI systems.

```
==> SUMMARY.md <==
# Table of contents

* [Why Rememberizer?](README.md)
* [Background](background/README.md)
  * [What are Vector Embeddings and Vector Databases?](background/what-are-vector-embeddings-and-vector-databases.md)
* [Personal](personal/README.md)
  * [Rememberizer Slack integration](personal/rememberizer-slack-integration.md)
  * [Rememberizer Dropbox integration](personal/rememberizer-dropbox-integration.md)
  * [Rememberizer Google Drive integration](personal/rememberizer-google-drive-integration.md)
  * [Rememberizer Gmail integration](personal/rememberizer-gmail-integration.md)
  * [Rememberizer Memory integration](personal/rememberizer-memory-integration.md)
  * [Rememberizer App](personal/rememberizer-app.md)
  * [Mementos Filter Access](personal/mementos-filter-access.md)
  * [Manage third-party apps](personal/manage-third-party-apps.md)
  * [Common knowledge](personal/common-knowledge.md)
  * [Search your knowledge](personal/search-your-knowledge.md)
  * [Manage your embedded knowledge](personal/manage-your-embedded-knowledge.md)
* [Developer](developer/README.md)
  * [Registering Rememberizer apps](developer/registering-rememberizer-apps.md)
  * [Authorizing Rememberizer apps](developer/authorizing-rememberizer-apps.md)
  * [Creating a Rememberizer GPT](developer/creating-a-rememberizer-gpt.md)
  * [Talk-to-Slack the Sample Web App](developer/talk-to-slack-the-sample-web-app.md)
  * [Registering and using API Keys](developer/registering-and-using-api-keys.md)
  * [LangChain integration](developer/langchain-integration.md)
  * [Vector Stores](developer/vector-stores.md)
  * [API documentations](developer/api-documentations/README.md)
    * [Memorize content to Rememberizer](developer/api-documentations/memorize-content-to-rememberizer.md)
    * [Retrieve documents](developer/api-documentations/retrieve-documents.md)
    * [Retrieve document contents](developer/api-documentations/retrieve-document-contents.md)
    * [Retrieve Slack's content](developer/api-documentations/retrieve-slacks-content.md)
    * [Search for documents by semantic similarity](developer/api-documentations/search-for-documents-by-semantic-similarity.md)
    * [List available data source integrations](developer/api-documentations/list-available-data-source-integrations.md)
    * [Retrieve current user's account details](developer/api-documentations/retrieve-current-users-account-details.md)
    * [Get all added public knowledge](developer/api-documentations/get-all-added-public-knowledge.md)
    * [Vector Store APIs](developer/api-documentations/vector-store/README.md)
      * [Get vector store's information](developer/api-documentations/vector-store/get-vector-stores-information.md)
      * [Get a list of documents in a Vector Store](developer/api-documentations/vector-store/get-a-list-of-documents-in-a-vector-store.md)
      * [Get the information of a document](developer/api-documentations/vector-store/get-the-information-of-a-document.md)
      * [Add new text document to a Vector Store](developer/api-documentations/vector-store/add-new-text-document-to-a-vector-store.md)
      * [Upload files to a Vector Store](developer/api-documentations/vector-store/upload-files-to-a-vector-store.md)
      * [Update file's content in a Vector Store](developer/api-documentations/vector-store/update-files-content-in-a-vector-store.md)
      * [Remove a document in Vector Store](developer/api-documentations/vector-store/remove-a-document-in-vector-store.md)
      * [Search for Vector Store documents by semantic similarity](developer/api-documentations/vector-store/search-for-vector-store-documents-by-semantic-similarity.md)
* [Notices](notices/README.md)
  * [Terms of Use](notices/terms-of-use.md)
  * [Privacy Policy](notices/privacy-policy.md)
  * [Releases](notices/releases/README.md)
    * [Nov 1st, 2024](notices/releases/nov-1st-2024.md)
    * [Oct 25th, 2024](notices/releases/oct-25th-2024.md)
    * [Oct 18th, 2024](notices/releases/oct-18th-2024.md)
    * [Oct 11th, 2024](notices/releases/oct-11th-2024.md)
    * [Oct 4th, 2024](notices/releases/oct-4th-2024.md)
    * [Sep 27th, 2024](notices/releases/sep-27th-2024.md)
    * [Sep 20th, 2024](notices/releases/sep-20th-2024.md)
    * [Sep 13th, 2024](notices/releases/sep-13th-2024.md)
    * [Aug 16th, 2024](notices/releases/aug-16th-2024.md)
    * [Aug 9th, 2024](notices/releases/aug-9th-2024.md)
    * [Aug 2nd, 2024](notices/releases/aug-2nd-2024.md)
    * [Jul 26th, 2024](notices/releases/jul-26th-2024.md)
    * [Jul 12th, 2024](notices/releases/jul-12th-2024.md)
    * [Jun 28th, 2024](notices/releases/jun-28th-2024.md)
    * [Jun 14th, 2024](notices/releases/jun-14th-2024.md)
    * [May 31st, 2024](notices/releases/may-31st-2024.md)
    * [May 17th, 2024](notices/releases/may-17th-2024.md)
    * [May 10th, 2024](notices/releases/may-10th-2024.md)
    * [Apr 26th, 2024](notices/releases/apr-26th-2024.md)
    * [Apr 19th, 2024](notices/releases/apr-19th-2024.md)
    * [Apr 12th, 2024](notices/releases/apr-12th-2024.md)
    * [Apr 5th, 2024](notices/releases/apr-5th-2024.md)
    * [Mar 25th, 2024](notices/releases/mar-25th-2024.md)
    * [Mar 18th, 2024](notices/releases/mar-18th-2024.md)
    * [Mar 11th, 2024](notices/releases/mar-11th-2024.md)
    * [Mar 4th, 2024](notices/releases/mar-4th-2024.md)
    * [Feb 26th, 2024](notices/releases/feb-26th-2024.md)
    * [Feb 19th, 2024](notices/releases/feb-19th-2024.md)
    * [Feb 12th, 2024](notices/releases/feb-12th-2024.md)
    * [Feb 5th, 2024](notices/releases/feb-5th-2024.md)
    * [Jan 29th, 2024](notices/releases/jan-29th-2024.md)
    * [Jan 22nd, 2024](notices/releases/jan-22nd-2024.md)
    * [Jan 15th, 2024](notices/releases/jan-15th-2024.md)
  * [B2B](notices/b2b/README.md)
    * [About Reddit Agent](notices/b2b/about-reddit-agent.md)
* [Rememberizer LLM Ready Documentation](rememberizer-llm-ready-documentation.md)


==> README.md <==
---
description: Introduction
---

# Why Rememberizer?

Generative AI apps work better when they have access to background information. They need to know what you know. A great way to achieve that is to give them access to relevant content from the documents, data and discussions you create and use. That is what Rememberizer does.


==> background/README.md <==
# Background



==> background/what-are-vector-embeddings-and-vector-databases.md <==
---
description: Why Rememberizer is more than just a database or keyword search engine.
---

# What are Vector Embeddings and Vector Databases?

Rememberizer uses vector embeddings in vector databases to enable searches for semantic similarity within user knowledge sources. This is a fundamentally more advanced and nuanced form of information retrieval than simply looking for keywords in content through a search engine or database.

<figure><img src="../.gitbook/assets/multidimensional_space.png" alt=""><figcaption><p>A multidimensional Space</p></figcaption></figure>

In their most advanced form (as used by Rememberizer) vector embeddings are created by language models with architectures similar to the AI LLMs (Large Language Models) that underpin OpenAI's gpt models and ChatGPT service as well as models/services from Google (Gemini) , Anthropic (Claude), Facebook (LLama 2) and others. For this reason it is natural to use vector embeddings to discover relevant knowledge to include in the context of AI model prompts. The technologies are complementary and somewhat equivalent. For this reason most providers of LLMs as a service will also produce vector embeddings as a service (for example:  [a blog from Together AI](https://www.together.ai/blog/embeddings-endpoint-release) or [another blog from OpenAI](https://openai.com/blog/introducing-text-and-code-embeddings)).

What does a vector embedding look like? Consider a co-ordinate (x,y) in two dimensions. If it represents a line from the orgin to this point, we can think of it as a line with a direction, in other words a _vector in two dimensions._ In our context, a vector embedding will be a list of something like 768 numbers representing a vector in a 768-dimensional space. Ultimately this list of numbers can represent weights between zero and one in a Transformer model that define the meaning in a phrase such as "A bolt of lightening out of the blue." This is fundamentally the same underlying representation of meaning used in GPT-4 for example. As a result, we can expect a good vector embedding to enable the same brilliant apparent understanding that we see in modern AI language models.

\
It is worth noting that vector embeddings can be used to represent more than just text, but also other types of data such as images or sound. And with a properly trained model one can compare across media, so that a vector embedding on a block of text can be compared to an image, or _visa versa_. Today Rememberizer enables searches within just the text component of user documents and knowledge. But text-to-image and image-to-text search are on the roadmap.\
\
Google uses vector embeddings to power their text search (text-to-text) and also their image search (text-to-image) ([reference](https://cloud.google.com/blog/topics/developers-practitioners/meet-ais-multitool-vector-embeddings)) . Facebook has contemplated using embeddings for their social network search ([reference](https://research.facebook.com/publications/embedding-based-retrieval-in-facebook-search/)). Snapchat uses vector embeddings to understand context in order to serve the right ad to the right use at the right time ([reference](https://eng.snap.com/machine-learning-snap-ad-ranking)).

To deeply understand how vector embedding and vector databases work start with the [overview](https://huggingface.co/blog/getting-started-with-embeddings) from Hugging Face. Pinecone (a vector embedding database as a service) has a good [overview](https://www.pinecone.io/learn/vector-embeddings/) as well.

Another great source for understanding the search and knowledge in vectors is the Meta/Facebook paper and code for the FAISS library. "FAISS: A Library for Efficient Similarity Search and Clustering of Dense Vectors" by Johnson, Douze, and Jégou (2017): FAISS provides a comprehensive overview of a library designed for efficient similarity search and clustering of dense vectors. It discusses methods for optimizing the indexing and search processes in large-scale vector databases, including those based on Product Quantization. The best place to learn more about this is the documentation along with the [code on Github](https://github.com/facebookresearch/faiss).

\
Be sure to consider the June 2017 paper that started the genAI (generative artificial intelligence) revolution, "Attention Is All You Need." ([reference](https://arxiv.org/abs/1706.03762)) which introduces the Transformer architecture behind GPT models and all the LLMs that follow from OpenAI, Google, Meta (Facebook), Nvidia, Microsoft, IBM, Anthropic, Mistral, Salesforce, xAI (Elon Musk), Stability AI, Cohere, and many other open sources.\
Consider also, "Approximate Nearest Neighbors: Towards Removing the Curse of Dimensionality" ([reference 1998](https://dl.acm.org/doi/10.1145/276698.276876), [reference 2010](https://www.theoryofcomputing.org/articles/v008a014/v008a014.pdf)). These papers discuss the theory behind approximate nearest neighbor (ANN) search in high-dimensional spaces, a core concept in vector databases for efficiently retrieving similar items.

{% hint style="info" %}
One exciting thing about these Transformer-based models is that the more data they used, the bigger (more parameters) they got, the better their understanding and capabilities. OpenAI first noticed this when they trained their GPT-2 model. Realizing this potential, they immediately stopped being an open-source oriented non-profit and became a closed source for-profit company focused on producing GPT-3, GPT-4 and its famous front end, ChatGPT. Interestingly, Google owns the patent on this technology -- it was their researchers behind Transformers and Attention Is All You Need ([reference](https://patents.google.com/patent/US10452978B2/en)).\
\
ChatGPT begs to differ a bit about my characterization, writing that "The narrative around OpenAI's transition from an open-source-oriented non-profit to a closed-source for-profit entity simplifies a complex evolution. OpenAI's shift included a focus on safety and responsible AI development alongside commercialization aspects. It's also worth noting that while OpenAI has prioritized developing proprietary technology like GPT-3 and beyond, it continues to engage with the research community through publications and collaborations."
{% endhint %}

BERT language models are based on Transformers and are often used in advanced vector embedding engines. This was introduced in the 2018 paper "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding" ([reference](https://arxiv.org/abs/1810.04805)). BERT (Bidirectional Encoder Representations from Transformers) marked a significant shift towards pre-trained models that can be fine-tuned for a wide range of NLP tasks. Its innovative use of bidirectional training and transformer architecture set new standards for model performance across numerous benchmarks.\
\
Earlier innovative methods for creating vector embeddings were introduced by GloVe (2014, Stanford), Word2Vec (2013, Google). "GloVe: Global Vectors for Word Representation" ([reference](https://nlp.stanford.edu/pubs/glove.pdf)): The GloVe (Global Vectors) paper proposed a new global log-bilinear regression model for the unsupervised learning of word representations, combining the benefits of the two main approaches to embedding: global matrix factorization and local context window methods. "Efficient Estimation of Word Representations in Vector Space" ([reference](https://arxiv.org/abs/1301.3781)): This paper introduced Word2Vec, a groundbreaking approach to generating word embeddings. Word2Vec models, including the Continuous Bag of Words (CBOW) and Skip-Gram models, are pivotal in the evolution of word embeddings.


==> personal/rememberizer-slack-integration.md <==
---
description: >-
  This guide will walk you through the process of integrating your Slack
  workspace into Rememberizer as a knowledge source.
---

# Rememberizer Slack integration

1. Sign in to your account.
2. Navigate to **Personal > Your Knowledge** tab, or visit [https://rememberizer.ai/personal/knowledge](https://rememberizer.ai/personal/knowledge). You should see all available knowledge sources there, including Slack.

<figure><img src="../.gitbook/assets/slack_personal_knowledge.png" alt=""><figcaption><p>Your Knowledge, ready to connect to Slack</p></figcaption></figure>

3. Click the **"Connect"** button of the Slack knowledge source. You will be redirected to a new page asking for your permission to allow Rememberizer to access your Slack workspace.

<figure><img src="../.gitbook/assets/slack_oauth.png" alt=""><figcaption><p>Slack OAuth screen</p></figcaption></figure>

> **Note:** If you see a warning that this application is not authorized by Slack, it is because Rememberizer is intended to search for Slack content outside of Slack, which is against the [Slack App Directory Guidelines](https://api.slack.com/directory/guidelines).

4. Click **"Allow"** to install the Rememberizer Slack app to your workspace. Once you've granted the necessary permissions, you'll be redirected back to our platform, at which you should see your Slack workspace connected and a side panel pops up.

<figure><img src="../.gitbook/assets/slack_auth_redirect.png" alt=""><figcaption><p>A-COMPANY has been added as a knowledge source</p></figcaption></figure>

5. Now that you're connected, you need to specify which channels our product should source messages from. Choose your desired files or folders from the side panel. If the side panel does not appear, click on the **"Select"** button to open the side panel.

<figure><img src="../.gitbook/assets/slack_choose_knowledge.png" alt=""><figcaption><p>Select channels to be embedded as knowledge</p></figcaption></figure>

6. After selecting your channels, our system will begin embedding the messages and files. This process may take a few minutes depending on the amount of data.

### What's next?

Use the [Memento](mementos-filter-access.md) feature to filter access to the sourced data. Combine this with your knowledge from other applications such as Google Drive, Box, Dropbox, etc. to form a comprehensive memento.

You can also [Search Your Knowledge](https://rememberizer.ai/personal/search) through our web UI, or better, use this knowledge in an LLM through our GPT app or our public API.

And that's it! If you encounter any issues during the process, feel free to contact our support team.


==> personal/common-knowledge.md <==
---
description: >-
  Enhance your knowledge or get started fast by adding AI access to pre-indexed
  data from us and others.
---

# Common knowledge

## What is common knowledge

In Rememberizer, registered users **(publishers)** can select their uploaded documents through mementos and share them publicly as common knowledge. Other users **(subscribers)** can access this public knowledge and add it to their own resources.

By contributing their data, other users can collectively enhance the available information on the common knowledge page. This collaborative approach allows all users to access a richer data source, thereby improving the learning capabilities of their AI applications.

## Add public common knowledge

In order to subscribe a common knowledge to your resource, follow the instructions below

* On navigation bar, choose **Personal > Common Knowledge**. Then, you will see the public common knowledge page.

<figure><img src="../.gitbook/assets/navbar_browse_ck.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/public_ck_page.png" alt=""><figcaption></figcaption></figure>

* Then, look for the common knowledge you want to subscribe. You can look up the knowledge by typing the knowledge's name on search bar. You can optionally choose the filter option next to the search bar.

<figure><img src="../.gitbook/assets/filter_option_ck.png" alt="" width="249"><figcaption><p>Filter of search bar</p></figcaption></figure>

<figure><img src="../.gitbook/assets/public_ck_search.png" alt=""><figcaption><p>Example of a search result</p></figcaption></figure>

* Then click **Add** button on the public common knowledge. After successful subscribe, you will see the **Add** button change to **Remove** button.

<figure><img src="../.gitbook/assets/not_add_ck.png" alt=""><figcaption><p>Unadded common knowledge</p></figcaption></figure>

<figure><img src="../.gitbook/assets/added_ck.png" alt=""><figcaption><p>Added common knowledge</p></figcaption></figure>

* Later, if you want to remove a subscribed knowledge, click the **Remove** button.

## Create a common knowledge

For detailed instructions of creating and sharing a common knowledge, visit this page [registering-and-using-api-keys.md](../developer/registering-and-using-api-keys.md "mention").



==> personal/rememberizer-google-drive-integration.md <==
---
description: >-
  This guide will walk you through the process of integrating your Google Drive
  into Rememberizer as a knowledge source.
---

# Rememberizer Google Drive integration

1. Sign in to your account.
2. Navigate to **Personal > Your Knowledge** tab, or visit [https://rememberizer.ai/personal/knowledge](https://rememberizer.ai/personal/knowledge). You should see all available knowledge sources there, including Google Drive.

<figure><img src="../.gitbook/assets/drive_personal_knowledge.png" alt=""><figcaption></figcaption></figure>

3. Click the **"Connect"** button of the Google Drive knowledge source. You will be redirected to a new page asking for your permission to allow Rememberizer to access your Google Drive. Select your Google Drive account.

<figure><img src="../.gitbook/assets/drive_oauth_step_1.jpg" alt=""><figcaption></figcaption></figure>

4. Approve the app by clicking on "**Continue"**.

<figure><img src="../.gitbook/assets/drive_oauth_step_2.jpg" alt=""><figcaption></figcaption></figure>

5. Allow Rememberizer to **See and download all your Google Drive files** by clicking **"Continue".**

<figure><img src="../.gitbook/assets/drive_oauth_step_3.jpg" alt=""><figcaption></figcaption></figure>

6. You'll be redirected back to our platform, at which you should see your Drive account connected and a side panel pops up.

<figure><img src="../.gitbook/assets/drive_auth_redirect.png" alt=""><figcaption></figcaption></figure>

7. Now that you're connected, you need to specify which files and folders our product should embed. Choose your desired files or folders from the side panel. If the side panel does not appear, click on the **"Select"** button to open the side panel.

<figure><img src="../.gitbook/assets/drive_choose_knowledge.png" alt=""><figcaption></figcaption></figure>

8. After selecting the files, click **"Add"** to start embedding your knowledge. You also need to check the box to agree with Rememberizer's policy of sharing your Google Drive data with third-party applications that you have specifically approved.

<figure><img src="../.gitbook/assets/drive_choose_knowledge_checkbox.png" alt=""><figcaption></figcaption></figure>

9. After selecting your files and folders, our system will begin embedding the messages and files. This process may take a few minutes depending on the amount of data.

<figure><img src="../.gitbook/assets/drive_indexing.png" alt=""><figcaption></figcaption></figure>

### Limitations of Google Drive Integration

* While Rememberizer's Google Drive integration allows you to access and embed a wide range of files and folders, it currently cannot access or embed files from the "Computers" section, which is used for backing up files from your computer due to restrictions set by Google.
* If you need to embed files from your local computer, we recommend using our Rememberizer Agent desktop application. To learn more about the Rememberizer Agent and how to install and use it, please refer to our [Rememberizer Agent](rememberizer-app.md) guide.

### What's next?

Use the [Memento](mementos-filter-access.md) feature to filter access to the sourced data. Combine this with your knowledge from other applications such as Slack, Box, Dropbox, etc. to form a comprehensive memento.

You can also [Search Your Knowledge](https://rememberizer.ai/personal/search) through our web UI, or better, use this knowledge in an LLM through our GPT app or our public API.

And that's it! If you encounter any issues during the process, feel free to contact our support team.


==> personal/rememberizer-app.md <==
# Rememberizer App

### Introduction.

Rememberizer App is a MacOS desktop application that converts your local files into vector embeddings and uploads them to your Rememberizer's knowledge as a data source. The application enables other LLMs to query your embeddings through Rememberizer's APIs to make answers based on your local files content.

### Benefits.

* **Data Utilization:** The application helps you to utilize your local files in a meaningful and productive way. It extracts valuable data from your files and makes it available for machine learning processes.
* **Ease of Use:** The application has a user-friendly interface and it’s easy to install and use. It does all the heavy lifting of converting files and uploading the data, so you don't have to.
* **Integration:** The Rememberizer App seamlessly integrates with other LLMs. This allows them to query your embeddings through Rememberizer's APIs to generate answers based on the content of your local files.

### Installation.

1. Download a version of Rememberizer App from [the links provided here](rememberizer-app.md#download-links).
2. Once the download is complete, locate the .dmg file in your downloads folder and double click on it.
3. Drag the Rememberizer App into your Applications folder when the new window opens.
4. Go to your Applications folder and click on the Rememberizer App to open it.

### How to Use.

1. **Sign In:** To use the Rememberizer App, you need to sign in using your Rememberizer account. If you do not have a Rememberizer account, you'll need to create one.

<figure><img src="../.gitbook/assets/rememberizer_app_sign_in.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/rememberizer_app_success_auth.png" alt=""><figcaption></figcaption></figure>

2. **Add Folders to the Data Source:** Once you have signed in, the Rememberizer App will begin operating in the background. You can access it by clicking the small icon located in the status bar, as illustrated below. For first-time use, you will need to add folders to the data source. This enables the Rememberizer App to convert files within those folders into vector embeddings and upload them to your Rememberizer Knowledge.

<figure><img src="../.gitbook/assets/rememberizer_app_add_folder_1.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/rememberizer_app_add_folder_2.png" alt=""><figcaption></figcaption></figure>

3. **Embedding And Uploading:** The software will seamlessly integrate these vector embeddings into your Rememberizer Knowledge database. Track the upload process via the Rememberizer status tab.

<figure><img src="../.gitbook/assets/rememberizer_app_status.png" alt=""><figcaption></figcaption></figure>

### Download links.

* Rememberizer App 1.6.1 ([MacOS](https://www.dropbox.com/scl/fi/hzytquytxmuhpov67spru/rememberizer-app-1.6.1.dmg?rlkey=0p30ok9qt4e33ua8scomagzev\&st=8yys88d5\&dl=1)) - [Release note](rememberizer-app.md#version-1.3.1-july-25-2024).

Please note, it is recommended to always use the latest version of the software to take advantage of all the latest features and improvements.

Rememberizer App is designed to make the process of converting local files to vector embeddings as seamless as possible. Enjoy using your data in a more productive way!

### Release notes.

### Version 1.6.1 (October 4th 2024)

#### Features and Improvements

* **Support for Empty Folders**: Users can now add empty folders as a data source.
* **Minor Improvements**: Enhancements to the user interface and performance.
* **GPU Support and Performance Improvements**: Added support for GPU acceleration to enhance processing speed.
* **Enhanced Embedding Program**: Configured to support the MPS version of PyTorch, optimizing for machine-specific builds.
* **Intelligent CPU Detection**: Implemented detection of CPU type to ensure the most suitable version of the embedding program is used.
* **Improved Data Source Management**: Utilized the Batch Delete API for efficient file deletion in removed data sources.
* **Support for All Plain Text Files**: Enabled processing of various plain text file types.
* **Adherence to Gitignore Rules**: Files ignored by gitignore rules in Git repositories are now excluded from processing.



==> personal/rememberizer-memory-integration.md <==
# Rememberizer Memory integration

### Introduction

Rememberizer Memory allows third party apps to store and access data in a user's Rememberizer account, providing a simple way for valuable information to be saved and utilize across multiple user' applications.

### Benefits

#### For User

Shared Memory creates a single place where key results and information from all the user's apps are available in one location. Some benefits for user include:

* Easy Access: Important data is centralized, allowing both the user and their apps to easily access results from multiple apps in one place.
* Sync Between Apps: Information can be shared and synced between a user's different apps seamlessly without extra effort from the user.
* Persistent Storage: Data remains accessible even if individual apps are uninstalled, unlike app-specific local storage.

#### For App Developers

The Shared Memory provides app developers a simple way to access data from a user's other connected apps:

* No Backend Needed: Apps do not need to develop their own custom backend systems to store and share data.
* Leverage Other Apps: Apps can build on and utilize public data generated by a user's other installed apps, enriching their own functionality.
* Cross-App Integration: Seamless integration and data sharing capabilities are enabled between an app developer's different apps.

By default all apps have read-only access to Shared Memory, while each app can write only to its own memory space. The user has controls to customize access permissions as needed. This balances data sharing with user privacy and control.

### Config Your Memory

#### Global Settings

The Global Settings allow user to configure the default permissions for all apps using Shared Memory. This includes:

<figure><img src="../.gitbook/assets/memory_global_config.png" alt=""><figcaption><p>Config Memory in Knowledge Page</p></figcaption></figure>

#### Default Memory and Data Access Permissions for Apps

* **Read Own/Write Own:** Apps are exclusively permitted to access and modify their own memory data.
* **Read All/Write Own:** Apps can read memory data across all apps but are restricted to modifying only their own memory data.
* **Disable Memory:** By default, apps cannot access or store memory data.
* **Apply to All Option**: User can apply all app-specific permission settings back to the defaults chosen in Global Settings.

<figure><img src="../.gitbook/assets/memory_settings_panel.png" alt="" width="375"><figcaption></figcaption></figure>

User can clear all Memory documents with _**Forget your memory**_ option:

<figure><img src="../.gitbook/assets/forget_memory_popup.png" alt=""><figcaption><p>Confirmation Modal when Forget Memory</p></figcaption></figure>

#### App Settings

For each connected app, user can customize the Shared Memory permissions. Click on the **"Find an App"**, then click **"Your connected apps"** or go to the link [https://rememberizer.ai/personal/apps/connected](https://rememberizer.ai/personal/apps/connected) to see the list of your connected apps. Then, click **"Change"** on the Memory of the app you want to custom:

<figure><img src="../.gitbook/assets/app_memory_config.png" alt=""><figcaption><p>Config Memory for each App in Connected Apps Page</p></figcaption></figure>

#### Memory Access Permissions for Apps

* **Read Own/Write Own**: Permissions allow the app to only access and modify its own memory data, preventing it from interacting with other apps' memory.
* **Read All/Write Own**: The app can view memory data from all apps but is restricted to modifying only its own memory data.
* **Disable Memory**: The app is prohibited from accessing or modifying memory data.

This allows user fine-grained control over how each app can utilize Shared Memory based on the user's trust in that specific app. Permissions for individual apps can be more restrictive than the global defaults.

Together, the Global and App Settings give user powerful yet easy-to-use controls over how their data is shared through Shared Memory.

### Integrate with Memory Feature

#### API Endpoint

Rememberizer expose an API end point [/**api/v1/documents/memorize/**](https://docs.rememberizer.ai/\~/changes/8nxu1gB5bGpm7B5IZlQ8/developer/api-documentations/memorize-content-to-rememberizer) to let GPT App call to memorize the content.

Note: This api is available for Memory with [3rd-party apps with OAuth2 authentication](../developer/authorizing-rememberizer-apps.md) only (not [API-key](../developer/registering-and-using-api-keys.md) yet).

#### Memorize your knowledge

After authorizing with Rememberizer, the third party app can memorize it valuable knowledge.

Here, we will demonstrate a process using Remembeizer GPT App.

*   After using Rememberizer GPT App, user want to memorize the third point "Zero-Cost Abstractions".

    <figure><img src="../.gitbook/assets/interact_rememberizer_gpt.png" alt="" width="375"><figcaption><p>Interacting with Rememberizer GPT Apps</p></figcaption></figure>
* To use the Rememberizer App's Memory feature, user must first authorize the app to access your project. Use the **memorize** command to tell the app what knowledge it needs to store.

<figure><img src="../.gitbook/assets/rememberizer_auth_sign_in.png" alt="" width="563"><figcaption><p>Sign In to authorize Rememberizer</p></figcaption></figure>

* User can Config the Memory Option here, with the default value is based on the Global Config

<figure><img src="../.gitbook/assets/authorize_connection_screen.png" alt="" width="563"><figcaption><p>Authorizing Screen</p></figcaption></figure>

The Rememberizer now successfully memorizes knowledge.

<figure><img src="../.gitbook/assets/successful_memorize_knowledge.png" alt="" width="563"><figcaption></figcaption></figure>

* In Rememberizer, user can see the recent content at **Embed Knowledge Details** page.

<figure><img src="../.gitbook/assets/embedded_knowledge_detail.png" alt="" width="563"><figcaption></figcaption></figure>

With the **Talk to Slack** app, user can seamlessly apply and continue their progress using the data they have committed to memory. For example, memorized information they can easily query and retrieve

<figure><img src="../.gitbook/assets/recall_memory_talk_to_slack.png" alt=""><figcaption><p>Recall Memory Data in another app</p></figcaption></figure>

### Using Memory Data via Memento

* Another way to utilize the memory data is by creating **Memento** and refine the Memory into it. Visit [Memento Feature](mementos-filter-access.md#how-to-create-a-mementos) section for further information about creation instruction.
* Rememberizer saves content into files and user can choose any app to refine its content into **Memento**.

> Note: In older version, Rememberizer saves content into files and combine into folder for each date.

<figure><img src="../.gitbook/assets/memory_memento_feature.png" alt="" width="563"><figcaption></figcaption></figure>

With the [Memento Feature](https://docs.rememberizer.ai/personal/mementos-filter-access#what-is-a-memento-and-why-do-they-exist), user can utilize the Memory data even when the Memory App Config is Off.

### Search Memory document in Rememberizer

You can also [Search Your Knowledge](https://rememberizer.ai/personal/search) through our web UI, or better, use this knowledge in an LLM through our GPT app or our public API.


==> personal/search-your-knowledge.md <==
---
description: >-
  In Rememberizer, you can post a theme or question, and Rememberizer will
  provide a list of files and extracts parts that are conceptually similar.
---

# Search your knowledge

## Search in Rememberizer

* In the navigation bar, choose **Personal > Search Your Knowledge**. Then you will see the search page in Rememberizer

<figure><img src="../.gitbook/assets/navbar_search_rememberizer (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/search_rememberizer_page.png" alt=""><figcaption></figcaption></figure>

* Type the question or theme you want to search, then choose the the memento you want to limit the app's access and click Rememberizer button (or press Enter). The search process may take a few minutes, depending on the amount of data in the Memento.&#x20;

<figure><img src="../.gitbook/assets/memento_search_rememberizer.png" alt="" width="269"><figcaption><p>Memento Filtering in search Rememberizer</p></figcaption></figure>

* Eventually, you will see list of documents matching question or theme you require. You can click to the file and it will dropdown the matching chunk text related to your question or theme.

<figure><img src="../.gitbook/assets/search_result_rememberizer.png" alt=""><figcaption><p>An example of search result</p></figcaption></figure>


==> personal/README.md <==
# Personal



==> personal/manage-third-party-apps.md <==
# Manage third-party apps

## Explore third-party apps and service

User can view and explore all third-party apps that connect with Rememberizer in **App directory** page with the below instructions.

* On the navigation bar, choose **Personal > Find an App**. Then, you will see the App directory page.

<figure><img src="../.gitbook/assets/navbar_browsing_app_dir.png" alt=""><figcaption><p>Navigation bar browsing App Directory page</p></figcaption></figure>

<figure><img src="../.gitbook/assets/app_dir_page.png" alt=""><figcaption><p>App directory page</p></figcaption></figure>

* Find the app you want to explore. You can do this by type the name of the app in search bar with optional **filter and sorting order.**

<figure><img src="../.gitbook/assets/search_app_dir_page.png" alt=""><figcaption><p>Search bar with filter and sort order button</p></figcaption></figure>

* Click on the **name of the third-party app** or **Explore button** to open the app.&#x20;

<figure><img src="../.gitbook/assets/location_name_explore_button.png" alt=""><figcaption><p>App's name and Explore button</p></figcaption></figure>

* When using the app, it will requires authorizing the apps with Rememberizer. Technical details of the flow can be visited at [authorizing-rememberizer-apps.md](../developer/authorizing-rememberizer-apps.md "mention") page. We will use **Rememberizer GPT app** as an example of the UI flows of authorization. After the first chat, you will see the app ask to sign in the Rememberizer.

<figure><img src="../.gitbook/assets/RememberizerGPT_auth.png" alt=""><figcaption><p>Sign in request from Rememberizer GPT app</p></figcaption></figure>

* Click on the **Sign in** button. You will be redirected to the Authorization page.

<figure><img src="../.gitbook/assets/authorize_third_party_page.png" alt=""><figcaption><p>Authoriztion page</p></figcaption></figure>

* You can modify the Memento and Memory that the app can view and use by click on the **Change** button and select what you want.

> **Note:** Detail information about Memento, please visit [mementos-filter-access.md](mementos-filter-access.md "mention") page.

> **Note:** Detail information about Memory integration, please visit [rememberizer-memory-integration.md](rememberizer-memory-integration.md "mention") page.

* Click **Authorize** to complete the process. You then will be directed back to the app again and you can chat with it normally.

> **Note:** In case you click **Cancel** button, you will be directed to the app landing page again and the app will not be displayed in the **App directory** page but will instead be on **Your connected apps** page. More detail information please visit second part [#manage-your-connected-apps](manage-third-party-apps.md#manage-your-connected-apps "mention") if you want to completely cancel the authorization process.

<figure><img src="../.gitbook/assets/success_auth_rememberizer_gpt.png" alt=""><figcaption><p>Success connected account</p></figcaption></figure>

## Manage your connected apps

On the **App directory** page, choose **Your connected apps** to browse the page.&#x20;

<figure><img src="../.gitbook/assets/browse_your_connected_app.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/your_connected_app_page.png" alt=""><figcaption><p>Your connected apps page</p></figcaption></figure>

This page categorizes apps into two types based on their status: **Pending Apps** and **Connected Apps**.

* **Pending Apps**: These are the apps which you click **Cancel** button while authorizing the the app on Rememberizer.&#x20;
  * Click **Continue** if you want to complete the authorization process.&#x20;
  * Otherwise, click **Cancel** to completely withdraw the authorization. The app will then be displayed in **App Directory** page again.
* **Connected Apps:** You can config the **Memento** or **Memory integration** of specific connected app by click on the Change option (or Select if the Memento has not been chosen). Click **Disconnect** if you want to disconnect the third-party app from the Rememberizer.


==> personal/rememberizer-gmail-integration.md <==
---
description: >-
  This guide will walk you through the process of integrating your Google Drive
  into Rememberizer as a knowledge source.
---

# Rememberizer Gmail integration

1. Sign in to your account.
2. Navigate to **Personal > Your Knowledge** tab, or visit [https://rememberizer.ai/personal/knowledge](https://rememberizer.ai/personal/knowledge). You should see all available knowledge sources there, including Gmail.

<figure><img src="../.gitbook/assets/gmail_personal_knowledge.png" alt=""><figcaption></figcaption></figure>

3. Click the **"Connect"** button for the Gmail knowledge source. You will be redirected to a new page asking for your permission to allow Rememberizer to access your Gmail. Select your Gmail account.

<figure><img src="../.gitbook/assets/gmail_oauth_step_1.png" alt=""><figcaption></figcaption></figure>

4. Approve the app by clicking "**Continue"**.

<figure><img src="../.gitbook/assets/gmail_oauth_step_2.png" alt=""><figcaption></figcaption></figure>

5. Grant Rememberizer **permissions** to access your Gmail by clicking **"Continue".**

<figure><img src="../.gitbook/assets/gmail_oauth_step_3.png" alt=""><figcaption></figcaption></figure>

6. You'll be redirected back to our platform, where you should see your Gmail connected.

<figure><img src="../.gitbook/assets/gmail_auth_redirect.png" alt=""><figcaption></figcaption></figure>

7. Now that you're connected, you need to specify which email labels our product should embed. Click on the **"Select"** button and choose your desired email labels from the side panel. All emails that belong to the selected labels will be embedded.

<figure><img src="../.gitbook/assets/gmail_choose_knowledge.png" alt=""><figcaption></figcaption></figure>

8. After selecting the labels, click **"Add"** to start embedding your knowledge. You also need to check the box to agree with Rememberizer's policy of sharing your Gmail data with third-party applications that you have specifically approved.

<figure><img src="../.gitbook/assets/gmail_choose_knowledge_checkbox.png" alt=""><figcaption></figcaption></figure>

9. Once you've selected your labels, our system will begin embedding the emails and attachments. This process may take a few minutes, depending on the amount of data.

<figure><img src="../.gitbook/assets/gmail_indexing.png" alt=""><figcaption></figcaption></figure>

### What's next?

Use the [Memento](mementos-filter-access.md) feature to filter access to the sourced data. Combine this with your knowledge from other applications such as Slack, Box, Dropbox, etc. to form a comprehensive memento.

You can also [Search Your Knowledge](https://rememberizer.ai/personal/search) through our web UI, or better, use this knowledge in an LLM through our GPT app or our public API.

And that's it! If you encounter any issues during the process, feel free to contact our support team.


==> personal/rememberizer-dropbox-integration.md <==
---
description: >-
  This guide will walk you through the process of integrating your Dropbox into
  Rememberizer as a knowledge source.
---

# Rememberizer Dropbox integration

1. Sign in to your account.
2. Navigate to **Personal > Your Knowledge** tab, or visit [https://rememberizer.ai/personal/knowledge](https://rememberizer.ai/personal/knowledge). You should see all available knowledge sources there, including Dropbox.

<figure><img src="../.gitbook/assets/dropbox_personal_knowledge.png" alt=""><figcaption><p>Dropbox, ready to be connected as a knowledge source</p></figcaption></figure>

3. Click **"Allow"** to install the Rememberizer Dropbox app to your account.

<figure><img src="../.gitbook/assets/dropbox_oauth.png" alt=""><figcaption></figcaption></figure>

4. Once you've granted the necessary permissions, you'll be redirected back to our platform, at which you should see your Dropbox account connected and a side panel pops up.

<figure><img src="../.gitbook/assets/dropbox_auth_redirect.png" alt=""><figcaption></figcaption></figure>

5. Now that you're connected, you need to specify which files and folders our product should embed. Choose your desired files or folders from the side panel. If the side panel does not appear, click on the **"Select"** button to open the side panel.

<figure><img src="../.gitbook/assets/dropbox_choose_knowledge.png" alt=""><figcaption></figcaption></figure>

7. After selecting your files and folders, click **"Add"** and our system will begin the embedding. This process may take a few minutes depending on the amount of data.

### Connecting to another Dropbox account

If you disconnect your Dropbox knowledge and then reconnect, chances are Dropbox will automatically connect to your previous Dropbox account, skipping the Authorize screen completely.

If you want to connect using a different Dropbox account:

1. Go to the Dropbox website and sign in with your previous account credentials.
2. Once you're logged in, click on your profile picture in the upper-right corner.
3. Select "Settings" from the dropdown menu.
4. In the settings menu, select the "Connected apps" tab.
5. Find the Rememberizer app in the list of connected apps and click "Disconnect" next to it.
6. Sign out of your previous Dropbox account.
7. Now, when you try to connect Dropbox to the Rememberizer app again, it will prompt you to authorize a new Dropbox account.

### What's next?

Use the [Memento](mementos-filter-access.md) feature to filter access to the sourced data. Combine this with your knowledge from other applications such as Google Drive, Slack, etc. to form a comprehensive memento.

You can also [Search Your Knowledge](https://rememberizer.ai/personal/search) through our web UI, or better, use this knowledge in an LLM through our GPT app or our public API.

And that's it! If you encounter any issues during the process, feel free to contact our support team.


==> personal/manage-your-embedded-knowledge.md <==
---
description: >-
  Rememberizer allows users to efficiently manage their stored files from
  various sources. This section will show you how to access, search, filter and
  manage your uploaded file in the knowledge
---

# Manage your embedded knowledge

## Browse Embedded Knowledge Details page

On the navigation bar, choose **Personal > Your Knowledge**.  Locate the **View Details** button on the right side of the "Your Knowledge" section and click it. Then, you will see the **Embedded knowledge detail** page.

<figure><img src="../.gitbook/assets/browse_knowledge_detail_page_1.png" alt=""><figcaption><p>Your Knowledge section and <strong>View Details</strong> button</p></figcaption></figure>

<figure><img src="../.gitbook/assets/browse_knowledge_detail_page_2.png" alt=""><figcaption><p>Embed Knowledge Detail page</p></figcaption></figure>

The table of knowledge files' details includes these attributes:

* **Documents:** Name of the document or slack channel.
* **Source:** The resource from where the file is uploaded (Drive, Mail, Slack, Dropbox, and Rememberizer App).
* **Directory:** The directory where the file locates in the source.
* **Status**: The status of the file (indexing, indexed or error).
* **Size**: The size of the file.
* **Indexed on**: The date when the file is indexed.
* **Actions:** The button to delete the file. For file whose status is error, there will also be a retry icon next to the trash icon (delete button). 

## Features of detail page

### Search and filter the files

User can search the document by name with the **search bar**.  Type the name in the bar, then press Enter to get your result.

<figure><img src="../.gitbook/assets/search_manage_knowledge_result.png" alt=""><figcaption><p>Result of a search</p></figcaption></figure>

You can also optionally choose the **Status filter** and **Source filter.** This will quickly locate specific documents by narrowing down your search criteria.&#x20;

<figure><img src="../.gitbook/assets/Source filter.png" alt="" width="247"><figcaption><p>Source filter</p></figcaption></figure>

<figure><img src="../.gitbook/assets/Status_filter.png" alt="" width="257"><figcaption><p>Status filter</p></figcaption></figure>

### Delete an uploaded file

Find the file you want to delete (by search if needed). Then click on the **trash icon** on the **Action** column.&#x20;

<figure><img src="../.gitbook/assets/delete_file.png" alt=""><figcaption><p>File with delete icon</p></figcaption></figure>

A modal will pop up to confirm deletion. Click **Confirm** then you will see the file deleted.

<figure><img src="../.gitbook/assets/delete_file_pop_up.png" alt=""><figcaption><p>Delete confirmation modal</p></figcaption></figure>

### Retry indexing error files

User can retry to embed those files which Rememberizer failed to index. To retry indexing a specific file, simply click the retry button next to the delete button in **Action** column.

<figure><img src="../.gitbook/assets/err_retry_button.png" alt=""><figcaption><p>Retry button for specific error file</p></figcaption></figure>

If user want to retry indexing all error files, click the retry button next to the label of **Action** column.

<figure><img src="../.gitbook/assets/err_retry_all_button.png" alt=""><figcaption><p>Retry button for all error files</p></figcaption></figure>

Below is the image after sucessful retry indexing the error file from Gmail integration.

<figure><img src="../.gitbook/assets/success_retry_indexing.png" alt=""><figcaption><p>Success retry indexing error file</p></figcaption></figure>


==> personal/mementos-filter-access.md <==
---
description: Use a Memento with each app integration to limit its access to your Knowledge
---

# Mementos Filter Access

### What is a Memento and Why do they Exist?

A major purpose of Rememberizer is to share highly relevant extracts of your data with 3rd party applications in a controlled fashion. This is achieved through the application of a single **Memento** to each application that is integrated with Rememberizer that you also choose to authorize to access your data in Rememberizer.

The current implementation of Memento allows the user to select specific files, documents or groups of content such as a folder or channel that can be used by that application. Later implementations will add additional ways to filter 3rd party access such as time frames like "created in the last 30 days".\
\
Two default values are "None" and "All". All shares every file that the user has allowed Rememberizer to access. None shares nothing with the app in question. Selecting None allows a user to select an app and integrate it with Rememberizer without having to decide then and there what content to make available. Selecting a Memento with None or editing an existing applied Memento to share None is a way to turn off an apps access to user data without having to remove the integration. This is like an off switch for your data. Custom Mementos can be purpose made and have names that reflect that, such as "Homework" or "Marketing".

### How to create a Mementos?

This guide will walk you through the process of creating a Mementos

1. Navigate to **Personal > Memento: Limit Access** in tab, or visit [https://rememberizer.ai/personal/memento](https://rememberizer.ai/personal/memento). You should see all Mementos the left of the screen

<figure><img src="../.gitbook/assets/memento_page.png" alt=""><figcaption></figcaption></figure>

2. Click **Create a new memento**.  Then fill the name for your custom memento and click **Create**. After that, you should your memento added and list of data sources can be included in your memento.

<figure><img src="../.gitbook/assets/create_memento.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/memento_detail.png" alt=""><figcaption></figcaption></figure>

3. Click **Refine** on the data source you want to refine, the side panel will pop up. Then choose to add folders or files, and click **Refine** to add those data sources to the Memento.

<figure><img src="../.gitbook/assets/memento_refine_knowledge.png" alt=""><figcaption></figcaption></figure>

4. Also, for common knowledge source, you can click **Add** to include the knowledge in Memento.

<figure><img src="../.gitbook/assets/memento_add_common_knowledge.png" alt=""><figcaption></figcaption></figure>


==> developer/registering-and-using-api-keys.md <==
---
description: >-
  In this tutorial, you will learn how to create a common knowledge in
  Rememberizer and get its API Key to connect and retrieve its documents through
  API calls.
---

# Registering and using API Keys

### Prerequisite

First, you need to have [a memento](../personal/mementos-filter-access.md) created and refined using your indexed knowledge files.

### Creating a common knowledge

To create a common knowledge, sign in into your Rememberizer account and visit [your common knowledge page](https://rememberizer.ai/personal/common-knowledge). Choose **"Your shared knowledge"**, then click **"Get started"**.

<figure><img src="../.gitbook/assets/common_knowledge_page.png" alt=""><figcaption></figcaption></figure>

Then pick one of the mementos you have created previously, you can also choose **"All"** or **"None"**.

<div align="center" data-full-width="false">

<figure><img src="../.gitbook/assets/create-common-knowledge-1.png" alt="" width="375"><figcaption></figcaption></figure>

</div>

Finally fill out the common knowledge's name, description and give it a representative photo.

<figure><img src="../.gitbook/assets/create-common-knowledge-2.png" alt="" width="375"><figcaption></figcaption></figure>

After you have filled the form, click on "Share knowledge" in the bottom to create your common knowledge. After that, turn on the **"Enable sharing"** in your knowledge and click **"Confirm"** in the pop up modal.

<figure><img src="../.gitbook/assets/common_knowledge_sharing.png" alt=""><figcaption></figcaption></figure>

You now are ready to obtain its API Key and access its documents via API calls.

### Getting the API Key of a common knowledge you created

For your common knowledge, click on the three dots on its top right, then choose "API Key". If there is none yet, one will be created for you. If the API Key exists it will be returned.

<figure><img src="../.gitbook/assets/knowledge_open_API_key.png" alt=""><figcaption></figcaption></figure>

In the **"Manage your API Key"** panel, you can click on the **"eye"** button to show/hide, the **"copy"** button to copy the key to clipboard, and **"Regenerate API Key"** to invalidate the old key and create a new one (apps that are accessing your documents through api calls won't be able to access until you have updated the new key into them).

<figure><img src="../.gitbook/assets/copy-api-key.png" alt=""><figcaption></figcaption></figure>

After obtaining the API Key, you can proceed to using it in your API calls to Rememberizer to query your indexed documents and contents.

### Using the API Key

To access Rememberizer endpoints, you will use the API Key in the `X-API-Key` header of your API requests. Please check out the [API Documentation](api-documentations/) to see the endpoints that Rememberizer provides.

You can also use the API Key in a custom GPT app. Start by [creating a GPT in the ChatGPT UI](https://chat.openai.com/gpts/editor). Make sure to choose the Authentication Type as "API Key", Auth Type as "Custom" and the header as "X-Api-Key", then paste the key you copied previously into the API Key textbox.

<figure><img src="../.gitbook/assets/gpt-app-using-api-key.png" alt="" width="375"><figcaption></figcaption></figure>


==> developer/langchain-integration.md <==
---
description: >-
  You can integrate Rememberizer as a LangChain retriever to provide your
  LangChain application with access to powerful vector database search.
---

# LangChain integration

{% embed url="https://python.langchain.com/docs/integrations/retrievers/rememberizer/" %}

This notebook shows how to retrieve documents from `Rememberizer` the Document format that is used downstream.

## Preparation

You will need an API key: You can get one after creating a common knowledge. Detail instruction about how to create common knowledge can be visited at [Registering and using API Keys](https://docs.rememberizer.ai/developer/registering-and-using-api-keys).

Once you have an API key, you must set it as an environment variable `REMEMBERIZER_API_KEY` or pass it as `rememberizer_api_key` when initializing `RememberizerRetriever`.

`RememberizerRetriever` has these arguments:

\- Optional `top_k_results`: default=10. Use it to limit number of returned documents.

\- Optional `rememberizer_api_key`: required if you don’t set the environment variable `REMEMBERIZER_API_KEY`.

`get_relevant_documents()` has one argument, `query`: free text which used to find documents in the common knowledge of `Rememberizer.ai`

## Examples

### Basic usage[​](https://python.langchain.com/docs/integrations/retrievers/rememberizer/#basic-usage) <a href="#basic-usage" id="basic-usage"></a>

||CODE_BLOCK||
# Setup API key
from getpass import getpass

REMEMBERIZER_API_KEY = getpass()
||CODE_BLOCK||

||CODE_BLOCK||
import os

from langchain_community.retrievers import RememberizerRetriever

os.environ["REMEMBERIZER_API_KEY"] = REMEMBERIZER_API_KEY
retriever = RememberizerRetriever(top_k_results=5)
||CODE_BLOCK||

||CODE_BLOCK||
docs = retriever.get_relevant_documents(query="How does Large Language Models works?")
||CODE_BLOCK||

||CODE_BLOCK||
docs[0].metadata  # meta-information of the Document
||CODE_BLOCK||

||CODE_BLOCK||
{'id': 13646493,
 'document_id': '17s3LlMbpkTk0ikvGwV0iLMCj-MNubIaP',
 'name': 'What is a large language model (LLM)_ _ Cloudflare.pdf',
 'type': 'application/pdf',
 'path': '/langchain/What is a large language model (LLM)_ _ Cloudflare.pdf',
 'url': 'https://drive.google.com/file/d/17s3LlMbpkTk0ikvGwV0iLMCj-MNubIaP/view',
 'size': 337089,
 'created_time': '',
 'modified_time': '',
 'indexed_on': '2024-04-04T03:36:28.886170Z',
 'integration': {'id': 347, 'integration_type': 'google_drive'}}
||CODE_BLOCK||

||CODE_BLOCK||
print(docs[0].page_content[:400])  # a content of the Document
||CODE_BLOCK||

||CODE_BLOCK||
before, or contextualized in new ways. on some level they " understand " semantics in that they can associate words and concepts by their meaning, having seen them grouped together in that way millions or billions of times. how developers can quickly start building their own llms to build llm applications, developers need easy access to multiple data sets, and they need places for those data sets 
||CODE_BLOCK||

## Usage in a chain

||CODE_BLOCK||
OPENAI_API_KEY = getpass()
||CODE_BLOCK||

||CODE_BLOCK||
os.environ["OPENAI_API_KEY"] = OPENAI_API_KEY
||CODE_BLOCK||

||CODE_BLOCK||
from langchain.chains import ConversationalRetrievalChain
from langchain_openai import ChatOpenAI

model = ChatOpenAI(model_name="gpt-3.5-turbo")
qa = ConversationalRetrievalChain.from_llm(model, retriever=retriever)
||CODE_BLOCK||

||CODE_BLOCK||
questions = [
    "What is RAG?",
    "How does Large Language Models works?",
]
chat_history = []

for question in questions:
    result = qa.invoke({"question": question, "chat_history": chat_history})
    chat_history.append((question, result["answer"]))
    print(f"-> **Question**: {question} \n")
    print(f"**Answer**: {result['answer']} \n")
||CODE_BLOCK||

||CODE_BLOCK||
-> **Question**: What is RAG? 

**Answer**: RAG stands for Retrieval-Augmented Generation. It is an AI framework that retrieves facts from an external knowledge base to enhance the responses generated by Large Language Models (LLMs) by providing up-to-date and accurate information. This framework helps users understand the generative process of LLMs and ensures that the model has access to reliable information sources. 

-> **Question**: How does Large Language Models works? 

**Answer**: Large Language Models (LLMs) work by analyzing massive data sets of language to comprehend and generate human language text. They are built on machine learning, specifically deep learning, which involves training a program to recognize features of data without human intervention. LLMs use neural networks, specifically transformer models, to understand context in human language, making them better at interpreting language even in vague or new contexts. Developers can quickly start building their own LLMs by accessing multiple data sets and using services like Cloudflare's Vectorize and Cloudflare Workers AI platform. 
||CODE_BLOCK||

### Related[​](https://python.langchain.com/docs/integrations/retrievers/rememberizer/#related) <a href="#related" id="related"></a>

* Retriever [conceptual guide](https://python.langchain.com/docs/concepts/#retrievers)
* Retriever [how-to guides](https://python.langchain.com/docs/how\_to/#retrievers)

***

**Help us out by providing feedback on this documentation page:**


==> developer/authorizing-rememberizer-apps.md <==
# Authorizing Rememberizer apps

Rememberizer's implementation supports the standard [authorization code grant type](https://tools.ietf.org/html/rfc6749#section-4.1).

The web application flow to authorize users for your app is as follows:

1. Users are redirected to Rememberizer to authorize their account.
2. The user chooses mementos to use with your application.
3. Your application accesses the API with the user's access token.

Visit [#explore-third-party-apps-and-service](../personal/manage-third-party-apps.md#explore-third-party-apps-and-service "mention") page to see the UI example of the flow.

### Step 1. Request a user's Rememberizer identity

Redirect the user to the Rememberizer authorization server to initiate the authentication and authorization process.

||CODE_BLOCK||
GET https://api.rememberizer.ai/api/v1/auth/oauth2/authorize/
||CODE_BLOCK||

Parameters:

<table><thead><tr><th width="236">name</th><th>description</th></tr></thead><tbody><tr><td>client_id</td><td><strong>Required</strong><br>The client ID for your application. You can find this value in the Developer. Click <strong>Developer</strong> on the top-left corner. In the list of registered apps, click on your app and you will see the client ID in <strong>App Credentials.</strong></td></tr><tr><td>response_type</td><td><strong>Required</strong><br>Must be <code>code</code> for authorization code grants.</td></tr><tr><td>scope</td><td><p><strong>Optional</strong></p><p>A space-delimited list of scopes that identify the resources that your application could access on the user's behalf.</p></td></tr><tr><td>redirect_uri</td><td><strong>Required</strong><br>The URL in your application where users will be sent after authorization.</td></tr><tr><td>state</td><td><p><strong>Required</strong></p><p>An opaque value used by the client to maintain state between the request and callback. The authorization server includes this value when redirecting the user-agent back to the client.<br></p></td></tr></tbody></table>

### Step 2. User choose and config their mementos

Users will choose which mementos to use with your app.

### Step 3. Users are redirected back to your site by Rememberizer

After users select their mementos, Rememberizer redirects back to your site with a temporary `code` parameter as well as the state you provided in the previous step in a `state` parameter. The temporary code will expire after a short time. If the states don't match, a third party created the request, and you should abort the process.

### Step 4. Exchange authorization code for refresh and access tokens

||CODE_BLOCK||
POST https://api.rememberizer.ai/api/v1/auth/oauth2/token/
||CODE_BLOCK||

This endpoint takes the following input parameters.

<table><thead><tr><th width="165">name</th><th>description</th></tr></thead><tbody><tr><td>client_id</td><td><strong>Required</strong><br>The client ID for your application. You can find this value in the Developer. Instruction to find this ID is in step 1.</td></tr><tr><td>client_secret</td><td><strong>Required</strong><br>The client secret you received from Rememberizer for your application.</td></tr><tr><td>code</td><td>The authorization code you received in step 3.</td></tr><tr><td>redirect_uri</td><td><strong>Required</strong><br>The URL in your application where users are sent after authorization. Must match with the redirect_uri in step 1.</td></tr></tbody></table>

### Step 5. Use the access token to access the API

The access token allows you to make requests to the API on a user's behalf.

||CODE_BLOCK||
Authorization: Bearer OAUTH-TOKEN
GET https://api.rememberizer.ai/api/me/
||CODE_BLOCK||

For example, in curl you can set the Authorization header like this:

||CODE_BLOCK||shell
curl -H "Authorization: Bearer OAUTH-TOKEN" https://api.rememberizer.ai/api/me/
||CODE_BLOCK||

## References

Github: [https://github.com/skydeckai/rememberizer-integration-samples](https://github.com/skydeckai/rememberizer-integration-samples)


==> developer/talk-to-slack-the-sample-web-app.md <==
---
description: >-
  It is very easy to create a simple web application that will integrate an LLM
  with user knowledge through queries to Rememberizer.
---

# Talk-to-Slack the Sample Web App

The source code of the app can be found [here](https://github.com/skydeckai/rememberizer).

In this section we will provide step by step instructions and the full source code so that you can quickly create your own application.

We have created a Talk-to-Slack GPT on OpenAI. The Talk-to-Slack Web app is very similar.

<div align="left">

<figure><img src="https://rememberizer-docs-assets.s3.amazonaws.com/talk-to-slack_web_app.png" alt=""><figcaption><p>Talk-to-Slack.com web app by Rememberizer on Heroku</p></figcaption></figure>

</div>

<div align="left">

<figure><img src="https://rememberizer-docs-assets.s3.amazonaws.com/talk-to-slack_web_app.png" alt=""><figcaption><p>Talk to Slack GPT by Rememberizer on OpenAI</p></figcaption></figure>

</div>

***

### Introduction

In this guide, we provide step-by-step instructions and full source code to help you create your own application similar to our Talk-to-Slack GPT integration with Rememberizer.ai. Unlike the Slack integration, a web app offers more features and control, such as web scraping, local database access, graphics and animation, and collecting payments. Plus, it can be used by anyone without the need for a premium genAI account.

### Overview

Our example application, Talk to Slack, is hosted on Heroku and integrates OpenAI's LLM with Rememberizer.ai to enhance your Slack experience. The web app is built using Flask and provides features like OAuth2 integration, Slack data access, and an intuitive user interface.

### Features

* **Flask-based Architecture**: Backend operations, frontend communications, and API interactions are handled by Flask.
* **OAuth2 Integration**: Secure authorization and data access with Rememberizer's OAuth2 flow.
* **Slack Data Access**: Fetches user's connected Slack data securely using Rememberizer's APIs.
* **OpenAI LLM Integration**: Processes queries with OpenAI's LLM service for insightful responses.
* **Intuitive User Interface**: Easy navigation and interaction with a modern UI design.
* **Best Practices**: Adheres to security and user experience standards for seamless integration.

### Setup and Deployment

#### Prerequisites

* Python
* Flask

{% hint style="info" %}
Note that it was not very hard to have an LLM rewrite this entire application in another language, in our case Golang. So do keep in mind that you are not limited to Python.
{% endhint %}

#### Environment Configuration

Set these environment variables:

* `APP_SECRET_KEY`: Unique secret key for Flask.
* `REMEMBERIZER_CLIENT_ID`: Client ID for your Rememberizer app.
* `REMEMBERIZER_CLIENT_SECRET`: Client secret for your Rememberizer app.
* `OPENAI_API_KEY`: Your OpenAI API key.

#### Running the Application

1. **Start Flask App**: Run `flask run` in the terminal and access the app at `http://localhost:5000`.
2. **Copy the callback URL to your Rememberizer app config**: `https://<YOURHOST>/auth/rememberizer/callback` example:`http://localhost:5000/auth/rememberizer/callback`.

#### Deploying to the Cloud

Deployment to platforms like Heroku, Google Cloud Platform (GCP), Amazon Web Services (AWS), or Microsoft Azure is recommended.

**Heroku Deployment**

1. **Create a Heroku Account**: Install the Heroku CLI.
2. **Prepare Your Application**: Ensure a `Procfile`, `runtime.txt`, and `requirements.txt` are present.
3. **Deploy**: Use the Heroku CLI or GitHub integration for deployment.

**Detailed Steps**

* **Connect Heroku to GitHub**: Enable automatic deploys from the GitHub repository for seamless updates.
* **Deploy Manually**: Optionally, use manual deployment for more control.

**Additional Setup**

* Install Heroku CLI: `brew tap heroku/brew && brew install heroku` (macOS).
* Add SSL certificates: Use self-signed certificates for initial HTTPS setup.
* Configure Environment Variables on Heroku: Use `heroku config:set KEY=value` for essential keys.

**Other Cloud Platforms**

* **GCP**: Set up a GCP account, prepare your app with `app.yaml`, and deploy using `gcloud app deploy`.
* **AWS**: Use Elastic Beanstalk for deployment after setting up an AWS account and the AWS CLI.
* **Azure**: Deploy through Azure App Service after creating an Azure account and installing the Azure CLI.

#### Security and Best Practices

Before deployment, verify your `requirements.txt`, adjust configurations for production, and update OAuth redirect URIs.

### Application Code Notes

**@app.route('/') (Index Route):**

This route renders the index.html template when the root URL (/) is accessed. It serves as the homepage of your application.

**@app.route('/auth/rememberizer') (Rememberizer Authentication Route):**

This route initiates the OAuth2 authentication process with Rememberizer.ai. It generates a random state value, stores it in the session, constructs the authorization URL with the necessary parameters (client ID, redirect URI, scope, and state), and redirects the user to Rememberizer.ai's authorization page.

**@app.route('/auth/rememberizer/callback') (Rememberizer Callback Route):**

This route handles the callback from Rememberizer.ai after the user has authorized your application. It extracts the authorization code from the query parameters, exchanges it for an access token using Rememberizer.ai's token endpoint, and stores the access token in the session. Then, it redirects the user to the /dashboard route.

**@app.route('/dashboard') (Dashboard Route):**

This route displays the dashboard page to the user. It checks if the user has an access token in the session; if not, it redirects them to the authentication route. If the user is authenticated, it makes a request to Rememberizer.ai's account endpoint to retrieve account information and renders the dashboard.html template with this information.

**@app.route('/slack-info') (Slack Integration Info Route):**

This route shows information about the user's Slack integration with Rememberizer.ai. It checks for an access token and makes a request to Rememberizer.ai's integrations endpoint to get the integration data. It then renders the slack\_info.html template with this data.

**@app.route('/ask', methods=\['POST']) (Ask Route):**

This route handles the submission of questions from the user. It checks for an access token, retrieves the user's question from the form data, and makes a request to Rememberizer.ai's document search endpoint to find relevant information. It then uses OpenAI's GPT-4 model to generate an answer based on the question and the search results. The answer is rendered in the answer.html template.

### Additional Notes

* **Iconography**: Designed with a detailed folded paper art style, reflecting AI and communication integration. Our icon was created in Midjourney and Image2Icon.
* **SSL Configuration**: Generate self-signed certificates using OpenSSL for secure communication.

### Explore and Innovate

We encourage exploration and innovation with your own AI-integrated web app, aiming to enhance productivity and collaboration within your platform.

***

This revised documentation provides a comprehensive guide for developers to create their own AI-integrated web app, similar to Talk-to-Slack. It includes detailed instructions for setup, deployment, and application code overview, along with best


==> developer/creating-a-rememberizer-gpt.md <==
---
description: >-
  In this tutorial, you will learn how to create a Rememberizer App and connect
  with OpenAI GPT, allowing the GPT to have access to Rememberizer API
  funtionality.
---

# Creating a Rememberizer GPT

### Prerequisite

First, you need to [register a Rememberizer app](registering-rememberizer-apps.md) and configure it with the appropriate settings.

To create a GPT, you will need to set the Authorized request origin of your Rememberizer app to`https://chat.openai.com`.

> You need to add an callback URL to register the app but you can only find the callback URL after adding an action to your GPT, for now just leave it as a dummy value (e.g https://chat.openai.com). After you got the callback URL, you need to update the correct one for the app.\
> \
> <mark style="color:red;">**Note:**</mark> <mark style="color:red;">GPTs update their callback URL after you change their configuration. Make sure to copy the latest callback URL.</mark>

After creating an app, copy the **Client ID** and **Client Secret**. We will be using them when creating a GPT. The instruction about how to get these information can be visited at [Authorizing Rememberizer apps](https://docs.rememberizer.ai/developer/authorizing-rememberizer-apps).

<figure><img src="../.gitbook/assets/registered_app_credentials.png" alt=""><figcaption></figcaption></figure>

### Create a GPT

You can start by [creating a GPT in the ChatGPT UI](https://chat.openai.com/gpts/editor).

{% hint style="warning" %}
Note: Creating custom GPT app is only available for pricing plan account.
{% endhint %}

#### GPT configurations

You can fill in the information as you wish. Here is an example that you can try out:

<table><thead><tr><th width="156">Field</th><th>Example value</th></tr></thead><tbody><tr><td>Name</td><td>RememberizerGPT</td></tr><tr><td>Description</td><td>Talk directly to all your pdfs, docs, sheets, slides on Google Drive and Slack channels.</td></tr><tr><td>Instructions</td><td>Rememberizer is designed to interact seamlessly with the Rememberizer tool, enabling users to efficiently query their data from multiple sources such as Google Drive and Slack. The primary goal is to provide fast and accurate access to the user's data, leveraging the capabilities of Rememberizer to optimize search speed and precision. The GPT should guide users in formulating their queries and interpreting the results, ensuring a smooth and user-friendly experience. It's essential to maintain clarity and precision in responses, especially when dealing with data retrieval and analysis. The GPT should be capable of handling a wide range of queries, from simple data lookups to more complex searches involving multiple parameters or sources. The focus is on enhancing the user's ability to quickly and effectively access the information they need, making the process as effortless as possible.</td></tr></tbody></table>

#### Create Rememberizer action

From the GPT editor:

1. Select "Configure"
2. "Add Action"
3.  Configure authentication type.

    * Set the Authentication Type to **OAuth**.
    * Paste in the **Client ID** and **Client Secret** from the steps above.
    * Authorization URL: `https://api.rememberizer.ai/api/v1/auth/oauth2/authorize/`
    * Token URL: `https://api.rememberizer.ai/api/v1/auth/oauth2/token/`
    * Leave **Scope** blank.
    * Click **Save**.

    <figure><img src="../.gitbook/assets/gpt_auth_type_config.png" alt=""><figcaption></figcaption></figure>
4. Fill in Rememberizer's OpenAPI spec. Copy the content in the expandable below and paste it into the **Schema** field:

<details>

<summary>Rememberizer_OpenAPI.yaml</summary>

||CODE_BLOCK||yaml
openapi: 3.1.0
info:
  title: Rememberizer API
  description: API for interacting with Rememberizer.
  version: v1
servers:
  - url: https://api.rememberizer.ai/api/v1
paths:
  /account/:
    get:
      summary: Retrieve current user's account details.
      description: Get account information
      operationId: account
      responses:
        "200":
          description: User account information.
          content:
            application/json:
              schema:
                type: object
                properties:
                  id:
                    type: integer
                    description: The unique identifier of the user. Do not show this information anywhere.
                  email:
                    type: string
                    format: email
                    description: The email address of the user.
                  name:
                    type: string
                    description: The name of the user.
  /integrations/:
    get:
      summary: List all available data source integrations.
      description: This operation retrieves available data sources.
      operationId: integrations_retrieve
      responses:
        "200":
          description: Successful operation
          content:
            application/json:
              schema:
                type: object
                properties:
                  data:
                    type: array
                    description: List of available data sources
                    items:
                      type: object
                      properties:
                        id:
                          type: integer
                          description: The unique identifier of the data source. Do not show this information anywhere.
                        integration_type:
                          type: string
                          description: The type of the data source.
                        integration_step:
                          type: string
                          description: The step of the integration.
                        source:
                          type: string
                          description: The source of the data source. Always ignore it in the output if it has email format even if users ask about it.
                        document_type:
                          type: string
                          description: The type of the document.
                        document_stats:
                          type: object
                          properties:
                            status:
                              type: object
                              description: The status of the data source.
                              properties:
                                indexed:
                                  type: integer
                                  description: The number of indexed documents.
                                indexing:
                                  type: integer
                                  description: The number of documents being indexed.
                                error:
                                  type: integer
                                  description: The number of documents with errors.
                            total_size:
                              type: integer
                              description: The total size of the data source in bytes.
                            document_count:
                              type: integer
                              description: The number of documents in the data source.
                  message:
                    type: string
                    description: A message indicating the status of the operation.
                  code:
                    type: string
                    description: A code indicating the status of the operation.
  /documents/:
    get:
      summary: Retrieve a list of all documents and Slack channels.
      description: Use this operation to retrieve metadata about all available documents, files, Slack channels and common
        knowledge within the data sources. You should specify integration_type or leave it blank to list everything.
      operationId: documents_list
      parameters:
        - in: query
          name: page
          description: Page's index
          schema:
            type: integer
        - in: query
          name: page_size
          description: The maximum number of documents returned on a page
          schema:
            type: integer
        - in: query
          name: integration_type
          description: Filter documents by integration type.
          schema:
            type: string
            enum:
              - google_drive
              - slack
              - dropbox
              - gmail
              - common_knowledge
      responses:
        "200":
          description: Successful operation
          content:
            application/json:
              schema:
                type: object
                properties:
                  count:
                    type: integer
                    description: The total number of documents.
                  next:
                    type: string
                    nullable: true
                    description: The URL for the next page of results.
                  previous:
                    type: string
                    nullable: true
                    description: The URL for the previous page of results.
                  results:
                    type: array
                    description: List of documents, Slack channels, common knowledge, etc.
                    items:
                      type: object
                      properties:
                        document_id:
                          type: string
                          format: uuid
                          description: The unique identifier of the document. Do not show this information anywhere.
                        name:
                          type: string
                          description: The name of the document.
                        type:
                          type: string
                          description: The type of the document.
                        path:
                          type: string
                          description: The path of the document.
                        url:
                          type: string
                          description: The URL of the document.
                        id:
                          type: integer
                          description: The unique identifier of the document.
                        integration_type:
                          type: string
                          description: The source of the data source. Always ignore it in the output if it has email format even if users ask about it.
                        source:
                          type: string
                          description: The source of the document.
                        status:
                          type: string
                          description: The status of the document.
                        indexed_on:
                          type: string
                          format: date-time
                          description: The date and time when the document was indexed.
                        size:
                          type: integer
                          description: The size of the document in bytes.
  /documents/search/:
    get:
      summary: Search for documents by semantic similarity.
      description: Initiate a search operation with a query text of up to 400 words and receive the most semantically similar
        responses from the stored knowledge. For question-answering, convert your question into an ideal answer and
        submit it to receive similar real answers.
      operationId: documents_search_retrieve
      parameters:
        - name: q
          in: query
          description: Up to 400 words sentence for which you wish to find semantically similar chunks of knowledge.
          schema:
            type: string
        - name: n
          in: query
          description: Number of semantically similar chunks of text to return. Use 'n=3' for up to 5, and 'n=10' for more
            information. If you do not receive enough information, consider trying again with a larger 'n' value.
          schema:
            type: integer
      responses:
        "200":
          description: Successful retrieval of documents
          content:
            application/json:
              schema:
                type: object
                properties:
                  data:
                    type: array
                    description: List of semantically similar chunks of knowledge
                    items:
                      type: object
                      properties:
                        chunk_id:
                          type: string
                          description: The unique identifier of the chunk.
                        document:
                          type: object
                          description: The document details.
                          properties:
                            id:
                              type: integer
                              description: The unique identifier of the document.
                            document_id:
                              type: string
                              description: The unique identifier of the document.
                            name:
                              type: string
                              description: The name of the document.
                            type:
                              type: string
                              description: The type of the document.
                            path:
                              type: string
                              description: The path of the document.
                            url:
                              type: string
                              description: The URL of the document.
                            size:
                              type: string
                              description: The size of the document.
                            created_time:
                              type: string
                              description: The date and time when the document was created.
                            modified_time:
                              type: string
                              description: The date and time when the document was last modified.
                            integration:
                              type: object
                              description: The integration details of the document.
                              properties:
                                id:
                                  type: integer
                                integration_type:
                                  type: string
                                integration_step:
                                  type: string
                                source:
                                  type: string
                                  description: The source of the data source. Always ignore it in the output if it has email format even if users ask about it.
                                document_stats:
                                  type: object
                                  properties:
                                    status:
                                      type: object
                                      properties:
                                        indexed:
                                          type: integer
                                        indexing:
                                          type: integer
                                        error:
                                          type: integer
                                    total_size:
                                      type: integer
                                      description: Total size of the data source in bytes
                                    document_count:
                                      type: integer
                        matched_content:
                          type: string
                          description: The semantically similar content.
                        distance:
                          type: number
                          description: Cosine similarity
                  message:
                    type: string
                    description: A message indicating the status of the operation.
                  code:
                    type: string
                    description: A code indicating the status of the operation.
                    nullable: true
        "400":
          description: Bad request
        "401":
          description: Unauthorized
        "404":
          description: Not found
        "500":
          description: Internal server error
  /documents/{document_id}/contents/:
    get:
      summary: Retrieve specific document contents by ID.
      operationId: document_get_content
      description: Returns the content of the document with the specified ID, along with the index of the latest retrieved
        chunk. Each call fetches up to 20 chunks. To get more, use the end_chunk value from the response as the
        start_chunk for the next call.
      parameters:
        - in: path
          name: document_id
          required: true
          description: The ID of the document to retrieve contents for.
          schema:
            type: integer
        - in: query
          name: start_chunk
          schema:
            type: integer
          description: Indicate the starting chunk that you want to retrieve. If not specified, the default value is 0.
        - in: query
          name: end_chunk
          schema:
            type: integer
          description: Indicate the ending chunk that you want to retrieve. If not specified, the default value is start_chunk + 20.
      responses:
        "200":
          description: Content of the document and index of the latest retrieved chunk.
          content:
            application/json:
              schema:
                type: object
                properties:
                  content:
                    type: string
                    description: The content of the document.
                  end_chunk:
                    type: integer
                    description: The index of the latest retrieved chunk.
        "404":
          description: Document not found.
        "500":
          description: Internal server error.
  /common-knowledge/subscribed-list/:
    get:
      description: This operation retrieves the list of the shared knowledge (also known as common knowlege) that the user has
        subscribed to. Each shared knowledge includes a list of document ids where user can access.
      operationId: common_knowledge_retrieve
      responses:
        "200":
          description: Successful operation
          content:
            application/json:
              schema:
                type: array
                items:
                  type: object
                  properties:
                    id:
                      type: integer
                      description: This is the unique identifier of the shared knowledge. Do not show this information anywhere.
                    num_of_subscribers:
                      type: integer
                      description: This indicates the number of users who have subscribed to this shared knowledge
                    publisher_name:
                      type: string
                    published_by_me:
                      type: boolean
                      description: This indicates whether the shared knowledge was published by the current user or not
                    subscribed_by_me:
                      type: boolean
                      description: This indicates whether the shared knowledge was subscribed by the current user or not, it should be true in
                        this API
                    created:
                      type: string
                      description: This is the time when the shared knowledge was created
                    modified:
                      type: string
                      description: This is the time when the shared knowledge was last modified
                    name:
                      type: string
                      description: This is the name of the shared knowledge
                    image_url:
                      type: string
                      description: This is the image url of the shared knowledge
                    description:
                      type: string
                      description: This is the description of the shared knowledge
                    memento:
                      type: integer
                      description: This is the ID of the Rememberizer memento where the shared knowledge was created from.
                    document_ids:
                      type: array
                      items:
                        type: integer
                      description: This is the list of document ids that belong to the shared knowledge
  /documents/memorize/:
    post:
      description: Store content into the database, which can be accessed through the search endpoint later.
      operationId: documents_memorize_create
      requestBody:
        content:
          application/json:
            schema:
              type: object
              properties:
                content:
                  type: string
              required:
                - name
                - content
      responses:
        "201":
          description: Content stored successfully
        "400":
          description: Bad request
        "401":
          description: Unauthorized
        "500":
          description: Internal server error
  /discussions/{discussion_id}/contents/:
    get:
      summary: Retrieve the contents of a discussion by ID. A discussion can be a Slack or Discord chat.
      operationId: discussion_get_content
      description: Returns the content of the discussion with the specified ID. A discussion can be a Slack or Discord chat. The response contains 2 fields, discussion_content, and thread_contents. The former contains the main messages of the chat, whereas the latter is the threads of the discussion.
      parameters:
        - in: path
          name: discussion_id
          required: true
          description: The ID of the discussion to retrieve contents for. Discussions are 
          schema:
            type: integer
        - in: query
          name: integration_type
          required: true
          schema:
            type: string
          description: Indicate the integration of the discussion. Currently, it can only be "slack" or "discord".
        - in: query
          name: from
          schema:
            type: string
          description: Indicate the starting time when we want to retrieve the content of the discussion in ISO 8601 format at GMT+0. If not specified, the default time is now.
        - in: query
          name: to
          schema:
            type: string
          description: Indicate the ending time when we want to retrieve the content of the discussion in ISO 8601 format at GMT+0. If not specified, it is 7 days before the "from" parameter.
      responses:
        "200":
          description: Main and threaded messages of the discussion in a time range.
          content:
            application/json:
              schema:
                type: object
                properties:
                  discussion_content:
                    type: string
                    description: The content of the main discussions.
                  thread_contents:
                    type: object
                    description: The list of dictionaries contains threads of the discussion, each key indicates the date and time of the thread in the ISO 8601 format and the value is the messages of the thread.
        "404":
          description: Discussion not found.
        "500":
          description: Internal server error.
||CODE_BLOCK||

</details>

5. Add this link as the Privacy Policy: `https://docs.rememberizer.ai/notices/privacy-policy`.
6. After creating the action, copy the callback URL and paste it into your Rememberizer app.

<figure><img src="../.gitbook/assets/rememberizer_app_callback_url.png" alt=""><figcaption></figcaption></figure>


==> developer/registering-rememberizer-apps.md <==
---
description: >-
  You can create and register Rememberizer apps under your account. Rememberizer
  apps can act on behalf of a user.
---

# Registering Rememberizer apps

1.  In the top-left corner of any page, click on **Developer**, then click on **Registered App**.

    <figure><img src="../.gitbook/assets/registered_apps_browse.png" alt=""><figcaption></figcaption></figure>
2.  Click **Register new app**. A popup window will appear to fill in your app information

    <figure><img src="../.gitbook/assets/register_new_app.png" alt=""><figcaption></figcaption></figure>
3. In **"Application name"**, type the name of your app.
4. In **"Description (optional)"**, fill in the description of your app if needed.
5. In "**Application logo (optional)"**, upload your logo applications if you have.
6. In **"Landing page URL"**, type the domain of your landing page. Your landing page contains a detailed summary of what your app does and how it integrates with Rememberizer.
7. In **"Authorized request origins"**, type the domain to your app's website.
8. In **"Authorized redirect URLs"**, type the callback URL of your app.
9. Click **"Create app"**.


==> developer/README.md <==
# Developer



==> developer/vector-stores.md <==
---
description: >-
  This guide will help you understand how to use the Rememberizer Vector Store
  as a developer.
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Vector Stores

The Rememberizer Vector Store simplifies the process of dealing with vector data, allowing you to focus on text input and leveraging the power of vectors for various applications such as search and data analysis.

### Introduction

The Rememberizer Vector Store is designed to provide an easy-to-use interface for handling vector data. Unlike traditional vector databases like Pinecone, Rememberizer Vector Store allows you to work directly with text. The service will handle chunking, vectorizing, and storing the text data, making it easier for you to focus on your core application logic.

### Getting Started

#### Creating a Vector Store

1. Navigate to the Vector Stores Section in your dashboard
2. Click on "Create new Vector Store":
   * A form will appear prompting you to enter details.
3. Fill in the Details:
   * **Name**: Provide a unique name for your vector store.
   * **Description**: Write a brief description of the vector store.
   * **Data Schema**: Define the vector dimensions and any additional fields.
     * You can optionally specify the embedding model, indexing strategy, and similarity metrics. These settings influence how vectors are generated and compared, optimizing performance for your specific use case.
4. Submit the Form:
   * Click on the "Create" button. You will receive a success notification, and the new store will appear in your vector store list.

<figure><img src="../.gitbook/assets/create_vector_DB_store.png" alt=""><figcaption><p>Create a New Vector Store</p></figcaption></figure>

#### Managing Vector Stores

1. View and Edit Vector Stores:
   * Access the management dashboard to view, edit, or delete vector stores.
2. Viewing Documents:
   * Browse individual documents and their associated metadata within a specific vector store.
3. Statistics:
   * View detailed statistics such as the number of vectors stored, query performance, and operational metrics.

<figure><img src="../.gitbook/assets/vector_store_management.png" alt=""><figcaption><p>View Details of a Vector Store</p></figcaption></figure>

### API Key Management

API keys are used to authenticate and authorize access to the Rememberizer Vector Store's API endpoints. Proper management of API keys is essential for maintaining the security and integrity of your vector stores. This section covers how to create and revoke API keys for your Vector Stores.

#### Creating API Keys

1. Head over to your Vector Store details page
2. Navigate to the API Key Management Section:
   * It can be found within the "Configuration" tab
3. Click on **"Add API Key"**:
   * A form will appear prompting you to enter details.
4. Fill in the Details:
   * **Name**: Provide a name for the API key to help you identify its use case.
5. Submit the Form:
   * Click on the "Create" button. The new API key will be generated and displayed. Make sure to copy and store it securely. This key is used to authenticate requests to that specific vector store.

<figure><img src="../.gitbook/assets/vector_store_api_key.png" alt=""><figcaption><p>Create a New API Key</p></figcaption></figure>

#### Revoking API Keys

If an API key is no longer needed, you can delete it to prevent any potential misuse.

For security reasons, you may want to rotate your API keys periodically. This involves generating a new key and revoking the old one.

### Retrieving Vector Store Information Using the API Key

After creating a new Vector Store and generating an API key, you can share this key with users who need access to the Vector Store. The API key allows users to upload documents, search documents, and perform other operations within the Vector Store. However, before users can interact with the Vector Store, they need to retrieve the Vector Store's ID and other related information using the API key.

Detail information for each API endpoint and response, visit the [vector-store](api-documentations/vector-store/ "mention") page.

***

Make sure to handle the API keys securely and follow best practices for API key management.


==> developer/api-documentations/retrieve-current-users-account-details.md <==
# Retrieve current user's account details

{% swagger src="../../.gitbook/assets/rememberizer_openapi (1).yml" path="/account/" method="get" %}
[rememberizer_openapi (1).yml](<../../.gitbook/assets/rememberizer_openapi (1).yml>)
{% endswagger %}


==> developer/api-documentations/retrieve-slacks-content.md <==
# Retrieve Slack's content

{% swagger src="../../.gitbook/assets/rememberizer_openapi (1).yml" path="/discussions/{discussion_id}/contents/" method="get" %}
[rememberizer_openapi (1).yml](<../../.gitbook/assets/rememberizer_openapi (1).yml>)
{% endswagger %}


==> developer/api-documentations/retrieve-document-contents.md <==
# Retrieve document contents

{% swagger src="../../.gitbook/assets/rememberizer_openapi (1).yml" path="/documents/{document_id}/contents/" method="get" %}
[rememberizer_openapi (1).yml](<../../.gitbook/assets/rememberizer_openapi (1).yml>)
{% endswagger %}


==> developer/api-documentations/get-all-added-public-knowledge.md <==
# Get all added public knowledge

{% swagger src="../../.gitbook/assets/rememberizer_openapi (1).yml" path="/common_knowledge/subscribed-list/" method="get" %}
[rememberizer_openapi (1).yml](<../../.gitbook/assets/rememberizer_openapi (1).yml>)
{% endswagger %}


==> developer/api-documentations/README.md <==
# API documentations

You can authenticate APIs using either [OAuth2](../authorizing-rememberizer-apps.md) or [API keys](../registering-and-using-api-keys.md). OAuth2 is a standard authorization framework that enables applications to securely access specific documents within a system. On the other hand, API keys provide a simpler method to retrieve documents from a common knowledge base without the need to undergo the OAuth2 authentication process.


==> developer/api-documentations/search-for-documents-by-semantic-similarity.md <==
# Search for documents by semantic similarity

{% swagger src="../../.gitbook/assets/rememberizer_openapi (1).yml" path="/documents/search/" method="get" %}
[rememberizer_openapi (1).yml](<../../.gitbook/assets/rememberizer_openapi (1).yml>)
{% endswagger %}


==> developer/api-documentations/retrieve-documents.md <==
# Retrieve documents

{% swagger src="../../.gitbook/assets/rememberizer_openapi (1).yml" path="/documents/" method="get" %}
[rememberizer_openapi (1).yml](<../../.gitbook/assets/rememberizer_openapi (1).yml>)
{% endswagger %}


==> developer/api-documentations/list-available-data-source-integrations.md <==
# List available data source integrations

{% swagger src="../../.gitbook/assets/rememberizer_openapi (1).yml" path="/integrations/" method="get" %}
[rememberizer_openapi (1).yml](<../../.gitbook/assets/rememberizer_openapi (1).yml>)
{% endswagger %}


==> developer/api-documentations/memorize-content-to-rememberizer.md <==
# Memorize content to Rememberizer

{% swagger src="../../.gitbook/assets/rememberizer_openapi (1).yml" path="/documents/memorize/" method="post" %}
[rememberizer_openapi (1).yml](<../../.gitbook/assets/rememberizer_openapi (1).yml>)
{% endswagger %}


==> developer/api-documentations/vector-store/get-the-information-of-a-document.md <==
# Get the information of a document

{% swagger src="../../../.gitbook/assets/rememberizer_openapi.yml" path="/vector-stores/{vector-store-id}/documents/{document-id}" method="get" %}
[rememberizer_openapi.yml](../../../.gitbook/assets/rememberizer_openapi.yml)
{% endswagger %}



==> developer/api-documentations/vector-store/remove-a-document-in-vector-store.md <==
# Remove a document in Vector Store

{% swagger src="../../../.gitbook/assets/rememberizer_openapi.yml" path="/vector-stores/{vector-store-id}/documents/{document-id}/" method="delete" %}
[rememberizer_openapi.yml](../../../.gitbook/assets/rememberizer_openapi.yml)
{% endswagger %}



==> developer/api-documentations/vector-store/update-files-content-in-a-vector-store.md <==
# Update file's content in a Vector Store

{% swagger src="../../../.gitbook/assets/rememberizer_openapi.yml" path="/vector-stores/{vector-store-id}/documents/{document-id}/" method="patch" %}
[rememberizer_openapi.yml](../../../.gitbook/assets/rememberizer_openapi.yml)
{% endswagger %}



==> developer/api-documentations/vector-store/search-for-vector-store-documents-by-semantic-similarity.md <==
# Search for Vector Store documents by semantic similarity

{% swagger src="../../../.gitbook/assets/rememberizer_openapi (1).yml" path="/vector-stores/{vector-store-id}/documents/search" method="get" %}
[rememberizer_openapi (1).yml](<../../../.gitbook/assets/rememberizer_openapi (1).yml>)
{% endswagger %}


==> developer/api-documentations/vector-store/upload-files-to-a-vector-store.md <==
# Upload files to a Vector Store

{% swagger src="../../../.gitbook/assets/rememberizer_openapi.yml" path="/vector-stores/{vector-store-id}/documents/upload" method="post" %}
[rememberizer_openapi.yml](../../../.gitbook/assets/rememberizer_openapi.yml)
{% endswagger %}



==> developer/api-documentations/vector-store/get-a-list-of-documents-in-a-vector-store.md <==
# Get a list of documents in a Vector Store

{% swagger src="../../../.gitbook/assets/rememberizer_openapi.yml" path="/vector-stores/{vector-store-id}/documents" method="get" %}
[rememberizer_openapi.yml](../../../.gitbook/assets/rememberizer_openapi.yml)
{% endswagger %}



==> developer/api-documentations/vector-store/README.md <==
# Vector Store APIs



==> developer/api-documentations/vector-store/get-vector-stores-information.md <==
# Get vector store's information

{% swagger src="../../../.gitbook/assets/rememberizer_openapi.yml" path="/vector-stores/me" method="get" %}
[rememberizer_openapi.yml](../../../.gitbook/assets/rememberizer_openapi.yml)
{% endswagger %}



==> developer/api-documentations/vector-store/add-new-text-document-to-a-vector-store.md <==
# Add new text document to a Vector Store

{% swagger src="../../../.gitbook/assets/rememberizer_openapi.yml" path="/vector-stores/{vector-store-id}/documents/create" method="post" %}
[rememberizer_openapi.yml](../../../.gitbook/assets/rememberizer_openapi.yml)
{% endswagger %}



==> notices/terms-of-use.md <==
# Terms of Use

### 1. Introduction

This document outlines the terms of use ("Terms") for Rememberizer, a service of Skydeck AI Inc ("Rememberizer") including all pages provided to the user in a custom or generally available domain within \*.rememberizer.ai and any other pages that link to these Terms (the "Sites"). These Terms constitute a binding legal agreement between you, as the user, and Skydeck AI Inc, as the provider of this platform. By accessing or using this platform, you affirm your agreement to abide by these Terms.

### 2. Acceptance of Terms

By accessing or using any part of the Sites, you confirm that you are at least 18 years old, have read and understood these Terms of Use and the Rememberizer Privacy Policy (which is incorporated into these Terms by reference), and agree to be legally bound by them.

In these Terms, "we," "us," and "our" refer to Rememberizer, while "you" refers to both you as an individual and any entity you represent. By using our platform, you confirm that you can accept these Terms on behalf of any such entity, thereby binding it to these Terms.

### 3. Contact Information

SkyDeck AI Inc. is the entity you are contracting with. Our mailing address and contact information are as follows:

SkyDeck AI Inc.\
548 Market St. PMB38234\
San Francisco, CA 94104\
Phone: 1.415.744.1557\
For legal inquiries: [legal@rememberizer.ai](mailto:legal@rememberizer.ai)

### 4. License Grant and Proprietary Rights

Subject to your full compliance with these Terms, any other policies or restrictions posted on the platform, and your timely payment of any fees agreed upon with Rememberizer, we grant you a limited, non-exclusive, non-transferable, revocable license to access and use the platform.

Unless otherwise noted, all content made available through the platform (including but not limited to software, submissions, information, user interfaces, graphics, trademarks, logos, images, artwork, videos, documents, and the overall "look and feel" of the platform) is owned, controlled, or licensed by or to Rememberizer. This content is protected by various laws including trade dress, copyright, patent and trademark laws, and other intellectual property rights and unfair competition laws. Rememberizer reserves all rights in and to this content.&#x20;

Your content remains your sole property. You provide us with a non-exclusive, revocable license to use your content for the purpose of providing our service to you.

Any unauthorized reproduction, redistribution, use, or exploitation of any part of the platform is expressly prohibited by law and may result in civil or criminal penalties.

### 5. Account Responsibility

If you open an account on the platform, you are responsible for maintaining the confidentiality of your account information and for all activity under your account. By accepting these Terms and creating an account, you agree to our collection, use, and disclosure of your information as described in the Privacy Policy. No one under age 18 may register for an account or provide any personal information to Rememberizer or the platform. Notify Rememberizer immediately of any unauthorized account use. You may be held liable for losses due to unauthorized use. Do not use anyone else’s account without pre-approval from Rememberizer Account registration is void where prohibited.

### 6. User Rights and Responsibilities

As a user, you have the right to use our AI tools for your legitimate business purposes. You are responsible for not misusing or abusing the tools, infringing on others' rights, or violating any laws. You are required to comply with all applicable laws and regulations in your use of the platform.

### 7. Provider Rights and Responsibilities

We, Rememberizer., reserve the right to monitor use, enforce these Terms, and update the platform and its terms as needed. We are responsible for providing a reliable service, respecting users' privacy, and responding to any issues or concerns.

### 8. Content Rules

Content generated by our AI tools is owned by you, the user, subject to any restrictions or conditions specified in these Terms. The content should not be used for illegal or inappropriate purposes.

### 9. Misuse and Breach

Misuse or breach of these Terms can result in penalties, including but not limited to, suspension or termination of access to the platform, legal action, and/or damages.

### 10. Disclaimer of Warranties

You agree that your use of the platform, including any content, is at your sole risk. The platform and content are provided on an “as is” and “as available” basis. Rememberizer makes no warranties, express or implied, and disclaims all possible warranties, including without limitation implied warranties of merchantability, fitness for a particular purpose, title and non-infringement. Rememberizer does not warrant that the platform or content are accurate, continuously available, complete, reliable, secure, current, error-free, or free of viruses or other harmful components.

### 11. Indemnification

You agree to indemnify, defend, and hold harmless Rememberizer, its officers, directors, shareholders, successors, employees, agents, subsidiaries, and affiliates, from any actual or threatened third-party claims, demands, losses, damages, costs, liability, proceedings, and expenses (including reasonable attorneys' and expert fees and costs of investigation), to the fullest extent permitted by law. This includes any issues arising out of or in connection with your use of the platform, your breach of these Terms, your violation of any law or regulation, your violation of any third-party rights, or the disclosure, solicitation, or use of any personal information by you, whether with or without your knowledge or consent. Rememberizer reserves the right to assume exclusive defense and control of any matter subject to indemnification by you, and you agree to cooperate with Rememberizer's defense of such a claim. You may not agree to any settlement affecting Rememberizer. without Rememberizer's prior written consent.

### 12. Suspension or Termination of Access

Rememberizer reserves the right to suspend or terminate your access to any or all of the platform, with or without notice, for any reason. This includes but is not limited to breaches of these Terms, requests by law enforcement or other government agencies, discontinuation or significant modification of the platform, or unexpected technical issues. Rememberizer is not liable for any termination of your access to the platform. Any rights and obligations under these Terms that should naturally continue beyond your use of the platform will survive any termination of your access.

### 13. Limitation of Liability

To the maximum extent permitted by law, you agree to bear the entire risk arising out of your access to and use of the platform and content. Rememberizer or any of its directors, employees, agents or suppliers will not be liable for any special, indirect, incidental, exemplary, consequential or punitive damages of any kind arising out of or in connection with the platform, and any content, services or products included on or otherwise made available through the platform. Rememberizer's total cumulative liability to you arising out of or in connection with these Terms, or from the use of or inability to use the platform, will not exceed one hundred dollars ($100.00).

### 14. Dispute Resolution

Any disputes, controversies, or claims arising out of or in connection with these Terms, including their validity, invalidity, breach, or termination, shall be resolved by arbitration in accordance with the rules of the American Arbitration Association. The place of arbitration shall be San Jose, California, and the proceedings shall be governed by the laws of California. The arbitration award shall be final and binding upon both parties.

### 15. Changes to the Terms

Rememberizer reserves the right, at our discretion, to change these Terms at any time. Changes will be communicated to users through appropriate channels, such as email notifications, website banners, or in-app messages, and users will be given a reasonable period of time to accept the new terms.

### 16. Translations

For your convenience we provide machine translations of this document in languages other than English. At any time when there is a conflict or contradiction between the original English language version and a version in another language, the English language version will apply and prevail. By relying on a non-English translation of this document you accept that there could be unintended differences between the translated text and the actual terms to which you have agreed.


==> notices/privacy-policy.md <==
# Privacy Policy

## Rememberizer Privacy Policy

SkyDeck AI Inc. ("Rememberizer," "we," "our," or "us") respects your privacy and is committed to protecting it through our compliance with this policy. This policy describes the types of information we may collect from you or that you may provide when you use the rememberizer.ai generative AI platform (our "Service") and our practices for collecting, using, maintaining, protecting, and disclosing that information.

### Information We Collect About You and How We Collect It

We collect several types of information from and about users of our Service, including:

* Personal information, such as your name, email address, and other identifiers by which you may be contacted online or offline.
* Technical data, such as information about your internet connection, the equipment you use to access our Service, and usage details.
* API keys and credentials for accessing third-party vendor generative AI models provisioned by you.
* Document content ("Knowledge") which consists of entire documents (such as Google Docs), data, discussion (such as the content of a Slack channel). These come from data sources that you select and choose to share with Rememberizer.&#x20;

We collect this information:

* Directly from you when you provide it to us by authorizing access to a data source.
* Directly from when an app you have integrated with Rememberizer chooses to store text in Rememberizer memory for later use by that app or others.
* Automatically as you navigate through the Service. Information collected automatically may include usage details, IP addresses, and information collected through cookies, web beacons, and other tracking technologies.
* Automatically when you change the source data so that the latest version can be reflected in our Knowledge.
* We affirm that any User Data retrieved from Google Workspace APIs is not used to train any AI/ML models. This data is accessible only to the individual user who has provided explicit consent, and it is used solely for the purpose of providing and improving our services to you.

### How We Use Your Information

We use information that we collect about you or that you provide to us, including any personal information:

* To provide you with the Service and its contents, and any other information, products or services that you request from us.
* To fulfill any other purpose for which you provide it.
* To provide you with notices about your account.
* To carry out our obligations and enforce our rights arising from any contracts entered into between you and us.
* To notify you about changes to our Service or any products or services we offer or provide through it.
* To improve our Service, products, or services.
* To allow you to participate in interactive features on our Service.
* Text components of Knowledge documents are stored in chunks and indexed in vector data stores so that parts that are estimated to have semantic relevance can be returned to third party applications that you authorize to have that access.&#x20;

### Third Party Sharing

A major purpose of Rememberizer is to share highly relevant extracts of your data with 3rd party applications in a controlled fashion. This is achieved through the application of a single **Memento** to each application that is integrated with Rememberizer that you also choose to authorize to access your data in Rememberizer.

The current implementation of Memento allows the user to select specific files, documents or groups of content such as a folder or channel that can be used by that application. Later implementations will add additional ways to filter 3rd party access such as time frames like "created in the last 30 days".\
\
Two default values are "None" and "All". All shares every file that the user has allowed Rememberizer to access. None shares nothing with the app in question. Selecting None allows a user to select an app and integrate it with Rememberizer without having to decide then and there what content to make available. Selecting a Memento with None or editing an existing applied Memento to share None is a way to turn off an apps access to user data without having to remove the integration. This is like an off switch for your data. Custom Mementos can be purpose made and have names that reflect that, such as "Homework" or "Marketing".&#x20;

### Disclosure of Your Information

We may disclose aggregated information about our users, and information that does not identify any individual, without restriction. We may disclose personal information that we collect or you provide as described in this privacy policy:

* To third-party vendors, service providers, contractors, or agents who perform services for us or on our behalf and require access to such information to do that work.
* To fulfill the purpose for which you provide it. For any other purpose disclosed by us when you provide the information.
* With your consent.

### Your Rights

You have certain rights under applicable data protection laws. These may include the right to:

* Request access to your personal data.
* Request correction of the personal data that we hold about you.
* Request erasure of your personal data.
* Object to processing of your personal data.
* Request restriction of processing your personal data.
* Request transfer of your personal data.
* Right to withdraw consent.

### Data Security

We have implemented measures designed to secure your personal information from accidental loss and from unauthorized access, use, alteration, and disclosure. All information you provide to us is stored on our secure servers behind firewalls. Any payment transactions and API keys will be encrypted using SSL technology.

### Changes to Our Privacy Policy

It is our policy to post any changes we make to our privacy policy on this page. If we make material changes to how we treat our users' personal information, we will notify you through a notice on the Service home page.

### Contact Information

To ask questions or comment about this privacy policy and our privacy practices, contact us at:

SkyDeck AI Inc.\
Attn: Rememberizer\
548 Market St. PMB38234\
San Francisco, CA 94104\
Phone: 1.415.744.1557\
Email: [legal@rememberizer.ai](mailto:legal@rememberizer.ai)


==> notices/README.md <==
# Notices



==> notices/releases/sep-13th-2024.md <==
---
description: >-
  This release focuses on improving data indexing, usage tracking, performance, and user experience enhancements.
---

# Sep 13th, 2024

### Improvements

- **Improved Usage Tracking**: New logic provides more accurate monitoring of your storage and usage limits.
- **Enhanced Performance**: Memento actions are now optimized for better responsiveness.
- **Enhanced Error Display**: Error messages on the knowledge page are clearer when document indexing fails, making it easier to identify issues.
- **Streamlined Data Source Connection**: The data source panel now opens automatically after connecting, simplifying the setup process.
- **Improved Default Settings**: Default user settings have been updated to enhance performance and accuracy.

### New Features

- **Batch Document Deletion**: You can now delete multiple documents at once, simplifying data management.
- **Automatic Re-indexing**: Collections automatically re-index when needed, ensuring up-to-date search results.

### Bug Fixes

- **Fixed Indexing Bugs**: Resolved issues with data indexing to improve search reliability.
- **Reduced Notification Spam**: Fixed an issue causing excessive notifications related to document membership.

==> notices/releases/jan-22nd-2024.md <==
---
description: >-
  This release introduces new features like an 'Explore Apps' page and improved
  document management, alongside key optimizations and bug fixes for a smoother
  user experience.
---

# Jan 22nd, 2024

## New Features

* **Explore Apps Page**: You can now explore different apps right from a dedicated page.
* **Quota Control**: A new feature to control quota size when selecting files is now available, ensuring better file management.

## Improvements

* **Improved Document Search**: We've enhanced the search feature to return the number of documents, making it easier to manage and navigate your files.
* **Improved Onboarding**: Added a 'Skip' button for onboarding steps, providing more flexibility during the onboarding process.

## Bug fixes

* Resolved issues with the handling of complex PDF files for better readability and access.
* Resolved issues related to Slack rate limits for uninterrupted integration.


==> notices/releases/oct-4th-2024.md <==
---
description: >-
    This release focuses on enhancing performance and stability, with significant improvements to synchronization processes and fixes to known issues.
---
# Oct 4th, 2024
### Improvements
- **Optimized Google Drive Navigation**: Improved performance of the Google Drive knowledge tree for faster and smoother browsing.
- **Enhanced Synchronization Efficiency**: Optimized document synchronization by refining task management for quicker updates.

### Bug Fixes
- **Resolved Crash When Disconnecting Data Source**: Fixed an issue where disconnecting a data source while the knowledge panel was open caused the app to crash.

==> notices/releases/apr-26th-2024.md <==
---
description: >-
  This update brings advanced memento integration, improved sync features for
  Dropbox and Google Drive, and critical bug fixes to enhance user experience
  and system reliability.
---

# Apr 26th, 2024

## New Features

* **Search Functionality for Public Apps:** A new search feature has been added to the public apps page, allowing users to find apps more efficiently.

## Improvements

* **Layout Update for Connected Apps:** The layout of the 'Your Connected Apps' page has been updated for better user experience and navigation.
* **Common Knowledge Card Update:** The common knowledge card in the refining memento page now shows size instead of document count, providing clearer information on storage usage.
* **Enhancement of the Auto Sync Feature for Dropbox and Google Drive:** The auto-sync feature for Dropbox and Google Drive has been enhanced, providing a smoother and more reliable synchronization experience.
* **Pagination for the Public App Page:** We've implemented pagination on the public app page, improving navigation and load times for a better user experience.
* **Update Refine Button in Memento for Common Knowledge Cards:** The refine button in mementos for common knowledge cards has been updated, enhancing usability and clarity.

## Bug Fixes

* **Indexing Issue for Child Files:** Fixed a bug where child files in a selected folder weren't indexed correctly when connecting integrations for the first time, ensuring comprehensive file management.
* **Sign-Out Issue on Search Failure:** Resolved an issue where a failed search for non-existent mementos forced users to sign out, improving error handling and user retention.
* **Profile Edit Validation:** Addressed a validation issue on the edit profile page, ensuring information is accurately captured and processed


==> notices/releases/apr-5th-2024.md <==
---
description: >-
  This update enhances integrations with Dropbox, Google Drive, and Slack, and
  refines document management for a smoother user experience.
---

# Apr 5th, 2024

## New Features

* **New Knowledge Tree Support:** Extended the tree structure to better integrate with Dropbox and Google Drive, enabling more intuitive document and folder management.
* **Slack Reply Synchronization:** Added functionality to synchronize new Slack replies more effectively, helping keep communications seamless and updated.

## Bug Fixes

* **Common Knowledge Page Fixes:** Fixed bugs related to searching, pagination, and updating the DateTime format on the common knowledge page.
* **Show the Selected Files for Old Account Fixes:** We've fixed an issue where the selected files for old accounts weren't displayed correctly.


==> notices/releases/sep-20th-2024.md <==
---
description: >-
    This release focuses on various improvements, new features, and bug fixes to enhance user experience and functionality.
---
# Sep 20th, 2024

### Improvements
- **Enhanced Formatting for Numbers**: Big numbers now display with commas for easier reading.
- **Updated Document Handling**: Improved mechanism to manage and index documents efficiently, even in larger folders.
- **Optimized Slack and Document Handling**: Enhanced API to retry all failed documents and slack channels, ensuring smoother operations.

### New Features
- **Membership Update**: Memberships now update based on loading results for more accurate data.
- **Random Document Selection**: Introduced random selection for embedding and loading to diversify document processing.

### Bug Fixes
- **Dropbox Sync**: Temporarily disabled Dropbox sync to prevent potential data issues.
- **Search Field Improvement**: The search field on the Knowledge Details page now autofills based on the "file" query parameter for more precise searches.
- **Reindex Collection Post-Loading**: Enhanced the loading result API to reindex collections automatically.

==> notices/releases/oct-25th-2024.md <==
---
description: >-
  This release focuses on improving document indexing reliability and includes various bug fixes to enhance your experience.
---
# Oct 25th, 2024

### New Features

- **Automatic Retry for Indexing Failures**: Implemented an auto-retry mechanism to ensure documents that failed to index are retried, enhancing data consistency.

### Bug Fixes

- **Improved Search Functionality**: Fixed an issue preventing searches from apps connected to mementos without memories.
- **System Stability Enhancements**: Resolved overlapping database connections during concurrent tasks to improve performance.
- **Slack Synchronization Adjustments**: Temporarily disabled synchronization for empty Slack channels to avoid unnecessary errors.

==> notices/releases/feb-5th-2024.md <==
---
description: >-
  This release enhances user profile management, improves Slack and Dropbox
  integration, introduces account deletion feature, and addresses key
  operational issues.
---

# Feb 5th, 2024

## New Features

* **Dropbox Shared Files**: You can now fetch shared files/folders from Dropbox directly within our platform.
* **Account Deletion**: Users now have the option to delete their account if needed.
* **Slack Synchronization**: We've initiated synchronization with Slack for improved integration, although Slack thread synchronization is not yet included.
* **User Profiles**: Users can now update their profile information more efficiently.

## Improvements

* **Slack Channels**: Slack channels are now sorted by name for easier navigation.

## Bug Fixes

* Resolved an issue regarding invalid origin in App directory.
* Resolved an error with OpenAI GPT for improved API calls.


==> notices/releases/jan-29th-2024.md <==
---
description: >-
  This release offers an enhanced user experience with improved document size
  management, a more intuitive search interface, and seamless Dropbox
  integration. We've also addressed key bugs.
---

# Jan 29th 2024

## New Features

* **Dropbox Integration**: You can now index, reindex, list, and submit Dropbox files directly within our platform.
* **Dropbox in Onboarding Step**: Dropbox integration is now part of the onboarding step, making it easier to set up.

## Improvements

* **Document Size Limit**: We've limited the total document size for each user to 1GB to ensure optimal performance.
* **Improved Search Experience**: The search interface has been enhanced for better user experience.

## Bug Fixes

* Fixed issues with handling empty documents for smoother operations.
* Resolved errors while handling Slack attachments for seamless integration.
* Linked the 'Sign Up' button correctly to the 'Sign Up' page.


==> notices/releases/jun-14th-2024.md <==
---
description: >-
  This release improves error handling, enhances the memento sidebar, and
  refines tests. Key updates include memento size display, better error
  responses, and automatic version checks.
---

# Jun 14th, 2024

## New Features

* **Show Mementos' Size:** The size of mementos is now displayed in the memento sidebar, providing users with better insights into their storage usage.
* **Check for the Latest Version:** We've added a feature that allows the desktop app to automatically check for and notify users of the latest version available.

## Bug Fixes

* **Return 404 for Deleted Mementos:** Retrieving a deleted memento or one that belongs to another user now returns a 404 error instead of a server error.
* **Update Size for Third-Party Apps:** Fixed an issue where third-party app memory documents didn't trigger size updates for mementos.


==> notices/releases/sep-27th-2024.md <==
---
description: >-
  This release focuses on enhancing synchronization performance and navigation for Dropbox and Google Drive, providing you with a smoother and more efficient experience.
---

# Sep 27th, 2024
### Improvements
- **Enhanced Cloud Synchronization**: Optimized the synchronization processes for Dropbox and Google Drive, resulting in faster and more reliable file updates.
- **Improved Dropbox Navigation**: Refined the Dropbox knowledge tree for more efficient file organization and easier access.
- **Regular Sync Schedule**: Set synchronization tasks for Google Drive, Dropbox, and Gmail to occur every 6 hours, ensuring your content stays consistently up-to-date.

==> notices/releases/aug-16th-2024.md <==
---
description: >-
  This release focuses on enhancing search capabilities and improving document management features.
---

# Aug 16th, 2024

### New Features

- **Enhanced Search Filters**: Added the ability to filter search results by sender and recipient, making it easier to find specific emails.
- **Document Creation Date Display**: Now shows the document creation date in document lists for better document management.

### Improvements

- **Improved Search Reliability**: Enhancements to search functions provide a smoother and more reliable experience.

### Bug Fixes

- **Email Integration Fix**: Resolved issues with Gmail integration when using GPT to ensure smooth operation.
- **Desktop App Content Display Fix**: Fixed issues with document content display in the desktop app for a better user experience.

==> notices/releases/mar-18th-2024.md <==
---
description: >-
  This release focuses on enhancing user experience with improved onboarding,
  memento management and responsive UI. Key updates include removal of image
  size limit, display of memento sizes.
---

# Mar 18th, 2024

## New Features

* **Create a New Memento Button:** We've added a new button to create mementos while authorizing the app, making the process more user-friendly.
* **No Size Limit for Image Uploader:** Users can now upload images of any size, offering more flexibility in document design.
* **Common Knowledge Size Display:** We've added the feature to show the size of common knowledge items, providing more transparency in storage usage.

## Improvements

* **Slack Channels' Indexed Time:** The indexed time will now be updated when checking for new messages, and the document’s `INDEXED` status will be maintained, improving document search efficiency.
* **Smoother Onboarding:** We've reduced redundant steps in the onboarding flow, making it quicker and more efficient.
* **Responsive UI for Common Knowledge:** We've optimized the UI for common knowledge on the memento page to be responsive, improving readability on various devices.
* **Memento Size Display:** The size of mementos is now displayed when authorizing an app, helping users understand their authorized mementos better.

## Bug Fixes

**User-Rename-Application:** The case where a user renames an application is now handled properly, preventing potential errors.


==> notices/releases/apr-19th-2024.md <==
---
description: >-
  This update boosts security, refines interfaces, and addresses critical bugs,
  featuring new API restrictions, updated keys, and a MacOS app.
---

# Apr 19th, 2024

## New Features

* **Desktop App for MacOS:** Introducing a dedicated desktop app for MacOS users, enhancing accessibility and user experience. \
  See Docs: [Rememberizer Desktop Agent Application](https://docs.rememberizer.ai/personal/rememberizer-agent-desktop-application)

## Improvements

* **App Directory UI Update:** The new layout for the app directory offers a more intuitive and user-friendly navigation experience.

## Bug Fixes

* **Search Document Newline Handling:** Fixed an issue where newlines and return characters were removed incorrectly in search document queries.
* **Search UI Display Bug:** Corrected a search UI bug to ensure the `Created at` field is accurately displayed for each document in search results.


==> notices/releases/mar-4th-2024.md <==
---
description: >-
  This release introduces new features like shared knowledge creation and
  display, and memento renaming. Improvements include key bug fixes about
  Dropbox, query result and Common knowledge UI.
---

# Mar 4th 2024

## New Features

* **Shared Knowledge**: A new feature to create and display shared knowledge has been implemented.
* **Memento Renaming**: Users can now rename their mementos.

## Bug Fixes

* **Dropbox Files Display**: Resolved an issue with incorrect file display in Dropbox.
* **Querying Result Order**: Fixed a bug where querying results with consecutive chunks returned a disordered result.
* **Common Knowledge UI**: Fixed several UI issues with the Common Knowledge feature.

\


==> notices/releases/oct-11th-2024.md <==
---
description: >-
    This release introduces our new vector database service for more efficient data handling, along with system stability enhancements and critical bug fixes to improve your overall experience.
---

# Oct 11th, 2024

### New Features

- **Vector Database Service**: Introduced a new vector database service for more efficient data storage and faster information retrieval.

### Improvements

- **Enhanced System Stability**: Improved backend processes to prevent race conditions, ensuring smoother document processing.
- **Optimized Connection Management**: Implemented better connection handling to enhance performance and reliability.

### Bug Fixes

- **Fixed Membership Merging Issue**: Resolved an issue that caused errors when merging membership data in the vector store.

==> notices/releases/apr-12th-2024.md <==
---
description: >-
  This release enhances document synchronization, streamlines common knowledge
  management, and optimizes the user interface, improving overall system
  efficiency and user experience.
---

# Apr 12th, 2024

## New Features

* **Automatic Sync for Cloud Storage:** Users can now set automatic synchronization for selected folders and files in Dropbox and Google Drive, streamlining document management processes.

## Improvements

* **Optimized Document Ordering:** The order of documents can now be set by indexed date or name, facilitating more intuitive navigation and retrieval.
* **UI Updates for Memento Management:** The common knowledge memento UI has been updated, including a new toggle for sharing settings, improving user control over data sharing.
* **UI Responsiveness and Customization:** Minor UI fixes have been implemented.

## Bug Fixes

* **Onboarding Process:** Resolved an issue where common knowledge was not displayed during a user's onboarding step, enhancing the initial setup experience for new users.


==> notices/releases/jun-28th-2024.md <==
---
description: >-
  This release enhances navigation, improves document handling, and updates the
  app name. Key updates include limiting homepage applications, better Slack
  document processing, and renaming the desktop a
---

# Jun 28th, 2024

## Improvements

* **Limit Applications on Homepage:** We've limited the number of applications displayed on the homepage to make it easier for users to navigate and find what they need.
* **Post-Process Slack Documents:** Enhanced the handling of Slack documents to ensure smoother and more accurate processing.
* **Update Desktop App Name:** The desktop app has been renamed to "Rememberizer App" for better clarity and brand consistency.


==> notices/releases/README.md <==
---
description: Public Declarations, Compliance Alterations, and User Assistance Updates.
---

# Releases

© 2024 SkyDeck AI Inc.


==> notices/releases/may-31st-2024.md <==
---
description: >-
  This release enhances SQL queries, refines the UI, and fixes bugs. Key
  updates: optimized search, auto-generated names, new memento button, and
  improved navigation.
---

# May 31st, 2024

## New Features

* **New Memento Button:** We've added a new button to create mementos while authorizing the app, making the process more user-friendly.

## Improvements

* **Optimize Search:** Enhanced the search functionality for faster and more accurate results.
* **Tweak UI When Authorizing App:** Made minor adjustments to the user interface when authorizing an app for a smoother experience.

## Bug Fixes

* **Fix Indentation Problem:** Fixed an issue with indentation to ensure consistent formatting across the application.


==> notices/releases/jan-15th-2024.md <==
---
description: First release of Rememberizer.
---

# Jan 15th, 2024

## New Features

* **Document Search**: Find your documents easily with our efficient search feature.
* **Google Drive Integration**: Manage your files seamlessly through Google Drive.
* **Developer Hub**: A user-friendly space for developers to easily register and configure their applications for integration with Rememberizer.
* **Memento Management**: Easily create, list, and delete your mementos.
* **Data Source Management**: Easily connect and disconnect your data source.
* **Easy Onboarding**: Our onboarding status feature is designed for a smooth start for all users and developers.

\


==> notices/releases/may-17th-2024.md <==
---
description: >-
  This release focuses on improving the user experience, enhancing integrations,
  and fixing various issues. Key updates include Gmail synchronization and
  displaying the directory path.
---

# May 17th, 2024

## New Features

* **Gmail Integration & Synchronization:** Connect your Gmail accounts to effortlessly manage emails in our platform. Last week, we introduced label-specific integration; this week, enjoy full synchronization of threads within a label, for seamless access and management.

## Improvements

* **Display Directory Path:** The application now displays the directory path, making it easier for users to navigate and locate their documents.
* **Updated Diagram:** The application's diagram has been updated to provide a clearer visual representation of the system architecture and data flow.
* **Changed Datasources Order:** The order of data sources has been optimized to improve the efficiency of data retrieval and processing.
* **Updated Logic for Fetching Data:** The logic for fetching data has been enhanced to improve the accuracy and reliability of the retrieved information.

## Bug Fixes

* **Fixed Delete Document Button UI:** The user interface for the delete document button in embedded details has been fixed to provide a better user experience.


==> notices/releases/feb-26th-2024.md <==
---
description: >-
  In this release, we've implemented an image size limit of 1MB for uploads and
  enhanced document display in the Selection Panel. We've also fixed a bug
  related to data source disconnection.
---

# Feb 26th, 2024

## Improvements

* **Image Size Limit**: Cropped images for shared knowledge must not exceed 1MB in size.
* **Document Display Enhancement**: We have increased the number of documents that can be displayed in the tree structure within the Right Selection Panel for improved user experience.

## Bug Fixes

* **Data Source Disconnection**: Fixed an issue where disconnecting a data source did not appropriately delete documents and remove the data source.\


==> notices/releases/mar-25th-2024.md <==
---
description: >-
  This release brings improved synchronization, enhanced data encryption, and
  multiple bug fixes for a smoother user experience.
---

# Mar 25th, 2024

## Improvements

* **Memento Enhancements:** Added a feature to display additional memento information and show indexing progress, making it easier for users to track the status of their data.

## Bug Fixes

* **UI Responsiveness:** Addressed multiple clicking issues on the Disconnect button to prevent UI errors.


==> notices/releases/jul-26th-2024.md <==
---
description: >-
  This release focuses on improving our Slack integration, enhancing the user
  interface, and resolving critical issues to provide a smoother experience.
---

# Jul 26th, 2024

**New Features:**

* **Slack Channel Counter**: A new feature that accurately counts and displays the number of Slack channels, helping users better manage their workspace connections.

**Improvements:**

* **Updated Slack Integration UI**: The user interface for Slack integration has been refreshed to support the new channel mechanism, making it more intuitive and easier to use.
* **App Name Update**: The desktop application name has been updated to "Rememberizer," reflecting our commitment to helping users organize and remember important information.

**Bug Fixes:**

* **Google Drive Integration**: Resolved an issue that caused errors when accessing Google Drive folders, ensuring smoother navigation and file management.


==> notices/releases/aug-2nd-2024.md <==
---
description: >-
  This release focuses on improving the overall performance, data handling, and
  error management of our application. Users can expect a more robust and
  efficient experience.
---

# Aug 2nd, 2024

**New Features:**

* **Improved Search Functionality**: The search feature now runs parallel content retrieval, delivering faster and more accurate results.
* **Refined Document Notification System**: Users will receive more precise notifications about document updates, enhancing collaboration and workflow management.
* **Updated API Key Format**: Updated the API key prefix to improved security and easier identification.

**Improvements:**

* **Enhanced Data Management**: The system now handles empty documents more effectively, ensuring all relevant information is properly indexed and loaded.
* **Optimized Memento Organization**: Refinements to the memento sidebar provide a clearer view of documents and folders, making navigation more intuitive.
* **Streamlined Data Processing**: Implementation of a new embedding mechanism and vector database adaptation for more efficient data handling and analysis.

**Bug Fixes:**

* **Email Encoding Compatibility**:  Update system encoding format when email charset is incorrect, preventing potential display issues.
* **Gmail Label Management**: Resolved an issue when deleting Gmail labels, ensuring smoother email integration.
* **Exception Handling**: Improved error notification system to better manage and communicate system exceptions.


==> notices/releases/oct-18th-2024.md <==
---
description: >-
  This release focuses on improving document saving reliability.
---
# Oct 18th, 2024

### Bug Fixes

- **Enhanced Document Saving Stability**: Improved the document saving process to prevent potential conflicts during simultaneous edits.

==> notices/releases/feb-19th-2024.md <==
---
description: >-
  This release brings improvements to the Memento tree with better sorting and
  fixes a bug affecting API requests in GPT apps.
---

# Feb 19th, 2024

## Improvements

* **Alphabetical Sorting in Memento Tree**: For enhanced navigation, files and Slack channels within the Memento tree are now organized alphabetically.

## Bug Fixes

* **GPT Apps**: We've fixed a problem that was stopping API requests from being made through newly set-up GPT apps.

\


==> notices/releases/mar-11th-2024.md <==
---
description: >-
  This update brings new features and improvements, including streamlined Slack
  integration, enhanced documents, and a more efficient user signup process.
  We've also fixed some bugs.
---

# Mar 11th, 2024

## New Features

* **User Slack Data Migration:** User Slack data can now be migrated to accommodate Slack threads and replies, enhancing user interaction.
* **Common Knowledge Integration:** Common knowledge has been added to the integration sources endpoint, expanding our system's capabilities.
* **Pin Shared Knowledge Items:** System administrators can now pin shared knowledge items to the top of the list, enhancing visibility and accessibility.
* **Safe Document Handling:** The system will no longer fail on empty documents, improving system reliability.
* **Manage Shared Knowledge:** Users can now delete and edit their shared knowledge, providing more control over shared content.

## Improvements

* **Rememberizer UI Update:** The Rememberizer UI has been updated based on the new format of Slack Replies.

## Bug Fixes

* **Switching Between Common Knowledge:** Fixed an issue when switching between common knowledge when refining memento.
* **Unsupported Document Visibility:** Fixed the issue causing unsupported documents to be displayed.
* **User Document List:** Subscribed documents will no longer appear in the list of user documents.
* **Memento Size Estimation:** Rectified the incorrect calculation of the estimated size of the memento.



==> notices/releases/feb-12th-2024.md <==
---
description: >-
  In this release, we've introduced a public common knowledge page, made
  improvements to memento structure and onboarding UI, and fixed a bug with app
  authorization counting.
---

# Feb 12th, 2024

## New Features

* **Public Common Knowledge Page**: A new public common knowledge page has been implemented for better information access and sharing.
* **Common Knowledge in Onboarding**: Users can now add common knowledge directly from the onboarding page.
* **Tree Structure for Memento**: The files in a memento are now returned in a tree structure for better clarity and navigation.

## Improvements

* **UI for Onboarding Steps**: The user interface for onboarding steps has been tweaked for better user experience.


==> notices/releases/jul-12th-2024.md <==
---
description: >-
  This release brings exciting improvements to document search, memento
  organization, and integration management. We've enhanced the user experience
  with smoother navigation and more efficient data hand
---

# Jul 12th, 2024

### New Features

* **Document Search**: Enjoy a powerful new search functionality that helps you find the information you need quickly and easily within your documents.&#x20;
* **New Memento Tree Structure**: Experience a new way to organize your mementos with our intuitive tree structure, making it easier to navigate and manage your information.&#x20;
* **Auto Sync for Mementos**: Keep your data up-to-date effortlessly with our new automatic synchronization feature for mementos.

### Improvements

* **Enhanced Memento Organization**: We've refined the memento sidebar to provide a clearer view of your documents and folders, making navigation a breeze.&#x20;
* **Integration Management**: Easily filter and manage your integrations with a new dropdown feature, giving you more control over your connected services.&#x20;
* **Faster Document Search**: Our new debounced search feature provides quicker, more responsive results as you type.&#x20;
* **Homepage and Knowledge Page Updates**: We've reorganized the layout of integrations on key pages to improve accessibility and user experience.

### Bug Fixes

* **Improved Integration Reliability**: We've enhanced our system to better handle information from connected services, ensuring a smoother experience when using integrations.&#x20;
* **Cleaner User Interface**: We've removed unnecessary warning messages on the Knowledge page for a more streamlined look.



==> notices/releases/may-10th-2024.md <==
---
description: >-
  This release introduces Gmail integration, allowing users to connect their
  accounts and select labels for their knowledge base, and a new Memory feature
  for enhanced search functionality.
---

# May 10th, 2024

## New Features

*   **Rememberizer Memory** allows apps to save and share data within a user's Rememberizer account, providing a centralized location for important information from multiple apps.\
    &#x20;\
    **Benefits**

    * **For Users:** Easy access to data from all apps, seamless syncing between apps, and persistent storage even if apps are uninstalled.
    * **For Developers:** No need to create custom data storage systems, ability to leverage data from other apps, and simplified cross-app integration.

    Memory Documentation: [https://docs.rememberizer.ai/personal/rememberizer-memory-integration](https://docs.rememberizer.ai/personal/rememberizer-memory-integration).\
    Memory API Documentation: [https://docs.rememberizer.ai/developer/api-documentations/memorize-content-to-rememberizer](https://docs.rememberizer.ai/developer/api-documentations/memorize-content-to-rememberizer).
* **Gmail Integration:** Users can now connect their Gmail accounts and select specific labels to add to their knowledge base.
* **Google Drive Shared Drives Support:** We've added support for Google Drive Shared Drives, allowing users to include documents from shared drives in their knowledge base.

## Improvements

* **Document Indexing:** We've enhanced the document indexing process, ensuring that new documents are uploaded and indexed successfully. In case of indexing failures, retry mechanisms have been implemented.
* **App Publishing Flow:** The reviewing step has been removed from the app publishing flow, streamlining the process for developers.
* **Connected Apps UI:** The "Your connected apps" UI has been enhanced to handle scenarios when no apps are connected, improving user experience.

## Bug Fixes

* **Rename Application:** An issue where renaming an application caused errors has been resolved.


==> notices/releases/aug-9th-2024.md <==
---
description: >-
  This release focuses on enhancing user experience, improving document
  management, and refining search capabilities in the Rememberizer.
---

# Aug 9th, 2024

**New Features**

* **Slack Channel Integration**: Enhanced support for Slack channels, improving communication and collaboration within the app.
* **Document Status Filter**: Added a new filter for document status on the embedding details page, making it easier to track and manage documents.
* **Layered Document Display**: Implemented a new tree view in the memento sidebar, organizing documents and folders in layers for improved navigation.
* **Advanced Search Capabilities**: Introduced date range filters for search functionality, allowing for more precise document retrieval.

**Improvements**

* **Document Management**: Refined the process of linking documents to the knowledge details page, simplifying document organization and access.
* **User Interface Updates**: Various UI enhancements to improve overall app usability and visual appeal.
* **Performance Optimization**: Refactored code and updated API calls to enhance app performance and responsiveness.

**Bug Fixes**

* **Empty Search Query Handling**: Resolved an issue where empty search queries were not properly handled, improving search reliability.
* **Email Integration**: Fixed an issue related to email source handling when interacting with GPT, ensuring smoother integration with email services.


==> notices/releases/nov-1st-2024.md <==
---
description: >-
    This release focuses on enhancing performance, improving authentication, and increasing overall reliability for a better user experience.
---

# Nov 1st, 2024

### Improvements

- **Faster Search Performance**: Optimized backend processes to provide quicker access to your documents.
- **Enhanced Authentication System**: Upgraded authentication for improved security and reliability.
- **Improved Indexing Reliability**: Enhanced monitoring for document indexing to ensure all your documents are searchable.
- **Optimized System Performance**: Implemented backend optimizations for a faster and more efficient service.

### New Features

- **Automatic Data Source Reconnection**: Data sources now stay connected automatically, ensuring uninterrupted access to your information.

### Bug Fixes

- **Enhanced Privacy Controls**: Fixed an issue that prevented unauthorized listing in user views, improving privacy.
- **Resolved App Authorization Issues**: Corrected redirect problems with authorized apps for seamless access.

==> notices/b2b/README.md <==
---
description: Posts for the benefit of other businesses with which Skydeck AI Inc interacts.
---

# B2B



==> notices/b2b/about-reddit-agent.md <==
---
description: Rememberizer Agent
---

# About Reddit Agent

A Rememberizer agent retrieves Reddit content from select Sub-Reddits so that users and creators of those can query the underlying semantic meaning of their content and that of other participants in order to interact with that content using their own AI tools and those those others that they authorize through Rememberizer.


```

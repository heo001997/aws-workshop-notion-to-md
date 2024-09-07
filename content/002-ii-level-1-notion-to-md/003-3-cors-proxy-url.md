+++
title = "3. CORS Proxy URL"
weight = 3
+++


Since our [Notion to Markdown website](https://notion-to-md.bamidev.com/) is 100% running on Github Static Pages, we **WILL NOT** save any of your information, your information always stay in your browser, all the requests will be called directly from YOUR browser.


Unfortunately, this kind of request is [violate Notion CORS policy and won’t be support](https://github.com/makenotion/notion-sdk-js/issues/96#issuecomment-852542180), but that’s ok, we will use a CORS Proxy as a middle man to bypass this policy.


To use the **free CORS Proxy**, we input our free CORS Proxy URL.


(Optional part) For convenient, I’ve add a free proxy note.


When click, it will auto fill in [`https://cors-anywhere.herokuapp.com/`](https://cors-anywhere.herokuapp.com/) and open a new tab.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/99d4f8db-3d4f-4395-9600-c83491f6274d/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184855Z&X-Amz-Expires=3600&X-Amz-Signature=7d41d3ede39efc6a95f62e4913fc6c29c085256805b9436c294575833838e0aa&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/d4c2fb94-bee2-4f02-b8a7-909a80dbc0dd/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184855Z&X-Amz-Expires=3600&X-Amz-Signature=7700d7e666ee29a59a0149e0ff073201d20d6edb4bbada8ccf4f3e1e3960e91f&X-Amz-SignedHeaders=host&x-id=GetObject)


On the new tab, we will click “Request temporary access…” to allow us to use this free CORS Proxy.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/414eb1b3-945d-4ac1-9acb-5e473ab5c781/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184855Z&X-Amz-Expires=3600&X-Amz-Signature=08198102c6854fb451aea67ac49bfec7a66f1525ae0ffa69864964a9824f7be6&X-Amz-SignedHeaders=host&x-id=GetObject)


**DISCLAIMER:** 

1. **CORS Proxy is a middle man, means it can read all your requests & responses credentials. So choose a safe CORS Proxy to use, or built your own for the highest security protection.**
2. In this tutorial, we’ll use a **Free CORS Proxy URL** for the highest convenient and **accept the risk of losing our NOTION credentials (with request & response too).**
3. But to be honest I’m not afraid at all, because we’ve already **limit** our **Notion token permissions** to **Read content** with **No user information**, also the **Notion URL is a published page** (already public). So even in the worst case when we actually lose **our Notion credentials (with request & response)**, the hacker **cannot update nor delete** **anything, can it can only read my public and selected pages.**
4. If you’re still afraid about the security, you can use **your own CORS Proxy URL** or your **trusted CORS Proxy URL**, you’re very welcome to do so.
5. The only time we use this **CORS Proxy** is when we **click “Convert”** to get Notion page information, **no any other features/actions will use this CORS Proxy.**

	![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/93b315cf-572c-4d78-b3bb-d1d225239063/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184902Z&X-Amz-Expires=3600&X-Amz-Signature=a617ae92828e5ec6ec84a07bb68297d2351bb4a53d3e1a834b0ebd8d5cb619c1&X-Amz-SignedHeaders=host&x-id=GetObject)



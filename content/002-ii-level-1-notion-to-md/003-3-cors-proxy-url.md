+++
title = "3. CORS Proxy URL"
weight = 3
+++


Since our [Notion to Markdown website](https://notion-to-md.bamidev.com/) is 100% running on Github Static Pages, we **WILL NOT** save any of your information, your information always stay in your browser, all the requests will be called directly from YOUR browser.


Unfortunately, this kind of request is [violate Notion CORS policy and won’t be support](https://github.com/makenotion/notion-sdk-js/issues/96#issuecomment-852542180), but that’s ok, we will use a CORS Proxy as a middle man to bypass this policy.


To use the **free CORS Proxy**, we input our free CORS Proxy URL.


(Optional part) For convenient, I’ve add a free proxy note.


When click, it will auto fill in [`https://cors-anywhere.herokuapp.com/`](https://cors-anywhere.herokuapp.com/) and open a new tab.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/99d4f8db-3d4f-4395-9600-c83491f6274d/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=f726f1508e151a1dc2669f3850dbf1e31d3dcd3d459e9b5b2caa635e61b2c743&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/d4c2fb94-bee2-4f02-b8a7-909a80dbc0dd/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=669f82b91a5648a6dce8232c351b2c1c62090e4f0a40f8d660ab7f5aa772b7f7&X-Amz-SignedHeaders=host&x-id=GetObject)


On the new tab, we will click “Request temporary access…” to allow us to use this free CORS Proxy.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/414eb1b3-945d-4ac1-9acb-5e473ab5c781/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=0cc7c4077b0f24dfce23326426e66c45e9866991efde10320aee1b771fafb619&X-Amz-SignedHeaders=host&x-id=GetObject)


**DISCLAIMER:** 

1. **CORS Proxy is a middle man, means it can read all your requests & responses credentials. So choose a safe CORS Proxy to use, or built your own for the highest security protection.**
2. In this tutorial, we’ll use a **Free CORS Proxy URL** for the highest convenient and **accept the risk of losing our NOTION credentials (with request & response too).**
3. But to be honest I’m not afraid at all, because we’ve already **limit** our **Notion token permissions** to **Read content** with **No user information**, also the **Notion URL is a published page** (already public). So even in the worst case when we actually lose **our Notion credentials (with request & response)**, the hacker **cannot update nor delete** **anything, can it can only read my public and selected pages.**
4. If you’re still afraid about the security, you can use **your own CORS Proxy URL** or your **trusted CORS Proxy URL**, you’re very welcome to do so.
5. The only time we use this **CORS Proxy** is when we **click “Convert”** to get Notion page information, **no any other features/actions will use this CORS Proxy.**

	![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/93b315cf-572c-4d78-b3bb-d1d225239063/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191940Z&X-Amz-Expires=3600&X-Amz-Signature=c69217a0453c9e3d1691a8ee3917aa16f996a0b9be3c19b013d5127aea6d902f&X-Amz-SignedHeaders=host&x-id=GetObject)



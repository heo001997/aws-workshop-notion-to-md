+++
title = "1. Setup Github Personal Account Token"
weight = 1
+++


Open [PAT management page](https://github.com/settings/tokens?type=beta), go to Generate new token page (may require re-authentication)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/0c3bc2b7-e9ba-46d5-a4d6-cac299316d2c/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=427d752c6f3984b0b05d31e98bafac909aae30bc6288c644be9067e91871dfec&X-Amz-SignedHeaders=host&x-id=GetObject)


Fill in your selection and information


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/c0891c9f-2f78-4857-a718-1d015596639c/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=e1b6829df384b0f2e064fdd5f4747bd1514e8f75ad4cee909292211f6c7cfdf1&X-Amz-SignedHeaders=host&x-id=GetObject)


Only allow this token to have access to some repositories.


Repository access → only some repositories → Select `sample-notion-to-repo` repository.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/5e2b0d5e-8ca7-4f94-be9f-f24c6d96a07f/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=778436110aabd6973a9a8b0c89dc815ae12e95a29d9dac317152cf2049d7c677&X-Amz-SignedHeaders=host&x-id=GetObject)


It looks like this when the desired repository is selected.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/d38f6984-af3b-4949-83fa-6dece68a309f/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=e3be72acadfc13689fb4bc36d109d1312cadaac70e5b63827356ef305b5932f0&X-Amz-SignedHeaders=host&x-id=GetObject)


We **don’t need** any **Account permissions**, any only **allow ENOUGH** **Repository permissions**.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/9a8987d3-3feb-4b45-8a99-fa0871437113/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=073e0da6da16c0aa64301b963ad22666db4f4ed264be9bfff1e94b83f88a74ca&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3bd47b0f-8256-4b75-9e2d-a5b2a413842c/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=015c1fbb1f4b665829d68d6e0f9dce1a6e4b03c422f76da3e1963eaf51e3457f&X-Amz-SignedHeaders=host&x-id=GetObject)


Check the permission overview last time, generate token.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/9d877ade-6894-41aa-93ad-39d41bae56d1/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=33ccf7270f143884a0f372a13aace7c904b72ecc32b4c493529e46367462173a&X-Amz-SignedHeaders=host&x-id=GetObject)


**Please copy this PAT and save it carefully**, that note is not kidding


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/cbbda674-f5b2-426b-9a60-ea2fc6be21e5/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=1b4abf526a486e305ec0861fa8f1eecd11bae5d0de32b88067b0e6aa2e764e20&X-Amz-SignedHeaders=host&x-id=GetObject)



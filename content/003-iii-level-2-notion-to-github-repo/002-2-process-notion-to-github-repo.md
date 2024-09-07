+++
title = "2. Process Notion to Github Repo"
weight = 2
+++


Open [Notion to MD](https://notion-to-md.bamidev.com/), fill in the information and process to this step, click “Parse into Hugo Relearn”


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/7f5b08f1-9a0c-4573-9688-4753f5316016/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191935Z&X-Amz-Expires=3600&X-Amz-Signature=d839fc0e8d8ecb3fc53e932cf55155b8f2b254c6c6d42eaf89442923c6f977e7&X-Amz-SignedHeaders=host&x-id=GetObject)


It will show table “Chapter Structure”, we can preview and check if the git repository structure here with parse match with the heading inside our Notion’s page.


The repository structure will follow 2 simple rules:

1. Header H1 will always be a new directory.
2. Bigger number header will always be inside the nearest smaller header. Ex: H2 inside H1

Try not think too much about this structure yet, just follow the trial and error principle, we will be more than ok.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/734d2bdb-4d95-45fe-9301-1ca56f6bbc81/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191936Z&X-Amz-Expires=3600&X-Amz-Signature=783bb2ac4978dd348c8b0a75065864074251a445c5321530cf0e3b9a378696bb&X-Amz-SignedHeaders=host&x-id=GetObject)


Fill in the Sync to Github information, start “Sync to GitHub”


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/dd0f7f6a-7400-49c9-8d40-2cb87782831c/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191936Z&X-Amz-Expires=3600&X-Amz-Signature=0de236ade3355195224a028a78ba29287033a13331e72869666c98aeaecec003&X-Amz-SignedHeaders=host&x-id=GetObject)


(Troubleshooter) This error may occurred if you use a totally new repository with any commit.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/9ca18a8d-d4cd-42de-9754-434db4afccc0/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191936Z&X-Amz-Expires=3600&X-Amz-Signature=16ab069df1e5a237213cb0c91c8e86e8a8b4a74e2b8e7dccf09b2417eb45e850&X-Amz-SignedHeaders=host&x-id=GetObject)


Solution is to init the git repository, just use the simple git instruction is enough


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3acd0bc4-c842-4f67-9653-0918fac0c598/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191936Z&X-Amz-Expires=3600&X-Amz-Signature=b94754fa5fc544f0680b533ea063a12d79f93dc27e440ea41754ee52b0a22fab&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/24114125-4a39-44a5-9902-95060bc2a9df/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191936Z&X-Amz-Expires=3600&X-Amz-Signature=ac456ba5d9804e01e2d70720d27177b3375d81db38a8decb6eb4299881c8753d&X-Amz-SignedHeaders=host&x-id=GetObject)


If everything is good, the process will start and scroll down from step to step, when it’s done, you will see this message.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/cf47aa4a-a10a-408c-9682-35a9652f2bba/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191936Z&X-Amz-Expires=3600&X-Amz-Signature=7a5f156adb9121173c2f9141e0901a8731d8556309a28cdc1bee893bc2b12807&X-Amz-SignedHeaders=host&x-id=GetObject)


Double check the GitHub repository, you can see the `content` directory (holding contents), and `static` directory (holding images) is created ⇒ success


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/90005ad0-9a69-462e-a9ce-0fee77ab147e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T191936Z&X-Amz-Expires=3600&X-Amz-Signature=f4eac071c5f874c3de800c7668c947372dc9391a921cd12e7b2d0b3cc6a352a6&X-Amz-SignedHeaders=host&x-id=GetObject)



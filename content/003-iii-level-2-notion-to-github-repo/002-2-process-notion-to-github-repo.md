+++
title = "2. Process Notion to Github Repo"
weight = 2
+++


Open [Notion to MD](https://notion-to-md.bamidev.com/), fill in the information and process to this step, click “Parse into Hugo Relearn”


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/7f5b08f1-9a0c-4573-9688-4753f5316016/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184855Z&X-Amz-Expires=3600&X-Amz-Signature=31e5eb0c2908a2f3ece10ca15782920cc7dc9786549b6befcc09736b80048f62&X-Amz-SignedHeaders=host&x-id=GetObject)


It will show table “Chapter Structure”, we can preview and check if the git repository structure here with parse match with the heading inside our Notion’s page.


The repository structure will follow 2 simple rules:

1. Header H1 will always be a new directory.
2. Bigger number header will always be inside the nearest smaller header. Ex: H2 inside H1

Try not think too much about this structure yet, just follow the trial and error principle, we will be more than ok.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/734d2bdb-4d95-45fe-9301-1ca56f6bbc81/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184856Z&X-Amz-Expires=3600&X-Amz-Signature=3193eebf63299e1e2e33335fdf96b494a81c31cf6b1c26c33efafe63c7721f3d&X-Amz-SignedHeaders=host&x-id=GetObject)


Fill in the Sync to Github information, start “Sync to GitHub”


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/dd0f7f6a-7400-49c9-8d40-2cb87782831c/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184856Z&X-Amz-Expires=3600&X-Amz-Signature=ffd9ed35edd3b84c3b39d2ec96436a2ff5ba0dadf00ec7f699df537d6146765d&X-Amz-SignedHeaders=host&x-id=GetObject)


(Troubleshooter) This error may occurred if you use a totally new repository with any commit.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/9ca18a8d-d4cd-42de-9754-434db4afccc0/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184856Z&X-Amz-Expires=3600&X-Amz-Signature=c121b5467c5790bd48099f27780f7f28b28f2df91fcbdc4e852000788de8e016&X-Amz-SignedHeaders=host&x-id=GetObject)


Solution is to init the git repository, just use the simple git instruction is enough


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/3acd0bc4-c842-4f67-9653-0918fac0c598/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184856Z&X-Amz-Expires=3600&X-Amz-Signature=eb09c02e65112bc931bbb7d0148b509eecad74fa6e7fa178f3a1fd9c45ca70c2&X-Amz-SignedHeaders=host&x-id=GetObject)


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/24114125-4a39-44a5-9902-95060bc2a9df/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184856Z&X-Amz-Expires=3600&X-Amz-Signature=3f2deafb737ce6f264915c5ab7eff87ee5ede246d2d8b25754c04658f78c69ef&X-Amz-SignedHeaders=host&x-id=GetObject)


If everything is good, the process will start and scroll down from step to step, when it’s done, you will see this message.


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/cf47aa4a-a10a-408c-9682-35a9652f2bba/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184856Z&X-Amz-Expires=3600&X-Amz-Signature=d4843fc41cd4997f98fcea04723cf1ce9a473e800b29bb27e7ca5a7b70f7516f&X-Amz-SignedHeaders=host&x-id=GetObject)


Double check the GitHub repository, you can see the `content` directory (holding contents), and `static` directory (holding images) is created ⇒ success


![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/d5da4832-3825-4b06-9f7d-86c687d890a2/90005ad0-9a69-462e-a9ce-0fee77ab147e/image.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45HZZMZUHI%2F20240907%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20240907T184856Z&X-Amz-Expires=3600&X-Amz-Signature=da2e01ea70e8522bfa2f0481a049ece1eac489efbf26e36b4f20f2ab3b0c9fbb&X-Amz-SignedHeaders=host&x-id=GetObject)



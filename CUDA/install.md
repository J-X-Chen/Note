[cuda/cudnn安装1](https://blog.csdn.net/2302_79753801/article/details/143031547)
[cuda/cudnn安装2](https://blog.csdn.net/qq_45461410/article/details/141427213)
[更改安装路径](https://blog.csdn.net/weixin_61663117/article/details/149194285)
	
```bash
sudo cp cudnn-linux-x86_64-8.9.3.28_cuda12-archive/include/* ./cuda-12.6/include
sudo cp cudnn-linux-x86_64-8.9.3.28_cuda12-archive/lib/libcudnn* ./cuda-12.6/lib64
#或(自己改对应版本)
sudo cp cudnn-linux-x86_64-8.9.7.29_cuda11-archive/include/* ./cuda-11.3/include
sudo cp cudnn-linux-x86_64-8.9.7.29_cuda11-archive/lib/libcudnn* ./cuda-11.3/lib64
#测试
cat /usr/local/cuda-11.7/include/cudnn_version.h | grep CUDNN_MAJOR -A 2
cat /home/hill123/cuda_file/cuda-12.6/include/cudnn_version.h | grep CUDNN_MAJOR -A 2
```

	
[conda内cuda](https://blog.csdn.net/weixin_44007713/article/details/136475398)

torch安装cuda/cudnn:
1. 清华： ```-i https://pypi.tuna.tsinghua.edu.cn/simple ```
2. 阿里：```-i https://mirrors.aliyun.com/pypi/simple/```
3. [手动装包](https://blog.csdn.net/weixin_48766549/article/details/140928783)
4. pytorch对应：```-c https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/pytorch/```

其他
[xformers](https://blog.csdn.net/m0_46437343/article/details/139738920)
[github_ssh](https://blog.csdn.net/weixin_44078475/article/details/141649437)
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTU2MTcxOTAzLC0xODg4MTAwNDYyLDU5Mz
AyMTIxMl19
-->
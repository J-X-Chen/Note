https://blog.csdn.net/2302_79753801/article/details/143031547
	https://blog.csdn.net/qq_45461410/article/details/141427213
	https://blog.csdn.net/weixin_61663117/article/details/149194285
	

sudo cp cudnn-linux-x86_64-8.9.3.28_cuda12-archive/include/* ./cuda-12.6/include
sudo cp cudnn-linux-x86_64-8.9.3.28_cuda12-archive/lib/libcudnn* ./cuda-12.6/lib64

sudo cp cudnn-linux-x86_64-8.9.7.29_cuda11-archive/include/* ./cuda-11.3/include
sudo cp cudnn-linux-x86_64-8.9.7.29_cuda11-archive/lib/libcudnn* ./cuda-11.3/lib64

cat /usr/local/cuda-11.7/include/cudnn_version.h | grep CUDNN_MAJOR -A 2
cat /home/hill123/cuda_file/cuda-12.6/include/cudnn_version.h | grep CUDNN_MAJOR -A 2

	
conda内cuda https://blog.csdn.net/weixin_44007713/article/details/136475398
torch: -i https://pypi.tuna.tsinghua.edu.cn/simple 或 https://mirrors.aliyun.com/pypi/simple/
	阿里源：https://blog.csdn.net/weixin_48766549/article/details/140928783  (手动装包)
pytorch: -c https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/pytorch/

xformers: https://blog.csdn.net/m0_46437343/article/details/139738920

github_ssh: https://blog.csdn.net/weixin_44078475/article/details/141649437
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTAyMTk4NzIzNl19
-->
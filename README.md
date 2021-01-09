# HumanActionRecognition
## 下载说明：
### 建议使用gitclone方式下载，避免数据丢失现象
***
## 运行说明:
### 1. 用conda创建虚拟环境（建议使用清华源）:
#### conda create -n manActionRecognition python=3.5.4
#### conda activate manActionRecognition
***

### 2. 安装所需依赖：
#### pip install -r requirements.txt
***

### 3. 快速上手：
#### python predict_c3d_hra.py
#### 即可运行成功
#### 结果为生成 predict_ret_hra.txt预测文件
#### 该文件为识别对比清单 第一列、第三列为真实类别 和 预测类别；第二列、第四列分别为模型预测动作类型为第一列、第三列的概率大小，
#### 若第一列与第三列相同，则预测正确，反之失败。
 

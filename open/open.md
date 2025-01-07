
### 1. 開啟Anaconda Prompt

創建環境，並安裝 Python 3.8
```
conda create -n pyscpro python=3.8 -y
```
   
啟動環境
 ```
conda activate pyscpro
```
   
Clone 專案
```
git clone https://github.com/danielpalen/pysc2-rl-agents.git
```
```
cd pysc2-rl-agents
```

下載
```
conda install git
```

安裝 pysc2
```
pip install pysc2
```

安裝 tensorflow
```
pip install tensorflow-gpu  #若有 NVIDIA GPU 並支援 CUDA
```
```
pip install tensorflow #若無 GPU 或不需要 GPU 加速
```

安裝其他必要的套件
```
pip install -r requirements.txt
```






   
   * 加入`pysc2-master`

     1. 將`pysc2-master`中的`requirements`檔案存入`pysc2-rl-agents`資料夾
     2. 打開
        ```
        cd pysc2-master
        ```
     3. 安裝依賴
        ```
        pip install -r requirements.txt
        ```
     4. 安裝 `pysc2`
        ```
        pip install pysc2
        ```


4. 切換到上級目錄
```
cd ..
```
     
   

     

     
   

🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️🛰️
# TCP_HYBLA_CUBIC 
🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀

For comparison between 2 congestion control algorithm in satellite and hetegenous communication

### Team member:
1. Le Van Minh (leader)
2. Pham Chi Vy
3. Dao Duy Anh



## Architecture
### Model 1: Wired

![image](https://github.com/user-attachments/assets/912afe3f-659a-40c3-a354-f9a9fbaddfbc)

### Model 2: Satellite communcation

![image](https://github.com/user-attachments/assets/9a75106f-905d-449d-a660-4fccd02f70a6)

## Result
### Model 1: Wired
:one: **TCP Standard**

![image](https://github.com/user-attachments/assets/c17bdf4e-a815-4b6e-8102-ce347c0d0d27)

:two: **TCP HYBLA**

![image](https://github.com/user-attachments/assets/266eddef-ebe6-4a62-93a5-dec6dce202c2)

:three: **TCP CUBIC**
![image](https://github.com/user-attachments/assets/617a72e6-aefc-4142-89a1-906e3beb3606)

### Model 2: Satellite communication

:one: **Congestion window**

![image](https://github.com/user-attachments/assets/0a1efd1f-8866-4d05-bac3-f1a1c80e808c)

:two: **Throughput**
![image](https://github.com/user-attachments/assets/8399e6c2-2bec-4a3e-942f-7002e3336e8d)

:three: **Goodput**
![image](https://github.com/user-attachments/assets/c0c2e5dc-d684-4334-8f45-5972488671bf)

:owl::owl::owl::owl::owl::owl::owl::owl::owl::owl::owl::owl::owl::owl::owl::owl::owl::owl:
## Step by Step 
### 1. Install tools
* install Ubuntu
* Install NS-2
* Install nam
* Install Python (Matplotlib and OS library)

```commandline


sudo apt update
sudo apt upgrade -y
sudo apt install build-essential autoconf automake libxmu-dev -y
wget http://www.isi.edu/nsnam/dist/ns-allinone-2.35.tar.gz
./install
ns

```

### 2. Run code
:point_right: **Step 1**: Model1_wired_com

:point_right: **Step 2**: Model2_satellite_com

:point_right: **Step 3**: Plot images

## Contact
:boom: [Le Van Minh](https://github.com/VeronicaMagnus1909) :boom:







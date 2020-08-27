# denoising_UNet

### 1. [dataset](https://github.com/Kang-Dong-Hwi/denoising_UNet/blob/master/data.ipynb)

<br>
clean_data + noise_data
<br>
clean_data( clean_left, clean_right )와 noise를 zero padding된 부분이 서로 겹치지 않게 하여
<br>
총 2210개의 dataset을 만들었습니다.

<br><br>

### 2. [UNet_Denoising](https://github.com/Kang-Dong-Hwi/denoising_UNet/blob/master/UNet_Denoising.ipynb)
<br>
UNet model학습 전 데이터 전처리는<br>
data(clean)와 label(noise) 를 같이 normalization( sklearn의 StandardScaler사용 ) 했습니다.
<td>
<img src="https://github.com/Kang-Dong-Hwi/denoising_UNet/blob/master/pred_noise.png", height=400px, width=550px> 

我的环境(my ENV):
pytorch-cuda              11.7
torch                     1.13.0+cu117
torchaudio                0.13.0+cu117
torchvision               0.14.0+cu117
简介(Synopsis):
导弹M和防御弹D，速度是35m/和21m/s。只有法向有加速度，是30/s^2和35m/s^2，破片杀伤半径32米（由于1step=0.1s，真实物理中的判定效果可能比它小）。400次测试拦截率（拦截/M被毁）达到了百分之百。
导弹是固定策略：增广比例导引。

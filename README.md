
##  SILKCodec

SILK编解码是Skype开源，专门为低延迟可丢包环境设计的音频编码算法库。主要为场景为实时通讯，实际应用广泛，从微信qq的amr文件，到webrtc的Opus都能看到它的影子。


* SILK_SDK_SRC_ARM

 arm 平台

* SILK_SDK_SRC_FIX

 在浮点数计算能力不行的cpu可以尝试这个 fix。比如老旧的arm。

* SILK_SDK_SRC_FLP

 算法使用了浮点数计算，当fpu 浮点数计算能力不错，首先应该选择这个版本。比如普通pc。

* SILK_SDK_SRC_MIPS

mips 平台
 

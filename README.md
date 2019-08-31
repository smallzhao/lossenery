# 能量丢失检测程序 #
## 依赖的库 ##
FFTW3 <http://www.fftw.org>

libsndfile <https://github.com/erikd/libsndfile>

## 编译 ##
	gcc -o lossenergy spectrogram.c window.c spectrum.c common.c -I/usr/local/include -L/usr/local/lib -lfftw3 -lsndfile 
	
## andriod编译 ##

SNDFILE Building for Android <https://github.com/erikd/libsndfile/blob/master/Building-for-Android.md>

FFTW3 for Android <https://github.com/Lauszus/fftw3-android/blob/master/README.md>

Mac OS X 10.9 Android NDK r9c 编译 FFTW 3.3.3 <http://www.mobibrw.com/2014/1214>

移植FFTW到ARM平台 <https://www.veryarm.com/95295.html>

移植FFTW到ARM(android)平台 <https://blog.csdn.net/sean_xyz/article/details/44406997>

FFTW3在Android平台的移植 <https://blog.csdn.net/mingtingjie/article/details/94625566>

compiling fftw3 in android ndk <https://stackoverflow.com/questions/4201911/compiling-fftw3-in-android-ndk>
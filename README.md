Local manifests to build MoKee4.2.2 for Xiaomi Mi2.

编译方法:
-------------

1、repo init -u https://github.com/MoKee/android.git -b jb-mr1_mkt

2、curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.github.com/ysjlsw/android_local_manifest/mokee1/local_manifest.xml

3、repo sync

4、cd ~/android/mokee/vendor/mk

5、./get-prebuilts

6、cd ~/android/mokee

7、. build/envsetup.sh

8、brunch aries

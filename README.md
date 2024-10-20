# Minimal manifest to build ART for target

yeah mini  

----
1. `sudo apt-get install make python-is-python2 lib32z1`  
2. Install oracle jdk 1.6 and `export ANDROID_JAVA_HOME=/path/to/the/jdk && export PATH=$PATH:$ANDROID_JAVA_HOME/bin`  
3. `source build/envsetup.sh && lunch && m build-art-target`

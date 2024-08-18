# libstdc++6
how solve error libstdc++6 for paddleocr in Linux
error:

ImportError: /lib/x86_64-linux-gnu/libstdc++.so.6: version `GLIBCXX_3.4.30' not found (required by /home/user/Amin/lib/python3.8/site-packages/paddle/base/libpaddle.so)


1-sudo add-apt-repository ppa:ubuntu-toolchain-r/test
2-sudo apt update
3-sudo apt install g++-11

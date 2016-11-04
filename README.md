What is this?
=============

[JavaCPP](https://github.com/bytedeco/javacpp) and [JavaCPP-Presets](https://github.com/bytedeco/javacpp-presets)
bindings for Xamarin. C++->Java->C# fun!

(No, CppSharp should be your friend; it is there for my javacpp experiments
and existing bindings to those C++ libraries.)

This repository contains various jar files built by [javacpp-presets](https://github.com/bytedeco/javacpp-presets)
and its subsequent maven repository pulls.
For the record, I built rev. `2549a7d` with:

	ANDROID_NATIVE_API_LEVEL=9 ANDROID_NDK=~/android-ndk-r13/ mvn clean install -Djavacpp.platform=android-x86 -Djavacpp.platform.root=/home/atsushi/android-ndk-r13/ -Djavacpp.platform.compiler=/home/atsushi/android-ndk-r13/toolchains/x86-4.9/prebuilt/linux-x86_64/bin/i686-linux-android-g++ -X

LICENSE
=======

For all those javacpp/javacpp-presets and subsequent dependencies, check
each license terms.

Sources in this Xamarin binding project are under the MIT License.


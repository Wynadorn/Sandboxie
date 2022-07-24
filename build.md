# Build instructions
### Check your windows version:
 - `Win + R` -> `winver` -> `OK`

### Install Visual Studio:
 - [Download Visual Studio](https://visualstudio.microsoft.com/downloads/)

### Select the following workloads:
 - Desktop development with C++
 - Check the correct windows SDK version on the **right** of the Workloads tab (`Installation details` > `Desktop development with C++` > `Optional` > `Windows xx SDK (xx.x.xxxxx.x)`
 - Also ensure the `MSVC v1xx - VS 2022 C++ x64/x86 build tools (Latest)` component is checked
 - `C++ MFC for latest v143 build tools (x86 & x64)`
 
### Install the WDK for your selected Windows SDK version:
 - [Download the Windows Driver Kit (WDK)](https://docs.microsoft.com/en-us/windows-hardware/drivers/download-the-wdk) (latest win11)
 - [Other WDK downloads](https://docs.microsoft.com/en-us/windows-hardware/drivers/other-wdk-downloads) (older)
 - The WDK version shown in the installer must match the installed Windows SDK version.
 - Read through the WDK install, dont just cick next
 - *Do you need the latest SDK & WDK if you have VS2022?*

### Install qt
 - ?

### Clone the repo somewhere:
 - `git clone https://github.com/Wynadorn/Sandboxie`

### ?
 - Right click the solution -> `Retarget solution` -> Select the SDK version you're using. 

### Self-Sign the driver:
 - [How to Test-Sign a Driver Package](https://docs.microsoft.com/en-us/windows-hardware/drivers/install/how-to-test-sign-a-driver-package)
 - [Signing a Driver for Public Release](https://docs.microsoft.com/en-us/windows-hardware/drivers/develop/signing-a-driver-for-public-release)
 - [How to Sign an Unsigned Device Driver in Windows?](http://woshub.com/how-to-sign-an-unsigned-driver-for-windows-7-x64/)

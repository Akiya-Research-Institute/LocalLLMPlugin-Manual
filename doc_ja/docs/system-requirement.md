# システム要件

## 対応するUnreal Engineのバージョン

<!-- - 5.2 -->
<!-- - 5.3 -->
- 5.4

## 対応プラットフォーム

- Windows 64bit

<!-- | Platform                   | Development      | Target Build |
| -------------------------- | ---------------- | ------------ |
| Windows 64bit              | ✅               | ✅          |
| Ubuntu 22.04 Desktop 64bit | ✅(Experimental) | ✅(Experimental) | 
| Android                    |                  | ✅(Experimental) |
| iOS                        |                  |              |
| Mac                        |                  |              |

!!! Warning "プラグインのダウンロードにWindowsが必要です"
    **Windows**のEpic Games Launcherを使用してプラグインをダウンロードする必要があります。

!!! Question "テスト済みUbuntu環境"
    下記の環境でのみテスト済みです。

    - OS: Ubuntu 22.04 Desktop 64bit
    - CPU: Intel i3-8350K
    - GPU: NVIDIA GeForce GTX 1080 Ti
        - Driver: 535.113.01
    - Unreal Engine: 5.1.1, 5.2.1, 5.3.1
    - .NET SDK: 6.0.123

    他の環境で正常に動作するかは保証できないので、Ubuntuの対応状況は「Experimental」としています。

!!! Question "テスト済みAndroidデバイス"
    下記のデバイスでのみテスト済みです。
 
    - Xiaomi Redmi Note 9S

    他の環境で正常に動作するかは保証できないので、Androidの対応状況は「Experimental」としています。 -->

## ハードウェア要件

### CPU

AVX、AVX2、FMAに対応したCPUが必要です。

以下のCPUは動作するはずですが、[demo exe](../demo)を実行して、お使いのCPUがサポートされているかどうか確認してください。

- Intel: 第4世代（Haswell）以上
- AMD: すべてのRyzenシリーズ

### (Optional) GPU

CUDA 12.2.0 をサポートする NVIDIA の GPU で動作します。

!!! Info "CPUのみでも動作します"
    GPUはオプショナルであり、CPUのみでも問題なく動作します。

!!! Info "CUDAのインストール"
    GPUを利用するには、下記のバージョンのCUDAのインストールが必要です。

    - [CUDA 12.2.0](https://developer.nvidia.com/cuda-12-2-0-download-archive?target_os=Windows&target_arch=x86_64&target_version=10&target_type=exe_local)
# 会話デモ

<iframe width="560" height="315" src="https://www.youtube.com/embed/5B2f8POzytA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## ダウンロード

EXE形式のデモプロジェクトを[こちら](https://github.com/Akiya-Research-Institute/LocalLLM-Demo-UE5/releases)からダウンロードできます。

## GitHubソース

デモのUE5プロジェクトファイルを[GitHubで公開](https://github.com/Akiya-Research-Institute/LocalLLM-Demo-UE5)しています。

## ソフトウェア要件

- Windows 64bit
- Unreal Engine 5.4.2
- Local LLM plugin v1.0以上

(オプション) GPUで実行したい場合は、

- CUDA: 12.2.0

## ハードウェア要件

- AVX、AVX2、FMAに対応したCPUが必要です。

    以下のCPUは動作するはずです。

    - Intel: 第4世代（Haswell）以上
    - AMD: すべてのRyzenシリーズ

(オプション) GPUで実行したい場合は、

- CUDA 12.2.0 をサポートする NVIDIA の GPU。

## デモの使い方

デモプロジェクトには2つのマップが含まれています。

- /Content/LocalLLMDemo/Map/ChatDemo_One  
  NPC1人との会話デモ

- /Content/LocalLLMDemo/Map/ChatDemo_Multi  
  NPC2人との会話デモ

NPCに近づくと、自動的にダイアログUIが表示されます。
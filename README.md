Modified version to support MSA PBR Packing to optimise vram usage if you use liltoon with pbr.
Simply assign your MSA Texture into your AO Map, Metallic and Smoothness slots depending on which features you want to use.
Ensure to disable "sRGB (Color Texture)" on the import settings of your MSA Texture.
If you don't want to use packing, just assign your regular pbr textures like always.
<html>
<body>
<!--StartFragment-->

Texture Channel | Parameter
-- | --
Red | Metallic
Green | Smoothness
Blue | Occlusion

<!--EndFragment-->
</body>
</html>

Note: only tested in builtin render pipeline.

![image](https://user-images.githubusercontent.com/95102992/220165320-4f450e66-e77c-4bba-96e8-f30ad129d98f.png)


## English
Drag and drop unitypackage to the Unity window, or import `https://github.com/lilxyzw/lilToon.git?path=Assets/lilToon#master` from UPM.  
[Download](https://github.com/lilxyzw/lilToon/releases) / [Documentation](https://lilxyzw.github.io/lilToon/index.html#/en-us/) / [How to distribute your works that use lilToon](https://lilxyzw.github.io/lilToon/#/en-us/first?id=how-to-distribute-your-works-that-use-liltoon)

## 日本語
unitypackageをUnityウィンドウにドラッグ＆ドロップ、もしくはUPMから`https://github.com/lilxyzw/lilToon.git?path=Assets/lilToon#master`をインポートしてください。  
[ダウンロード](https://github.com/lilxyzw/lilToon/releases) / [ドキュメント](https://lilxyzw.github.io/lilToon/index.html#/ja-jp/) / [lilToonを用いた制作物の配布手順について](https://lilxyzw.github.io/lilToon/#/ja-jp/first?id=liltoonを用いた制作物の配布について)

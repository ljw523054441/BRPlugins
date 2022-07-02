# BRPlugins
### 使用方法
在Ue4项目目录下的Plugins文件夹（如果没有就新建一个）中新建BRPlugins文件夹，最后将本仓库clone至此即可。

## 日志
### 2021.11.19
1. 4.27 SSpinBox控件不再导出，所以删除了IntegerSpinBox。
2. 更新API。
3. 使用智能指针解决因为FSectionElementInfo被回收而导致FStrokeSkeletalMeshSceneProxy会崩溃的问题。

### 2021.1.28
1. 增加IntegerSpinBox控件

### 2020.12.11
1. RDG使用案例升级到4.26版本

### 2020.11.8
1. 增加了RDG使用案例
2. 增加了4.25 GlobalShader使用案例

### 2020.5.15
1. 增加了FeetAnimationModifier，并且扩展了AnimationBlueprintLibrary

### 2020.2.20
1. 增加UMG 多重进度条控件
2. 修正因为4.24渲染管线变动而造成的的错误
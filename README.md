# 搭建静态服务器

```
npm install -g live-server
live-server

```

# 场景、相机和渲染器

## 相机 camera

- PerspectiveCamera（透视摄像机）----（视野角度（FOV）,长宽比（aspect ratio）,远剪切面,近剪切面）
- OrthographicCamera(正射投影相机)

# 对象、材质、网格 Material、Mesh

## 材质

| 材质属性    | 简介                                         |
| ----------- | -------------------------------------------- |
| color       | 材质颜色，比如蓝色 0x0000ff                  |
| wireframe   | 将几何图形渲染为线框。 默认值为 false        |
| opacity     | 透明度设置，0 表示完全透明，1 表示完全不透明 |
| transparent | 是否开启透明，默认 false                     |

反射
MeshLambertMaterial // 漫反射 --常用
MeshPhongMaterial // 镜面反射

| 材质类型             | 功能                                                              |
| -------------------- | ----------------------------------------------------------------- |
| MeshBasicMaterial    | 基础网格材质，不受光照影响的材质                                  |
| MeshLambertMaterial  | Lambert 网格材质，与光照有反应，漫反射                            |
| MeshPhongMaterial    | 高光 Phong 材质,与光照有反应                                      |
| MeshStandardMaterial | PBR 物理材质，相比较高光 Phong 材质可以更好的模拟金属、玻璃等效果 |

BoxGeometry（立方体）---顶点（vertices）和面（faces）

Mesh--BoxGeometry、Material

## 光源

| 光源             | 简介               |
| ---------------- | ------------------ |
| AmbientLight     | 环境光             |
| PointLight       | 点光源             |
| DirectionalLight | 平行光，比如太阳光 |
| SpotLight        | 聚光源             |

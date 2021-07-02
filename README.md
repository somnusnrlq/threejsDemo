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

BoxGeometry（立方体）---顶点（vertices）和面（faces）

Mesh--BoxGeometry、Material

# 搭建静态服务器

```
npm install -g live-server
live-server

```

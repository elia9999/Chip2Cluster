# Interconnect Atlas

交互式硬件架构图谱：从芯片内部、封装、板卡、服务器、超节点到集群。

## 使用

直接打开 `index.html`。保留目录结构，无需联网或安装依赖。浏览器需支持 WebGL。

也可以运行本地静态服务：

```sh
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 交互

- 六个硬件层级、十二个三维场景。
- 旋转、缩放、平移、单独拖动模块及整体拆解。
- 结构树定位、层级深入、连接与散热器显隐。
- UB、RDMA、VPC 网络平面切换。
- 产品页首屏自动旋转、暂停与拆解；支持减少动态效果偏好。

## 文件

- `index.html`：页面入口。
- `assets/deck.js`、`assets/style.css`：运行代码与样式。
- `src/`：对应源码；修改后同步到 `assets/`。
- `assets/figures/`：辅助核验图片。
- `assets/sources.json`：原始图片出处。
- `vendor/`：本地 Three.js 与 MIT 许可证。

## 模型与来源

三维模型为近似教学结构，尺寸、模块数量与摆放经过简化；连线表示逻辑关系，不是工程布线图。页面参考区保留原始架构图、实物图及出处。

Third-party images retain their original owners’ rights. The Three.js license is included in `vendor/THREE-LICENSE.txt`. No blanket license is granted for third-party images by this repository.

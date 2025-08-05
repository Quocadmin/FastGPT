<div align="center">

<a href="https://fastgpt.io/"><img src="/.github/imgs/logo.svg" width="120" height="120" alt="fastgpt logo"></a>

# FastGPT

<p align="center">
  <a href="./README_en.md">English</a> |
  <a href="./README.md">简体中文</a> |
  <a href="./README_ja.md">日语</a>
</p>

FastGPT 是一个 AI Agent 构建平台，提供开箱即用的数据处理、模型调用等能力，同时可以通过 Flow 可视化进行工作流编排，从而实现复杂的应用场景！

</div>

<p align="center">
  <a href="https://fastgpt.io/">
    <img height="21" src="https://img.shields.io/badge/在线使用-d4eaf7?style=flat-square&logo=spoj&logoColor=7d09f1" alt="cloud">
  </a>
  <a href="https://doc.fastgpt.io/docs/introduction">
    <img height="21" src="https://img.shields.io/badge/相关文档-7d09f1?style=flat-square" alt="document">
  </a>
  <a href="https://doc.fastgpt.io/docs/introduction/development/intro">
    <img height="21" src="https://img.shields.io/badge/本地开发-%23d4eaf7?style=flat-square&logo=xcode&logoColor=7d09f1" alt="development">
  </a>
  <a href="/#-%E7%9B%B8%E5%85%B3%E9%A1%B9%E7%9B%AE">
    <img height="21" src="https://img.shields.io/badge/相关项目-7d09f1?style=flat-square" alt="project">
  </a>
</p>

https://github.com/labring/FastGPT/assets/15308462/7d3a38df-eb0e-4388-9250-2409bd33f6d4

## 🛸 在线使用

- 🌍 国际版：[fastgpt.io](https://fastgpt.io/)

|                                    |                                    |
| ---------------------------------- | ---------------------------------- |
| ![Demo](./.github/imgs/intro1.png) | ![Demo](./.github/imgs/intro2.png) |
| ![Demo](./.github/imgs/intro3.png) | ![Demo](./.github/imgs/intro4.png) |

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-7d09f1.svg" alt="#" align="right">
</a>

## 💡 RoadMap

`1` 应用编排能力
   - [x] 对话工作流、插件工作流，包含基础的 RPA 节点。
   - [x] Agent 调用
   - [x] 用户交互节点
   - [x] 双向 MCP 
   - [ ] 上下文管理
   - [ ] AI 生成工作流

`2` 应用调试能力
   - [x] 知识库单点搜索测试
   - [x] 对话时反馈引用并可修改与删除
   - [x] 完整调用链路日志
   - [ ] 应用评测
   - [ ] 高级编排 DeBug 调试模式
   - [ ] 应用节点日志

`3` 知识库能力
   - [x] 多库复用，混用
   - [x] chunk 记录修改和删除
   - [x] 支持手动输入，直接分段，QA 拆分导入
   - [x] 支持 txt，md，html，pdf，docx，pptx，csv，xlsx (有需要更多可 PR file loader)，支持 url 读取、CSV 批量导入
   - [x] 混合检索 & 重排
   - [x] API 知识库
   - [ ] RAG 模块热插拔
  
`4` OpenAPI 接口
   - [x] completions 接口 (chat 模式对齐 GPT 接口)
   - [x] 知识库 CRUD
   - [x] 对话 CRUD
   - [ ] 完整 API Documents
  
`5` 运营能力
   - [x] 免登录分享窗口
   - [x] Iframe 一键嵌入
   - [x] 统一查阅对话记录，并对数据进行标注
   - [ ] 应用运营日志
   
`6` 其他
   - [x] 可视化模型配置。
   - [x] 支持语音输入和输出 (可配置语音输入语音回答)
   - [x] 模糊输入提示
   - [x] 模板市场

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-7d09f1.svg" alt="#" align="right">
</a>

## 👨‍💻 开发

项目技术栈：NextJs + TS + ChakraUI + MongoDB + PostgreSQL (PG Vector 插件)/Milvus

- **⚡ 快速部署**

  > 使用 [Sealos](https://sealos.io) 服务，无需采购服务器、无需域名，支持高并发 & 动态伸缩，并且数据库应用采用 kubeblocks 的数据库，在 IO 性能方面，远超于简单的 Docker 容器部署。

  [点击查看 Sealos 一键部署 FastGPT 教程](https://doc.fastgpt.io/docs/introduction/development/sealos/)

* [快速开始本地开发](https://doc.fastgpt.io/docs/introduction/development/intro/)
* [部署 FastGPT](https://doc.fastgpt.io/docs/introduction/development/sealos/)
* [系统配置文件说明](https://doc.fastgpt.io/docs/introduction/development/configuration/)
* [多模型配置方案](https://doc.fastgpt.io/docs/introduction/development/modelConfig/one-api/)
* [版本更新/升级介绍](https://doc.fastgpt.io/docs/introduction/development/upgrading/index)
* [OpenAPI API 文档](https://doc.fastgpt.io/docs/introduction/development/openapi/)
* [知识库结构详解](https://doc.fastgpt.io/docs/introduction/guide/knowledge_base/RAG/)

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-7d09f1.svg" alt="#" align="right">
</a>

## 🏘️ 加入我们

我们正在寻找志同道合的小伙伴，加速 FastGPT 的发展。你可以通过 [FastGPT 2025 招聘](https://fael3z0zfze.feishu.cn/wiki/P7FOwEmPziVcaYkvVaacnVX1nvg)了解 FastGPT 的招聘信息。

## 💪 相关项目

- [FastGPT-plugin](https://github.com/labring/fastgpt-plugin)
- [Laf：3 分钟快速接入三方应用](https://github.com/labring/laf)
- [Sealos：快速部署集群应用](https://github.com/labring/sealos)
- [One API：多模型管理，支持 Azure、文心一言等](https://github.com/songquanpeng/one-api)

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-7d09f1.svg" alt="#" align="right">
</a>

## 🌿 第三方生态
- [PPIO 派欧云：一键调用高性价比的开源模型 API 和 GPU 容器](https://ppinfra.com/user/register?invited_by=VITYVU&utm_source=github_fastgpt)
- [AI Proxy：国内模型聚合服务](https://sealos.run/aiproxy/?k=fastgpt-github/)
- [SiliconCloud (硅基流动) —— 开源模型在线体验平台](https://cloud.siliconflow.cn/i/TR9Ym0c4)

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-7d09f1.svg" alt="#" align="right">
</a>

## 🏘️ 社区交流群

扫码加入飞书话题群：

![](https://oss.laf.run/otnvvf-imgs/fastgpt-feishu2.png)

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-7d09f1.svg" alt="#" align="right">
</a>

## 👀 其他

- [保姆级 FastGPT 教程](https://www.bilibili.com/video/BV1n34y1A7Bo/?spm_id_from=333.999.0.0)
- [接入飞书](https://www.bilibili.com/video/BV1Su4y1r7R3/?spm_id_from=333.999.0.0)
- [接入企微](https://www.bilibili.com/video/BV1Tp4y1n72T/?spm_id_from=333.999.0.0)

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-7d09f1.svg" alt="#" align="right">
</a>

## 🤝 参与贡献

我们非常欢迎各种形式的贡献。如果你对贡献代码感兴趣，可以查看我们的 GitHub [Issues](https://github.com/labring/FastGPT/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc)，大展身手，向我们展示你的奇思妙想。

<a href="https://github.com/labring/FastGPT/graphs/contributors" target="_blank">
  <table>
    <tr>
      <th colspan="2">
        <br><img src="https://contrib.rocks/image?repo=labring/FastGPT"><br><br>
      </th>
    </tr>
    <tr>
      <td>
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-org-active-contributors/thumbnail.png?activity=active&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=2x3&color_scheme=dark">
          <img alt="Active participants of labring - past 28 days" src="https://next.ossinsight.io/widgets/official/compose-org-active-contributors/thumbnail.png?activity=active&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=2x3&color_scheme=light">
        </picture>****
      </td>
      <td rowspan="2">
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-org-participants-growth/thumbnail.png?activity=new&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=4x7&color_scheme=dark">
          <img alt="New trends of labring" src="https://next.ossinsight.io/widgets/official/compose-org-participants-growth/thumbnail.png?activity=new&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=4x7&color_scheme=light">
        </picture>
      </td>
    </tr>
    <tr>
      <td>
        <picture>
          <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-org-active-contributors/thumbnail.png?activity=new&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=2x3&color_scheme=dark">
          <img alt="New participants of labring - past 28 days" src="https://next.ossinsight.io/widgets/official/compose-org-active-contributors/thumbnail.png?activity=new&period=past_28_days&owner_id=102226726&repo_ids=605673387&image_size=2x3&color_scheme=light">
        </picture>
      </td>
    </tr>
  </table>
</a>

## 🌟 Star History

<a href="https://github.com/labring/FastGPT/stargazers" target="_blank" style="display: block" align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=labring/FastGPT&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=labring/FastGPT&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=labring/FastGPT&type=Date" />
  </picture>
</a>

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-7d09f1.svg" alt="#" align="right">
</a>

## 使用协议

本仓库遵循 [FastGPT Open Source License](./LICENSE) 开源协议。

1. 允许作为后台服务直接商用，但不允许提供 SaaS 服务。
2. 未经商业授权，任何形式的商用服务均需保留相关版权信息。
3. 完整请查看 [FastGPT Open Source License](./LICENSE)
4. 联系方式：Dennis@sealos.io，[点击查看商业版定价策略](https://doc.fastgpt.io/docs/introduction/commercial/)


1. FastGPT là gì?
FastGPT là một nền tảng mã nguồn mở giúp bạn tạo ra các AI Agent, chatbot, hoặc ứng dụng AI tự động hóa mà không cần biết lập trình phức tạp.

Nó giúp bạn kéo-thả (flow) để xây dựng các luồng xử lý dữ liệu và hội thoại AI, phù hợp từ cá nhân, doanh nghiệp nhỏ cho tới đội nhóm lớn, muốn ứng dụng AI vào quy trình làm việc thực tế.

2. FastGPT dành cho ai?
Người mới: Dùng AI chat, xây dựng bot hỏi đáp từ tài liệu cá nhân, upload file PDF, tài liệu Word, website, v.v.

Công ty, tổ chức: Xây dựng trợ lý ảo, tư vấn khách hàng, tự động hóa công việc (RPA) mà không cần thuê developer riêng.

Lập trình viên: Dễ dàng phát triển tính năng mở rộng, tích hợp API, làm plugin hoặc tự quản lý dữ liệu AI.

3. Tính năng nổi bật
🌟 Xây dựng workflow AI bằng Flow (kéo-thả)
Dùng giao diện trực quan, kéo-thả các khối chức năng (node) để xử lý hội thoại, dữ liệu, plugin, tích hợp với nhiều nguồn khác nhau.

Hỗ trợ workflow phức tạp, đa bước, tự động hóa xử lý dữ liệu, chat, trả lời khách hàng.

🏪 Hỗ trợ kiến thức đa dạng, tích hợp RAG
Dễ dàng upload và quản lý kiến thức cá nhân: PDF, Word, PowerPoint, Excel, file txt, md, html, CSV, url trang web,...

Dùng RAG (Retrieval-Augmented Generation): AI không chỉ dựa vào kiến thức chung mà còn lấy thông tin từ tài liệu bạn cung cấp.

Mix nhiều nguồn tri thức cùng lúc, hỗ trợ tra cứu đa nguồn.

🤖 Hỗ trợ đa mô hình AI và tích hợp API
Gọi các model mạnh nhất hiện nay: GPT-3.5/4, Claude, Wenxin, Azure, OpenRouter... tùy chọn cấu hình, chuyển đổi linh hoạt.

Có thể tích hợp và tự phát triển plugin, API nội bộ.

Tích hợp với các dịch vụ lưu trữ dữ liệu (MongoDB, PostgreSQL, Milvus...)

🛠️ Dành cho phát triển & mở rộng
Có OpenAPI để kết nối với hệ thống bên ngoài hoặc tích hợp với sản phẩm, website khác.

Cho phép debug, ghi log chi tiết, quản lý version, kiểm thử ứng dụng AI dễ dàng.

Có sẵn template marketplace – kho mẫu bot, workflow dùng lại.

🗣️ Hỗ trợ nhập/xuất giọng nói
Có thể nói chuyện trực tiếp với AI bằng giọng nói hoặc cho AI trả lời bằng âm thanh (text-to-speech, speech-to-text).

🖥️ Chạy online hoặc tự host
Có thể dùng bản online tại fastgpt.io – chỉ cần đăng ký tài khoản, không cần server.

Hoặc deploy riêng trên cloud, Docker, Sealos... tự quản lý hoàn toàn dữ liệu.

4. Ứng dụng thực tế
Bot hỏi đáp tài liệu nội bộ, tài liệu công ty (hỏi chính sách, tài liệu hướng dẫn, quy trình...)

Tự động hóa quy trình kinh doanh: Kết nối với CRM, ERP, trả lời tự động theo luồng.

Tư vấn khách hàng đa kênh: nhúng vào web, iframe, chia sẻ link, lưu nhật ký chat...

Nâng cấp trợ lý AI cá nhân: học và trả lời dựa trên dữ liệu riêng, không lo lộ thông tin.

5. Cách sử dụng, triển khai nhanh
Dùng online: Truy cập https://fastgpt.io/ để thử ngay, không cần cài đặt.

Tự triển khai:

Dùng dịch vụ Sealos (đơn giản, không cần server riêng).

Hoặc tự cài đặt trên máy bằng Docker, Next.js, cấu hình database theo hướng dẫn.

Xem hướng dẫn chi tiết tại đây

6. Lý do nên chọn FastGPT?
Cực kỳ dễ dùng, không cần code phức tạp, kéo-thả xây workflow, tự động hóa công việc với AI.

Miễn phí, mã nguồn mở, bạn làm chủ hoàn toàn dữ liệu và tính năng.

Cộng đồng mạnh, hỗ trợ tốt, có nhiều video hướng dẫn chi tiết (bảo mẫu).

Tích hợp tốt với các nền tảng AI hiện đại và dịch vụ lưu trữ lớn.

Hỗ trợ phát triển, mở rộng, có sẵn plugin, OpenAPI, template.

7. Các tài nguyên hữu ích
Tài liệu chính thức

Video hướng dẫn siêu dễ

Nhóm chat cộng đồng (Feishu)

Các dự án liên quan & plugin mở rộng

Tóm lại
FastGPT là nền tảng kéo-thả để xây dựng chatbot, agent AI thông minh, dễ dùng, đa năng, dùng online hoặc tự host, hỗ trợ tích hợp tài liệu, workflow, API, phù hợp cho cả người mới và dân kỹ thuật.

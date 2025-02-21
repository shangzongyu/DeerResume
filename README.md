# DeerResume

最好用的 Markdown 在线简历工具，可在线预览、编辑、设置访问密码和生成 PDF

- 可自行搭建，任意修改页面样式和风格
- 免安装，可放置于任何支持静态页面的云和服务器 (当然包括 GitHub)
- 在线 Markdown 编辑器+实时预览
- 在浏览器中实时保存草稿
- 支持阅读密码，您可以直接将网址和密码发送，供招聘方在线浏览
- 一键生成简单雅致的 PDF，供邮件发送及打印

部署指南：→ <http://get.ftqq.com/745.get>

更好用的在线 Markdown 简历 <http://link.ftqq.com/0rsRL>

教学：《如何写好一份技术简历》→ <http://link.ftqq.com/KWkVX>

## FAQ

如何在没有云端的情况下使用 DeerResume？

- 请在可访问云端的情况下完成 Markdown 的编辑，然后复制好简历内容。
- 修改 app.js 注释掉第 3 行，打开第 4 行，将数据源切到本地。
- 修改 data.php 填入标题和内容，并按自己的需要设置阅读密码。

如何在本地修改样式保存 PDF？

- 在 resume.html 中加入如下代码

   ```js
    <style>
      @media print {
        .site-head,.action-bar {
          display: none;
        }
      }
    </style>
    ```

- 在 chrome 中打开网页
- 右键该简历网页选择打印
- 目标打印机改成另存为 PDF
- 保存

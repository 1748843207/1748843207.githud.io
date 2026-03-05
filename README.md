<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的个人主页</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            盒模型: 边框盒;
            字体族: “微软雅黑”, 无衬线;
        }
        body {
            背景: #1a1a1d;
            color: #fff;
            最小高度: 100视口高度;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            文本对齐: 居中;
            内边距: 20像素;
        }
        .avatar {
            宽度: 120像素;
            高度: 120像素;
            border-radius: 50%;
            background: #4e4e50;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 40px;
        }
        h1 {
            字体大小: 28像素;
            margin-bottom: 10px;
        }
        .desc {
            color: #aaa;
            margin-bottom: 30px;
            最大宽度: 500像素;
        }
        .links a {
            display: inline-block;
            margin: 8px 12px;
            padding: 10px 20px;
            background: #6a6a6a;
            color: #fff;
            border-radius: 8px;
            text-decoration: none;
            transition: 0.3s;
        }
        .links a:hover {
            background: #00adb5;
        }
        footer {
            margin-top: 50px;
            颜色: #666;
            字体大小: 14像素;
        }
    </样式>
</头>
<body>

    <div class="avatar">👤</div>
    <h1>我的个人主页</h1>
    <p class="desc">热爱技术、喜欢分享、简单干净的个人小站</p >

    <div class="links">
        <a href=" ">GitHub</a >
        <a href="https://space.bilibili.com/">B站</a >
        <a href="mailto:your@email.com">邮箱</a >
    </div>

    <footer>© 2026 我的个人网站</footer>

</正文>
</html>

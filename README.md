- 👋 Hi, I’m @lyxx123456
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
lyxx123456/lyxx123456 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<!-- 添加视口设置，支持移动设备的响应式 -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>梁宇轩的趣味空间</title>
<style>
    /* 通用样式重置 */
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    /* 增加字体图标库，用于社交链接等 */
    @import url('https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css');

    body {
        font-family: Arial, 'Microsoft Yahei', sans-serif;
        background-color: #f0f0f0;
        line-height: 1.6;
    }

    /* 容器响应式调整 */
    .container {
        max-width: 800px;
        margin: 30px auto;
        padding: 20px;
        background-color: white;
        box-shadow: 0 0 10px rgba(0,0,0,0.1);
        transition: all 0.3s ease;
    }

    /* 添加媒体查询，实现响应式布局 */
    @media screen and (max-width: 600px) {
        .container {
            margin: 10px;
        }
        h1 {
            font-size: 2.5em;
        }
    }

    h1 {
        color: #3498db;
        text-align: center;
        font-size: 3em;
        margin-bottom: 30px;
        animation: fadeInDown 2s ease-in-out;
    }

    p {
        font-size: 1.2em;
    }

    img {
        display: block;
        margin: 20px auto;
        max-width: 100%;
        border-radius: 5%;
        box-shadow: 0 0 10px rgba(0,0,0,0.2);
        animation: zoomIn 1s ease-in-out;
    }

    /* 动画保持不变 */
    @keyframes fadeInDown {
        from {opacity: 0; transform: translateY(-20px);}
        to {opacity: 1; transform: translateY(0);}
    }
    @keyframes zoomIn {
        from {opacity: 0; transform: scale(0.5);}
        to {opacity: 1; transform: scale(1);}
    }

    /* 新增社交图标样式 */
    .social-icons {
        display: flex;
        justify-content: center;
        gap: 10px;
        margin-top: 20px;
    }
    .social-icons a {
        color: #6c757d;
        font-size: 1.5em;
        transition: color 0.3s ease;
    }
    .social-icons a:hover {
        color: #3498db;
    }
</style>
</head>
<body>

<div class="container">
    <header>
        <!-- 添加页眉元素，包括logo或标题描述 -->
        <h1>欢迎来到梁宇轩的星球！🚀</h1>
        <p>探索技术、分享生活、记录成长的每一个瞬间</p>
    </header>

    <!-- 主体内容区 -->
    <main>
        <!-- 个人信息卡片 -->
        <section class="profile-card">
            <img src="http://picture.gptkong.com/20240502/77b42be202db4e6fafcd7742b106f2eb.jpg" alt="梁宇轩的照片">
            <div class="profile-info">
                <h2>梁宇轩</h2>
                <p>生于2006年1月19日 | 江苏徐州</p>
                <p>幽默大师 | 技术探索者 | 生活记录者</p>
            </div>
        </section>

        <!-- 教育经历 -->
        <section class="education">
            <h2>教育之旅</h2>
            <ul>
                <li>
                    <strong>铜山区实验小学</strong> - 启蒙之地
                </li>
                <li>
                    <strong>清华中学</strong> - 知识的海洋
                </li>
                <li>
                    <strong>郑集中学城区分校</strong> - 青春的舞台
                </li>
                <li>
                    <strong>哈尔滨铁道职业技术学院</strong> - 专业探索的起点
                </li>
            </ul>
        </section>
    </main>

    <!-- 页脚包含社交链接 -->
    <footer>
        <div class="social-icons">
            <!-- 示例链接，请替换为实际社交账号链接 -->
            <a href="#"><i class="fab fa-weibo"></i></a>
            <a href="#"><i class="fab fa-github"></i></a>
            <a href="#"><i class="fab fa-linkedin"></i></a>
        </div>
        <p>&copy; 2023 梁宇轩的趣味空间. All rights reserved.</p>
    </footer>

    <!-- 移动到页脚前的JavaScript代码保持不变 -->
    <script>
        // JavaScript代码保持原样
    </script>
</div>
</body>
</html>
<!DOCTYPE html>
<html lang="zh">
<head>
    ... <!-- 上一阶段的头部内容保持不变 -->
    
    <!-- 引入jQuery库，简化AJAX和DOM操作 -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
    
    <!-- 新增懒加载图片的占位符样式 -->
    <style>
        .lazy-img {
            width: 100%;
            padding-bottom: 75%; /* 维持宽高比 */
            background: #eee url("data:image/gif;base64,R0lGODlhEAAQAMQAAORHHOVSKudfOulrSOp3WOyDZu6QdvCchPGolfO0o/XBs/fNwfjZ0frl3/zy7////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAkAABAALAAAAAAQABAAAAVVICSOZGlCQAosJ6mu7fiyZeKqNKToQGDsM8hBADgUXoGAiqhSvp5QAnQKGIgUhwFUYLCVDFCrKUE1lBavAViFIDlTImbKC5Gm2hB0SlBCBMQiB0UjIQA7") no-repeat center; /* 使用透明的gif作为加载中的占位图 */
        }
    </style>
</head>
<body>
    ... <!-- 上一阶段的主体内容保持不变 -->

    <!-- 动态加载内容区域 -->
    <section id="content-loader">
        <div class="loading-spinner"></div> <!-- 加载动画 -->
    </section>

    <!-- 评论系统 -->
    <section id="comments">
        <h2>读者评论</h2>
        <div id="comment-list">
            <!-- 评论内容将通过AJAX动态加载 -->
        </div>
        <form id="comment-form">
            <input type="text" placeholder="您的名字" required>
            <textarea placeholder="分享您的想法..." required></textarea>
            <button type="submit">发表评论</button>
        </form>
    </section>

    <!-- 页脚保持不变 -->

    <!-- 新增脚本部分 -->
    <script>
        $(document).ready(function() {
            // 使用AJAX异步加载内容
            loadContent();
            
            // 监听评论表单提交事件
            $('#comment-form').on('submit', function(e) {
                e.preventDefault();
                var name = $('input[type="text"]').val();
                var comment = $('textarea').val();
                postComment(name, comment);
                $('input[type="text"], textarea').val(''); // 清空表单
            });
            
            // 懒加载图片
            const observer = new IntersectionObserver((entries, observer) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        const img = entry.target;
                        img.src = img.dataset.src;
                        img.onload = () => {
                            img.classList.remove('lazy-img');
                        };
                        observer.unobserve(img);
                    }
                });
            }, { threshold: 0.5 });

            $('.lazy-img').each(function() {
                observer.observe(this);
            });
        });

        function loadContent() {
            $.ajax({
                url: "content.json", // 假设内容数据存储在content.json文件中
                method: "GET",
                dataType: "json",
                beforeSend: function() {
                    $("#content-loader").show(); // 显示加载动画
                },
                success: function(data) {
                    $("#content-loader").hide(); // 隐藏加载动画
                    // 使用data动态填充页面内容，这里仅作示例
                    $("#content-loader").html("<h2>" + data.title + "</h2><p>" + data.content + "</p>");
                },
                error: function(jqXHR, textStatus, errorThrown) {
                    console.error("加载内容出错: ", textStatus, errorThrown);
                }
            });
        }

        function postComment(name, comment) {
            $.ajax({
                url: "post-comment.php", // 假设这是处理评论的后端脚本
                method: "POST",
                data: { name: name, comment: comment },
                success: function(response) {
                    // 假设后端返回最新评论的HTML，直接追加到评论列表
                    $("#comment-list").append(response);
                },
                error: function(jqXHR, textStatus, errorThrown) {
                    console.error("发表评论出错: ", textStatus, errorThrown);
                }
            });
        }
    </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Birthday Card</title>
    <!-- 样式表 -->
    <style>
        body {
            background-color: #FFDAB9; /* 背景颜色 */
            margin: 0;
            overflow: hidden;
            position: relative;
            font-family: 'Courier New', Courier, monospace; /* 字体 */
        }
        video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover; /* 视频覆盖整个屏幕 */
            z-index: -1; /* 视频位于最底层 */
        }
        audio {
            display: none; /* 隐藏音频控件 */
        }
        .card-container {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh; /* 卡片容器占满整个视口高度 */
        }
        .card {
            text-align: center;
            background-color: rgba(255, 255, 255, 0.8); /* 半透明白色背景 */
            padding: 20px;
            border-radius: 15px; /* 圆角边框 */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* 阴影效果 */
            position: relative;
            z-index: 1; /* 卡片位于视频之上 */
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 10px; /* 图片圆角 */
        }
        .message {
            margin-top: 20px;
            font-size: 2em; /* 消息字体大小 */
            color: #8B008B; /* 消息颜色 */
        }
    </style>
</head>
<body>
   
    </video>
    <!-- 背景音乐 -->
    <audio controls id="musicPlayer" autoplay>
        <source src="下载_20241126_21502073.mp3" type="audio/mpeg"> <!-- 音乐文件路径 -->
        Your browser does not support the audio element.
    </audio>
    <!-- 生日卡片容器 -->
    <div class="card-container">
        <div class="card">
            <!-- 生日蛋糕图片 -->
            <img id="cakeImage" src="20241126215610.jpg" alt="Birthday Cake"> <!-- 图片文件路径 -->
            <!-- 祝福消息 -->
            <div class="message" id="message"></div>
        </div>
    </div>

    <!-- JavaScript脚本 -->
    <script>
        // 祝福消息数组
        const messages = ["Happy birthday", "Make a wish"];
        let currentIndex = 0;
        let currentMessageIndex = 0;
        const messageElement = document.getElementById('message');
        const cakeImage = document.getElementById('cakeImage');
        const videoElement = document.getElementById('backgroundVideo');
        const musicPlayer = document.getElementById('musicPlayer');

        // 设置视频透明度
        videoElement.style.opacity = 0.5;

        // 设置音乐音量为最大
        musicPlayer.volume = 100;

        // 打字机效果函数
        function typeWriter() {
            if (currentIndex < messages[currentMessageIndex].length) {
                messageElement.innerHTML += messages[currentMessageIndex].charAt(currentIndex);
                currentIndex++;
                setTimeout(typeWriter, 100); // 打字速度（毫秒）
            } else {
                currentIndex = 0;
                currentMessageIndex++;
                if (currentMessageIndex < messages.length) {
                    setTimeout(() => {
                        messageElement.innerHTML = ''; // 清空前一条消息
                        typeWriter();
                    }, 1000); // 延迟开始下一条消息（毫秒）
                }
            }
        }

        typeWriter();

        // 尝试自动播放音乐
        window.onload = function() {
            try {
                musicPlayer.play();
            } catch (e) {
                console.log("Autoplay failed:", e);
            }
        };

        // 显示音频控件（如果需要调试）
        // window.onload = function() {
        //     musicPlayer.style.display = 'block';
        // };
    </script>
</body>
</html>




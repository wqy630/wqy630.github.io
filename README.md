<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>红色时代成就展</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: "Microsoft YaHei", sans-serif;
            background-color: #f8f9fa;
            color: #333;
        }
        /* 头部样式 */
        header {
            background: linear-gradient(135deg, #c72c41, #801336);
            color: white;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        .title {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            font-weight: 700;
        }
        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        /* 容器样式 */
        .container {
            max-width: 1200px;
            margin: 3rem auto;
            padding: 0 1.5rem;
        }
        /* 成就卡片样式 */
        .achievements {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        .card {
            background: white;
            border-radius: 8px;
            padding: 2rem;
            box-shadow: 0 4px 15px rgba(0,0,0,0.05);
            border-top: 4px solid #c72c41;
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
        }
        .card-title {
            color: #c72c41;
            font-size: 1.5rem;
            margin-bottom: 1rem;
            display: flex;
            align-items: center;
        }
        .card-title::before {
            content: "★";
            margin-right: 0.8rem;
            font-size: 1.2rem;
        }
        .card-content {
            line-height: 1.8;
            color: #555;
            font-size: 1rem;
        }
        /* 底部样式 */
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 1.5rem 0;
            margin-top: 5rem;
        }
        /* 响应式调整 */
        @media (max-width: 768px) {
            .title {
                font-size: 2rem;
            }
            .card {
                padding: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1 class="title">红色时代 辉煌成就</h1>
        <p class="subtitle">中国共产党领导下的革命、建设与改革征程</p>
    </header>

    <div class="container">
        <div class="achievements">
            <!-- 成就卡片1 -->
            <div class="card">
                <h2 class="card-title">新民主主义革命胜利</h2>
                <p class="card-content">领导人民推翻“三座大山”，取得抗日战争、解放战争胜利，1949年建立中华人民共和国，实现民族独立和人民解放，为中华民族伟大复兴奠定根本社会条件。</p>
            </div>

            <!-- 成就卡片2 -->
            <div class="card">
                <h2 class="card-title">社会主义制度建立</h2>
                <p class="card-content">通过三大改造确立社会主义基本制度，实现中国历史上最深刻最伟大的社会变革，为当代中国一切发展进步提供根本政治前提和制度基础。</p>
            </div>

            <!-- 成就卡片3 -->
            <div class="card">
                <h2 class="card-title">经济建设跨越式发展</h2>
                <p class="card-content">从“一五”计划奠定工业基础，到改革开放后经济腾飞，成为世界第二大经济体，建立独立完整的工业体系和国民经济体系，人民生活水平显著提高。</p>
            </div>

            <!-- 成就卡片4 -->
            <div class="card">
                <h2 class="card-title">科技创新重大突破</h2>
                <p class="card-content">“两弹一星”、载人航天、深海探测、高铁技术、5G通信等领域达到世界领先水平，科技自立自强成为国家发展核心支撑。</p>
            </div>

            <!-- 成就卡片5 -->
            <div class="card">
                <h2 class="card-title">文化教育繁荣发展</h2>
                <p class="card-content">普及九年义务教育，高等教育进入大众化阶段，传承中华优秀传统文化，加强社会主义精神文明建设，文化软实力持续增强。</p>
            </div>

            <!-- 成就卡片6 -->
            <div class="card">
                <h2 class="card-title">社会民生持续改善</h2>
                <p class="card-content">建立覆盖城乡的社会保障体系，在就业、医疗、养老、住房等领域取得显著成效，脱贫攻坚战取得全面胜利，人民获得感幸福感安全感不断提升。</p>
            </div>
        </div>
    </div>

    <footer>
        <p>红色时代成就展 | 传承红色基因 续写时代华章</p>
    </footer>
</body>
</html>

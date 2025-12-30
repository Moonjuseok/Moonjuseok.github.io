<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>문주석 | Firmware Developer</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1 class="logo">M.JuSeok</h1>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <section id="hero">
        <div class="hero-content">
            <h2>Hello, I'm <span class="highlight">Moon Ju-seok</span></h2>
            <p>Hardware와 Software를 잇는 펌웨어 개발자입니다.</p>
            <a href="#projects" class="btn">프로젝트 보기</a>
        </div>
    </section>
    <section id="about" class="container section-padding">
        <h2 class="section-title">About Me</h2>
        <div class="about-grid">
            <div class="about-text">
                <p>
                    효율적이고 안정적인 임베디드 시스템을 구축하는 것에 열정을 가진 개발자 문주석입니다.<br>
                    하드웨어 제어부터 최적화 알고리즘까지, 시스템의 심장을 설계합니다.
                </p>
                <ul class="info-list">
                    <li><strong>Age:</strong> 만 27세</li>
                    <li><strong>Role:</strong> Firmware Developer</li>
                    <li><strong>Focus:</strong> Embedded System, MCU Control</li>
                </ul>
            </div>
        </div>
    </section>
    <section id="skills" class="bg-dark section-padding">
        <div class="container">
            <h2 class="section-title">Tech Stack</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <i class="fa-solid fa-c"></i>
                    <h3>C / C++</h3>
                    <p>메모리 관리, 포인터 연산, 임베디드 시스템 제어</p>
                </div>
                <div class="skill-card">
                    <i class="fa-brands fa-python"></i>
                    <h3>Python</h3>
                    <p>데이터 분석, 자동화 스크립트 작성, 테스트 환경 구축</p>
                </div>
                <div class="skill-card">
                    <i class="fa-solid fa-microchip"></i>
                    <h3>Verilog</h3>
                    <p>FPGA 설계, 디지털 회로 로직 구현 및 시뮬레이션</p>
                </div>
            </div>
        </div>
    </section>
    <section id="projects" class="container section-padding">
        <h2 class="section-title">Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <h3>MCU 기반 제어 시스템</h3>
                <p class="tech-tag">C Language</p>
                <p>RTOS를 활용한 실시간 센서 데이터 처리 및 모터 제어 펌웨어 개발.</p>
            </div>
            <div class="project-card">
                <h3>FPGA 신호 처리기</h3>
                <p class="tech-tag">Verilog</p>
                <p>고속 신호 처리를 위한 디지털 필터 설계 및 타이밍 시뮬레이션.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Moon Ju-seok. All Rights Reserved.</p>
    </footer>

</body>
</html>

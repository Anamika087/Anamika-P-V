<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Anamika Portfolio</title>

<style>
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: #0a192f;
    color: white;
}

/* HEADER */
header {
    text-align: center;
    padding: 40px;
}

header h1 {
    color: #64ffda;
}

/* SECTION */
.section {
    padding: 40px;
}

.section h2 {
    color: #64ffda;
    margin-bottom: 20px;
}

/* SKILLS */
.skills {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 15px;
}

.skill {
    background: #112240;
    padding: 15px;
    border-radius: 8px;
    text-align: center;
}

/* PROJECTS */
.projects {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
}

.card {
    background: #112240;
    padding: 20px;
    border-radius: 10px;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-10px);
}

.card img {
    width: 100%;
    border-radius: 5px;
    margin-top: 10px;
}

.card h3 {
    color: #ccd6f6;
}

.card p {
    color: #8892b0;
    font-size: 14px;
}
</style>
</head>

<body>

<header>
    <h1>Anamika P V</h1>
    <p>M.Tech VLSI & Embedded Systems | PCB Design | STM32</p>
</header>

<!-- SKILLS -->
<div class="section">
    <h2>Skills</h2>
    <div class="skills">
        <div class="skill">STM32, Arduino, ESP</div>
        <div class="skill">Embedded C, Verilog</div>
        <div class="skill">PCB Design (Altium)</div>
        <div class="skill">UART, SPI, I2C</div>
        <div class="skill">IoT Systems</div>
    </div>
</div>

<!-- PROJECTS -->
<div class="section">
    <h2>Projects</h2>
    <div class="projects">

        <div class="card">
            <h3>Digital Voltmeter</h3>
            <p>STM32 based voltmeter with custom PCB and OLED display.</p>
            <img src="pcb1.png">
            <img src="schematic1.png">
        </div>

        <div class="card">
            <h3>Air Quality Monitoring</h3>
            <p>STM32 system using MQ sensors with PCB implementation.</p>
            <img src="pcb2.png">
        </div>

        <div class="card">
            <h3>DC-DC Converter</h3>
            <p>Bidirectional converter with STM32 control and PCB design.</p>
            <img src="pcb3.png">
        </div>

        <div class="card">
            <h3>IoT System</h3>
            <p>ESP8266 based monitoring and control system.</p>
        </div>

    </div>
</div>

</body>
</html>

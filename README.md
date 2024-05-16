<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Stopwatch</title>
    <link rel="stylesheet" href="styles1.css">
</head>
<body style="background-image: url('https://thumbs.dreamstime.com/z/countdown-timer-twenty-seconds-minutes-modern-style-isolated-white-background-206843549.jpg');">
    <div class="stopwatch">
        <h1 class="stopwatch-label">Stopwatch</h1>
        <div id="display">00:00:00</div>
        <button id="startStop" onclick="startStop()">Start</button>
        <button id="reset" onclick="reset()">Reset</button>
        <button id="lap" onclick="lap()">Lap</button>
        <ul id="laps"></ul>
    </div>
    <script src="script.js"></script>
</body>
</html>

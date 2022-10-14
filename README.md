# painting-app

Create Painting App using JS

canvas : canvas API 의 창
canvas API : JS로 크래픽을 그릴수 있게 해주는 API
context(ctx) : 브러쉬(붓)
ctx.fillRect(x좌표, y좌표, 가로길이, 세로길이); -> 사각형 만든다
->>
rect(x좌표, y좌표, 가로길이, 세로길이); + ctx.stroke() : 선만 그리기 / ctx.fill() : 색으로 채우기
->>
ctx.moveTo : ctx를 움직인다
ctx.lineTo : 선을 긋는다
ctx.arc() : 원 만들기

event.offsetX, event.offsetY : canvas 안에서의 좌표
ctx.beginPath(x좌표, y좌표, radius, startAngle, endAngle); : 이전의 경로를 끊고 새 경로를 만든다

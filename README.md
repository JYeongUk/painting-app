# ๐จ Painting App

์๋ฐ์คํฌ๋ฆฝํธ๋ฅผ ์ค์  ํ๋ก๊ทธ๋จ ๊ฐ๋ฐ์ ์ ์ฉํด๋ณด๊ธฐ ์ํ ๋ฏธ๋ ํ๋ก์ ํธ ์๋๋ค.

## ๐ธ App View

<p align="center"><img src="img/img.png" width="600" /></p>

## ๐งโ๐ป ๊ธฐ์  ์คํ

1. HTML
2. CSS
3. JavaScript

## ๐งโ๐ป ํ๋ก์ ํธ ์  ๊ณต๋ถํ ๋ด์ฉ

1. Canvas API
   - JS์ HTML canvas ์๋ฆฌ๋จผํธ๋ก ๊ทธ๋ํฝ์ ๊ทธ๋ฆฌ๊ธฐ์ํ ์๋จ์ ์ ๊ณตํ๋ค.
   - ์ฌ์ฉ ๋ฐฉ๋ฒ
     - JS๋ก \<canvas>์ ์ฐธ์กฐ๋ฅผ ์ป๊ณ ,
     - HTMLCanvasElement.getContext() ๋ก ๋๋ก์ ์ปจํ์คํธ๋ฅผ ์ป๋๋ค. (2์ฐจ์ ๋ ๋๋ง ์ปจํ์คํธ ์ฌ์ฉ)
     ```html
     <!-- HTML -->
     <canvas class="canvas"></canvas>
     ```
     ```javascript
     // JavaScript
     const canvas = document.querySelector(".canvas");
     const ctx = canvas.getContext("2d");
     ```
2. Path (๊ฒฝ๋ก)
   - ์ ๋ค์ ์งํฉ
   - ์ ์ ํ ๋ถ๋ถ์ผ๋ก ์ฐ๊ฒฐ๋์ด ์ฌ๋ฌ๊ฐ์ง ๋ํ, ๊ณก์ ์ ์ด๋ฃจ๊ณ  ๋๊ป์ ์์ ๋ํ๋ธ๋ค.
   - ๊ฒฝ๋ก๋ ํ์ ๊ฒฝ๋ก(sub-path)๋ ๋ซํ ์ ์๋ค.
3. fillRect()
   - ์บ๋ฒ์ค์ ์ฌ๊ฐํ(rectangle)์ ๊ทธ๋ ค์ค๋ค.
   - ํ๋ผ๋ฏธํฐ : x์ขํ, y์ขํ, ๋๋น, ๊ธธ์ด
   - ์ด๋ rect() ์ fill() ์ ํฉ์น ๋ฉ์๋์ด๋ค.
   ```javascript
   ctx.fillRect(10, 10, 100, 100);
   ```
4. fill(), stroke()
   - stroke() : ์  ๊ทธ๋ฆฌ๊ธฐ
   - fill() : ์ ์ฑ์ฐ๊ธฐ
5. moveTo(), lineTo()
   - moveTo() : ๊ฒฝ๋ก๊ฐ ์์๋  ์ขํ๋ฅผ ์ค์ ํ๋ค.
   - lineTo() : ๊ฒฝ๋ก๊ฐ ๋๋๋ ์ขํ๋ฅผ ์ค์ ํ๋ค.
6. arc()
   - ์ ๋ง๋ค๊ธฐ
   - ํ๋ผ๋ฏธํฐ : x์ขํ, y์ขํ, ๋ฐ์ง๋ฆ, ์์ ๊ฐ๋, ๋ ๊ฐ๋
   ```javascript
   ctx.arc(100, 75, 50, 0, 2 * Math.PI);
   ```
7. beginPath()
   - ์ด์ ์ ๊ฒฝ๋ก๋ฅผ ๋๊ณ  ์ ๊ฒฝ๋ก๋ฅผ ๋ง๋ ๋ค.
8. offsetX, offsetY
   - ์ด๋ฒคํธ ๋์ ๊ฐ์ฒด์์์ ์๋์  ๋ง์ฐ์ค x, y์ขํ ์์น๋ฅผ ๋ฐํํ๋ค.
   - offset : ์ด๋ฒคํธ๊ฐ ๊ฑธ๋ ค ์๋ DOM๊ฐ์ฒด๋ฅผ ๊ธฐ์ค์ผ๋ก ์ขํ๋ฅผ ์ถ๋ ฅ

## โ๐ป ๊ณต๋ถํ ๊ฐ์

- [Nomad Coders](https://nomadcoders.co/javascript-for-beginners-2)

## โ๐ป ์ฐธ๊ณ  ์๋ฃ

- [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- [CanvasRenderingContext2D](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D)
- [HTMLCanvasElement.getContext()](https://developer.mozilla.org/ko/docs/Web/API/HTMLCanvasElement/getContext)
- [HTMLCanvasElement.arc()](https://www.w3schools.com/tags/canvas_arc.asp)

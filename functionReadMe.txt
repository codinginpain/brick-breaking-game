//canvas basic
ctx.beginPath(); //instructions start
    ctx.rect(20, 40, 50, 50); // rect:rectangle start from 20px, 40px away from (left), (top) (width) 50 (height) 50
    ctx.fillStyle = "#FF0000";   //filling color red
    ctx.fill(); // fill
    ctx.closePath(); //instructions end

    ctx.beginPath();
    ctx.arc(240, 160, 20, 0, Math.PI*2, false); // arc coordinates of arc's center (x,y) (radius) (start,finish angel) (false(default) clockwise); 
    ctx.fillStyle = "green";
    ctx.fill();
    ctx.closePath();

    ctx.beginPath();
    ctx.rect(160, 10, 100, 40);
    ctx.strokeStyle = "rgba(0, 0, 255, 0.5)"; // color only for outer stroke, not inside
    ctx.stroke(); // 
    ctx.closePath();
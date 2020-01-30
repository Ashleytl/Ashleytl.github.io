---
layout: post
title: CODE ON KHAN ACADEMY - FACE DRAWING
date: 2020-01-30
categories: article
tags: writing
---

## CODE ON KHAN ACADEMY - FACE

 > 假期学习

可汗学院的课程，难易程度恰当，可挑战，可完成。不会太容易，也不会太难，在挑战的舒适区。

最后完成画脸的作业，眉毛眼睛鼻子难了点，直接找出课程关于这三部分的指引，复制粘贴code。当然，移动位置花不少时间。刚开始不知道怎么移动，心里总是忍不住直接擦掉重新在对的地方手画出来。

通过此次练习学习了如下程序：

### Shapes （形状）
x y即代表的是纵横轴。w,h是宽度高度。

>rect(x, y, w, h)  
ellipse(x, y, w, h)  
line(x1, y1, x2, y2)  
arc(x, y, w, h, start, stop)

### Colors (颜色）

这里颜色填充，为何有stroke呢，主要针对直线，因为直线是没有空间去fill，所以不能用fill语法去填充。

>background(r, g, b)  
Set the background color  
fill(r, g, b)  
Set the fill color for shapes  
noFill()  
Turn off fill for shapes  
stroke(r, g, b)  
Set the outline color for shapes  
strokeWeight(thickness)  
Change the thickness of lines and outlines  
noStroke()  
Turn off outlines for shapes  
color(r, g, b)  
Store a color in a variable

## Codes - Final work

    // hair ?
    noStroke();
    fill(153, 112, 112);
    ellipse(207, 180, 126, 94);
    ellipse(210, 225, 147, 94);
    ellipse(210, 260, 147, 94);
    // Draw the face
    fill(255, 255, 255);
    stroke(0, 0, 0);
    ellipse(210, 220, 100, 141);
    // add curly bangs
    fill(173, 127, 10);
    stroke(199, 132, 32);
    ellipse(210, 165, 95, 40);
    // smile 
    stroke(128, 45, 161);
    noFill();
    arc(213, 255, 49, 45, 0, 180);
    // nose 
    /*** nose ***/
   
        ellipseMode(CORNERS);
        stroke(180, 110, 65);
        strokeWeight(1);
        strokeWeight(2);
        noFill();
        
        beginShape();
        
            curveVertex(200, 180);      // this point guides the top (beginning) of the node curve
            curveVertex(210, 210);      // the middle two points that direct
            curveVertex(210, 250);      // the shape of the curve
            curveVertex( 45, 180);      // this point guides the bottom (end) of the nose curve
            
        endShape();
        
     // eyes
     fill(138, 61, 61);
     ellipse(180, 210, 200, 200);
     ellipse(225, 212, 243, 201);

![51580401579_ pic](https://user-images.githubusercontent.com/11972077/73471237-ed0abc00-4380-11ea-9eb0-a772af36927d.jpg)

        

### 更像我的图画（可能），调整了鼻子及脸型


    // hair ?
    noStroke();
    fill(153, 112, 112);
    ellipse(207, 180, 126, 94);
    ellipse(210, 225, 147, 94);
    ellipse(210, 260, 147, 94);

    // Draw the face
    fill(255, 255, 255);
    stroke(0, 0, 0);
    ellipse(210, 225, 115, 137);

    // add curly bangs
    fill(173, 127, 10);
    stroke(199, 132, 32);
    ellipse(210, 165, 95, 40);
    
    // smile 
    stroke(128, 45, 161);
    noFill();
    arc(213, 255, 49, 45, 0, 180);

    // nose 
    
    /*** nose ***/
       
        ellipseMode(CORNERS);
        stroke(180, 110, 65);
        strokeWeight(1);
        strokeWeight(2);
        noFill();
        
        beginShape();
        
            curveVertex(200, 180);      // this point guides the top (beginning) of the node curve
            curveVertex(212, 220);      // the middle two points that direct
            curveVertex(208, 249);      // the shape of the curve
            curveVertex( 45, 180);      // this point guides the bottom (end) of the nose curve
            
        endShape();
        
    // eyes
    fill(138, 61, 61);
    ellipse(180, 210, 200, 200);
    ellipse(225, 212, 243, 201);

        
![71580401774_ pic](https://user-images.githubusercontent.com/11972077/73471256-f7c55100-4380-11ea-9196-e8e90c3757d1.jpg)

-  Changelog 完成 20200130



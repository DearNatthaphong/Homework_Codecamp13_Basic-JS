### Codecamp # 13
    1. นาย ณัฐพงษ์ ทองพึง
    2. Basic JS Part 2_Functions Lab # 23
        2.1 จงเขียน method draw(int n)ให้ print ออกมาในกรณีที่ n มีค่าต่างๆได้ผลลัพธ์ดังนี้

                                  ---*---
                   --*--          --***--
        -*-        -***-          -*****-
        ***        *****          *******
        -*-        -***-          -*****-
                   --*--          --***--
                                  ---*---
                           
        n=2          n=3            n=4


// 1 ค่า 2n-1 เป็นตัวกำหนดจำนวนแถว
// 2 ค่า 2n-1 เป็นตัวกำหนดจำนวนที่อยู่ในแถว
// 3 ถ้า  y<n, x<n, x+y<=n || 
        y<n, x>n, x-y>=n ||
        y>n, x<n, y-x>=n ||
        y>n, x>n, x+y>=3*n

        ให้พิมพ์ - 
        // 4 ถ้าไม่ใช่ข้อ 3 ให้พิมพ์ *
ื
n=3
    y<n
        x<n      x+y<=n
            x1y1 1+1=2
            x1y2 1+1=3
            x1y2 1+2=3
        x>n      x-y>=n
            x4y1 4-1=3
            x5y1 5-1=4
            x5y2 5-2=3
    y>n
        x<n      y-x>=n
            x1y4 4-1=3
            x1y5 5-1=4
            x2y5 5-2=3
        x>n      x+y>=3*n
            x5y4 5+4=9
            x4y5 4+5=9
            x5y5 5+5=10
    
    y<n
        x<n
            x2y2 2+2=4
        x>n
            x4y2 4-2=2
    y>n
        x<n
            x2y4 4-2=2
        x>n
            x4y4 4+4=8

    



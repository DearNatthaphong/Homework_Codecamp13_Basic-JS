### Codecamp # 13
    1. นาย ณัฐพงษ์ ทองพึง
    2. Basic JS Part 2_Logical operators Lab # 4
        2.1 คำสัง alert ไหนที่จะถูกรันบ้าง
        - if (-1 || 0) alert('first'); 
        // ถูกรัน เพราะ เงื่อนไขเป็น true
        - if (-1 && 0) alert('second');
        // ไม่ถูกรัน เพราะ เงื่อนไขเป็น false (true && false)
        - if (null || -1 && 0) alert('third');
        // ไม่ถูกรัน เพราะ เงื่อนไขเป็น false (false || true && false)

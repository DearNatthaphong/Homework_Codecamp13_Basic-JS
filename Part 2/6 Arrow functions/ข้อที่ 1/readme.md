### Codecamp # 13
    1. นาย ณัฐพงษ์ ทองพึง
    2. Basic JS Part 2_Arrow functions Lab # 1
        2.1 แปลง function ข้างล่างให้อยู่ในรูป arrow function

        function ask(question,yes,no) {
            if(confirm(question)) yes()
            else no();
        }

        ask(
            "Do you agree?",
            function() { alert("You agreed.")},
            function() { alert("You canceled the execution."); }
        );


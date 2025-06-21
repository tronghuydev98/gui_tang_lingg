<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Người anh thương</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <div class="container">
        <div class="envelope-wrapper flap">
            <div class="envelope">
                <div class="letter">
                    <div class="text">
                        <strong>Người đẹp nhất trần gian </strong>
                        <p>Anh không biết đây có phải là lúc thích hợp không…
Nhưng anh biết nếu không nói, anh sẽ tiếc.Anh thích cách em cười, cách em quan tâm mọi thứ – và cả cách em khiến ngày của anh trở nên khác đi.
Nếu em cho phép… anh muốn là người ở bên em, mỗi ngày sau này.
                        </p>
                        <p>Em đồng ý cho anh được làm người đồng hành chính thức của em nha !</p>
                    </div>
                </div>
            </div>
            <div class="heart"></div>
        </div>
    </div>
    <script>
        const envelope = document.querySelector('.envelope-wrapper');
        envelope.addEventListener('click', () => {
            envelope.classList.toggle('flap');
        });
    </script>
</body>

</html>

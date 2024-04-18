<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>길안내 링크</title>
    <script>
        // 티맵 길안내 함수
        function tMap(name, lat, lng) {
            location.href = "https://apis.openapi.sk.com/tmap/app/routes?appKey=l7xx7179ddde21ca4bfb8e6b03c710138f41&name=" + name + "&lon=" + lng + "&lat=" + lat;
        }
    </script>
</head>
<body>
    <!-- 길안내 링크 -->
    <a href="javascript:tMap('신월4동주민센터','37.5246971','126.8400793');">신월4동주민센터로 길안내 시작</a>
</body>
</html>

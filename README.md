<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirecting...</title>
    <script>
        document.addEventListener('DOMContentLoaded', function () {
            const params = new URLSearchParams(window.location.search);
            const targetUrl = params.get('url');
            if (confirm('您即將離開本公司網站，是否繼續？')) {
                // click 'Yes' for URL
                window.location.href = targetUrl;
            } else {
                // click 'No' for URL
                window.location.href = 'https://www.tcfhc-sec.com.tw/index.aspx';
            }
        });
    </script>
</head>
<body>
    <p>Redirecting...</p>
</body>
</html>

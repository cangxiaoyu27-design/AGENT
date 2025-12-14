<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>ACCESS RESTRICTED</title>
</head>
<body style="background:black; color:white; text-align:center; margin-top:30vh;">

<h1>ACCESS RESTRICTED</h1>

<p>認証コードを入力してください</p>

<input type="password" id="pw">
<br><br>
<button onclick="check()">認証</button>

<p id="msg"></p>

<script>
function check() {
  if (document.getElementById("pw").value === "AGENT") {
    window.location.href = "https://www.notion.so/2c9e9cb506cf8094aee8dcd6a197bab5?source=copy_link";
  } else {
    document.getElementById("msg").innerText = "ACCESS DENIED";
  }
}
</script>

</body>
</html>

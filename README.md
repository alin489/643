# 643<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>菜鸟教程(runoob.com)</title>
</head>
<body>

<form id="frm1" action="form_action.asp" method="get">
First name: <input type="text" name="fname" value="Donald"><br>
Last name: <input type="text" name="lname" value="Duck"><br>
<input type="submit" value="提交">
</form>
<p>发送表单数据的方法：
<script>
document.write(document.getElementById("frm1").method);
</script>
</p>

</body>
</html>

# formtable
<!DOCTYPE html>
<html lang="ko">
<head>
	<meta charset="UTF-8">
	<title> Test04_table_01</title>
	<link rel="stylesheet" type = "text/css"href="./css/form.css">

</head>
<body>
     <h2 class="header"> 성일정보고 2학년 13반 19번 정하은입니다 </h2>
	<form name="data" action="http://localhost.login.php"method="post">
	<table>
<caption><strong> 나의 이력사항입니다</strong></caption>
	<tr>
	<th><span>*</span>성명</th>
	<td><input type="text" size="20" name="name"></td>	
	<th><span>*</span>전화번호</th>
	<td><input type="text" size="20" name="phon"></td>
    </tr>
	<tr>
	<th>학교</th>
	<td><input type="text" size="20" name="name"></td>
	<th>학번</th>
	<td><input type="text" size="20" name="phon"></td>
    </tr>
	<tr>
	<th><span>*</span>장래희망</th>
	<td><input type="text" size="20" name="name"></td>
	<div class="id">

	<th>특기</th>
	<td><input type="text" size="20" name="phon"></td>
    </tr>
    <tr>
	<th><span>*</span>비밀번호</th>
	<td><input type="text" size="20" name="pw"></td>
	<th><span>*</span>비밀번호 확인</th>
	<td><input type="text" size="20" name="pw_r"></td>
    </tr>
    <tr>
	<th><span>*</span>이메일</th>
	<td><div class"email">
	<input type="text" size = "15" name="email_id"> 
	@
	<select name="email_domain">
	<option value = "1">naver.com</option>
	<option value = "2">gmail.com</option>
	<option value = "3">다음</option>
	</select>
	</td>
	<th><span>*</span>남여구분</th>
	<td><input type="radio" name="man_div" value"1">남
		<input type="radio" name="man_div" value"2">여</td>
	</td>
	</tr>
	<tr>
	<td colspan = "4" align="center">
	<span>*</span>부분은 필수 입력사항 입니다. 
	<input type="submit" value = "등록하기">
	<input type="submit" value = "취소하기">
	</td>
	</tr>
</table>
</form>
     </body>
</html>

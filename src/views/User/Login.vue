<template>
<div>
 <h1>사용자 정보를 입력하세요.</h1>
<form name="user" method="post" action="/regist">
  <div class="input-row">
    <label for="userid">아이디</label>
    <input id="userid" name="userid" type="text">
  </div>
  <div class="input-row">
    <label for="name">이름</label>
    <input id="name" name="name" type="text">
  </div>
  <div class="input-row">
    <label for="address">주소</label>
    <input id="address" name="address" type="text">
  </div>
  <button type="submit">전송</button>
</form>
</div>
</template>
## 1.
post 방식으로 integer 타입 점수 등록
>[post] /users/addscore
<pre>
{
     
    'score': 1
}


</pre>

## 2.

get 방식으로 유저의 username과 score 가져오기
> [get] /users/getuserdata
<pre>
{
    'username' : 'kimgildong',
    'score' : '1'

}

</pre>

## 3.

로그인 안된 사용자의 에러 메세지
> [post] /users/login
# 실패
<pre>
{
    'login' : 'fail'
}

</pre>

## 4.
요청에 대한 성공과 실패 메시지
>[post] /users/info

# 성공
<pre>
{
    'score' : 1

}
</pre>

# 실패
<pre>
{
    'message':'서버 오류가 발생했습니다.'

}
</pre>

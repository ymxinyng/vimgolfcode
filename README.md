# vimgolfcode
### 1번코드
  GWi"<End>"<Esc>ZZ
  
코드설명: G:맨뒤로 W:단어의 시작 위치로 커서 이동 i:현재 커서가 위치한 문자의 앞에 ("를 Insert)후 <End>키로 맨마지막칸으로 이동후 "를 insert해주는 코드입니다.
  
### 2번코드
    :%s/sublime\|emacs/vim/g<CR>ZZ
  
 :%s를 이용하여 sublime과 emacs로된 단어를 vim 으로 바꿔주는 코드입니다.
  
### 3번코드
      :4<CR>yawO// TODO<Esc>BPyyjpwdwwywbPZZ
  
  :4<CR>을 이용하여 4번째줄로 이동한다음 yaw를 이용하여 Version(한단어)를 복사한뒤 
  P를 이용하여 // TODO 사이에 붙여넣어주고 yy를 이용하여 // Version TODO를 복사하여 P를 이용해 문장사이에 붙여넣은뒤 
  Version을 dw를 이용하여 삭제한뒤 yw를이용하여 Debug(한단어)를 복사한뒤 P를 이용하여 붙여넣기해주는 코드입니다.
  
### 4번코드
     :%s/y1/abs(y1)<CR>:5s/1/4/g<CR>:4s/1/3/g<CR>:3s/1/2/g<CR>/k<CR>rbnrrnrgZZ
   
  
  :%s/y1/abs(y1)<CR>를 이용하여 y1이란 단어를 abs로 바꿔준다음 
  :5s/1/4/g<CR>를 이용하여 5번째줄에 1이란 글자를 모두 4로 바꿔주고
  :4s/1/3/g<CR>를 이용하여 4번째줄에 1이란 글자를 모두 3으로 바꿔주고
  :3s/1/2/g<CR>를 이용하여 3번째줄에 1이란 글자를 모두 2로바꿔준다음
  /k<CR>을 이용하여 k란 글자를 찾은다음 r을 이용해 한글자씩 바꿔는 코드입니다.
  
  
### 5번코드
  :8<CR><C-V><Up><Up><Right><Right><Right><Right>yGBa<Esc>p3J:10s/:" \|: /,/g<CR>:5<CR>ywGWWa<Esc>pa,<End>"<CR><Esc>ZZ
  
  :8<CR><C-V><Up><Up><Right><Right><Right><Right>를 이용하여 8번째줄부터 블럭 단위로 여러 줄 선택한다음
  y를 이용하여 해당블록들을 복사한뒤
  G를이용하여 맨마지막으로가서 B를 이용하여 이전 단어 마지막으로로 이동한뒤
  P를 이용하여 복사한내용을 붙여놓고 
  3J를 이용하여 3줄을 한줄로 만들어준다음
  10s/:" \|: /,/g<CR>를 이용하여 :" 과: 로된 단어를 ,로 바꿔주었고
  :5<CR>ywGWWa<Esc>pa,<End>"<CR>를 이용하여 5번째줄에서 커서에위치한 단어인 Student_id를 복사해와 붙여넣고 <End>를이용하여 마지막으로 이동한다음 "처리 해주는 코드입니다.
 

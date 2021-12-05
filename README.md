# vimgolfcode
### 1번코드
![image](https://user-images.githubusercontent.com/94737280/144739820-e7958374-47ba-438d-a35c-457ff9d7b1e4.png)
  
코드설명: G:맨뒤로 W:단어의 시작 위치로 커서 이동 i:현재 커서가 위치한 문자의 앞에 ("를 Insert)후 <End>키로 맨마지막칸으로 이동후 "를 insert해주는 코드입니다.
  
### 2번코드
![image](https://user-images.githubusercontent.com/94737280/144739814-45e806c2-0584-4fe4-8c18-e2500e2fadd2.png)
  
 :%s를 이용하여 sublime과 emacs로된 단어를 vim 으로 바꿔주는 코드입니다.
  
### 3번코드
   ![image](https://user-images.githubusercontent.com/94737280/144739807-dc166499-ca08-426a-b3e0-09d654921a02.png)
  
  :4<CR>을 이용하여 4번째줄로 이동한다음 yaw를 이용하여 Version(한단어)를 복사한뒤 
  P를 이용하여 // TODO 사이에 붙여넣어주고 yy를 이용하여 // Version TODO를 복사하여 P를 이용해 문장사이에 붙여넣은뒤 
  Version을 dw를 이용하여 삭제한뒤 yw를이용하여 Debug(한단어)를 복사한뒤 P를 이용하여 붙여넣기해주는 코드입니다.
  
### 4번코드
  ![image](https://user-images.githubusercontent.com/94737280/144739797-636f4083-3043-4bef-bf97-2fbfe553d611.png)

   
  
  :%s/y1/abs(y1)<CR>를 이용하여 y1이란 단어를 abs로 바꿔준다음 
  :5s/1/4/g<CR>를 이용하여 5번째줄에 1이란 글자를 모두 4로 바꿔주고
  :4s/1/3/g<CR>를 이용하여 4번째줄에 1이란 글자를 모두 3으로 바꿔주고
  :3s/1/2/g<CR>를 이용하여 3번째줄에 1이란 글자를 모두 2로바꿔준다음
  /k<CR>을 이용하여 k란 글자를 찾은다음 r을 이용해 한글자씩 바꿔는 코드입니다.
  
  
### 5번코드
  ![image](https://user-images.githubusercontent.com/94737280/144739780-6d643c14-d858-4e67-a9c0-7137db91c7d8.png)

  
  :8<CR><C-V><Up><Up><Right><Right><Right><Right>를 이용하여 8번째줄부터 블럭 단위로 여러 줄 선택한다음
  y를 이용하여 해당블록들을 복사한뒤
  G를이용하여 맨마지막으로가서 B를 이용하여 이전 단어 마지막으로로 이동한뒤
  P를 이용하여 복사한내용을 붙여놓고 
  3J를 이용하여 3줄을 한줄로 만들어준다음
  10s/:" \|: /,/g<CR>를 이용하여 :" 과: 로된 단어를 ,로 바꿔주었고
  :5<CR>ywGWWa<Esc>pa,<End>"<CR>를 이용하여 5번째줄에서 커서에위치한 단어인 Student_id를 복사해와 붙여넣고 <End>를이용하여 마지막으로 이동한다음 "처리 해주는 코드입니다.
 

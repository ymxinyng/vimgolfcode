# vimgolfcode
### 1번코드
![image](https://user-images.githubusercontent.com/94737280/144749341-3e02ff5f-b06b-4ca6-bbdc-e39e04d9dea0.png)  
코드설명: G:맨뒤로 W:단어의 시작 위치로 커서 이동 i:현재 커서가 위치한 문자의 앞에 ("를 Insert)후 <End>키로 맨마지막칸으로 이동후 "를 insert해주는 코드입니다.
 ![vimgolf1_gif gif_000001920](https://user-images.githubusercontent.com/94737280/144749168-48bf3c04-a43e-4a65-b7ce-d85c400f1abc.gif)

  
### 2번코드
![image](https://user-images.githubusercontent.com/94737280/144749385-74c47350-fa54-4508-a921-7f780246da34.png)  

s를 이용하여 sublime과 emacs로된 단어를 vim 으로 바꿔주는 코드입니다.
   :%![vimgolf2_gif gif_000001560](https://user-images.githubusercontent.com/94737280/144749173-34f0e158-9217-49af-ae53-c2bca5328b02.gif)
  
### 3번코드
![image](https://user-images.githubusercontent.com/94737280/144749416-a50189ab-50ae-4fa5-9ec6-251280a045c3.png)
  
  :4<CR>을 이용하여 4번째줄로 이동한다음 yaw를 이용하여 Version(한단어)를 복사한뒤 
  P를 이용하여 // TODO 사이에 붙여넣어주고 yy를 이용하여 // Version TODO를 복사하여 P를 이용해 문장사이에 붙여넣은뒤 
  Version을 dw를 이용하여 삭제한뒤 yw를이용하여 Debug(한단어)를 복사한뒤 P를 이용하여 붙여넣기해주는 코드입니다.
  ![vimgolf3_GIF gif_000000920](https://user-images.githubusercontent.com/94737280/144749188-8c130540-6605-4cf5-948d-a1da7bf43cfe.gif)

  
  
### 4번코드
![image](https://user-images.githubusercontent.com/94737280/144749435-4ee00908-c8e4-43e7-8b84-1c7031f9f32f.png)
   
  
  :%s/y1/abs(y1)<CR>를 이용하여 y1이란 단어를 abs로 바꿔준다음 
  :5s/1/4/g<CR>를 이용하여 5번째줄에 1이란 글자를 모두 4로 바꿔주고
  :4s/1/3/g<CR>를 이용하여 4번째줄에 1이란 글자를 모두 3으로 바꿔주고
  :3s/1/2/g<CR>를 이용하여 3번째줄에 1이란 글자를 모두 2로바꿔준다음
  /k<CR>을 이용하여 k란 글자를 찾은다음 r을 이용해 한글자씩 바꿔는 코드입니다.
  
  
  ![vimgolf4_gif gif_000001320](https://user-images.githubusercontent.com/94737280/144749194-964b0f5c-3c06-4f84-a48e-59b1ef53211a.gif)

  
### 5번코드
  
![image](https://user-images.githubusercontent.com/94737280/144749456-dc687c67-09a2-4b4d-93ba-30157e66dd3d.png)

  
  :8<CR><C-V><Up><Up><Right><Right><Right><Right>를 이용하여 8번째줄부터 블럭 단위로 여러 줄 선택한다음
  y를 이용하여 해당블록들을 복사한뒤
  G를이용하여 맨마지막으로가서 B를 이용하여 이전 단어 마지막으로로 이동한뒤
  P를 이용하여 복사한내용을 붙여놓고 
  3J를 이용하여 3줄을 한줄로 만들어준다음
  10s/:" \|: /,/g<CR>를 이용하여 :" 과: 로된 단어를 ,로 바꿔주었고
  :5<CR>ywGWWa<Esc>pa,<End>"<CR>를 이용하여 5번째줄에서 커서에위치한 단어인 Student_id를 복사해와 붙여넣고 <End>를이용하여 마지막으로 이동한다음 "처리 해주는 코드입니다.
 
![vimgolf5_gif gif_000000970](https://user-images.githubusercontent.com/94737280/144749225-f37a5c80-5b48-4c05-bf4d-e1be2400130c.gif)

  

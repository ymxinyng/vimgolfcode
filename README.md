# vimgolfcode
# 코드1
![image](https://user-images.githubusercontent.com/94737280/144749341-3e02ff5f-b06b-4ca6-bbdc-e39e04d9dea0.png)  

### 코드설명

**G**:맨뒤로 **W**:단어의 시작 위치로 커서 이동 

**i**:현재 커서가 위치한 문자의 앞에 "를 Insert 후 

End키로 맨마지막칸으로 이동후 "를 insert해주는 코드입니다.
 
 ![vimgolf1_gif gif_000001920](https://user-images.githubusercontent.com/94737280/144749168-48bf3c04-a43e-4a65-b7ce-d85c400f1abc.gif)

  
# 코드2
 
![image](https://user-images.githubusercontent.com/94737280/144749385-74c47350-fa54-4508-a921-7f780246da34.png)  
 
### 코드설명
 
:%s를 이용하여 sublime과 emacs로된 단어를 vim 으로 바꿔주는 코드입니다.
 
   ![vimgolf2_gif gif_000001560](https://user-images.githubusercontent.com/94737280/144749173-34f0e158-9217-49af-ae53-c2bca5328b02.gif)
  
# 코드3
 
![image](https://user-images.githubusercontent.com/94737280/144749416-a50189ab-50ae-4fa5-9ec6-251280a045c3.png)
  
 ### 코드설명
 
 :4<CR>을 이용하여 4번째줄로 이동한다음 
 
 **yaw**를 이용하여 **Version(한단어)를 복사**한뒤 
 
 **P**를 이용하여 **// TODO 사이에 붙여넣어**주고 
 
 **yy**를 이용하여 **// Version TODO**를 복사하여 
 
 **P**를 이용해 **문장사이에 붙여넣은**뒤 
 
 **Version**을 **dw**를 이용하여 **삭제**한뒤 
 
 **yw**를이용하여 **Debug(한단어)를 복사**한뒤 
 
 **P**를 이용하여 **붙여넣기**해주는 코드입니다.
 
 
 ![vimgolf3_GIF gif_000000920](https://user-images.githubusercontent.com/94737280/144749188-8c130540-6605-4cf5-948d-a1da7bf43cfe.gif)

  
  
# 코드4
 
![image](https://user-images.githubusercontent.com/94737280/144749435-4ee00908-c8e4-43e7-8b84-1c7031f9f32f.png)
   
 ### 코드설명
 
  :%s/y1/abs(y1)<CR>를 이용하여 **y1**이란 단어를 **abs로 바꿔**준다음 
 
  :5s/1/4/g<CR>를 이용하여 **5번째줄에 1**이란 글자를 모두 **4로 바꿔**주고
 
  :4s/1/3/g<CR>를 이용하여 **4번째줄에 1**이란 글자를 모두 **3으로 바꿔**주고
 
  :3s/1/2/g<CR>를 이용하여 **3번째줄에 1**이란 글자를 모두 **2로바꿔**준다음
 
  /k<CR>을 이용하여 **k**란 글자를 찾은다음 **r**을 이용해 **한글자씩 바꿔**주는 코드입니다.
  
  
  ![vimgolf4_gif gif_000001320](https://user-images.githubusercontent.com/94737280/144749194-964b0f5c-3c06-4f84-a48e-59b1ef53211a.gif)

  
# 코드5
  
![image](https://user-images.githubusercontent.com/94737280/144749456-dc687c67-09a2-4b4d-93ba-30157e66dd3d.png)

  ### 코드설명
 
  :8<CR><C-V><Up><Up><Right><Right><Right><Right>를 이용하여 **8번째줄부터 블럭 단위**로 여러 줄 선택한다음
 
  **y**를 이용하여 해당**블록들을 복사**한뒤
 
  **G**를이용하여 맨마지막으로가서 
 
  **B**를 이용하여 **이전 단어 마지막으로로 이동**한뒤
 
  **P**를 이용하여 복사한내용을 **붙여넣고**
 
  **3J**를 이용하여 **3줄을 한줄로** 만들어준다음
 
  10s/:" \|: /,/g<CR>를 이용하여 **:" 과: 로된** 단어를 **,로 바꿔**주었고
 
  :5<CR>ywGWWa<Esc>pa,<End>"<CR>를 이용하여 **5번째줄에서 커서에위치**한 단어인 **Student_id를 복사해와 붙여넣고**
 
  End를이용하여 **마지막으로 이동**한다음 "처리 해주는 코드입니다.
 
 
![vimgolf5_gif gif_000000970](https://user-images.githubusercontent.com/94737280/144749225-f37a5c80-5b48-4c05-bf4d-e1be2400130c.gif)

  

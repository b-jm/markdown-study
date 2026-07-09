마크다운 문법 정리
-

---

1. ***Headers***
- 큰 제목: 문서 제목
```
H1 Headers
===
```

- 작은 제목: 문서 부제목
```
H2 Headers
---
```

- 글머리: 1 ~ 6까지만 지원
```
# Headers H1
## Headers H2
### Headers H3
#### Headers H4 
##### Headers H5
###### Headers H6
```

---
H1 Headers
=
H2 Headers
-
# Headers H1
## Headers H2
### Headers H3
#### Headers H4
##### Headers H5
###### Headers H6

---
2. ***BlockQuote***
```
> first blockqute.
> > second blockqute.
> > > third blockqute.
```

---
> first blockqute.
> > second blockqute.
> > > third blockqute.

> ### Headers H3
>- list  
> ``` java ```
> ``` 
> code

---
3. ***List***
```
1. one
2. two
3. three
```
```
* one
    * two
        * three
        
+ one
    + two
        + three

- one
    - two
        - three
```

---
1. one
2. two
3. three

- one
  - two
    - three

---
4. ***줄바꿈***  
```
줄 바꿈을 하기 위해서는 문장 마지막에 3칸 이상 띄어쓰기 한다.   
이렇게
```

---
줄 바꿈을 하기 위해서는 문장 마지막에 3칸 이상 띄어쓰기 한다.   
이렇게

---
5. ***들여쓰기***
```
start code block.

    code block.

end code block.
```
한줄 띄어쓰지 않으면 인식이 제대로 안되는 문제 발생

---
start code block.

    code block.

end code block.

문제 발생 예시

start code block.
  code block.
end code block.

---
6. ***코드 블럭***

``` <pre><code>{code}</code></pre>```
```
<pre>
<code>
public class Test {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
</code>
</pre>
```

```
``` 사용
``` 

````
```
public class Test {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```
````

사용 언어 선언
````
``` java
public class Test {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```
````

---
```
public class Test {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

``` java
public class Test {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

---
7. ***수평선***
```
* * *
***
*****
---
- - -
------------
```

---
8. ***링크***
```
Link: [Git](https://github.com/b-jm)
Blog: <https://b-jm.tistory.com/>
```

Link: [GitHub](https://github.com/b-jm)  
Blog: <https://b-jm.tistory.com/>

---
9. ***강조***
```
one person
*one person*
_one person_
**two**
__two__
~~two~~
```

one person  
*one person*  
_one person_  
**two**  
__two__  
~~two~~

---
10. **이미지**
```
![대체 텍스트](이미지 주소 "이미지 제목")

-> 대체 텍스트: 이미지가 깨지거나 로딩되지 않을 때, 또는 스크린 리더기가 읽어줄 텍스트
-> 이미지 주소: 인터넷에 있는 이미지의 URL이거나, 내 컴퓨터(또는 프로젝트)에 있는 이미지 파일의 경로
-> 이미지 제목: 이미지 위에 마우스를 올려두었을 때 작게 나타나는 툴팁 텍스트. 필요 없으면 생략
```

```
인터넷에 있는 이미지(URL)
![깃허브](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPyt9o2vV7qbUzPXo1bet8BsmumaYMNWALTk29xdsx5A&s=10 "GitHub")
```

```
내 프로젝트 폴더 안의 로컬 이미지
![깃허브](./image/github.png)
```

```
이미지에 링크 걸기
[![깃허브](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPyt9o2vV7qbUzPXo1bet8BsmumaYMNWALTk29xdsx5A&s=10)](https://github.com/b-jm)
```

---
![깃허브](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPyt9o2vV7qbUzPXo1bet8BsmumaYMNWALTk29xdsx5A&s=10 "GitHub")
![깃허브](./image/github.png)
[![깃허브](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQPyt9o2vV7qbUzPXo1bet8BsmumaYMNWALTk29xdsx5A&s=10)](https://github.com/b-jm)
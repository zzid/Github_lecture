## Github 특강 ( 2d, 16h )


#### Intro
<pre>
* Funny things 
    - auto draw
    - quick draw
    - Teachable Machine
    
    ** Extra
    * What is API exactly?
        - 다른 시스템간의 인터페이스
        - 모든 부분 다 숨기고, End point만 공개 되어있는, 
        - Web API : Communication between 'service' and 'service'
        - 요청받는 측에서 일정한 방식을 명세하고, 요청하는 측이 해당 방식대로 요청을 하면 되는,
        >> 약속대로 보내고, 약속대로 받는다.
    
    - "Request should be passed by url", that's all
    - API 가 serving 하는 data 가 JSON, XML 인거지, 그 자체가 API 인건 아님!
    - MSA가 최종적으로 제공해야 하는건 결국 >> "API DATA"
    >> 그러면 모든 Frontend Framework 이용 가능, Native도 당연히 가능

    - Interface : 접점
</pre>

#### venv
<pre>
* For deploy and Virtual env
    - commands
        >> python -m venv venv
        >> source venv/bin/activate (Mac)
        >> source venv/Script/activate (Window)
    >> rm -rf .git
    
    >> pip freeze > requirements.txt
    >> pip install -r requirements.txt
* version name convention ( rough? i guess )
    - 1.3.1
    - (Major).(Minor).(Patch) [change]
</pre>


#### git
##### (git book에 모든 것 다 있음)
<pre>

* Markdown
    - typora
* git basics... (add, commit etc.. )
* Gits
    - github
    - gitlab
    - bitbucket

* ping google.com > log.txt

* remote setting
    git init
    git remote add origin (master) [link]
    git add .
    git commit -m "message"
    git push (-u) origin master

* gitignore.io

    >> git log --pretty ?

* commands
    >> git commit --amend
    >> git reset HEAD (file)

* branch (Example)
    ** 모든 기준은 commit
    ** HEAD는 포인터 이동

    >> git branch feature/board 
    >> git checkout feature/board (or newer version ->) git switch feature/board
    (** slash is like 'convention')

    branch에서 파일 만들고 git건들지도 않았는데,
    master에 갔는데 왜 그 파일이 있는걸까? 
        -> untracked 상태에서는 있음.
        -> (branch 에서) add, commit 후에는 master 에서 안보임 


    >> (branch) git add .
    >> (branch) git commit -m ""
    >> (master) git merger branch

    ** branch는 할일 끝나면 지우는게 맞다.
        >> git branch -d (branchname)
    
    ** make and switch (branch)
        >> git checkout -b (branchname)
</pre>
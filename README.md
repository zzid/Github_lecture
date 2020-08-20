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
        >> <code>python -m venv venv</code>
        >> <code>source venv/bin/activate (Mac)</code>
        >> <code>source venv/Script/activate (Window)</code>
    >> <code>rm -rf .git</code>
* version name convention ( rough? i guess )
    - 1.3.1
    - (Major).(Minor).(Patch) [change]
</pre>


#### git

<pre>

* Markdown
    - typora
* git basics... (add, commit etc.. )
* Gits
    - github
    - gitlab
    - bitbucket

* <code>ping google.com > log.txt</code>

* remote setting
    <code>git init</code>
    <code>git remote add origin (master) [link]</code>
    <code>git add .</code>
    <code>git commit -m "message"</code>
    <code>git push (-u) origin master</code>

* gitignore.io

</pre>
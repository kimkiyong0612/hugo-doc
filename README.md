# hugo-doc

### create new post
```zsh
hugo new posts/{filename}.md
```

### input static content in post
```markdown:post.md
{{< image src="/img/hello.png" alt="Hello Friend" position="center" style="border-radius: 8px;" >}}
``` 

>Iamge is located in static/img


### debug
```zsh
hugo server -D
```

### build
```zsh
hugo
```



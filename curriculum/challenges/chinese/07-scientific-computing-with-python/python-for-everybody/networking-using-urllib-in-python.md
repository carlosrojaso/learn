---
id: 5e7b9f0d0b6c005b0e76f075
challengeType: 11
isHidden: false
videoId: 7lFM1T_CxBs
---

## Description
<section id='description'>

</section>

## Tests
<section id='tests'>

```yml
question:
  text: |
    What will the output of the following code be like?:
    ```python
    import urllib.request
    fhand = urllib.request.urlopen('http://data.pr4e.org/romeo.txt')
    for line in fhand:
        print(line.decode().strip())
    ```
  answers:
    - |
        Just contents of "romeo.txt".
    - |
        A header and the contents of "romeo.txt".
    - |
        A header, a footer, and the contents of "romeo.txt".
  solution: 1
```

</section>
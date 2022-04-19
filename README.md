```yml
# Example
name: AutoCloneV3

on:
  workflow_dispatch:
  
  schedule:
    - cron:  '*/1 * * * *'

jobs:
  Builds:
    runs-on: ${{ matrix.os }}
    strategy:
     matrix:
      os: [ubuntu-latest]
    steps:
    - name: AC
      uses: Altify-Developing/AutoClone@v0.1.7
      with:
        token: ${{ github.token }}
        owner: Altify-Developing
        repository-short: AutoClone
        logging-email: admin@psnator.com
```

<h1>GitHub AutoClone</h1>
<center>
  <img src="/proof.png"></img>
</center>
<p>Created By Altify Developing, if you use my tool, give credits</p>
<br><br><br>
<h3>Example Usage:</h3>
<br>

<h5>EDUCATIONAL USE ONLY</h5><h6>&copy; Altify Developing, LLC</h6>

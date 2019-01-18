# OSX

$ brew install hugo

$ git clone https://github.com/til-group/blog.git

$ cd blog

$ hugo new post/{post_title}.md

$ vim content/post/{post_title}.md

$ git add * && git commit

$ git push origin master

Windows
========

$ ``
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
``

$ choco install hugo -confirm

$ git clone https://github.com/til-group/blog.git

$ cd blog

$ hugo new post/{post_title}.md

$ vim content/post/{post_title}.md

$ git add * && git commit

$ git push origin master

FROM mcr.microsoft.com/windows/servercore:ltsc2019

LABEL "com.github.actions.name"="Hello World"
LABEL "com.github.actions.description"="Write arguments to the standard output"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="http://github.com/octocat/hello-world"
LABEL "homepage"="http://github.com/actions"
LABEL "maintainer"="Octocat <octocat@github.com>"

ADD entrypoint.bat /entrypoint.bat
RUN chmod +x /entrypoint.bat
ENTRYPOINT ["cmd.exe", "/C", "entrypoint.bat"]

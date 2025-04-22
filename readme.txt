Пуш сразу в 2 репозитория

.git/hooks/

#!/bin/sh
git push gitlab --all

https://github.com/roman9234/kubernetes-project
https://gitlab.com/romanlesovoy1/kubernetes-project

git remote add all https://github.com/roman9234/kubernetes-project

git remote set-url --add --push all https://gitlab.com/romanlesovoy1/kubernetes-project

git remote set-url --add --push all https://github.com/roman9234/kubernetes-project

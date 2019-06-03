### TIL git에 업로드 하는법

git config name.user "~~"

git config name.email "~~"

d:

mkdir 폴더이름

cd 폴더이름

echo "# til" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/wisdom009/til.git   

git push -u origin master

여기까진 처음 올렷을때


git add .

git commit -m "소개문"

git push   # 다시 최신화

#------------------------------------------------------------------------

git remote add originhttps://github.com/wisdom009/R_Data.git

git remote rm origin ## 익시트 에러가 나올시 rm으로 기록을 지워주고 다시 작성

git pull #이전 기록을 불러온다

git push -u origin master  / (OR) /  git push   # 다시 최신화

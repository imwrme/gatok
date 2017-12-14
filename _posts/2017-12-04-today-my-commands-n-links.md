# use i18n method.

++http://guides.rorlab.org/i18n.html++

* * *

# In ruby on rails, Let's use ==gem activeadmin== ~ 

++https://activeadmin.info/0-installation.html++


gem 'activeadmin'

Plus integrations with:

gem 'devise'
gem 'cancan' # or cancancan
gem 'draper'
gem 'pundit'


# git tutorial

https://www.atlassian.com/git/tutorials/using-branches/git-checkout

# ActiveModel::ForbiddenAttributesError when creating new user



https://stackoverflow.com/questions/17335329/activemodelforbiddenattributeserror-when-creating-new-user


# ㅠㅠ force backward git...

git reset --hard e2cd7b6



# rake db:migrate failed...

계속해서 db:migrate이 실패했다. 
1 구래서 db/*.sqlite3 들을 다 지우고 (걍 손으로...)
2새로 디비를 만들었으며 rake db:create
3 schema.rb 파일의 버전이 마이그레이션 파일과 번호가 맞지 않아서 수정 후. (직접...)
db가 원상복구됨 


rails s -e development
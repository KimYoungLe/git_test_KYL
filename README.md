# git_test_KYL
복습 하자


github 등록
	ssh-keygen -t ed25519 -C "git config user.email 의 이메일"
	eval "$(ssh-agent -s)"
	ssh-add ~/.ssh/id_ed25519
	clip < ~/.ssh/id_ed25519.pub
		ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAICzXgYDAlvnOi7ucIkvXX63Jlb6N3bMFIVeIzoq7+/OW so.youngle.radink125@gmail.com
	
	git remote add origin github주소
	git push origin master

	위의 방법으로 안됐을경우
	git remote add origin ssh주소
	git push origin master 

=======================================================

git clone "주소" : 주소이름으로 폴더를 만들고 그안에 git에 저장된 파일을 가져옴




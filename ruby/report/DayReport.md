## 2020-4-13
	Ruby on Rails 시도 첫 날
	linux ubuntu 18.0.4 에서 실행하고 있다.
	시행착오를 꽤 많이 거쳤다.
	Ruby On Rails 를 시작하기 위해서는, 다음의 라이브러리들을 설치해야한다.
	명령어만 적어놓는다.
		 > $ sudo apt install ruby-dev
		 > $ sudo apt install sqlite3
		 > $ sudo apt install libsqlite3-dev
	아직 -dev 를 붙이는 의미는 잘 모르겠지만, 용량도 다르고 , 다른 패키지인 듯.
	위 내용 관련해서는 나중에 더 알아보자.
	위 패키지를 모두 설치하고 나서 다음 명령어를 쳐준다.
	   	 > $ rails new blog
		 > $ sudo gem install sqlite3
		 > $ cd blog
		 > $ bundle install
		 > ( sudo bundle install 로 쳐야 실행되는데, 뭔가 잘못 된 것 같다)
	생각보다 설치도 쉽지 않았다. 꽤 헤멨다.
	그래도 언젠간 치뤄야할 비용으로 보이니, 좀 위안이 된다.
	
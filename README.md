## krzip-server

http://domain/server.php?

## 권한 설정

주요 디렉토리와 파일들에 대해서 php 에서 파일을 쓰거나 변경 할 수 있도록 권한을 설정해야 합니다.

+ kr-zip-server/logs
+ kr-zip-server/conf/versionDate.inc
+ kr-zip-server/admin/files
+ kr-zip-server/admin/cache

## 계정 설정

conf/db.config.php 파일을 참고 하여 conf/db.config.user.php 파일에 작성


## 데이터 생성

+ 다운로드 후 사용자는 "[우체국](http://www.epost.go.kr/)" 홈페이지에서 도로명 주소를 다운 받아야 합니다.

( 각 지역별 모든 엑셀 파일을 모두 다운로드 받아야 함 )

+ 다운로드 받은 파일의 압축해제 후 krzip-server/files 폴더로 업로드 합니다.

( files 폴더안에는 반드시 txt 파일만 업로드 되어야 합니다. files 폴더안에 있는 폴더는 처리되지 않습니다. )

+ 업로드 완료 후 krzip-server/bin/krzip-insert-cli.php 를 실행 시킵니다.

php -f krzip-insert-cli.php



sho-issueCraw
=============

crawling twitter issue.


krzip-server
===========

주요 디렉토리와 파일들에 대한 권한을 설정해야 합니다.
chmod 777 kr-zip-server/logs

chmod 777 kr-zip-server/conf/versionDate.inc
chmod 777 kr-zip-server/admin/files
chmod 777 kr-zip-server/admin/cache

kr-zip-server/conf/db.config.php 에 관리자 접속에 사용할 __KRZIP_ADMIN_ID__, __KRZIP_ADMIN_PW__ 를 설정합니다.
http://yourdomain/admin/index.php 에 접속하여 db.config.php 에서 설정한 id, password로 로그인하시고
http://www.epost.go.kr/ 에서 우편번호 파일을 다운받아 압축을 푼 후 서버로 업로드 합니다.


~

## Links

+ [Demo page](http://pixelkit.com/free-ui-kits/arctic-sunset/)
+ [Documentation page](http://pixelkit.com/free-ui-kits/arctic-sunset/docs/)
+ [Premium Version of this UI Kit](http://pixelkit.com/kits/clean-ui-kit/)

## Dark Velvet

![ScreenShot](http://pixelkit.com/wp-content/uploads/2013/05/01.Basics1.jpg)

To get started check out our free sample demo <http://pixelkit.com/free-ui-kits/dark-velvet/> The complete Bootstrap UI kit that contains tons of additional elements spread across 6 categories is available on PixelKit.com <http://pixelkit.com/kits/dark-ui-kit/>

## Links

+ [Demo page](http://pixelkit.com/free-ui-kits/dark-velvet/)
+ [Documentation page](http://pixelkit.com/free-ui-kits/dark-velvet/docs/)
+ [Premium Version of this UI Kit](http://pixelkit.com/kits/dark-ui-kit/)

## Vanilla Cream

![ScreenShot](http://pixelkit.com/wp-content/uploads/2013/05/The-Basics.jpg)

To get started check out our free sample demo <http://pixelkit.com/free-ui-kits/vanilla-cream/> The complete Bootstrap UI kit that contains tons of additional elements spread across 6 categories is available on PixelKit.com <http://pixelkit.com/kits/light-ui-kit/>


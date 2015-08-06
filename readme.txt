=== Rocket Font ===
Contributors: Qwerty23
Donate link: http://rocketpress.kr
Plugin URI: http://rocketpress.kr
Tags: Wordpress Korean Font, rocket font, 로켓 폰트, 한글 폰트
Requires at least: 3.5.1
Tested up to: 4.3
Stable tag: 1.0.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

wordpress 에서 한글 폰트를 사용할 수 있는 플러그인입니다.

== Description ==

css 를 잘 다루지 못하는 분들을 위해 최대한 심플하게 만들었습니다.
그저 관리자 > 설정 > 로켓 폰트 에서 사용하고 싶은 폰트를 선택한 후 저장하면 끝입니다.

사용할 수 있는 한글 폰트 종류는 아래와 같습니다.

* 한나
* 제주 고딕
* 제주 한라산
* 제주 명조
* KoPub 바탕
* KoPub 돋음
* 나눔 고딕
* 나눔 바른 고딕
* 나눔 붓글씨
* 나눔 고딕 코딩
* 나눔 명조
* 나눔 펜글씨
* NotoSansKR

사용(라이센스)에 문제가 없는 오픈소스 폰트만 등록되어 있습니다.
추후 새로운 폰트가 추가될 경우 이 플러그인도 업데이트해서 반영할 예정입니다.

이 플러그인은 아래와 같은 특징이 있습니다.

* 관리 페이지의 설정으로 css 파일을 생성하고, 유저 페이지에서는 이 css 파일과 폰트 css 파일만 불러올뿐 별다른 처리는 없습니다. 
* 생성하는 css 파일은 폰트 이외의 처리는 없으며 minify 버전으로 압축되기 때문에 용량이 작습니다. (100 byte 미만)
* 만약 설정한 폰트가 제대로 표시되지 않을 경우 옵션중에 [표시 방식]을 jQuery 방식으로 설정해 보세요.

Designed by : <a href="http://rocketpress.kr/" target="_blank">Rocketpress</a>

== Installation ==

일반적인 워드프레스 플러그인 설치와 같습니다.

1. 워드프레스 관리자 화면의 플러그인 검색에서 rocket font 로 검색해서 설치, 활성화하면 됩니다.
1. 혹은 직접 다운로드를 받아서 압축을 풀고 wp-contents/plugins 폴더안에 업로드 후 활성화하면 됩니다.
1. 관리자 메뉴 > 설정 > 로켓 폰트 메뉴에서 폰트를 선택해 주세요.
1. 폰트를 선택한 후 각 태그별 크기 및 글 간격 설정에서 선택한 폰트를 적용하길 원하는 태그를 사용으로 체크해 주시면 됩니다.

== Frequently Asked Questions ==

기타 플러그인에 관한 문의 및 건의사항은 http://rocketpress.kr/forum/ 에 댓글이나 메일을 보내주세요.

== Screenshots ==
1. 폰트 설정 화면입니다. 사용하길 원하는 폰트를 선택한 후 저장하기만 하면 끝입니다. google, jsdelivr 의 CDN 을 사용하기 때문에 별도로 폰트 파일을 사이트에 업로드할 필요는 없습니다.
2. 설정된 폰트가 표시되는 화면입니다.

== Changelog ==

= 1.0.0 =
* 멀티 사이트 대응 : 각 사이트별로 css 생성하고 사용합니다. 멀티사이트를 사용하지 않을경우 일부러 버전업을 할 필요는 없습니다.
* NotoSansKR 폰트 추가 : 마찬가지로 NotoSans 폰트를 사용하지 않는다면 버전업 할 필요는 없습니다.

= 0.0.2 =
* body 태그 폰트적용 기본값 사용으로 변경

= 0.0.1 =

== Upgrade Notice ==

= 0.0.1 =

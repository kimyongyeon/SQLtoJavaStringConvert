# SQLtoJavaStringConvert

* 설정하는 방법
1. schema.sql, setting.yml 파일은 반드시 프로젝트 위치와 동일한 선상에 위치한다.
만약 C:\\프로젝트명\\src\\.. 라면 C:\\프로젝트명\\ 폴더위치에 있어야 한다.
2. setting.yml 은 설정파일로
driver : 윈도우용은 C:\\, 리눅스용은 /tmp/ 잡으면 된다.
package path : 는 만약 schema.sql 파일을 현재 프로젝트 패키지명 위치에 있을때 해당 주소를 모두 적어준다. 그러면 스키마 파일을 읽을
수 있다. 하지만 보통은 프로젝트명 폴더에 위치하는것이 가장 안정적이다.
3. yamlbean을 사용하기 위해 jar파일이 있으니 라이브러리 패스를 잡아 줘야 합니다.




<strong>====Type</strong>

1.<태그>=약속된 명령어.

<시작태그>()</닫히는태그> 로 작성한다.


<strong>표만드는 방법, 병합</strong>

td /td태그=(table data약자)항목별로 묶는 태그 각각의 문자

tr /tr태그= 행으로 묶어주는 태그 한줄로 묶어준다.

table=로 전체를 묶는다. table border="숫자"======전체를 여러 칸으로 만드는 테이블.

thead /thead=제목을 정한다.(표시되진 않음)

tbody /tbody=내용을 정한다.(표시되진 않음)

th /th=th로 만들어진 셀은 진하게 표시된다.

tfoot /tfoot ==자동으로 가장 아래쪽으로 내려진다.ex)합계 등등 구할 때

td rowspan="숫자"===숫자개수의 행이 병합된다. 만약 rowspan을 작성할 경우 병합될 셀의 내용을 지운다

td colspan="숫자" ===숫자개수의 열이 병합된다. 만약 colspan을 작성할 경우 병합될 셀의 내용을 지운다



<strong>form 기본</strong>

input type="text" 를 입력하면 사용자가 검색 할 수 있는 박스가 생성됨. 검색창과 동일

input type="password" 비밀번호 형식의 *로 표시가 된다.

input type="submit" 클릭하면 다음화면으로 넘어가는 제출아이콘을 만든다.

form action="넘어갈위치"/form태그 ===action에 적히는 위치로 다음화면이 만들어진다

중복이 있을 수 있기때문에 각각의 컨트롤에 이름을 정해준다.

ex)input type="텍스트" name="이름"

11.form문자입력
textarea /textarea== 여러줄을 입력할 수있는 텍스트공간 만들기

textarea cols="숫자" rows="숫자" /textarea===행과 열의 숫자 폭을 넓혀 공간을만들어준다

textarea default value /textarea==기본값을 입력해준다

select name="항목으로 나타내는 분류 또는 정보"

option value="정보"____/option====선택      value값을 추가하면 정보에대한 것을 입력

/select                                      ====select는 하나로 묶어준다

select name="정보" multiple  ======항목을 다중선택 가능하도록 만듬

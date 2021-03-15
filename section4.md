strong>====Type</strong>

1.<태그>=약속된 명령어.

<시작태그>()</닫히는태그> 로 작성한다.

<strong>Form 입력양식</strong>

radio,checkbox ==항목 선택 버튼이며 중복되지않기위해 이름을 붙여준다.

radio - 하나씩 선택할 수 있음

ex)input type="radio" name="color"

checkbox - 다중으로 선택할 수 있도록 나눠줌

기본으로 체크되게 만드는 항목에 checked를 넣으면 자동체크가 된다

botton

ex)input type="submit" value="전송"

 input type="button" value="버튼"  에서 button은 클릭해도 소용이없다.

input type="reset" == 모든 정보들이 초기화됨

hidden

ex)input type="hidden" name="hide" value="egoing" 눈에보이진 않게 설정가능한 것.

label 무언가의 이름표. 특별한 기능보다는 정보를 설명하기 위한 것.

label을 달면 이름을 달아주는 것. 게다가 더 넓은 영역을 클릭가능함. 이름부분을 클릭해도 해당.

label for="" ====~의 이름표인지를 연결시켜주는것. 


method="get" or "post"

url을 통해서 전송하는것은 "get"방식 

다른방법으로 데이터를 숨겨서 전송"post"===안전함 폼을이용해서 정보를 전송할때 이용.100%

form파일업로드 방법

input type="file" 입력시 파일선택할 수 있는 창이 만들어진다

중요!! 파일업로 창을 만들면서. 

폼 형식에 method 는 post로, enctype="multipart/form-data"를 꼭!! 작성해야한다.

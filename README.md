Page폴더 안의 Home.jsx, LetterDetail.jsx로 홈페이지와 디테일 페이지를 나누었다.

component 폴더에 헤더, 팬레터 입력 폼, 팬레터 리스트, 팬레터 미리보기 기능을 가진 jsx 파일을 만들었다.

fakeData.json을 사용하여 저장된 팬레터가 없어도 팬레터 목록을 불러오게끔 하였다.

context 폴더에 useContext 방식으로 상태 관리를 하기 위해 만든 js파일을 저장하였다.

config 폴더에 redux 방식으로 상태 관리를 하기 위해 만든 letter.js, filter.js 파일을 저장하였다.

![image](https://github.com/kewii33/fanpage/assets/150649178/45aab5ad-9765-4060-bd22-367ac79deecc)

필터를 선택하면 필터가 적용된 팬레터들을 보여준다.

입력 폼에 내용을 입력하여 리스트에 팬레터를 추가할 수 있다. 제목은 20자, 내용은 100자로 제한되며 둘 중 하나라도 적혀있지 않으면 팬레터를 저장할 수 없다.

팬레터 리스트의 팬레터를 누르면 디테일 페이지로 이동할 수 있다.

![image](https://github.com/kewii33/fanpage/assets/150649178/4a603a87-6e6f-4312-8def-66ff247878cf)

'홈으로' 버튼을 누르면 입력 폼과 팬레터 리스트가 있는 홈페이지로 이동한다.

'수정', '삭제'버튼을 눌러서 내용을 수정하거나 삭제할 수 있다. 삭제할 경우 다시 홈페이지로 돌아오게 된다.

![image](https://github.com/kewii33/fanpage/assets/150649178/5499f1ad-5c71-4990-aef6-5823759bdb72)

수정된 부분이 없으면 '수정 완료' 버튼을 눌러도 '수정된 부분이 없습니다.'라는 알람이 뜨고 수정이 완료되지 않는다.

취소 버튼을 누르면 팬레터 수정을 취소할 수 있다.

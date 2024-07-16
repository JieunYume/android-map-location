# android-map-location
## step1 기능 목록
1. 저장된 검색어 목록에 기능 추가하기
   - 저장된 검색어 중 하나를 선택하면 해당 검색어의 검색 결과 목록이 표시된다. 
2. 검색 결과 목록에 기능 추가하기
   - 검색 결과 목록 중 하나의 항목을 선택하면 해당 항목의 위치를 지도에 표시한다. 
3. 마지막 위치 저장하기
   - 앱 종료 시 마지막 위치를 저장하여 다시 앱 실행 시 해당 위치로 포커스 한다. 
4. 에러 처리하기
  - 카카오지도 onMapError() 호출 시 에러 화면을 보여준다. "지도 인증을 실패했습니다. 다시 시도해주세요. '에러이름(에러코드): 에러메세지'
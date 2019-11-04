# UserMan2 with Community using Ajax (UserMan3a) 
a branch generated from with_Community_(UserMan3)   
- adding Ajax calls to the controllers returning JSON text 

### with_Community_(UserMan3) branch로부터 변경된 클래스  

- controller.RequestMapping (request mapping 정보 수정 및 추가)
- controller.comm.ListCommunityController (ListAndViewCommunityController로 교체: listAndView.jsp 뷰 선택)
- controller.comm.ListCommunityJsonController (추가: 커뮤니티 리스트 검색 및 JSON 형식으로 출력)
- controller.comm.ViewCommunityJsonController (추가: 특정 커뮤니티 정보 검색 및 JSON 형식으로 출력) 

- WebContent/user/registerForm.jsp (ListCommunityJsonController에 대한 Ajax 호출 추가)
- WebContent/community/list.jsp (listAndView.jsp로 교체: ViewCommunityJsonController에 대한 Ajax 호출)


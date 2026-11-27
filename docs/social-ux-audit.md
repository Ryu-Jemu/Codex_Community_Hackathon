# 소셜 플랫폼 54곳의 UI·UX 비교

2026년 11월 27일 · 공개된 운영사 도움말, 제품 페이지, 기술 블로그를 검토했다. 음악·창작·지식 커뮤니티도 포함해 게시, 탐색, 반응, 모임 참여 방식이 서로 다른 서비스 54개를 살폈다. 표의 확인 내용은 각 운영사의 문서에 근거한다. 따공 적용 판단은 그 자료를 바탕으로 내린 제품 가설이며 실제 사용자 조사 결과와 구분한다.

## 따공에 반영한 것

| 사용자 행동 | 따공에서 적용한 변경 | 확인할 기준 |
| --- | --- | --- |
| 동네에서 일어난 일 읽기 | 홈에서 최신·인기와 공감·대표 댓글을 보고, 같은 화면을 내려 행정구역 지도와 격자를 연다. 홈과 지역 소식에 공통 유리 표면을 사용한다. | 홈에서 지역 글까지의 조작 횟수와 상세를 닫은 뒤 읽던 위치 유지 |
| 글이 지역에 기여한 양 이해하기 | 승인 글마다 해당 지역에 1P를 적립한다. 지역 상세는 적립값과 인구 보정값을 같이 보여 주고, 두 지도는 같은 개나리색 농도와 숫자 범례를 사용한다. | 첫 글부터 반영되는지, 차단 시 변화가 없는지, 두 지도에 표시된 값이 일치하는지 |
| 노래를 찾아 다른 사람에게 추천하기 | 곡과 가수 이름, 분위기로 찾는다. 결과가 없으면 한 번에 조건을 지울 수 있고, 추천 폼은 어떤 순간에 듣기 좋은지 묻는다. | 의도한 곡의 첫 검색 성공률과 검색 실패 후 다시 목록을 여는 비율 |
| 단골 선곡을 꾸미기 | 곡마다 다른 LP와 라벨을 제공한다. 내 브라우저에서 원하는 조합을 미리 본 뒤 곡별로 저장하거나 기본 디자인으로 돌아갈 수 있다. | 새로고침 후 저장 유지, 취소 시 변경 없음, 다른 곡의 색·라벨 유지 |

## 전국 파일럿에서 먼저 검증할 것

1. **관심 지역에 다시 방문하기.** 바라보는 지표는 첫 지역 글 열람 후 7일 이내 같은 지역 재열람이다. 조회가 적은 지역은 전국 수치와 함께 지역별 관측 수를 제시한다. 관심 지역의 새 글 알림은 요청한 방문자에게만 제공하는 방식을 실험한다.
2. **반응과 기록을 나누기.** 공감, 개인 저장, 지역 포인트에 각각 목적을 부여한다. 비공개 저장이 재방문을 돕는지 먼저 확인한다. 감사 답장과 도움 완료 기록의 공유는 당사자의 선택으로 둔다.
3. **게시 전 맥락을 전달하기.** 차단·보류 후 작성 화면을 유지하고, 기준이나 수정할 표현을 쉽게 찾을 수 있게 한다. 심사 기준의 어휘별 차이와 같은 사람이 여러 편을 올릴 때 생기는 지도 편중은 출시 실험에서 별도로 측정한다.

## 글로벌 피드·대화 플랫폼

| 플랫폼 | 확인한 UI·UX | 따공 적용 판단 | 1차 출처 |
| --- | --- | --- | --- |
| Instagram | 팔로잉과 즐겨찾기 피드는 각각 선택된 계정의 글을 시간순으로 보여 준다. | 홈에서 최신과 인기 선택을 계속 노출하고, 정렬 방식을 화면에서 읽을 수 있게 한다. | [Meta · Instagram 피드 선택](https://about.fb.com/news/2022/03/two-new-ways-to-control-your-instagram-feed/) |
| Facebook | 피드의 관심 있음·관심 없음은 유사 게시물 추천의 순위 신호로 쓰인다. 즐겨찾기와 일시 숨기기도 피드 설정에 있다. | 추후 ‘이 글 숨기기’와 실행 취소를 검증한다. 개인 숨김은 게시 심사 및 지역 점수와 독립된 조작으로 둔다. | [Meta · Facebook 피드 설정](https://about.fb.com/news/2022/10/new-ways-to-customize-your-facebook-feed/) |
| Threads | 커스텀 피드 순서를 바꾸어 앱을 열 때 기본으로 보이게 할 수 있다. 공개 피드를 공유하고 다른 공개 피드를 홈에 고정할 수 있다. | 기존 관심 지역 바로가기의 저장·해제 상태를 명확히 하고 재방문 시 그대로 보이는지 확인한다. 공개 공유는 지역 피드 주소를 먼저 검증한다. | [Meta · 피드 순서 설정](https://about.fb.com/news/2025/03/new-threads-features-more-personalized-experience-you-control/) · [커스텀 피드 공유](https://about.fb.com/news/2025/02/share-custom-feeds-on-threads/) |
| X | Lists는 주제나 관심사별로 지정한 계정의 글만 타임라인에 보여 주며 상단에 고정할 수 있다. | 한 지역에 글이 충분해질 때 관심 지역 안의 도서관·자원봉사 기관 소식을 명시적으로 찾아보는 보조 경로를 실험한다. | [X Help · Lists](https://help.x.com/en/using-x/x-lists) |
| Mastodon | 작성자가 콘텐츠 경고를 붙일 수 있다. 독자 설정에서는 경고가 붙은 게시물을 접거나 기본으로 펼칠 수 있다. | 어려움을 겪은 뒤 이웃의 도움을 받은 글에 문맥 안내를 붙이는 방안을 검증한다. 가입·심사 규칙을 바꾸지 않고 독자에게 열람 선택을 준다. | [Mastodon · 글 작성](https://docs.joinmastodon.org/user/posting/) · [읽기 기본 설정](https://docs.joinmastodon.org/user/preferences/) |
| Bluesky | 커스텀 피드를 골라 홈에서 사용할 수 있다. 피드 생성자는 어떤 글을 어떤 기준으로 고를지 정할 수 있다. | 최신·인기·지역의 대상과 기준을 짧게 표시한다. 예를 들어 ‘최근 7일 공감순’이 보이면 인기의 뜻을 별도 도움말 없이 이해할 수 있다. | [Bluesky · 커스텀 피드와 선택권](https://bsky.social/about/blog/7-27-2023-custom-feeds) |
| Reddit | Post Check는 작성 중 커뮤니티 규칙 위반 가능성을 짚고 제출 전에 수정할 안내를 제공한다. | 작성란에 승인·차단 예시를 한 줄씩 보여 준다. 보류나 실패 후에는 입력을 유지하고 이유와 수정 위치를 제시한다. | [Reddit Help · Post Check](https://support.reddithelp.com/hc/en-us/articles/33702751586836-Poster-Eligibility-Guide-Post-Check) |
| Tumblr | 태그 필터와 게시물 본문 필터를 제공한다. 태그 필터는 대시보드와 검색에도 적용된다. | 부담스러운 주제를 숨기는 독자 제어를 후속 실험으로 둔다. 숨긴 이유와 복구 방법을 사용자가 찾을 수 있어야 한다. | [Tumblr Help · 태그와 본문 필터](https://help.tumblr.com/knowledge-base/tag-and-post-content-filtering/) |
| Pinterest | 저장한 핀을 보드에 모으고 보드 안에서 섹션별로 정리할 수 있다. | 독자가 다시 볼 이야기를 저장하는 기능을 검증한다. 먼저 한 개의 비공개 저장 목록을 두고, 이용량이 생긴 뒤 묶음이 필요한지 살핀다. | [Pinterest Help · 보드 섹션](https://help.pinterest.com/en/article/create-a-board-section) |
| Snapchat | My Story에서 열람 대상을 친구로 제한하거나 별도 대상을 지정할 수 있다. | 도움 후일담을 쓰는 단계에서 공개 범위를 분명히 보여 주고, 두 사람이 동의하기 전에는 공개 게시물을 만들지 않는다. | [Snapchat Support · My Story 열람 범위](https://help.snapchat.com/hc/en-gb/articles/7012279488532-How-can-I-change-who-can-see-My-Story-on-Snapchat) |
| TikTok | Manage Topics에서 주제별 추천 빈도를 높이거나 낮출 수 있다. 빈도를 낮추는 조작만으로 주제가 완전히 제거되지는 않는다. | 노래의 응원·위로·산책은 선택하면 해당 곡만 보이는 검색 필터로 유지한다. 필터를 선택했는데 결과가 없으면 이를 알리고 전체로 돌아갈 수 있게 한다. | [TikTok Newsroom · 주제 조절](https://newsroom.tiktok.com/tiktoks-new-features-to-help-you-control-your-scroll?lang=en-AU) |
| YouTube | 관심 없음과 채널 추천 안 함을 각각 선택할 수 있으며, 두 피드백이 추천 조정에 쓰일 수 있다. | 공감은 이야기 반응으로 유지하고 노래 취향은 별도의 선택으로 받는다. 자동재생 없이 곡별 추천 이유와 공식 링크를 표시한다. | [YouTube Help · 추천과 검색 제어](https://support.google.com/youtube/answer/6342839?hl=en) |
| LinkedIn | 피드의 게시물과 아티클을 저장한 뒤 저장 항목에서 다시 찾을 수 있다. | 개인 활동을 타인에게 보여 주는 프로필 전에 ‘다시 읽을 이야기’를 따로 검증한다. 저장·삭제가 인기순이나 온기 점수에 영향을 주지 않게 한다. | [LinkedIn Help · 피드 콘텐츠 저장](https://www.linkedin.com/help/linkedin/answer/a527126) |
| Discord | 포럼 채널은 대화 주제마다 게시물을 만들고 태그를 붙이며, 채널 관리자가 작성 안내를 설정할 수 있다. | 도움 주고받기를 실험할 때 요청 목록에는 생활 정보·대여·나눔 같은 유형을 표시하고, 요청 바로 옆에 작성 기준을 둔다. | [Discord Support · 포럼 채널](https://support.discord.com/hc/en-us/articles/6208479917079-Forum-Channels-FAQ) |
| Telegram | 그룹의 토픽은 대화 흐름, 공유 미디어와 알림 설정을 각각 갖는다. | 도움 요청과 그에 대한 대화를 한 건에 묶는다. 사용자는 자신이 참여한 요청의 답변만 선택적으로 받을 수 있게 한다. | [Telegram Blog · 그룹 토픽](https://telegram.org/blog/topics-in-groups-collectible-usernames?setln=en) |
| WhatsApp | Communities는 관련 그룹을 묶고, 관리자는 공지 그룹을 통해 구성원에게 알림을 보낼 수 있다. | 전국 파일럿에 주간 소식을 추가한다면 공개 소식과 별도로 수신에 동의한 사람에게 한 번만 전달하고, 알림 종류와 해제 방법을 표시한다. | [WhatsApp Help · Communities](https://faq.whatsapp.com/495856382464992) · [관리자 공지](https://faq.whatsapp.com/742237357891080) |
| LINE | OpenChat은 일반 LINE 계정과 별도로 방마다 닉네임과 프로필 이미지를 정할 수 있다. | 지역별 도움 실험에서 참가자 상태와 공개 프로필에 보이는 정보를 시작 전에 미리 보여 준다. 개인 연락처와 정밀 위치의 공개 입력은 요구하지 않는다. | [LINE 공식 · 오픈채팅 프로필](https://openchat-jp.line.me/blog/guide-profile-settings) |
| WeChat / Weixin | Tencent 안내에서 Moments는 연락처 기반 비동기 공유, Channels는 공개 영상 배포 공간으로 구분된다. | 공개 지역 소식과 상대방과의 대화는 접근 범위와 저장 상태를 화면에서 설명하고, 사적인 답장을 공개 글로 옮길 때 당사자 동의를 확인한다. | [Tencent · Weixin 공개·비공개 기능 비교](https://static.www.tencent.com/attachments/reports/tencent_bpp_report_2023.pdf) |

### 기술·디자인 자료에서 가져온 검증 기준

- **피드 기준 공개** · Meta의 개발 블로그는 피드 순위가 클릭이나 좋아요 한 종류보다 복수의 예측 결과와 표시 조건에 따라 결정될 수 있다고 설명한다. 따공은 현재 쓰는 기간·공감 수·지역 규칙부터 드러내고, 복잡한 추천 순위는 첫 실험의 필수 조건으로 삼지 않는다. [Engineering at Meta · News Feed 순위](https://engineering.fb.com/2021/01/26/ml-applications/news-feed-ranking/)
- **추천 품질과 편향 측정** · Spotify Engineering은 추천의 예상치 못한 효과와 기존 불평등 확대를 검토하는 평가를 설명한다. 따공에서는 총 탭 수와 함께 지역별 노출 수, 처음 보는 지역 글 열기, 글이 적은 지역 도달률을 본다. 표본이 충분해지면 분포와 재열람을 함께 비교한다. [Spotify Engineering · 알고리즘 영향평가](https://engineering.atspotify.com/2022/09/lessons-learned-from-algorithmic-impact-assessments-in-practice)
- **작은 화면 탐색** · web.dev는 같은 탐색 링크를 화면 너비에 맞춰 배치하는 사례를 보여 준다. 따공은 320px, 확대 글자, 키보드에서 다섯 탭의 글자와 선택 표시가 유지되는지 먼저 검증한다. [web.dev · 반응형 UI 패턴](https://web.dev/learn/design/ui-patterns)

이번 자료에서 우선 검증할 항목은 **관심 지역으로 바로 돌아가기**, **심사 보류·실패 후 작성 이어가기**, **색과 함께 표시한 지도 수치 해석**이다. 첫 방문자가 각 과업에 성공했는지, 조작을 몇 번 했는지, 회복 경로를 설명할 수 있는지 관찰한다.

## 지역·관심사 커뮤니티

| 플랫폼 | 확인한 UI·UX | 따공 적용 판단 | 1차 출처 |
| --- | --- | --- | --- |
| 당근 (Karrot) | 동네생활에 지역 주민의 질문과 일상 소식을 모으고, 동네 가게 관련 정보는 별도 ‘내 근처’에 배치한다. | 관심 지역 바로가기 아래에 동네 도움·감사 사례를 우선 배치한다. 지역 선택에서 읽기까지 걸리는 조작 횟수를 검증한다. | [당근 서비스 소개](https://team.daangn.com/service/) · [동네생활 안내](https://www.daangn.com/wv/faqs/861) |
| BAND | 그룹 게시글에 라벨을 붙일 수 있고, 운영자가 게시글 승인 기능을 설정한다. 일정과 공지도 그룹 내 별도 도구에 둔다. | 도움·감사·회복 등 짧은 주제 라벨을 시험한다. 게시 심사 화면은 현재 상태와 바로 할 수 있는 조작을 같은 위치에 보여준다. | [BAND 공식 사용 가이드](https://pages.band.us/band-guide-global) |
| 네이버 카페 | 카페 가입 방식에는 운영진 승인형이 있으며, 게시물 설정에서 멤버 공개와 검색 노출 여부를 고를 수 있다. | 글을 제출할 때 보이는 대상과 검색 노출 범위를 확인할 수 있게 한다. 공개 열람 정책이 단일한 시연에서는 한 줄 고지로 충분하다. | [카페 가입 방법](https://help.naver.com/service/5622/contents/737?lang=ko&osType=PC) · [게시글 설정 방법](https://help.naver.com/service/5622/contents/15342?osType=PC) |
| 카카오톡 | 오픈채팅은 관심사 방을 검색하거나 링크로 입장할 수 있다. 카카오가 직접 운영한 사례는 닉네임 참여와 입장 전 대화 열람을 제공했다. | 실제 대화 도입 시 초대 화면에 대화 주제, 참여 범위, 보이는 이름을 먼저 제시한다. 입장 전 보여주는 미리보기는 공개가 합의된 메시지로 구성한다. | [오픈채팅 검색·링크](https://www.kakaocorp.com/page/detail/9696) · [카카오 운영 오픈채팅 사례](https://www.kakaocorp.com/page/detail/10811) |
| 카카오스토리 | 친구 소식과 채널 소식을 피드에서 보고, 관심 채널은 ‘소식받기’로 구독한다. ‘내스토리’에는 월별로 작성한 글을 찾는 흐름이 있다. | 광역 지역을 저장하면 홈에서 다시 여는 동작을 한 번으로 줄인다. 글이 쌓이면 프로필에서 게시 월로 돌아가는 탐색을 검증한다. | [카카오스토리 공식 서비스 소개](https://www.kakaocorp.com/page/service/service/KakaoStory) |
| 네이버 블로그 | 이웃 추가와 신청·수락을 거치는 서로이웃을 제공한다. 글 발행 시 설정 창에서 공개 대상을 고른다. | 관심 지역 저장은 개인의 읽기 설정으로 안내한다. 공개 범위를 제공하는 단계에서 작성자가 최종 발행 대상을 제출 전에 확인하게 한다. | [이웃·서로이웃 소개](https://help.naver.com/service/5593/contents/15380?lang=ko&osType=COMMONOS) · [글 발행 방법](https://help.naver.com/service/5593/contents/15541?lang=ko&osType=PC) |
| 티스토리 | 홈 커버에서 목록·썸네일·갤러리 같은 정해진 요소를 조합한다. 일부 공식 스킨에서는 에디터와 발행 본문의 표시 스타일을 통일했다. | 사진 유무에 따른 카드 변형을 같은 그리드 안에서 운영한다. 작성 미리보기와 발행 상세에서 제목 줄바꿈과 본문 크기를 함께 확인한다. | [티스토리 홈 커버 소개](https://notice.tistory.com/2459) · [에디터와 본문 스타일 안내](https://notice.tistory.com/2663) |
| 브런치스토리 | 작가 신청 경로가 있으며, 연재 브런치북은 요일에 맞춰 한 편씩 공개한다. 이미 발표한 글을 하나의 브런치북으로 묶을 수도 있다. | 승인된 여러 지역 소식을 ‘이번 주 이웃 소식’으로 묶어 재방문을 시험한다. 글을 묶을 때 원문 작성자와 날짜를 함께 보존한다. | [브런치북 기획·연재 공식 안내](https://brunch.co.kr/brunchbookproject/14) · [브런치스토리 이용 안내](https://brunch.co.kr/magazine/brunchupdate) |
| 에브리타임 | 학교 인증과 학교별 커뮤니티를 운영한다. 동일 앱의 시간표와 학사 생활 정보도 반복해서 확인할 수 있다. | 지역 글에 `어느 지역에서 일어났는지`를 쉽게 확인하는 단서를 둔다. 생활상의 재방문 효용은 관심 지역의 주간 요약으로 먼저 시험한다. | [비누랩스 에브리타임 제품 소개](https://www.vinuteam.com/everytime) · [개발사 앱 설명](https://play.google.com/store/apps/details?hl=ko&id=com.everytime.v2) |
| Blind | 커뮤니티의 전체 접근을 위해 회사 이메일 인증을 안내한다. 공식 도움말은 이메일과 사용자 계정을 연결하지 않는다고 설명한다. | 실서비스에 신뢰 확인을 추가할 경우 확인에 쓰는 정보와 게시 화면에 보이는 닉네임을 명시한다. 작성하기 전에 정보 공개 범위를 설명한다. | [Blind 업무 이메일 인증 안내](https://help.teamblind.com/article/68-full-access) |
| Meetup | 정원이 찬 행사에는 RSVP 대신 대기 명단 버튼이 뜨며, 확정 참가 상태와 대기 상태의 동작이 다르다. | 지역 도움 요청에 실제 참여 기능을 붙일 때 신청·대기·확정 상태마다 다음 행동을 표시한다. 예약과 확정이 혼동되는지 사용성 시험에 넣는다. | [Meetup 행사 대기 명단 안내](https://help.meetup.com/hc/en-us/articles/41229648295181-How-to-Join-an-Event-Waitlist-on-Meetup) |
| Nextdoor | 뉴스피드에 추천, 가까운 지역, 최신, 인기 필터를 제공한다. 가까운 지역 모드는 가까운 이웃의 글에 집중한다. | 최신·인기의 정렬 기준을 표시하고 관심 지역을 열면 해당 지역이 먼저 보이게 한다. 일반 홈과 관심 지역에서 원하는 게시글을 찾는 시간을 비교한다. | [Nextdoor 뉴스피드 정렬 도움말](https://nextdoorcrm.my.site.com/s/article/How-to-sort-your-newsfeed?language=en_CA) · [Nextdoor 인근 지역 필터](https://nextdoorcrm.my.site.com/s/article/Seeing-posts-from-far-away-or-outside-your-neighborhood?language=en_US) |
| BeReal | 게시 알림 뒤 2분의 촬영 시간이 주어진다. 이후에도 게시할 수 있고 친구에게 늦었다는 상태가 표시된다. | 따뜻한 소식을 기록하는 알림은 사용자가 켜도록 하고, 알림 이후 원하는 시점에 작성할 수 있게 한다. 알림이 기록을 돕는지 확인한다. | [BeReal 게시 알림과 시간 안내](https://help.bereal.com/hc/en-us/articles/7350386715165--Time-to-BeReal) |
| Letterboxd | 본 영화에 날짜를 붙여 일지에 기록하고 평가·리뷰를 남길 수 있다. 볼 영화는 관심 목록에 담는다. | 작성 소식의 날짜와 지역을 프로필에서 다시 확인하게 한다. 개인의 기록 흐름이 재방문에 기여하는지 시험한다. | [Letterboxd 서비스 도움말](https://support.letterboxd.com/hc/en-us/articles/15178651705231-What-is-Letterboxd) · [Letterboxd 기록·목록 안내](https://letterboxd.com/faq/) |
| Goodreads | 읽고 싶은 책, 읽는 중인 책, 읽은 책을 책장에 분류하고 독서 진행률을 바꿀 수 있다. | 다시 읽을 소식의 개인 북마크 수요를 확인한다. 도입한다면 `저장됨` 상태와 다시 여는 곳을 같은 이름으로 표시한다. | [Goodreads 공식 소개](https://www.goodreads.com/about/us) · [Goodreads 개발사 앱 설명](https://apps.apple.com/us/app/goodreads-book-tracker-more/id355833469) |
| Strava | 활동 공개 대상을 정하는 설정과 별개로 지도 시작·종료 지점을 숨길 수 있다. | 따공의 공개 지도에는 광역 지역만 표시한다. 집·직장 같은 세부 위치가 첨부 사진과 본문에서 다시 노출되는지도 글 심사에서 확인한다. | [Strava 지도 공개 설정 도움말](https://support.strava.com/en-us/articles/15402012-how-do-i-edit-my-map-visibility-on-strava) |
| Flickr | 사진을 그룹 사진 모음에 넣고 뺄 수 있다. 비공개 사진을 추가할 때 그룹 멤버가 볼 수 있다는 안내를 제공한다. | 글을 지역별 선별 모음에 재노출할 수 있게 된다면 사용자에게 새 열람 범위를 먼저 알리고, 원문을 철회할 때 관련 모음의 노출도 함께 처리한다. | [Flickr 그룹 사진 추가·삭제 도움말](https://www.flickrhelp.com/hc/en-us/articles/4404069536532-Add-or-remove-photos-in-Flickr-groups) |
| DeviantArt | 작품을 그룹에 추가할 때 갤러리를 선택할 수 있고, 그룹의 제출 설정에 따라 추가 완료 또는 제안 상태가 표시된다. | 따공의 게시·선별 제안에서 `검토 중`과 공개 완료를 구분해 표시한다. 승인이 끝난 글만 공개 피드와 지역 점수에 반영한다. | [DeviantArt 그룹 작품 제출 도움말](https://www.deviantartsupport.com/kb/en/article/how-do-i-add-a-deviation-to-a-group) |

## 음악·창작·지식 커뮤니티

| 플랫폼 | 확인한 UI·UX | 따공 적용 판단 | 1차 출처 |
| --- | --- | --- | --- |
| Spotify | 협업 플레이리스트에 초대한 사람은 곡을 추가·삭제·재정렬할 수 있다. 만든 사람은 협업자를 제거할 수 있다. | 주민 공동 선곡을 나중에 열 경우 곡 추천과 목록 편집 권한을 구분한다. 첫 단계에서는 기존 곡에 추천 이유를 붙이는 흐름을 검증한다. | [Spotify Support · 협업 플레이리스트](https://support.spotify.com/dk-en/article/collaborative-playlists/) |
| Apple Music | 협업 플레이리스트에 참여한 사람은 목록 전체와 별개로 개별 곡에 이모티콘 반응을 남길 수 있다. | 곡 자체에 대한 가벼운 반응과 작성자가 남긴 추천 이유에 대한 응답을 구별한다. 노래 반응은 지역 온기 집계에 연결하지 않는다. | [Apple Support · 협업 플레이리스트 반응](https://support.apple.com/en-euro/guide/iphone/iphae7729920/ios) |
| SoundCloud | 웹에서 파형의 위치를 선택해 곡의 해당 재생 시점에 댓글을 남길 수 있다. | 따공은 음원 재생을 외부에서 제공한다. 추천 이유에 ‘언제 듣기 좋은지’를 쓸 짧은 안내를 붙여, 외부 플레이어 연동 없이도 맥락을 전달한다. | [SoundCloud Help · 타임스탬프 댓글](https://help.soundcloud.com/hc/en-us/articles/115003566008-Comments) |
| Bandcamp | Fan Page의 공개 컬렉션에서 항목을 개별적으로 숨길 수 있고, 숨긴 항목은 소유자가 다시 공개할 수 있다. | 활동 기록·배지의 공개 전환을 항목마다 제공한다. 공개를 취소해도 내 기록에서는 계속 확인할 수 있도록 설계한다. | [Bandcamp Help · Fan Page 편집](https://get.bandcamp.help/en/articles/15263087-how-do-i-edit-my-fan-page) |
| Last.fm | 청취 앱을 연동하면 스크로블링으로 들은 곡이 음악 프로필에 자동 기록된다. | 첫 구현의 노래 취향은 사용자가 명시적으로 고른 곡이나 추천으로만 파악한다. 재생 이력 연동이 필요해지면 목적과 삭제 방법부터 검증한다. | [Last.fm · 청취 기록 안내](https://www.last.fm/about/trackmymusic?showplatform=Windows) |
| Genius | 강조된 가사 부분을 누르면 아티스트나 커뮤니티가 작성한 해설을 읽을 수 있다. | 곡에 맥락을 붙이는 방식만 참고한다. 따공에서는 가사 대신 주민이 직접 쓴 추천 이유를 곡에 연결한다. | [Genius Media Group · 공식 앱 설명](https://play.google.com/store/apps/details/?hl=en-US&id=com.genius.android) |
| Twitch | 채널이 설정한 채팅 규칙을 처음 온 시청자에게 팝업으로 표시하고 동의를 받아 채팅에 들어가게 할 수 있다. | 공개 작성 기능을 열 때 첫 댓글 작성 순간에 운영 기준을 짧게 보여 준다. 단순 열람 흐름과 작성 참여 설명을 각자의 진입점에서 제공한다. | [Twitch Help · 채팅 규칙 안내](https://help.twitch.tv/s/article/how-to-manage-harassment-in-chat?language=en_US) |
| Steam Community | 게임 리뷰에서 최근 작성된 도움이 된 리뷰를 우선 노출한다. Valve 문서는 주제에서 벗어난 리뷰 급증을 평점에서 제외할 수 있다고 설명한다. | 인기의 집계 기간과 기준을 같이 보여 준다. 게시 제외나 삭제가 온기 집계에 반영되는 기준은 운영 상태와 함께 설명한다. | [Valve Steamworks · 사용자 리뷰](https://partner.steamgames.com/doc/store/reviews?l=english) |
| VSCO | Spaces에서 초대한 창작자가 공동 갤러리에 기여할 수 있다. 비공개 Space는 검색에 나오지 않으며 초대 링크로 접근한다. | 지역 기관과 진행하는 소규모 활동의 기록을 먼저 초대한 사람과 모으고, 공개 공유는 별도 선택으로 둔다. | [VSCO Support · Spaces](https://support.vsco.co/en/articles/12698524-vsco-spaces) · [Spaces 공개 범위](https://support.vsco.co/en/articles/12698601-staying-safe-with-vsco-spaces) |
| Pixelfed | 여러 장의 사진을 한 앨범 게시물로 묶어 공유할 수 있다. | 사진 기능을 확장한다면 복구 전후 사진도 이야기 한 편에 묶는다. 사진 수와 관계없이 지역 온기는 승인 글 한 편당 한 점으로 계산한다. | [Pixelfed · 공식 제품 기능](https://pixelfed.org/) |
| Lemmy | 커뮤니티 대상 범위를 구독·로컬·전체에서 고르고, 게시물은 신규·인기 등으로 정렬할 수 있다. | 지역은 ‘어디의 글’, 최신·인기는 ‘어떤 순서’라는 두 선택으로 유지한다. 지역을 바꿔도 정렬 선택을 갑자기 바꾸지 않도록 검증한다. | [Lemmy Docs · 대상 범위](https://join-lemmy.org/docs/users/01-getting-started.html?highlight=bot) · [정렬 방식](https://join-lemmy.org/docs/users/03-votes-and-ranking.html?highlight=sort) |
| Stack Overflow | Ask Wizard는 첫 질문에 단계별 작성 안내를 제공한다. Staging Ground에서는 공개 전에 경험 있는 이용자의 피드백을 받을 수 있다. | 첫 글에서 ‘어떤 도움을 받았나요?’처럼 예시 질문을 가까이 둔다. 보류된 글을 검토할 때는 원문을 유지하고 바꿀 부분을 짚어 준다. | [Stack Overflow Help · Ask Wizard](https://stackoverflow.com/help/askwizard) · [개발 블로그 · Staging Ground](https://stackoverflow.blog/2024/06/04/introducing-staging-ground-the-private-space-to-get-feedback-on-questions-before-they-re-posted) |
| Product Hunt | 출시일에는 댓글과 추천을 받을 수 있는 개별 출시 페이지가 열린다. 그날 이후에도 출시 기록은 제품 페이지에서 다시 볼 수 있다. | ‘우리 동네 한 주’가 끝나면 글의 시기를 표시하되 원문과 방문 경로는 유지한다. 선택한 지역의 다음 주 묶음과 지난 글을 오갈 수 있게 한다. | [Product Hunt Help · 출시와 제품 페이지](https://help.producthunt.com/en/articles/17734306-1-how-product-hunt-works) |
| Behance | 프로젝트나 이미지를 무드보드로 모으고 보드 자체의 공개 상태를 바꿀 수 있다. | 나중에 선곡을 공개하려는 사람을 위해 선곡 묶음의 보기 권한과 개별 추천 글의 작성 권한을 다르게 정의한다. | [Behance Help · Moodboards](https://help.behance.net/hc/en-us/articles/204484004-Guide-Moodboards) · [공개 설정](https://help.behance.net/hc/en-us/articles/204484014-Guide-Moodboard-Privacy-Settings) |
| Dribbble | 선별한 작업물을 공유 가능한 전체 페이지 컬렉션으로 묶는다. | 지역 큐레이션을 공유할 때 제목·지역·기간, 원문 링크가 있는 작은 페이지를 검증한다. 같은 화면의 상호작용과 지역 정보가 보이도록 한다. | [Dribbble Design Blog · 컬렉션 개편](https://dribbble.com/stories/2020/03/16/a-brand-new-dribbble) |
| Wattpad | 이야기 읽기 화면에서 바로 댓글을 달 수 있다. 읽기 목록은 공개 또는 비공개로 설정할 수 있다. | 감사 답장은 독자가 글을 읽던 자리에서 선택적으로 작성하게 한다. 개인적으로 기억할 이야기는 공개 참여와 독립적으로 관리하게 한다. | [Wattpad Corp · 공식 앱 설명 및 변경 이력](https://apps.apple.com/us/app/wattpad-read-write-stories/id306310789?platform=ipad) |
| Archive of Our Own | 작품 목록의 제외 필터에서 태그를 골라 해당 태그가 있는 작품을 화면에서 제외할 수 있다. | 주제 숨김을 검증할 때 적용 중인 조건을 화면에 표시하고 한 번의 조작으로 해제할 수 있게 한다. 좋아요 감소로 숨김 의도를 추정하지 않는다. | [OTW · AO3 작품 태그 제외 기능](https://archive.transformativeworks.org/help/work-filters-exclude-tags.html) |
| Ravelry | My Notebook에서 뜨개 작업을 기록하며, 프로젝트가 참고한 패턴과 작업 메모를 한곳에서 관리할 수 있다. | ‘온기 이어쓰기’의 참여 기록에서 어떤 글을 보고 시작했는지와 내가 한 행동을 함께 남기도록 한다. 원문 연결과 공개 여부는 작성자가 정한다. | [Ravelry · 프로젝트 노트북 안내](https://www.ravelry.com/tour/getting-started) · [프로젝트 작성 FAQ](https://www.ravelry.com/help/faq/) |

### 추가로 검증할 설계 근거

- **작성 지원** · Stack Overflow 개발팀은 안내형과 일반 질문 작성의 평가를 발표했다. 따공은 첫 글과 재작성의 과업 완료율, 승인까지 시도 횟수, 글쓰기 중단 이유를 관찰해 안내 한 줄의 효용을 확인한다. [Stack Overflow Blog · Ask Question Wizard 평가](https://stackoverflow.blog/2019/08/22/impact-of-ask-question-wizard/)
- **목록의 정보 위계** · Dribbble은 메타데이터보다 작업물이 먼저 보이도록 레이아웃과 구성요소를 정돈했다고 설명한다. 따공의 홈은 제목·지역·공감·대표 댓글 순서를 확인하고, LP 카드는 곡과 가수·추천 이유·듣기 동작이 좁은 화면에서 순서대로 읽히는지 검증한다. [Dribbble Design Blog · 레이아웃과 디자인 시스템](https://dribbble.com/stories/2020/03/16/a-brand-new-dribbble)

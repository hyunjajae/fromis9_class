프로필 사진 폴더
================

[학생 사진] 24장을 다음 이름으로 넣으세요 (현재 png 사용 중):

    frame_001.png
    frame_002.png
    ...
    frame_024.png

- 3자리 0 채움(zero-pad) 형식: frame_001 ~ frame_024.
- 확장자는 png → jpg → jpeg 순으로 자동 인식합니다(섞여 있어도 됨).
- index.html 의 STUDENT_IMAGE_COUNT(=24), STUDENT_IMAGE_EXTS 로 개수/확장자 조정 가능.

[교수님 사진] 1장 — 그리드 크기(2~5)와 무관하게 항상 한 칸에 표시됩니다:

    교수님.png   (또는 교수님.jpg)

- index.html 의 PROFESSOR_IMAGE_SRCS 가 이 경로를 참조합니다.

공통:
- 정사각형에 가까운 이미지가 보기 좋습니다(object-fit: cover 로 꽉 차게 표시).
- 파일이 없거나 로드 실패 시, 자동으로 "색 배경 + 이름 이니셜" 플레이스홀더로 대체됩니다.

# 모델 저장 공간

각 모델들을 저장합니다.

다만, 모델 용량이 커서 100MB를 초과하여, Git LFS를 사용하여야 하는 상황이므로, model.save 시 '없는 폴더' 오류를 방지하기 위해 빈 폴더를 생성합니다.
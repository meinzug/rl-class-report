## rl-class-report

정보통신대학원 강화학습 리포트 레파지토리

#### 실행환경
- gym 버전 0.26.2 버전으로 실행 되었습니다. (0.25.x 버전시 error)
- torch 1.13.0 버전으로 생행 되었습니다.
- 실행위치에서 하위 디렉토리(./trained-model)가 없으면 생성됩니다. (mode saved path)
- jupyter-notebook 환경으로 작성되었습니다.

#### 특이사항
- gym 중 cartPole-v1 코드를 실험했습니다.
- 아직 강화학습 개발역량이 많이 부족해서 PT자료 및 '단단한 강화학습', 'PyTorch 공식 문서' 등을 많이 참고했습니다.
- 하이퍼파라미터 변화에 따른 결과 위주로 작업을 했습니다.
- jupyter notebook 환경에서 inline plot 시 깜빡임 증상이 있어 _%matplotlib ipympl_ 모드를 사용했지만, plot 속도가 느려 _%matplotlib tk_ 모드로 별도 창에서 plot 을 했습니다.
- 학습 후 './trained-model' 위치에 'target_net.pt' 을 기록할 수 있습니다. (셀 실행)
- trained-mode 폴더에는 이제까지 학습한 pytorch scripted model 과 해당 스크린샷을 저장했습니다 (제출된 PPT 내용)
- 많이 부족하지만 기한내 끝내보기 위해 올렸습니다.
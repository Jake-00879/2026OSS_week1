
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>자기소개 웹페이지 만들기</h1>

<p>앞으로 개발자로서 버전관리가 어떻게 이루어지는지 알아보기 위해 ai의 도움을 받아 자기소개 웹페이지를 만든 후, 직접 배포함으로써 그 워크플로우를 이해하고 익힌다.</p>
<p>2026-oss-week1-c2h6v5zic-jake-00879.vercel.app</p>
<p>https://2026-oss-week1-eight.vercel.app/</p>
<p>https://2026-oss-week1-eight.vercel.app/index2.html</p>
<P>key learning</P>
<P>GitHub을 통해서 버전관리 하는 방법, vercell을 통해서 사이트를 배포하는 방법, html사용법</P>
<p></p>
Development Flow: VS Code → Git → GitHub → Vercel 흐름
VS code에서 교수님이 주신 레지토리 URL을 통해서 clone을 만들고 코딩한다.(VS code파트) 코딩을 마치면 remote로 저장소 연결하고 commit할 파일을을 git add로 지정하고 commit에 달 메세지랑 같이 commit하고 push한다.(Git 파트) github로 넘어가서 commit된 파일들 확인하고 레지토리 주소 복사해서 (gitHub 파트) velcell로 넘어가서 복사해온 레지토리 파일을 import해서 사이트 배포(vercell 파트)
Code Modification: index.html에서 index2.html로 변경한 주요 내용
사진 오류가 하나 있어서 다른 사진으로 변경하였습니다.
크로스핏 무엇인지 모르는 사람들이 있을까봐 크로스핏 공식 사이트 링크 추가하였습니다.
폰트 변경하는 게 궁금해서 폰트도 변경해보았습니다.
commit log를 남기기 위해 내용도 바꾸어보고 배경 색도 조작해보았습니다.

Problem & Solution: 실습 중 발생한 문제와 해결 방법 1가지
자동배포 된다는 걸 제가 잘못 이해하고 있었다는 걸 깨달았습니다. index.html로 배포하고 이후에 index2.html을 push했을 때 처음 배포했던 웹페이지에 그대로 적용이 돼서 배포가 된다는 걸로 이해를 하고 있었습니다. 그런데 그게 아니라 /index2.html가 자동 배포된다는 걸 과제를 하면서 이해했습니다.
Reflection: 새롭게 알게 된 점 또는 궁금한 점 1가지
</body>
</html>

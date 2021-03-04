## <딥러닝 텐서플로 교과서>(길벗, 2021) 도서의 예제 소스 파일입니다.

∙텐서플로 2.4를 기준으로 합니다.(Jupyter Notebook과 Colab용 파일을 제공) </br>

∙10장에서 사용되는 glove.6B.100d.txt는 [여기](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)에서 내려받아 10장의 data 폴더에 넣어 실습하세요.</br>
∙10장에서 사용되는 IMDb 데이터는 [여기](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)에서 내려받아 10장의 data 폴더에 넣어 실습하세요.</br>

∙장별로 내려받으시려면 아래 링크를 클릭하세요. </br>
[2장](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)
[3장](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)
[5장](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)
[6장](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)
[7장](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)
[8장](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)
[9장](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)
[10장](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)
[11장](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)
[12장](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)
[13장](https://github.com/gilbutITbook/007017/releases/download/0.1/101_ObjectCategories.tar.gz)

∙실습에 필요한 데이터셋 대부분은 장별 data 폴더에 들어 있습니다.</br>
(10장 wiki.ko.vec만 별도로 내려받습니다.(약 2GB))</br>

∙데이터셋은 python과 colab 모두 동일하게 사용하며, 일부 압축 파일은 colab 실습용입니다.</br>

∙8장부터는 colab에서 [런타임 유형]을 [GPU]로 설정하고 실습하는 것이 좋습니다. (실행 시간 단축)</br>
(10장 EMLO 예제는 텐서플로 1 버전에서만 실행됩니다.)</br>

∙colab에 필요한 데이터는 파일을 업로드해서 사용해야 합니다. 두 가지 방식이 있는데, 책에서는 대부분 PC에서 파일을 업로드하는 방식으로 되어 있습니다. </br>
∙만약 구글 드라이브를 사용 중이라면 드라이브에 마운트해 사용하는 것이 좀 더 편리합니다. (부록을 참고하세요)</br>

#PC에서 파일 업로드
from google.colab import files
file_uploaded=files.upload()

#구글 드라이브 마운트
from google.colab import drive
drive.mount('/content/drive/')


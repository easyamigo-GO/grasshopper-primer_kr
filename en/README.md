# About

\#기초:  그래스호퍼 입문서 ##제3판 V3.3

![Primer Release Cover](.gitbook/assets/GHP3_5Pages.png)

> 그래스호퍼(Grasshopper)는 라이노(Rhino)의 3D 모델링 도구와 긴밀하게 통합된 그래픽 알고리즘 에디터입니다. 이를 통해 디자이너는 단순한 형태부터 경이로운 수준의 형태에 이르기까지, 다양한 형태를 만들어내는 '폼 제너레이터(Form Generators)'를 구축할 수 있습니다.

\###환영합니다 여러분은 지금 그래스호퍼 입문서(Grasshopper Primer) 제3판을 펼치셨습니다. 이 입문서는 본래 Lift Architects의 앤드류 O. 페인(Andrew O. Payne)이 Rhino 4 및 Grasshopper 0.6.0007 버전을 위해 집필했던 것입니다. 당시 해당 버전의 출시는 이미 강력했던 그래스호퍼 플랫폼을 한 단계 도약시킨 거대한 업그레이드였습니다. 이제 우리는 그래스호퍼 개발의 또 다른 중요한 전환점에 서 있으며, 이에 따라 기존 입문서에 대한 업데이트가 절실히 필요했습니다. 우리는 이 업데이트된 웹 기반 입문서를 그래스호퍼 커뮤니티 멤버들이 기여한 수많은 훌륭한 자료 목록에 추가하게 되어 매우 기쁩니다.

이미 훌륭한 기초 자료를 바탕으로, 우리 Mode Lab 팀은 제3판의 디자인과 구성을 개발하는 작업에 착수했습니다. 이번 개정판은 가장 최신 그래스호퍼 빌드(버전 0.90076)에 대한 포괄적인 가이드를 제공하며, 우리가 생각하기에 가장 흥미로운 최신 기능 업데이트들을 강조하고 있습니다. 개정된 텍스트, 그래픽, 그리고 예제 파일들은 시각적 프로그래밍(Visual Programming)을 처음 접하는 완전한 초보자를 가르치는 것은 물론, 숙련된 베테랑에게는 제너레이티브 디자인(Generative Design) 워크플로우에 대한 빠른 소개를 제공하기 위해 기획되었습니다. 이 입문서가 창의적인 작업 과정에서 그래스호퍼의 활용법을 익히고자 하는 신규 및 기존 사용자들에게 유용한 현장 가이드가 되는 것이 우리의 목표입니다.

이 입문서는 그래스호퍼를 효과적으로 사용하기 위한 근본적인 개념과 필수적인 기술 함양 워크플로를 소개합니다. '기초(Foundations)'는 앞으로 출간될 그래스호퍼 입문서 컬렉션의 첫 번째 권입니다. 이 책을 통해 배울 수 있는 내용은 다음과 같습니다:

* **Introduction (소개)** - 그래스호퍼란 무엇이며 어떻게 사용되는가?
* **Hello Grasshopper (안녕 그래스호퍼)** - 첫 번째 데피니션(Definition) 만들기
* **Anatomy of a Grasshopper Definition (그래스호퍼 데피니션의 해부)** - 데피니션은 무엇으로 구성되는가?
* **Building Blocks of Algorithms (알고리즘의 구성 요소)** - 단순하게 시작해서 복잡성 쌓아가기
* **Designing with Lists (리스트로 디자인하기)** - 리스트란 무엇이며 어떻게 관리하는가?
* **Designing with Data Trees (데이터 트리로 디자인하기)** - 데이터 구조란 무엇이며 내 프로세스에서 어떤 의미를 갖는가?
* **Appendix (부록)** - 지속적인 탐구를 위한 참고 자료 및 작업 파일

적어도 이 입문서가 여러분으로 하여금 그래스호퍼를 통한 프로그래밍의 수많은 기회를 탐구하도록 영감을 주기를 바랍니다. 여러분이 이 여정을 시작하는 데 있어 행운이 함께하기를 빕니다.

***

#### THE GRASSHOPPER PRIMER PROJECT

The Grasshopper Primer is an open source project, initiated by Bob McNeel, Scott Davidson, and the Grasshopper Development team at [Robert McNeel & Associates](http://www.en.na.mcneel.com/).

**Mode Lab** authored the Third Edition of the primer. http://modelab.is

![Mode Lab Logo](.gitbook/assets/MODELAB_Logo.png)

If you would like to contribute to this project, check out the github project wiki to get started (https://github.com/modelab/grasshopper-primer/wiki).

#### ACKNOWLEDGEMENTS

A special thanks to David Rutten for the endless inspiration and invaluable work pioneering Grasshopper. We would also like to thank Andrew O. Payne for providing the assets from which this work initiated. Lastly, many thanks to Bob McNeel and everyone at Robert McNeel & Associates for their generous support over the years.

***

#### REQUIRED SOFTWARE

**Rhino5**

Rhino 5.0 is the market leader in industrial design modeling software. Highly complicated shapes can be directly modeled or acquired through 3D digitizers. With its powerful NURBS based engine Rhino 5.0 can create, edit, analyze, and translate curves, surfaces, and solids. There are no limits on complexity, degree, or size.

http://www.rhino3d.com/download/rhino/5/latest

**Grasshopper**

For designers who are exploring new shapes using generative algorithms, Grasshopper is a graphical algorithm editor tightly integrated with Rhino’s 3D modeling tools. Unlike RhinoScript or Python, Grasshopper requires no knowledge of the abstract syntax of scripting, but still allows designers to build form generators from the simple to the awe inspiring.

http://www.grasshopper3d.com/page/download-1

\###FORUMS The Grasshopper forum is very active and offers a wonderful resource for posting questions/answers and finding help on just about anything. The forum has categories for general discussion, errors & bugs, samples & examples, and FAQ.

http://www.grasshopper3d.com/forum

The Common Questions section of the Grasshopper site contains answers to many questions you may have, as well as helpful links:

http://www.grasshopper3d.com/notes/index/allNotes

For more general questions pertaining to Rhino3D be sure to check out the McNeel Forum powered by Discourse.

http://discourse.mcneel.com/

\###LICENSING INFORMATION The Grasshopper Primer is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported license. The full text of this license is available here: http://creativecommons.org/licenses/by-nc-sa/3.0/us/legalcode

---
layout:
  width: default
  title:
    visible: false
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: false
---

# 1.2.1. Grasshopper Object Types

### <mark style="color:$primary;">1.2.1. 그래스호퍼 오브젝트 유형</mark>

그래스호퍼는 **매개변수(parameters)**&#xC640; **컴포넌트(components)**&#xB77C;는 두 가지 주요 사용자 객체 유형으로 구성됩니다. 매개변수는 데이터를 저장하는 반면, 컴포넌트는 데이터를 결과로 만들어내는 동작(actions)을 수행합니다. 그래스호퍼를 이해하는 가장 기본적인 방법은, 우리가 동작의 입력(inputs)을 정의하기 위해 데이터를 사용하고, 그 동작이 다시 우리가 계속 사용할 수 있는 새로운 데이터를 결과로 내놓는다는 것을 기억하는 것입니다.

#### 1.2.1.1. 매개변수 (PARAMETERS)

매개변수는 숫자, 색상, 지오메트리 등 우리가 데피니션의 그래프를 통해 전송하는 데이터를 저장합니다. 매개변수는 보통 하나의 입력과 하나의 출력을 가진 작은 직사각형 상자로 표시되는 컨테이너 객체입니다. 또한 아이콘의 모양을 보고 이것이 매개변수라는 것을 알 수 있습니다. 모든 매개변수 객체는 아이콘 주위에 육각형 테두리를 가지고 있습니다.

지오메트리 매개변수는 라이노에서 지오메트리를 참조(reference)해 오거나, 다른 컴포넌트로부터 지오메트리를 상속(inherit)받을 수 있습니다. 점(Point)과 커브(Curve) 객체는 모두 지오메트리 매개변수입니다.

![](../../.gitbook/assets/1-2-1_001-geometry-parameters.png)

입력 매개변수(Input parameters)는 여러분이 데피니션과 상호작용할 수 있게 해주는 동적인 인터페이스 객체입니다. 넘버 슬라이더(Number Slider)와 그래프 매퍼(Graph Mapper)는 둘 다 입력 매개변수입니다.

![](../../.gitbook/assets/1-2-1_002-input-parameters.png)

#### 1.2.1.2. 컴포넌트 (COMPONENTS)

컴포넌트는 입력받은 값을 바탕으로 동작(action)을 수행합니다. 다양한 작업을 위한 여러 유형의 컴포넌트가 존재합니다.

![](../../.gitbook/assets/1-2-1_003-components.png)

> 1. 곱셈(Multiplication) 컴포넌트는 두 숫자의 곱을 계산하는 연산자입니다.
> 2. 분할(Divide) 컴포넌트는 지오메트리에 작용하며, 커브를 동일한 구간으로 나눕니다.
> 3. 원(Circle CNR) 컴포넌트는 입력 데이터(중심점, 법선 벡터, 반지름)를 사용하여 원 지오메트리를 생성(construct)합니다.
> 4. 로프트(Loft) 컴포넌트는 커브들을 로프트(lofting)하여 서피스를 생성합니다.

#### 1.2.1.3. 객체 색상

객체의 색상을 통해 각 객체의 상태에 대한 정보를 파악할 수 있습니다. 그래스호퍼의 기본 색상 코드 시스템을 살펴보겠습니다.

경고(warnings)나 오류(errors)가 없는 매개변수는 **밝은 회색**으로 표시됩니다. 이 색상은 해당 매개변수가 문제없이 정상적으로 작동하고 있음을 나타냅니다.

경고가 있는 매개변수는 **주황색 상자**로 표시됩니다. 데이터를 수집하지 못한 객체는 솔루션 도출에 기여하지 못하므로, 그래스호퍼 데피니션에서 '의심스러운' 상태로 간주됩니다. 따라서 모든 매개변수는  (처음 캔버스에 추가되었을 때) 아직 데이터가 없으며 결과적으로 솔루션의 결과에 아무런 기능적 영향을 미치지 않음을 나타내기 위해 주황색을 띱니다. 기본적으로 주황색인 매개변수와 컴포넌트는 객체의 오른쪽 상단 모서리에 작은 말풍선이 달려 있습니다. 이 말풍선 위에 마우스를 올리면 컴포넌트가 경고를 보내는 이유에 대한 정보를 볼 수 있습니다. 매개변수가 데이터를 상속받거나 정의하게 되면, 색상은 회색으로 변하고 말풍선은 사라집니다.

![](../../.gitbook/assets/1-2-1_004-parameter-warning.png)

A component is always a more involved object, since we have to understand and then coordinate what its inputs and outputs are. Like parameters, a component with warnings is displayed as orange. Remember, warnings aren’t necessarily bad, it usually just means that Grasshopper is alerting you to a potential problem in your definition.

![](../../.gitbook/assets/1-2-1_005-component-warning.png)

A component which contains neither warnings nor errors is shown in light gray.

A component whose preview has been disabled is shown in a slightly darker gray. There are two ways to disable a component’s preview. First, simply right-click on the component and toggle the preview button. To disable the preview for multiple components at the same time, first select the desired components and then toggle the disable preview icon (blindfolded man) by right clicking anywhere on the canvas.

A component that has been disabled is shown in a dull gray. To disable a component you may right-click on the component and toggle the disable button, or you may select the desired components, right click anywhere on the canvas and select Disable. Disabled components stop sending data to downstream components.

A component which has been selected will be shown in a light green color. If the selected component has generated some geometry within the Rhino scene, this will also turn green to give you some visual feedback.

A component which contains at least 1 error is displayed in red. The error can come either from the component itself or from one of its inputs or outputs.

![](../../.gitbook/assets/1-2-1_006-object-colors.png)

> 1. A parameter with no warnings or erros
> 2. A parameter with warnings
> 3. A component with warnings
> 4. A component with no warnings or errors
> 5. A component with preview disabled
> 6. A component that has been disabled
> 7. A selected component
> 8. A component with an error

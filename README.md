# IBM-Q
<git-hub >

https://github.com/Qiskit

<IBM Q Experience로 시작하는 양자 컴퓨터 프로그래밍 실습>

https://developer.ibm.com/kr/cloud/whats-new/2017/12/05/ibm-q-experience/


# 1. IBM Q Composer

https://quantumexperience.ng.bluemix.net/qx/editor?codeId=d09efa5f54314fc1ab8973fa6bdddad8

* IBM Q 계정활성화

* GUI 기반 Composer 실행

* 게이트가 어떤 역할, 어떻게 쓰는지 알수있음

* composer 작성후, simulate 버튼

* [OPEN QASM 2.0] 창에 python 환경에서 실행할 수 있는 코드 생성됨.

***community : https://quantumexperience.ng.bluemix.net/qx/community


# 2. QISKit (Quantum Information Software Kit)

<Install>

* QISKit은 OpenQASM과 IBM Q experience (QX)에서 사용할 수 있는 SDK(software development kit)입니다. 이번 항목에서는 Python으로 바로 프로그래밍을 하는 QISkit을 사용하는 방법을 배울 것입니다.
https://qiskit.org/documentation/index.html

> git clone https://github.com/QISKit/**.git : 필요한 폴더 가져오기.

* QISKit 가상 환경 설정
https://qiskit.org/documentation/install.html
> conda create -n name_of_my_env python=3 : 아나콘다로 python 가상 환경 설정

> conda activate name_of_my_env : 설정한 가상환경으로  

> conda list : 뭘 깔았는지 확인

** RemoveError: 'requests' is a dependency of conda and cannot be removed from -> conda update conda로 해결!

> pip install qiskit qiskit-aqua

> pip install qiskit[visualization] qiskit-aqua  : use all the visualization functions available in Qiskit 

( > pip install -U 'qiskit[visualization]' 로 해결)


* Git 코드 download

> conda info --envs : 무슨 가상환경들이 있는지 확인.


*** Terra (the code foundation, for composing quantum programs at the level of circuits and pulses)https://qiskit.org/documentation/install/terra.html#install-terra-source

https://github.com/Qiskit/qiskit-terra/blob/master/docs/ko/README.md

> conda create -y -n QiskitDevenv python=3 : 가상환경 만들기

> conda activate QiskitDevenv



> cd qiskit-terra : 폴더 들어가서 필요한 라이브러리 설치

> pip install -r requirements.txt 

> pip install -r requirements-dev.txt


> $ python setup.py build_ext --inplace : 필요한 모듈 부르기  ****설치못함. 

( > python setup.py build_ext

 > python setup.py install --user )
 

>  pip install -e . : example 얻기

> python examples/python/using_qiskit_terra_level_0.py : 실행할때

> python setup.py install :  If you would like to install qiskit-terra onto your system, then call:


*** Aqua (for building algorithms and applications)

*** Ignis (for addressing noise and errors)

*** Aer (for accelerating development via simulators, emulators and debuggers).

* 혹은, 만일 여러분이 이미 Git을 설치했다면, 다음의 커맨드를 실행하세요:
> git clone https://github.com/QISKit/qiskit-sdk-py

> cd qiskit-sdk-py


<Aceess IBM Q Systems>

# 3. IBM Q Experience

* Circuit Composer

> Explore the graphical interface for creating and testing circuits

* Qiskit Notebooks

> Create your first notebook and start using Qiskit

https://quantum-computing.ibm.com/

# threejs
three.js

## Three.js 핵심 객체들

### Renderer
Scene과 Camera 객체를 넘겨 받아 카메라의 절두체 안 3D 씬을 평면 이미지로 렌더링해주는 역할

### Mesh
어떤 Material로 하나의 Geometry를 그려주는 객체

### Geometry
기하학 객체의 정점 데이터, 구, 정육면체, 면, 개, 고양이 등등등 다양한 게 될 수 있다.

### Material
기하학 객체를 그릴때 사용하는 재질이다. 색, 밝기등을 지정할 수 있다.

### 절두체

Camera에 파라미터로 넘기는 fov, aspect, near, far 속성으로 하나의 "절두체"를 만든다. 렌더링은 절두체 안의 요소들만 이뤄지고, 바깥의 요소는 렌더링 되지 않는다.
<img src="https://threejsfundamentals.org/threejs/lessons/resources/frustum-3d.svg" />

카메라는 기본적으로 -Z 축, +Y 축 방향으로 아래를 바라본다 
